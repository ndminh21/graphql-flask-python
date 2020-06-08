# graphql-flask-python

## Implement GraphQL server using Python Graphene
Graphene is basically python GraphQl client library. with the help of that, we can create your GraphQL Server.

### Step 1: Setting up your project
First, to set up a project create a directory/folder like below
```
$ mkdir graphql-flask
$ cd graphql-flask
```
It's time to create a virtual environment. So we can avoid conflict, from global packages.
It helps us to manage different packages versions for individual projects. if you don't have a virtual environment then
install it using below command
```
$ pip install virtualenv
$ virtualenv venv
$ source venv/bin/activate
```
Install require dependencies, using below command:
```
$ pip install flask flask-graphql flask-migrate flask-sqlalchemy graphene graphene-sqlalchemy
```
