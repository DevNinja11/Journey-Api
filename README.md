
# Journey-manager-api

## Project Overview
An API for travel management built with Java, Spring Boot, and the Spring Framework. This toy project serves as a theoretical basis for a series of articles on Medium about Java and Spring. 

## Tech Stack
![Java](https://img.shields.io/badge/Java-11-orange) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-2.3.7-brightgreen) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13-blue) ![Maven](https://img.shields.io/badge/Maven-3.6.3-red) ![JUnit](https://img.shields.io/badge/JUnit-5.7.0-yellowgreen)

## Key Features
- **Create a trip:** `POST /api-travels/v1/travels`
- **Update a trip:** `PUT /api-travels/v1/travels`
- **Delete a trip (by id):** `DELETE /api-travels/v1/travels/{id}`
- **Get report of travels in a period of time:** `GET /api-travels/v1/travels?startDate={startDate}&endDate={endDate}&page={page}&size={size}&sort={sort}`
- **Find a unique trip by id:** `GET /api-travels/v1/travels/{id}`
- **Find a trip by order number:** `GET /api-travels/v1/travels/byOrderNumber/{orderNumber}`
- **Get statistics about the travels:** `GET /api-travels/v1/statistics`

## My Contributions
- Developed the API endpoints for creating, updating, deleting, and retrieving travel records using Java and Spring Boot.
- Integrated Spring Security for JWT-based authentication to secure access to the API.
- Utilized Spring Data JPA with PostgreSQL for efficient data management and CRUD operations.
- Implemented RESTful APIs for smooth communication between the backend and potential frontend applications.

## Impact
- Enhanced application security with JWT-based authentication.
- Streamlined travel data management through efficient CRUD operations.
- Provided a robust backend solution that can easily integrate with various front-end technologies.
- Contributed to an increase in the understanding and implementation of secure web application practices in Java and Spring.

## License
This API is licensed under the MIT License.
