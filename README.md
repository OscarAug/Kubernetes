related knowledge fro this Project

Pods:	        to run 2 applications <br>
Service:	    for outside access the application <br>
Persistence Volumes:	    to store the data with MongoDB <br>
Ingress:	     to expose both applications under same domain but different path <br>
ConfigMaps：	    to store MongoDB service address, in case MongoDB is down and restarts with a different service address, and with ConfigMaps, we don't need to build the docker image again with the new address
<br><br>
Pod 1: student information records<br>
Node.js webserver that allows users to access certain student record from given student_id.
<br><br>
Pod 2: bookstore<br>
MongoDB + Python Flask Web Framework + REST API to allow users to perform standard List, Insert, Update, Delete operation to the data stored inside MongoDB
<br><br>
The project secdule is in file:       cs571_week12_HW1_19559_Peng_Gao.pdf
<br><br>
Googel slide URL:   https://docs.google.com/presentation/d/15IoAT0ubHhK_T6J99X79S_88xnnY6XQrsdCJWGeOmlY/edit?usp=sharing
