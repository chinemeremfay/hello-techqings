## Run it

Run the following commands in your terminal to build the Docker image and start the container:

```bash
docker build -t hello-app .
docker run -d -p 8000:8000 --name hello-app hello-app
