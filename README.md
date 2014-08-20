Bot application will be run in a [docker](https://www.docker.com/) container. 

If you want to run it yourself build an image from a given `Dockerfile`

    docker build -t my_bantumi .
and run it:

    docker run -p 8080 my_bantumi

This command will run the container and expose its web API on http://localhost:8080/


In case you want to run it locally, you will need java 8. Then execute: 

    cd bot
    ./gradlew run

