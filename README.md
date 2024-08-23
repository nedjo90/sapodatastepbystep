# Table des Matières

1. [Définir le Modèle de Données](#define-data-model)
2. [Implémenter / Enregistrer le Service](#implement-register-the-service)
3. [Ajouter le Service au Catalogue de Services](#add-service-to-service-catalog)
4. [Dépannage](#dépannage)
5. [Contribution](#contribution)
6. [Licence](#licence)

---

# Définir le Modèle de Données

1. **T-CODE** `SEGW`
2. **Créer un Projet**:
    1. `Project` = `ZGW_MYPROJECT_PO_USERNAME`
    2. `Description` = `Service for PO`
    3. Cliquez sur `Objet Local` => Créez un projet avec 4 dossiers :
        1. `Data Model`:
            1. `Entity Types` => structure (work area = one row)
            2. `Entity Set` => internal table (more than one entity/rows)
        2. `Service Implementation`
        3. `Runtime Artifacts`
        4. `Service Maintenance`
    4. Créez une structure avec son tableau interne :
        1. Avec des champs un par un
            1. Clic droit sur `Entity Types` -> `Create`
            2. Entrez `Entity Type Name` = `POHeader` (Structure)
            3. Cochez `Create Related Entity Set`
            4. `Entity Set Name` = `POHeaderSet` (Internal Table)
            ![SEGW4](images/SEGW4.jpg) <!-- Image située dans le dossier 'images' -->
            5. Opérations ou Méthodes => déclenchées par des points de terminaison
            6. Définir les champs de la structure (work area) et du tableau interne :
                1. Double-cliquez sur `/Data Model/Entity Types/POHeader/Properties`
                2. Créez un champ
                    1. Ajoutez le nom du champ
                    2. Ajoutez le Type dans `Edm Core Type`
                    3. Ajoutez la Longueur dans `Max`
                3. Complétez les autres configurations si nécessaire
        2. Avec des champs en utilisant la Structure DDIC
            1. Clic droit sur `/Data Model` -> `Import` -> `DDIC Structure`
            2. `Name` = `POHeader` (Structure)
            3. Cochez `Entity Type`
            4. `ABAP Structure` = `EKKO` (par exemple)
            5. Cochez `Create Default Entity Set` (Créer un tableau interne par défaut relatif)
            6. Cliquez sur `Next`
            7. Sélectionnez les champs souhaités
            8. Cliquez sur `Next`
            9. Sélectionnez `Is Key`
            10. Cliquez sur `Finish`

# Implémenter / Enregistrer le Service

1. Cliquez sur ![Generate Runtime Object](images/Generate_Runtime_Object.png) (Générer l'objet runtime) => Génération de la classe pour :
    - MPC (Model Provider Class) => définit l'interface du service Gateway
    - DPC (Data Provider Class) => fournit les fonctionnalités du service Gateway
      => MPC & DPC ne sont pas connectés par un codage => communication via Configuration
    - Enregistrement du Service => Service technique que le système externe doit appeler
2. Fournir le Package et le Transport
3. Sauvegarder (par exemple, stockage local)

# Ajouter le Service au Catalogue de Services

1. **Déploiement**
    1. **Déploiement Intégré**
        1. Cliquez sur `/Service Maintenance/{nom du service}`
        2. Sélectionnez le système à activer
        3. Cliquez sur Enregistrer
        4. `System Alias` = `LOCAL` (par exemple)
        5. `Creation Information -> Package Assignment` = `Local Object` (par exemple)
        6. Cliquez sur ![Validate](images/Validate.png) <!-- Image située dans le dossier 'images' -->
    2. **Déploiement Non Intégré**
        1. À compléter
2. **Tester le Service :**
    1. Cliquez sur `Maintain` (t-code : `/n/IWFND/MAINT_SERVICE`) et `Yes`
    2. Cliquez sur le service à tester
    3. Cliquez sur `Call Browser` ou `SAP Gateway Client` (t-code : `/n/IWFND/GW_CLIENT`)
        1. Dans `SAP Gateway Client`, cliquez sur `HTTP` pour voir l'URL
            1. => ==Sensible à la casse==
    4. Testez `{URL}?$format=xml`
        [format=xml](format=xml.md)
    5. Testez `{URL}?$format=json`
        [format=json](format=json.md)
    6. Testez `{URL}$metadata`
        [metadata](metadata.md)
    7. Pour voir les erreurs, utilisez le service `/n/IWFND/ERROR_LOG`
3. **Extraction des Données :**
    1. `{URL}POHeaderSet` (tableau interne)
        [Get before method implementation](Get_before_method_implementation.md)
    2. **Implémenter la Méthode :**
        1. Allez dans `SEGW`
        2. Clic droit sur `Service Implementation/{POHeaderSet}`
        3. Cliquez sur `Go to ABAP Workbench` & ![Validate](images/Validate.png) <!-- Image située dans le dossier 'images' -->
        4. Clic droit sur `{project_name_DPC_EXT}/Methods/Inherited Methods/{service}_GET_ENTITYSET` & `Redfine`
        5. Sauvegardez & Activez (F3)
        6. Testez à nouveau la requête `{URL}POHeaderSet` (tableau interne)
            [Get after method implementation](Get_after_method_implementation.md)
        7. Entrez une méthode pour extraire des données
        8. Sauvegardez & activez
        9. Testez à nouveau la requête `{URL}POHeaderSet` (tableau interne)
            [Get after method implementation and populate table](Get_after_method_implementation_and_populate_table.md)
        10. Comprendre l'URL OData
            [OData URL](OData_URL.md)
