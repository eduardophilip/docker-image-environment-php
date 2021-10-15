<h2>PHP environment with docker</h2>

I built this project to help people who want to run a simple PHP environment project and don't want to install applications like xampp, wamp, or whatever.

In these files, you will have a simple image Docker to run an environment with PHP 8, MySql, and phpMyAdmin without WAMP, LAMP, or MAMP.


## To run this is necessary to have a Docker installed in your machine.
### HERE are the links to learn how to install and run the docker on your operating system:
- [Windows Install](https://docs.docker.com/desktop/windows/install/)
- [Mac Install](https://docs.docker.com/desktop/mac/install/)
- [Linux Install](https://docs.docker.com/engine/install/ubuntu/)

### To run this project:
- Clone this repository;
- Open your terminal in the directory root of this project;
- Write ``` docker-compose up ```  and wait to download the images;
- After this, on your docker desktop it should look like this:
- ![docker2](https://user-images.githubusercontent.com/64706973/137483173-f3f51d83-4061-4198-8cc5-78748683c6ad.PNG)
- Now open your browser in [localhost:8000](http://localhost:8000) to see your project PHP and [localhost:8080](http://localhost:8080) to see your phpMyAdmin;
- Your **localhost:8000** should look like this:
- ![localhost8000](https://user-images.githubusercontent.com/64706973/137484855-ec7494f8-83c3-4a34-9e55-45e7b07f50bd.PNG)
- To enter in your phpMyAdmin Type ``` username: MYSQL_USER ``` and ``` password: MYSQL_PASSWORD ```
- ![Capture](https://user-images.githubusercontent.com/64706973/137483465-090df965-0a0d-4ed6-84cc-e04b1ee825d1.PNG)

## And done. Your environment PHP is ready to build your project

---
author: Eduardo Philip <br>
date: 2021/10/15 <br>
linkedin: https://www.linkedin.com/in/eduardo-philip/
...

