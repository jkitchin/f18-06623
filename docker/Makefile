build:
	docker build -t f18-06623 .

push:
	docker tag f18-06623  jkitchin/f18-06623:v1
	docker push jkitchin/f18-06623:v1


run:
	docker run -it  -p 5543:5543 --expose 5543 jkitchin/f18-06623:v1
