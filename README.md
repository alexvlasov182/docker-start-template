# Quickstart: Compose and Rails
This Quickstart guide shows you how to use Docker Compose to set up and run a Rails/PostgreSQL app. Before starting, install Compose.

## Define the project
Start by setting up the files needed to build the app. The app will run inside a Docker container containing its dependencies. Defining dependencies is done using a file called Dockerfile. To begin with, the Dockerfile consists of: