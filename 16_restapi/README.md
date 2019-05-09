Go Lang REST API
=================

* Simple RESTful API to create, read, update and delete books.

## Quick Start


``` bash
# Install mux router
go get -u github.com/gorilla/mux
```

``` bash
go build
./16_restapi
```

## Endpoints

### Get All Books
``` bash
GET api/books
http://localhost:8000/books
```
### Get Single Book
``` bash
GET api/books/{id}
http://localhost:8000/books/{id}
```

### Delete Book
``` bash
DELETE api/books/{id}
http://localhost:8000/books/{id}
```

### Create Book
``` bash
POST api/books

# Request sample
# {
#   "isbn":"4545454",
#   "title":"Book Three",
#   "author":{"firstname":"Harry",  "lastname":"White"}
# }
```

### Update Book
``` bash
PUT api/books/{id}
http://localhost:8000/books/{id}

# Request sample
# {
#   "isbn":"4545454",
#   "title":"Updated Title",
#   "author":{"firstname":"Harry",  "lastname":"White"}
# }

```

