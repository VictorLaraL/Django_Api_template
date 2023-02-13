# Django_Api_template
Template to my personal Django projects.

## Docker and actions configuration
The first think to you need to do is configure the github secrets and connect with docker token, you ned to configure two variables in secrets:

  * DOCKERHUB_USER: This is the variable of your username in docker hub.
  * DOCKERHUB_TOKEN: This is for the token that docker hub provides.

Later configure your github actions, in .github folder, if you configure your Docker Hub credentials you only check if variabes are correct in the checks.yml file.

You only need to repo and configure your actions like this:

  *   