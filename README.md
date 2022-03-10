# k8s-deployment-webservice-template
A template for deploying web servers to k8's with a mongo db.

This depends on nginx, and assume you have a dev and prod namespace. The route for the service is /NAMESPACE/SERVICE/ENDPOINT

## Using

Replace SERVICENAME with the name of your service. MUST NOT BE MORE THAN 12 CHARS OR IT THE DEPLOYMENT WILL NOT WORK

Replace GITHUB-USER-OR-ORG/SERVICENAME with the service github name, example: horvatic/zracni-udar-service

