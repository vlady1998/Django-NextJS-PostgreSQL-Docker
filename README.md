
# Introduction

This is a basic boilerplate with Django REST as the backend server, PostgreSQL as the database and Next.js as the frontend.

# Technical Details
-   PostgreSQL used as the primary database.
-   Superuser is already initialized with the credentials: Username- `admin`, Email- `admin@admin.com`, Password- `admin`
-   Integration with Django Rest Framework
-   Integrated Djoser for user register/login/logout workflows.
-   Used JWT for Authentication.
-   API Documentation is configured using swagger.
-   Containerized using Docker and managed using docker-compose.
-   A typescripted Next.js client has been preinstalled and integrated with docker-compose.
-   Added Chakra UI and Chakra icons in the frontend as a design and component library alongwith axios for making api calls.

# How to Run the project.

1. Clone the repo `git clone https://github.com/vlady1998/Django-NextJS-PostgreSQL-Docker.git`.

2. Change the current directory to the template `cd django-nextjs-boilerplate`.

3. Build the docker containers`docker-compose -f docker-compose.dev.yml build` for the dev containers and `docker-compose -f docker-compose.prod.yml build` for the prod containers.

4. Run the docker containers`docker-compose -f docker-compose.dev.yml up` for the dev containers and `docker-compose -f docker-compose.prod.yml up` for the prod containers.

# API Documentation
API documentation is done using swagger. Visit `/swagger` for API documentation.
