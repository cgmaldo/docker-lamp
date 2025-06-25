# Dockernize PHP app
https://docs.docker.com/guides/php/containerize/

- Create a directory mariadb-data/ for MariaDB persistence data
- Create in DockerHub a Personal access token (PAT) named docker-tutorial with scope read & write
- Add in Github Settings/Secrets and variables/Actions DOCKER_USERNAME with id-dockerhub (as variable) and DOCKERHUB_TOKEN with the previous value PAT (as secret)
- Logout from DockerHub with: docker logout 
- Login into DockerHub with: docker login -u superyeahster and use the PAT
- In DockerHub go into your respository actions
- Set up a workflow yourself and commit changes 
- Now in DockerHub, we have in our repository a image for deployment