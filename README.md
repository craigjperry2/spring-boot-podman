# Notes

Built using podman on Ubuntu on WSL2. Written in VSCode using remote WSL function.

    $ java -Djarmode=layertools -jar target/docker-example-0.0.1-SNAPSHOT.jar list
    $ podman build . --tag demo
    $ podman run -it -p8080:8080 demo:latest
