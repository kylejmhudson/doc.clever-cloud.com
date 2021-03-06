---
title: MongoDB
position: 5
---


## MongoDB <span class="cc-beta pull-right" title="Currently in Beta version"></span>
<div class="alert alert-hot-problems">
  <h5>Note for Beta Version</h5>
  <div>MongoDB is free during the beta period. No credits wil be charged.</div>
</div>
MongoDB is an open source NoSQL document-oriented database.

### Add a database

[This article](/databases-and-services/add-service/) describes the process to add a database on Clever Cloud.

### Connect to your database

#### Standard connection string format

You will receive your MongoDB credentials by email. The URI to connect it to your application is the following:  

``mongodb://db_username:db_password@db_host/db_name``


#### Command line connection

You can connect to your database like on your local machine with this prompt:

``mongo db_name -u db_username -p db_password --host db_host``

#### Web administration tools

Below are some examples of web tools that can be used to manage your Mongo database :

* [https://github.com/wearefractal/smog](https://github.com/wearefractal/smog)

<figure class="cc-content-img">
  <img src="/assets/images/mongo-smog-screenshot.png"/></a>
</figure>
<figcaption>
    Smog admin panel overview
</figcaption>

* [https://github.com/andzdroid/mongo-express](https://github.com/andzdroid/mongo-express)

<figure class="cc-content-img">
  <img src="/assets/images/mongo-express-screenshot.png"/></a>
</figure>
<figcaption>
    Express-Mongo admin panel overview
</figcaption>


### MongoDB + Node.js sample application

This [page](/nodejs/nodejs-mongodb-sample-app/) points out the process to deploy a Simple MongoDB + Node.js Todolist application on Clever Cloud.
