# Hesk-help-desk
# Deploying HESK Help Desk with Docker Compose

## Overview

This guide will walk you through deploying the HESK Help Desk application using Docker Compose on a GCP Compute Engine instance.

## Steps

1. Create a GCP Compute Engine instance with Ubuntu (e2-medium, 2vCPU, 4GB RAM, 30GB disk).
2. Install Docker and Docker Compose on the Compute Engine instance.
3. Download the HESK application zip file.
4. Write a Dockerfile for the HESK application.
5. Write a Docker Compose file for the HESK application and MySQL database.
6. Access the website using the Compute Engine instance's IP address followed by `/install` (http//:ip/install).
7. Install HESK and address any permission errors if encountered.
8. Configure the database and complete the setup.
9. Delete the `install` folder from the HESK directory using the CLI.
10. Reload the website to finalize the setup.

HESK Help Desk should now be installed and accessible on your Compute Engine instance.
