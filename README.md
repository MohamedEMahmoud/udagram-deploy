# Hosting a Full-Stack Application - Udagram

<h1> Hosting Link   </h1>

- http://udagram-storage.s3-website-us-east-1.amazonaws.com

<h1> CircleCI Badge </h1>

[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://app.circleci.com/pipelines/github/MohamedEMahmoud/udagram-deploy/4/workflows/718961cc-85cf-483c-8d0d-20e4ae2979fd/jobs/11)

<h1> Introduction </h1>

- This is the final project of the udacity fullstack Js Nanodegree. The goal is how to deploy Full-Stack Application on `AWS` services.
- Elastic Beanstalk was used for the `udagram-api`
- RDS was used for the `PostgreSQL` database
- S3 was used for hosting `udagram-frontend`

# project setup

<h2> Running Udagram locally </h2>

You will need to create a `.env` file in udagram-api with the following variables :

- POSTGRES_HOST
- POSTGRES_USERNAME
- POSTGRES_PASSWORD
- POSTGRES_DB
- POSTGRES_PORT
- AWS_ACCESS_KEY_ID
- AWS_DEFAULT_REGION
- AWS_SECRET_ACCESS_KEY
- PORT
- URL
- JWT_SECRET

<h2> Install dependencies for API </h2>

     npm backend:install

<h2> Install dependencies for Client </h2>

     npm frontend:install
