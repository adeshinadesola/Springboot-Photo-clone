# Photo Clone

**Photo Clone** is a Spring Boot API designed to integrate photo management functionalities into applications. It provides features to save, download, and store photos in real-time from devices.

## Usage

After successfully running the application, you can interact with the API using HTTP requests. Ensure that the application is running on localhost:8080 or adjust the port accordingly in the configuration.

## API Endpoints

The following endpoints are available:

- **GET /photos:** Retrieve all photos.
- **GET /photos/{id}:** Retrieve a specific photo by ID.
- **POST /photos:** Upload a new photo.
- **GET /photos/{id}/download:** Download a photo.
  <!-- Add more endpoints as needed -->

For detailed information about request and response formats, refer to the **API documentation**.

## Configuration

The application can be configured using the `application.properties` file located in the `src/main/resources` directory. Modify the properties to suit your environment or requirements.

## Dependencies

This project utilizes the following dependencies:

- **Spring Boot:** Framework for creating stand-alone, production-grade Spring-based applications.
- **Spring Data JPA:** Simplifies the implementation of data access layers by automatically generating queries.
- **H2 Database:** In-memory database for testing and development.
- **Maven:** Build automation tool for managing project dependencies.

## License

This project is licensed under the **MIT License**.

---
## Contact
Feel free to reach out to me via:
- [LinkedIn](https://www.linkedin.com/in/adeshina-adesola-48040b20a/)
- Discord: adeshinadesola
