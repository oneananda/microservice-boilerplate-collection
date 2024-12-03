# ASP.NET Core WebAPI Microservice Boilerplate

This is a minimal boilerplate for building microservices using ASP.NET Core WebAPI. It includes:
- A sample `WeatherForecast` API.
- Docker support for containerization.
- Configuration for different environments (`appsettings.json`).

## Features
- **REST API**: A basic setup with a sample controller.
- **Swagger**: API documentation available at `/swagger` (enabled in development).
- **Environment Configuration**: Configurable via `appsettings.json` and `appsettings.Development.json`.
- **Docker Support**: Prebuilt Dockerfile for containerization.

## Requirements
- .NET SDK (6.0 or higher)
- Docker (optional for containerization)

## Running the Application
1. Clone the repository and navigate to the folder:
   ```bash
   git clone https://github.com/oneananda/microservice-boilerplate-collection.git
   cd ASPNetCore
   ```

2. Build and run the application:
   ```bash
   dotnet build
   dotnet run
   ```

3. Access the API:
   - Swagger UI: [http://localhost:5000/swagger](http://localhost:5000/swagger)
   - Weather API: [http://localhost:5000/WeatherForecast](http://localhost:5000/WeatherForecast)

## Running with Docker
1. Build the Docker image:
   ```bash
   docker build -t aspnetcore-microservice .
   ```

2. Run the container:
   ```bash
   docker run -p 5000:80 aspnetcore-microservice
   ```

3. Access the API as above.

## Next Steps
- Add your own controllers and endpoints.
- Extend the configuration as needed.
- Implement your own middleware or custom services.

## Contributing
Contributions are welcome! Refer to the main repository's `CONTRIBUTING.md` for guidelines.



