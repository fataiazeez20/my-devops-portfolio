## Docker Image

The application image is automatically built and pushed to Docker Hub through GitHub Actions.

Docker Hub:

fataiazeez20/devops-demo

Pull the image:

docker pull fataiazeez20/devops-demo:latest

Run the container:

docker run -p 5000:5000 fataiazeez20/devops-demo:latest
