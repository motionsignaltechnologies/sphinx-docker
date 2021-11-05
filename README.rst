

-----------
INFORMATION
-----------

Author: Kit Chambers
Contact: kit.chambers@motionsignaltechnologies.com

Motion Signal Technologies Ltd. 
All rights reserved 

The contents of this file are considered proprietary and usage or 
reproduction without prior authorization is strictly prohibited.  

-----------
DESCRIPTION
-----------

Basic image containing sphinx for building documentation
 
--------
Building
--------

..

	docker build -t motionsignaltechnologies/sphinx-docker:latest .
	
	docker push motionsignaltechnologies/sphinx-docker:latest
 
Or just pull image from docker hub

..
   
   docker pull motionsignaltechnologies/sphinx-docker:latest

-------
Running
-------

.. 

   $ docker run -it --entrypoint /bin/bash -v $(pwd):/host/ motionsignaltechnologies/sphinx-docker:latest


	$ docker run --entrypoint /bin/bash 	

	$ aws ecr get-login-password --region us-east-2 | docker login --username AWS --password-stdin 217963016703.dkr.ecr.us-east-2.amazonaws.com
	$ docker pull 217963016703.dkr.ecr.us-east-2.amazonaws.com/msf-datamanager:debug-latest
	
	note - You can also access other AWS resources 
	
	
