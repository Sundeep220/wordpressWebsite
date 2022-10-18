# wordpressWebsite


A wordpress website installed on nginx webserver using mySQL and PHP. 
- Used 3 containers: 
  - nginx container
  - mysql container
  - wordpress container
  
- I didn't have an digital ocean account so I could'nt host this website on a domain so I was not able to provide the SSL certificate using Let's encrypt.

- To run this :
  - git clone this repo
  - go to your project folder
  - type the command: 
      - `docker-compose up -d`
  - use command `docker-compose ps` to view all the running containers, the containers must be runnig on ports 80, 3306,9000 for nginx,mysql, and wordpress respectivvely.
  - If there are some error check the logs with command: 
    - `docker-compose logs [service name]`
  - to view the application:
      - go to your browser and type url for your localhost server on port 80. You should see the installation of wordpress website.
      - the credentials for root user: 
        - username: `admin`
        - password: `Admin22`
