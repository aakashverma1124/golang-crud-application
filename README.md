# golang-crud-application
This is a complete crud based GoLang application with ElephantSQL. ElephantSQL is a PostgreSQL database hosting service.
***
# Project Development Directory Structure
***
<pre>
|- go-crud 
    |- middleware
        |- handlers.go
    |- models
        |- models.go
    |- router
        |- router.go
    |- .env
    |- main.go
</pre>
***

# models

The models package will store the database schema. We will use struct type to represent or map the database schema in golang.

Create a new folder models in the go-crud project.
Create a new file models.go in the models. (check file for the code)

# middleware

The middleware package is the bridge between APIs and Database. This package will handle all the db operations like Insert, Select, Update, and Delete (CRUD).

Create a new folder middleware in the go-crud project and create a new file handlers.go inside it. (check file for the code)