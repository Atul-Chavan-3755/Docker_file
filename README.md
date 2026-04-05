This project demonstrates how to containerize a simple static HTML application using Docker and serve it with Nginx.

The Dockerfile uses the official Nginx base image, removes the default content, and copies custom HTML files into the container. The application runs inside a container and is accessible via a mapped port on the host machine.

📁 Project Structure:

* Dockerfile → Defines the container image
* index.html → Main static web page

⚙️ Build Image:
docker build -t html-app .

▶️ Run Container:
docker run -d -p 8080:80 html-app

🌐 Access Application:
http://localhost:8080

🐳 Docker Commands:

* Build image → docker build -t html-app .
* Run container → docker run -d -p 8080:80 html-app
* Stop container → docker stop <container_id>
* Remove container → docker rm <container_id>
* Remove image → docker rmi html-app

🚀 Key Benefits:

* Lightweight and fast deployment
* Consistent environment across systems
* Easy to scale and manage

This setup is ideal for beginners learning Docker or for deploying simple static websites quickly.

