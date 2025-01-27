# python_rest_tutorial

Example project to show how to to build and design RESTful web services using Python, Flask, Docker and MongoDB.

Here is an article you can follow to create this project from the beginning:
https://www.dvt.co.za/news-insights/insights/item/355-restful-web-services-using-python-flask-docker-and-mongodb

Inside the root project you can run

```
sudo docker-compose build
```

and then run the folowing to start the container and expose the API:

```
sudo docker-compose up
```

Once the container is running, you can access it by opening your browser and typing in localhost:5000/hello. This should 
display a "Hello World!" message.

There are also other endpoints to test with, and can be found in the article mentioned at the top.
