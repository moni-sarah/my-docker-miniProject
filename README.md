# my-docker-miniProject

# POZOS Docker Infrastructure POC

## Objectives
The objectives of this practice exam are to demonstrate the management of a docker infrastructure, including improving an existing application deployment process, versioning infrastructure releases, and implementing best practices for docker infrastructure.

## Infrastructure
- **Operating System:** CentOS 7.6
- **Environment:** Docker installed on a single machine or virtual machine.
- **Security:** Firewall and other security mechanisms must not be disabled without justification.

## Application
The application, named "student_list", consists of two modules:
1. **REST API**: Provides a list of students with their ages based on a JSON file.
2. **Web App**: Allows end-users to access the list of students.

## Files Provided
- **Dockerfile**: Used to build the API and Web App images.
- **docker-compose.yml**: Defines services and their configurations for deployment.
- **requirements.txt**: Contains required Python packages for the API.
- **student_age.json**: JSON file containing student names and ages.
- **student_age.py**: Source code for the API in Python.
- **index.php**: PHP page for end-users to interact with the service.

## Instructions
1. Ensure Docker is installed on the CentOS 7.6 machine or virtual machine.
2. Clone the repository containing the application source code.
3. Navigate to the directory containing the Dockerfile and docker-compose.yml.
4. Build the Docker images using `docker-compose build`.
5. Deploy the application using `docker-compose up`.
6. Access the Web App through a web browser at `http://localhost`.

## Notes
- The API will be accessible at `http://localhost:5000`.
- The Web App will be accessible at `http://localhost`.
- Data storage is handled using a PostgreSQL container defined in the `docker-compose.yml`.

## Security Considerations
- It's important not to disable any security mechanisms without justification, as per POZOS's security policies.
- Ensure proper permissions are set for sensitive data and services.
