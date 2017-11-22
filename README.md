# python-flask-microservice

This is the code used in this series of articles: 

- https://medium.com/p/building-microservices-with-python-part-i-5240a8dcc2fb

This is a basic approach of building a Microservice on top of Flask, with some useful packages like:

- [Flask](http://flask.pocoo.org/)
- [Flask-Injector](https://pypi.python.org/pypi/Flask-Injector)
- [Connexion](https://github.com/zalando/connexion)

# Requirements

We are going to build a microservice to index rooms information coming from another service (crawler). This service will be responsible for indexing the information into Elasticsearch.

This is a modification to ssola's github to show just the first stage of the project.
I had problems following along as I am new to python, connexion and flask and am also learning this and the instructions on the
step by step does not have all the steps. I kinda tinkered around until I got it working and also saw that lots of others had problems
so I'm posting this as a part 1 solution so that you guys can get it running also before moving on to part 2.

All rights go to ssola and thank you, Sergio, for leading me into py, connexion and flask for microservices.

# microservices-part1
