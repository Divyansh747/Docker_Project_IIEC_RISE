# Docker_Project_IIEC_RISE
Docker project on Nextcloud deployment linked with mysql database. 

# Steps to run project on your local machine :-
 
1) Install GNU/Linux based operating system , I am using RHEL 8.0 as base os.
2) Download and install Docker community edition on your local machine
3) Download docker-compose.yml file from my github projects link available below.
4) command:- “docker-compose up” run from same location where you have downloaded docker compose yml file.
5) After installation everything will be setup according to yml instructions.
6) open browser and visit → http://localhost:8080 , (replace localhost with your local system ip).
7) On first run you have to signup with below credentials
	username:- admin
	password:- example
Now change database to Mysql/MariaDB	 
	database name:- db
	database host:- db
	database password:- example
8) Now click finish. This will take few minutes to setup whole user.
9) Successfully deployed Nextcloud on your local machine.
