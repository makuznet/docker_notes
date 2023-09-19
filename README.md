# This repo contains docker course notes and commands.

1. ## Look at images and containers.
    ```bash

    ```

1. ## Delete images and containers.
    ```bash
    
    ```

1. ## Build a container.  
    > DOCKER BUILD DOT TAG RELEASE
    ```bash
    docker build . -t work:0.1
    ```
    1. -t, a tag.      
        > It's worth adding a release "work:0.1"!  
    1. . (dot) means all the files in a folder.    

1. ## Run a container
    > DOCKER RUN DAEMON PORT ENVIRONMENT IMAGE
    ```bash
    docker run --name my-database -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=netlab mysql:5.7
    ```
    1. -d daemon, run into background.  
    1. -p port container:host.  
    1. -e ENV, environmental variable.  
    1. mysql:5.7 an image name and a version.  
