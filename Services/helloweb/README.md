`BaseImage` *jboss/wildfly* <br/>
* It will bring up all the services and run them in a detach mode.
* It creates a network for all the services in the compose file and expose them on port 8080 on localhost.
* It will download the specified images if not already downloaded.
* The files uploaded in deployments directry will be copied automatically in the container on specified path. 
