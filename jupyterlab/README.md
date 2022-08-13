This directory contains initial outline to add JupyterLab to the DS workbench supported by the mlflow-docker app. <br>

To add JupyterLab to the workbench, start with a standard image provided by JupyterLab such as the one found here: https://hub.docker.com/r/jupyter/all-spark-notebook<br>

We’ll need a Dockerfile to build the JupyterLab container properly<br>

Since we’ve already got our docker-compose.yml configured for the rest of the stack, we'll just add a container configuratin for jupyterlab:<br>

Jupyterlab Service:<br>
	>> Configure JupyterLab container and image options <br>
	>> Set user<br>
	>> Open a port for JupyterLab to run on <br>
	>> Assign a local volume to JupyterLab <br>
	>> Configure environment variables <br>
<br><br>

This should run JupyterLab on the selected local host port with mlflow running on port 5000. 
