# HTTP-Caching-Proxy

### 1. Project Introduction:
- Used C++ to implement a HTTP caching proxy server so that users can access different websites through this proxy server.
- It can handle GET, POST, CONNECT requests and cache responses.
- [Detailed description](https://github.com/CaoRui0910/HTTP-Caching-Proxy/blob/main/HTTP%20Caching%20Proxy.pdf)
- [Tips & Resources](https://neat-iodine-05e.notion.site/Tips-Resources-f86cda054220434e99be8225a603ffd5)

### 2. Usage
- This project is deployed with docker, to run it, `cd` into the docker-deploy folder. Then run:
  - `sudo chmod 777 -R .`
  - `sudo docker-compose up`
- Next, you must configure your web browser to use this proxy. Once set up, you can access web pages through this proxy.
  - [How to test](https://neat-iodine-05e.notion.site/Test-debug-e7b8e523931345498131169bd6095b9a)
  - The test cases we used are located in `./docker_deploy/testcases.txt`. Corresponding logs are located in `./docker_deploy/logs/proxy.log`.
