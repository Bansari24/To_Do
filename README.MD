## Docker + React App + API Express + MySQL

This project implements a quick start up project using the facebook`s create-react-app as the app front end,
a configured express API server connected to a MySQL database (easy to change) and optionally the phpMyAdmin
preconfigured as the database admin. And even better, all stack works as Docker containers.

After install Docker, run the following code to setup the development or production stack:

````
$ npm install -g create-react-app  

$ docker-compose up
````

And that`s all, in the docker-compose.yml file its possible to change the enabled ports, database password, dev/production envoroments and other simple configs, change it as you need.


To rebuild and run:

```
docker-compose down && docker-compose build && docker-compose up -d
```

# ScreenShots
![todo1](https://user-images.githubusercontent.com/57503162/82068655-4680c780-96a0-11ea-8d2c-9eee957a4abb.jpeg)
![todo2](https://user-images.githubusercontent.com/57503162/82068656-4680c780-96a0-11ea-9f81-f9040f09f892.jpeg)
![todo3](https://user-images.githubusercontent.com/57503162/82068659-4680c780-96a0-11ea-9504-f761686af413.jpeg)
![todo4](https://user-images.githubusercontent.com/57503162/82068660-47195e00-96a0-11ea-843f-d813e0fc4ec2.jpeg)

