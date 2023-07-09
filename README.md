# Simple Notes App
This is a simple notes app built with React and Django.


## My work is to deploy this application on the Nginx web server and you can check this out - 
![image](https://github.com/HitanshuGupta/nginx-fullstack-app-deployment/assets/72181617/cb8530ba-551a-4f1c-9144-16429c5199cb)

#### HERE IS THE LINK - [notes.hitanshu.live](http://notes.hitanshu.live/) (It might not work later because the app is running on aws ec2 and it will cost afterward. )

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
