необходимо выполнить в текущей папке с index.html 
doker run -d -p 80:80 -v ${PWD}:/usr/share/nginx/html --name=dim_nginx nginx
