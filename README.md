# devopsmini-1

## Project Overview
This project is a platform for booking tickets for events. The main features of the platform include:

- Backend for user authentication, event management, and payment processing.
- Static frontend for users to interact with the platform.
- API to handle ticket orders and interact with other services.

## Project Architecture
The platform architecture is based on the following components:

- **Backends**: Django (running via Docker).
- **Frontend**: Static files stored on AWS S3 with caching via CloudFront.
- **Database**: PostgreSQL hosted on AWS RDS.
- **Caching**: Redis for caching event search results and user sessions.
- **Deployment**: EC2 for hosting backend and API services.

## Technologies Used
- **Docker**: For containerizing all services for easy deployment.
- **PostgreSQL**: The primary database for managing user, event, and order information.
- **Redis**: Caching system to enhance the platform’s performance.
- **AWS S3**: Used for storing frontend static files.
- **AWS CloudFront**: For caching and accelerating frontend content delivery.
- **GitHub Actions**: CI/CD pipelines for automating deployment processes.

<p align="center">
<img style="width: 100%;" src="https://i.postimg.cc/nzykWKNd/result.gif">
</p>
