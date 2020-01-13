#docker-compose使わない場合
run: #roはread only
	docker run --name nginx_test -v /Users/masataka/nginx/html:/usr/share/nginx/html:ro -d -p 80:80 nginx
stop_rm:
	docker stop nginx_test && docker rm nginx_test