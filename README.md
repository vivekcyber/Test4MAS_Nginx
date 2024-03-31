# Test4MAS_Nginx

This repository contains code to build and deploy Nginx as container on K8s cluster.


Key points to note - 

1. This installation is completely driven through Jenkins. Refer to devops_scripts folder to check out the dockerfile & jenkinsfile used.

2. Nginx landing page has been customised to showcase the build workflow. Link to Nginx accessible from internet http://3.1.23.209:30153/

3. NodePort service efined to expose the nginx app.
   
