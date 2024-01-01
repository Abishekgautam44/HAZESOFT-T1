HAZESOFT-T1
-----------
This repository contains a Dockerfile that automates the setup of an Nginx server using Alpine Linux.

Usage
-----
Follow the steps below to use the Dockerfile and run the application:

1. Clone the Repository:

```bash
git clone https://github.com/Abishekgautam44/HAZESOFT-T1.git
```
2. Get inside the Repository:
```bash
cd HAZESOFT-T1
```
3. Build the Docker Image:
```bash
docker build -t hazesoft-t1 .
```
4. Run the Docker Container:
```bash
docker run -p 9000:80 --name=app1 hazesoft-t1
```

The application will be accessible at http://localhost:9000/site/index.html.