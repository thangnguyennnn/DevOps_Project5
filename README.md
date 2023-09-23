[![CircleCI](https://dl.circleci.com/status-badge/img/gh/thangnguyennnn/DevOps_Project5/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/thangnguyennnn/DevOps_Project5/tree/main)
# DevOps_Project5

This project utilizes the following steps:

1.Create a cluster using the command line via the eks_create_cluster.sh script configured in the cluster.yml file.
2.Deploy the application using the config.yml file.
3.Details:
- CircleCI performs a lint check on various files.
- Build and push the Docker image to Docker Hub.
- Deploy the "green" environment.
- Wait for manual approval.
- Deploy the new "blue" environment.
- Remove the old "blue" environment.