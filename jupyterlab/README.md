This directory contains theoretical scripts to add JupyterLab to the DS workbench supported by the mlflow-docker app. <br>

To add JupyterLab to the workbench, start with a standard image provided by JupyterLab such as the one found here: https://hub.docker.com/r/jupyter/all-spark-notebook<br>

We’ll need a Dockerfile to build the JupyterLab container properly<br>

Since we’ve already got our docker-compose.yml configured for the rest of the stack, I’ll just add the JupyterLab container to that compose file:<br>

Jupyterlab Service:
	Configure JupyterLab container and image options
	Set user
	Open a port for JupyterLab to run on
	Assign a local volume to JupyterLab
	Configure environment variables
<br><br>

This should run JupyterLab on the selected local host port with mlflow running on port 5000. 
