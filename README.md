# CRUD App with Spring Boot

This is the code developed in the tutorial on creating a flexible CRUD app with Spring Boot.

It features full REST compliance and an embedded database.

### Requirements

- Maven
- JDK 7

### Running

To build and start the server simply type

```sh
$ mvn spring-boot:run
```

from the root directory.

### Using

You can see what urls are available using curl:

```sh
$ curl localhost:8080
```

You can view existing people objects using a similar request:

```sh
$ curl localhost:8080/persons
```

and can create new ones using a POST:

```sh
$ curl -x POST -H "Content-Type:application/json" -d '{ "firstName" : "Karl", "lastName" : "Penzhorn" }' localhost:8080/persons
```

### Todo

 - Switching out database
 - Paging results
 - Writing tests

### License
----

MIT

