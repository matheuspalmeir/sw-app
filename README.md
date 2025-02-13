# sw-app

The SW App is an application end-to-end that consumes the [Star Wars API](https://swapi.dev/documentation) via an Laravel API Gateway and displays the data in a user-friendly way.

This repo contains two subfolders the swapi-frontend and the swapi-gateway.

GitHub Repositories:

UI: https://github.com/matheuspalmeir/swapi-frontend

API: https://github.com/matheuspalmeir/swapi-gateway

You can run the entire application with Docker.
So, before jumping on the application, make sure you have Docker installed on your machine.

After cloning the repositories properly (clone UI and API repo), navigate to this project directory and run the following command to start the application:

```bash
docker-compose up -build
```

This will start the application and make it accessible at http://localhost:3000.
To check the API, you can access it at http://localhost:8000.
Please, see the readme file in the swapi-gateway folder for more information and also the readme in the swapi-frontend folder.
