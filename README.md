This project includes a Dockerfile used to containerize a simple HTML application. The Dockerfile defines the steps required to build a lightweight and portable Docker image using the official Nginx base image.

It removes the default Nginx web content and copies the custom HTML file into the container’s web root directory (`/usr/share/nginx/html`). The container exposes port 80 and runs the Nginx server in the foreground to serve the static web page.

This setup allows the application to run consistently across different environments without requiring additional configuration, making deployment simple and efficient.
