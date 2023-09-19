# This repo contains docker course notes and commands.

1. ## Run a container
    > -t work means a tag named "work". It's worth adding a release "work:0.1"  
    1. -d daemon, run into background.  
    1. -p port container:host.  
    1. -e ENV, environmental variable.  
    1. mysql:5.7 an image name and a version.  
    ```bash
    sudo docker run --name my-database -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=netlab mysql:5.7
    ```