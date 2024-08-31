# Magshimim Bat-Yam, You May Want To Read This

In this challenge, I want you to learn about docker and show me that you are able to do your own research and understand 
how to break the security of this application.

Thus, it makes sense for you to run this app.

# Learning Goals

This exercise teaches you about docker, docker-compose, nginx, flask, and how to think like a hacker.

# How to Run

First, make sure you have docker installed; it's will be helpful since all your project's components will run via docker

Simply run `docker-compose up` and you can access the app via `localhost:80`.

After you have done it, you can send HTTP requests to this Nginx server using your browser, or the `curl` command:

```
curl http://localhost:80/
```
The server response should be "Hello , World!"
With the curl command, we sent a request to Nginx, a server that acts as a "reverse proxy." Nginx passes the request to the Flask application and returns the result to us.

(Bonus: read more about the curl command using `man curl`, it is one of the most valuable commands out there)

# Your Goal

First, before solving the challenge - Let's learn about Docker:

#### Docker image
Run the following command:

```
docker images
```

Read about docker images and understand what they are.

#### Docker container
Run the following command:

```
docker ps
```

Read about docker container

#### Dockerfile
Run the following command:

```
less Dockerfile
```

Read about Dockerfile, understand the "FROM" keyword
What are the differences between docker and VM?

#### docker-compose.yml
Run the following command:

```
less Dockerfile
```

If you are not familiar with yaml files, read about them, and then read about docker-compose and why we need them. Read also about docker's volume, port-mapping and networks

#### docker troubleshooting

Learn about how to run commands inside a docker container, and try to attach to the nginx's container, and from there print the nginx.conf file. 

Also, it's a great opportunity to read about Nginx. The nginx's configuration tells nginx to block the access to the Admin's endpoint in the flask application - make sure that you understand the configuration. 

For the challenge, your mission is to be an admin, which means getting the admin message without being blocked. Good luck.
