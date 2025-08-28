# Docker Nginx 
<li> docker run -p 80:80 nginx : >> you can assign any port you like your nginx to run on</li>
 
 <li> docker run -p 4000:80 -d nginx : >> run in background ( -d stands for detach)</li> 
 <li> docker run -p 8000:80 -d --name dtest nginx : This is for running docker in background with a specified session name</li> 
 <li> docker logs dtest : checking the logs of the container  </li>
