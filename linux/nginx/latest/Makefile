all: nginx

nginx:
	docker build --compress -t epicmorg/nginx:latest .
	docker push epicmorg/nginx:latest

	docker tag epicmorg/nginx:latest epicmorg/balancer:latest
	docker push epicmorg/balancer:latest
