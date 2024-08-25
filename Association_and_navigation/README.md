Objectif => 
    -   **Association** = connection between entities => specifies the cardinality between Entity Types
    -   **Naviagation** = relationship between entities

Create Assocition & Navigation:

1. Go to `SEGW`
2. Right-click `{service}/Data Model/Association`
3. Click on `Create`
   1. `Association Name` = `HeadToItemAss` (e.g)
   2. `Principal Entity`
      1. `Entity Type Name` = `POHeader` (e.g)
      2. `Cardinality` = `1` (e.g)
      3. `Navigation Property` = `HeadToItemNav` (e.g)
   3. `Dependent Entity`
      1. `Entity Type Name` = `POItem` (e.g)
      2. `Cardinality` = `N 1..n` (e.g)
4. Hit `Next`
5. Must specifiy => `Dependent Property` = **Key** like Foreign Key concept between Princpal Entity and Dependent Entity
6. Hit `Next`
7. `Association Set` is create for multiple entries (i.e tables/arrays)
8. Hit `Finish`, we generate:
   1. `Association`
   2. `Navigation Property`
   3. `Association Set`
   4. Test to query metadata: [analysis of the metadata after association](./analysis_metadata_after_association.md)
   5. Test to query POHeader to see additional links: [Query option with Navigation Property](./query_option_with_navigation_property.md)
   6. Test the query with navigation property: [See example](./query_option_with_navigation_property.md/#test-of-query-option-with-navigation-property)
      1. `URL = {baseurl}/{endpoint}('{paramter}')/{navigationproperty}` 
   7. Test with expand option which give you the header data: [For example](./query_option_with_navigation_property.md/#test-with-expand-option)