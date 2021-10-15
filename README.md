<h2>PHP environment with docker</h2>

I build this project to help people that run a simple environment PHP project and don't want to install applications like xampp, wamp, or another one.

In these files, you will have a simple image Docker to run an environment with PHP 8, MySql, and phpMyAdmin without WAMP, LAMP, or MAMP.


## To run this is necessary to have a Docker installed in your machine.
### HERE are the links to learn how to install and run the docker on your operating system:
- [Windows Install](https://docs.docker.com/desktop/windows/install/)
- [Mac Install](https://docs.docker.com/desktop/mac/install/)
- [Linux Install](https://docs.docker.com/engine/install/ubuntu/)

## To better expirience in windows
[See this article]()

### To run this project:
- Clone this project
- Open your terminal in this directory
- Write ``` docker-compose up ``` wait to download the images
- After these open your browser in [localhost:8000](http://localhost:8000) to see your project PHP and [localhost:8080](http://localhost:8080) to see your phpMyAdmin
- To enter in your phpMyAdmin Type ``` username: MYSQL_USER ``` and ``` password: MYSQL_PASSWORD ```

### And done. Your environment PHP is ready to build your project
