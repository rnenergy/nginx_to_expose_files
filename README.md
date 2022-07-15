# nginx_to_expose_files
NGINX server for windows machines for quick exposing of huge files, that you need to download
1. Unzip all folders nearby your huge file and replace huge file to html folder.
2. Just start Nginx.exe and you have "html" folder exposed on port 2345. (Do not forget to open port 2345 in your firewall)
	To STOP Nginx server - run stop_nginx.bat, or reboot the server. Do not forget close exposed port 2345.
3. Or you can change port in /conf/nginx.conf (Do not forget to open exposed port in your firewall)
	To STOP Nginx server - run stop_nginx.bat, or reboot the server. Do not forget close exposed port.
