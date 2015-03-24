#Readme for django01

This example is basic one that is not using compose at all. It's creating an image from django oficial library image and starting up.

#How-to

See https://github.com/docker-library/docs/tree/master/django for details on how to build and work with django image

Shorten version copy pasted from above document:

You can then build and run the Docker image:

	docker build -t my-django-app .
	docker run --name some-django-app -d my-django-app

You can test it by visiting `http://container-ip:8000` in a browser or, if you need access outside the host, on `http://localhost:8000` with the following command:

	docker run --name some-django-app -p 8000:8000 -d my-django-app

