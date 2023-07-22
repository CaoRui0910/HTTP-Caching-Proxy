# HTTP-Caching-Proxy

### 1. Project Introduction:
- Used C++ to implement a HTTP caching proxy server so that users can access different websites through this proxy server.
- It can handle GET, POST, CONNECT requests and cache responses.

### 2. Usage
- This project is deployed with docker, to run it, `cd` into the docker-deploy folder. Then run:
  - `sudo chmod 777 -R .`
  - `sudo docker-compose up`
- Next, you must configure your web browser to use this proxy. Once set up, you can access web pages through this proxy.

### 3. Notes
- The test cases we used are located in `./docker_deploy/testcases.txt`.
- Corresponding logs are located in `./docker_deploy/logs/proxy.log`
