# Manatee

Traffic Control Project.

## Getting Started

* Install Docker and Docker Compose

```
https://docs.docker.com/compose/install/
```

* Clone the repository

```
git clone https://github.com/magnumresearch/manatee-docker.git
```

* To run the images, use the Docker Compose configuration in the repo folder (Because the MySQL image uses 3306 port by default. Please make sure that other MySQL instances are stopped in advance.)

```
docker-compose up
```

* Visit the application page

```
http://127.0.0.1:8080/
```
