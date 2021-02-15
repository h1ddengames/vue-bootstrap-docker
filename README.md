> # vue-bootstrap-docker

- Vue 2 + Bootstrap-Vue 4 + Docker (Docker-Compose)

<hr>
<br>

> ## Project setup

- This project was created by following these steps:

1. Create the project using vue cli: ``vue create vue-bootstrap-docker``
2. Select ``Default ([Vue 2] babel, eslint)``
3. Wait for the cli to create the files.
4. Add Dockerfile with .dockerignore
5. Add docker-compose.yml

<hr>
<br>

> ## Developing in Docker container

- NOTE: All commands **``MUST``** be run on WSL, LINUX, OR MAC.
- NOTE: Hot reload does **``NOT WORK``** on Windows Docker.

<br>

- If you have this project downloaded on Windows: move all project files to WSL by running this command on WSL terminal:

    ```bash
    cd /path/to/this/project/on/your/windows && cp -R . ~/app
    ```

    or just run this in a WSL directory:
 
    ```bash
    git clone https://github.com/h1ddengames/vue-bootstrap-docker.git
    ```

<br>

- Follow these steps to develop this vue app in a docker container:

1. With a terminal opened in WSL: change directory into this project's main folder.
2. With Docker running, run the following command: ``docker-compose --file docker-compose.yml up -d``
3. Open ``localhost:8080`` in the browser.
4. Run Visual Studio Code from the terminal with: ``code .``
5. Test vue-bootstrap-docker development environment by changing some html or vue template and observe the browser for a hot reload when you save changes to the file.

<br>
<hr>
<br>