# Project2-Compose

## Overview
This repository contains the Docker Compose configuration and related files for setting up and running a Jenkins CI/CD pipeline using Docker-In-Docker (DinD) technology. The Jenkins pipeline is designed to automate the build, test, and deployment of a Node.js web application.

The Node.js web application used in this project is forked from the [AWS Elastic Beanstalk Express JS Sample Repository](https://github.com/aws-samples/aws-elastic-beanstalk-express-js-sample). The Docker Compose setup simulates a real-world scenario where Jenkins runs in a containerized environment and executes Docker commands inside its container.

## Features
- **Docker-In-Docker (DinD)**: Jenkins is configured to run Docker commands within its container, enabling seamless integration with Docker-based applications.
- **Automated CI/CD Pipeline**: The project uses Jenkins pipelines to automate the build, test, and deployment stages for the Node.js web application.
- **Docker Compose Setup**: A Docker Compose configuration file is provided to orchestrate the Jenkins environment with necessary services.

## Prerequisites
To use this project, ensure the following are installed on your Linux machine:
- Docker
- Docker Compose
- Minimum system requirements: 1 GB RAM, 2 CPU cores, 10 GB free disk space

## Setup
1. Fork the [AWS Sample Node.js Web Application](https://github.com/aws-samples/aws-elastic-beanstalk-express-js-sample) repository.
2. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/Project2Compose.git
