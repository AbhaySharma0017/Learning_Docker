# Two-Tier Flask Application with Docker Networking

This project demonstrates how to set up a two-tier architecture using Docker: a Flask-based backend connected to a MySQL database, communicating over a custom Docker network.

## 🧱 Architecture Overview

- **Backend**: A Flask application using `flask-mysqldb` to interact with a MySQL database.
- **Database**: MySQL running in a separate container.
- **Docker Network**: A user-defined bridge network (`mynetwork`) is used to allow seamless communication between the containers by hostname.

> ⚠️ **Note**: The Flask application code used in this project was sourced from a public repository. I did not write the Flask app code myself — this setup focuses on Dockerizing and networking the components.
