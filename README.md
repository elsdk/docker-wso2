# WSO2 API Manager with Identity Server as Key Manager and API Manager Analytics Support

## Prerequisites

 * Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git), [Docker](https://www.docker.com/get-docker) and [Docker Compose](https://docs.docker.com/compose/install/#install-compose)
   in order to run the steps provided in following Quick start guide.

## Quick Start Guide

1. Clone this repo

   ```
   git clone https://github.com/wso2/docker-apim
   ```

2. Build images locally and start up the containers

   ```
   docker-compose up --build
   ```

   *Note*: Wait for about 3 minutes for all the containers to start up, there's a 3 minute health-check period to ensure that all the services are up and running.

3. Access the WSO2 API Manager web UIs using the below URLs via a web browser. Credentials everywhere: `admin/admin`

   - [https://localhost:9443/publisher](https://localhost:9443/publisher)
   - [https://localhost:9443/devportal](https://localhost:9443/devportal)
   - [https://localhost:9443/admin](https://localhost:9443/admin)
   - [https://localhost:9443/carbon](https://localhost:9443/carbon)

   Please note that API Gateway will be available on following ports.

   - [https://localhost:8243](https://localhost:8243)
   - [https://localhost:8280](https://localhost:8280)

   Access the WSO2 API Manager Analytics web UIs using the below URL via a web browser.
   
   - [https://localhost:9643/analytics-dashboard](https://localhost:9643/analytics-dashboard)
