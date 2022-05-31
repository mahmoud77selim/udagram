# udacity Advanced Full-Stack Web Development Nanodegree Program

# PROJECT 3 Hosting a Full-Stack Application "Udagram"

# Built With
Angular    - Single Page Application Framework
Express    - Javascript  API Framework
Node       - Javascript  Runtime
Postgresql - database

* Pipeline Status (main Branch): 


# Access Website Endpoint
```bash
http://1frontend-bucket1.s3-website-us-east-1.amazonaws.com
```

# Hosting
Project is hosted on AWS.
* Backend API using Nodejs using Amazon Elastic Beanstalk.
* Database using Postgres using Amazon RDS.
* Frontend using Angular using Amazon S3.

# CI/CD pipeline
CircleCi is linked to the project on Github udagram repository.
* automatically deploy the website to the AWS.
* automatically execute when source code pushed into Github repository.

## Testing
Project have no Unit test on the back-end and contains two test suite for the frontend: 
* Unit tests using the Jasmine Framework.
* End-To-End tests(e2e) using Protractor and Jasmine.

## clone, install dependencies, Build, Test and run server by running the below commands
```bash
git clone https://gitlab.com/mahmoud77selim/udagram.git
```
```bash
cd udagram
```

```bash
yarn backend:install && yarn frontend:install
```
```bash
yarn backend:build && yarn frontend:build
```

```bash
yarn backend:run
```
```bash
yarn frontend:run
```

```bash
yarn backend:test
```
```bash
yarn frontend:test
```
```bash
yarn frontend:e2e
```

## Host and start the project on local machine

Edit the values of apiHost to be http://localhost:3000/api/v0 at the following files

udagram/udagram-frontend/src/environments/environment.prod.ts
udagram/udagram-frontend/src/environments/environment.ts

```bash
cp udagram-api/.env.example udagram-api/.env
```
```bash
yarn backend:build && yarn frontend:build
```

```bash
docker-compose up -d
```

```bash
yarn backend:run
```
```bash
yarn frontend:run
```

```bash
GET http://localhost:3000
```
```bash
GET http://localhost:5432
```

```bash
yarn backend:test
```

```bash
yarn frontend:test
```

```bash
yarn frontend:e2e
```

# Project By: Mahmoud Hassanein.