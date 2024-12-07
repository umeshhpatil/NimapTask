CRUD operation task

Machine Test: Category & Product Management with Spring Boot
This project demonstrates the implementation of a RESTful application using Spring Boot to manage Category and Product entities. It includes CRUD operations, database integration, and a one-to-many relationship between categories and products.

Key Features
Frameworks & Tools
Spring Boot for rapid application development.
Spring Data JPA & Hibernate for ORM and database interaction.
RDBMS Integration (configured, not in-memory).
Annotation-based configuration (No XML).
RESTful APIs using Spring RestController.
Functional Requirements
1. Category Management APIs
API Endpoint	HTTP Method	Description
/api/categories?page={pageNumber}	GET	Fetch all categories with pagination.
/api/categories	POST	Create a new category.
/api/categories/{id}	GET	Fetch a category by ID.
/api/categories/{id}	PUT	Update a category by ID.
/api/categories/{id}	DELETE	Delete a category by ID.
2. Product Management APIs
API Endpoint	HTTP Method	Description
/api/products?page={pageNumber}	GET	Fetch all products with pagination.
/api/products	POST	Create a new product.
/api/products/{id}	GET	Fetch a product by ID.
/api/products/{id}	PUT	Update a product by ID.
/api/products/{id}	DELETE	Delete a product by ID.
3. Additional Requirements
Relationship: Establish a one-to-many relationship between Category and Product:
One Category → Multiple Products.
Server-side Pagination for retrieving categories and products.
Nested Responses: When fetching a single product, its associated category details should also be included in the response.
task_Nimap_infotec/NimapTask-main/README.md at main · akshaygithub2002/task_Nimap_infotec 
