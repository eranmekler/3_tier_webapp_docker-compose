
# 3-Tier Web Application with Docker Compose

**Introduction**

This repository demonstrates building a simple 3-tier web application using Docker Compose. The application consists of the following components:

* **Frontend:** Container running a Nginx image as webserver
* **Backend:** Container running a  Bitnami/wordpress image handling application logic and database communication.
* **Database:** Container running a Bitnami/mariadb image database storing application data.

**Why Docker Compose?**

* **Simplified Deployment:** Docker Compose streamlines the process of deploying the multi-container application by managing all services (containers) through a single configuration file.
* **Scalability:** Easily scale your application by spinning up new containers on demand.
* **Reproducibility:** The Dockerized environment ensures consistent behavior across different environments.

**Prerequisites**

Before we dive in, you'll need to have the following installed on your system:

* **Docker:** Get it here: [https://www.docker.com/](https://www.docker.com/)
* **Docker Compose:** Instructions for installation can be found here: 
[https://docs.docker.com/compose/install/](https://docs.docker.com/compose/install/)

**Running the Application**

 **Clone the Repository:**



  `git clone https://github.com/eranmekler/3_tier_webapp_docker-compose`


 **Navigate to the Project Directory:**



  `cd  3_tier_webap_docker-compose`


**Build and Run the Application:**



   `docker compose up`

**Accessing the Application**

Once the application is up and running, you can access the frontend by visiting 
http://localhost:80 in your web browser.

**Terminate The Application:**



 `docker compose down`

![](https://github.com/eranmekler/3_tier_webapp_docker-compose/blob/main/3_tier_webapp_docker-compose.svg)
