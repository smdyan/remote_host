# remote_host

setup vps services:

1. create project dir /home/smdyan/vps

2. copy compose.yml to remote host

3. create dir and link for each service vlms:
	- doku_conf -> /vlm_docker/dokuwiki/config/
	- swag_conf -> /vlm_docker/swag/config/
	- wguard_conf -> /vlm_docker/wireguard/config

4. copy file 'dokuwiki.subdomain.conf' to ./swag_conf/nginx/proxy-confs 

5. copy file 'default.conf' to ./doku_conf/nginx/site-confs

6. complete the setup by appending install.php to URL

7. copy dokuwiki pages to ./doku_conf/dokuwiki/data/pages 
