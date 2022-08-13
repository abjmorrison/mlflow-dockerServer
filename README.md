## This repo tests an example mlflow server on the local host. 

### MLﬂow <br>
MLﬂow provides facilities for experiment tracking, model management, registry, and deployment interface.<br>
### PostgreSQL database <br>
The PostgreSQL database is the storage layer for MLﬂow for backend metadata.<br>
### Docker Compose <br>
Docker Compose is used to build and orchestrate the application which will run on http://localhost:5000<br>
<br>
An example ML script is included in the mlflow directory. <br>
<br>
Note: for the purposes of this example, a .env file was included to show the environment variables that must be set to run this application. In all other instances, a .env file should not be published to github. 
<br><br>
To build and run this application on your local server, run `docker compose --env-file .env up --build