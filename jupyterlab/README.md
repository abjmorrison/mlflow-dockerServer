This directory contains initial outline to add JupyterLab to the DS workbench supported by the mlflow-docker app. <br>

To add JupyterLab to the workbench, start with a standard image provided by JupyterLab such as the one found here: https://hub.docker.com/r/jupyter/all-spark-notebook<br>

[Dockerfile](https://github.com/abjmorrison/mlflow-dockerServer/blob/main/jupyterlab/Dockerfile): builds the container for JupyterLab<br>
[docker-compose.yml](https://github.com/abjmorrison/mlflow-dockerServer/blob/main/jupyterlab/docker-compose.yml): add this to the docker-compose.yml to include a JupyterLab container in our mlflow app. <br>

Jupyterlab Service:<br>
	>> Configure JupyterLab container and image options <br>
	>> Set user<br>
	>> Open a port for JupyterLab to run on <br>
	>> Assign a local volume to JupyterLab <br>
	>> Configure environment variables <br>
<br><br>

This should run JupyterLab on the selected local host port with mlflow running on port 5000. 
