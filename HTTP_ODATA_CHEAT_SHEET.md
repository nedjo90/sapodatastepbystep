# SAP Netweaver Gateway and OData Services Notes

## Key Concepts

- **CRUD Operations**: 
  - **GET**: Fetches data from the server using a URI.
  - **POST**: Creates data on the server.
  - **PUT**: Updates data on the server.
  - **DELETE**: Removes data from the server.

- **OData Query Options**:
  - **Framework Provided (No Coding Required)**:
    - `$format`: Determines the format (e.g., JSON, XML).
    - `$count`: Retrieves the count of records.
    - `$expand`: Joins related tables.
  - **Coding Required**:
    - `$filter`: Applies a WHERE clause to filter results.
    - `$orderby`: Sorts data.
    - `$top`: Limits the number of rows returned.
    - `$skip`: Skips a specified number of rows.

## Examples

- **Basic URI for GET Method**:
  - `GET /sap/opu/odata/sap/<SERVICE_NAME>/<ENTITYSET_NAME>`
  - Add options like `$format=json` or `$filter=<field> eq <value>`.

- **DPC_EXT Methods**:
  - **GET_ENTITYSET**: Handles data retrieval for entity sets.
  - **GET_ENTITY**: Handles data retrieval for a specific entity by key.
  - **EXPANDED_ENTITY**: Retrieves associated entities using `$expand`.

## HTTP Status Codes

- **2xx (Success)**:
  - `200 OK`: Request successful.
  - `201 Created`: Data successfully created.
  - `204 No Content`: Data successfully deleted.

- **4xx (Client Errors)**:
  - `400 Bad Request`: Invalid URI or query.
  - `401 Unauthorized`: Authentication required.
  - `404 Not Found`: Data not found.

- **5xx (Server Errors)**:
  - `500 Internal Server Error`: Generic server issue.
  - `503 Service Unavailable`: Server is temporarily down.

## Tips for ABAP Developers

- **No Coding Required** for options like `$format`, `$count`, and `$expand`.
- **Custom Logic Needed** for `$filter`, `$orderby`, `$top`, and `$skip`.
- Ensure proper handling of URI parameters in DPC methods for accurate data retrieval.

## URI Syntax and Changes

- **Filter Example**: 
  - `GET /sap/opu/odata/sap/<SERVICE_NAME>/<ENTITYSET_NAME>?$filter=<field> eq <value>`
  - Filters results based on conditions.

- **Orderby Example**: 
  - `GET /sap/opu/odata/sap/<SERVICE_NAME>/<ENTITYSET_NAME>?$orderby=<field> desc`
  - Sorts results in descending order.

