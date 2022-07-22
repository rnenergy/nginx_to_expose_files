# nginx_to_expose_files
NGINX server for windows machines for quick exposing of huge files, that you need to download
1. Unzip all folders nearby your HUGE FILE on the server and replace HUGE FILE to html folder.
2. Just run as Administrator Strat_server.bat and you have "html" folder exposed on port 2345. (Port will be added to the firewall by .bat file)
	To STOP Nginx server - run as Administrator Stop_nginx.bat. (Port will be deleted from firewall by .bat file)
