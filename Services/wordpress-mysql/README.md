`BaseImage` *mysql:5.7* and *wordpress:5.1.1-php7.3-apache*  <br/>
* It will bring up all the services and run them.
* It creates a network for all the services in the compose file with database connectivity and expose the wordpress service on port 8081.
* It will download the specified images if not already downloaded.
* Infrastructure As Code with PATing (port address translation).<br/><br/>

`For Docker volumes` <br/>
![](screen-shots/docker-volume.png)
<br/><br/>

`For Container Info and IPs`
![](screen-shots/docker-info-ip.png)
<br/><br/>

`Sample without PATing`
![](screen-shots/Sample-without-PATing.png)
<br/><br/>

`Sample with PATing`
![](screen-shots/Sample-with-PATing.png)
<br/><br/>
