# Magshimim Bat-Yam, You May Want To Read This

This challenge is different. I want you to show me an actual bypass here.

Thus, it makes sense for you to run this app.

# Learning Goals

This exercise teaches you about docker, docker-compose, nginx, flask, and how to think like a hacker.

# How to Run

First, make sure you have docker installed; it's will be useful since all your project's components will run via docker

Simply run `docker-compose up` and you can access the app via `localhost:80` (this accesses the Nginx proxy which has the access restrictions in place)

After you have done it, you can send HTTP requests to this server using your browser, or the `curl` command:

```
curl curl http://localhost:80/
```
The server response should be "Hello , World!"

# Your Goal

Your mission is to be an admin, which means getting the admin message without being blocked. Good luck.
