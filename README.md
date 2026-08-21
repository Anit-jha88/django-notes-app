# Simple Notes App for Devops Community
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/Anit-jha88/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```
3. Create a network
```
docker network create notes-app-nw
```

4. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
