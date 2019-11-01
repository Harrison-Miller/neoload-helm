# Neoload Helm Chart

This chart launches a neoload controller and loadgenerator. Using the official
Docker images https://github.com/Neotys-Labs/Docker

## Installation

Copy the values.yaml to your working directory and override the values you need to change
such as apiToken and zone.

Then run `helm upgrade neoload neoload --install --namespace neoload -f values.yaml`
