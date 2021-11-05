# DESCRIPTION

Basic image containing sphinx for building documentation
 

# Building


	docker build -t motionsignaltechnologies/sphinx-docker:latest .
	
	docker push motionsignaltechnologies/sphinx-docker:latest
 
Or just pull image from docker hub

   docker pull motionsignaltechnologies/sphinx-docker:latest


# Running

   docker run -it --entrypoint /bin/bash -v $(pwd):/host/ motionsignaltechnologies/sphinx-docker:latest


	
