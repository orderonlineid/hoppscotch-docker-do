# Hoppscotch Docker Compose

This Docker Compose file contains services of: 
- Frontend
- Backend
- Admin

These services use for API Testing and development

To run the Docker Compose file, follow these steps:

1. Run the following command to start the containers defined in the Docker Compose file:

    ```bash
    docker-compose up
    ```

    This command will build and start the containers specified in the Compose file. You should see the output of each container in the terminal.

2. If you want to run the containers in the background, you can use the `-d` flag:

    ```bash
    docker-compose up -d
    ```

    This will start the containers in detached mode, and you won't see the container output in the terminal.

3. To stop the containers, you can use the following command:

    ```bash
    docker-compose down
    ```

    This command will stop and remove the containers defined in the Compose file.

That's it! You have now successfully run the Docker Compose file and started the containers. Feel free to customize the Compose file according to your needs.