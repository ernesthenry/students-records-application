

#### Students records CRUD API. CRUD means Create, Read, Update, and Delete. Our API will have the following endpoints:

- GET /api/students will return all students and will be accepting GET requests.

- GET /api/students/{id} will return a student record by referencing its id and will be accepting GET requests.

- POST /api/students will create a new student record and will be accepting POST requests.

- PUT /api/students/{id} will update an existing student record by referencing its id and will be accepting PUT requests.

- DELETE /api/students/{id} will delete a student record by referencing its id and will be accepting DELETE requests.

#### The Student record  only contains name and course as details. We will  use the endpoints to develop an actual student records application that will make use of the API.