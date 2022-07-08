### Register user

```
POST api/User
```

Create a new user

#### Request

```
{
    "firstName": "name",
    "lastName": "name",
    "email": "real@mail.no",
    "password": "password"
}

```

#### Response

```
200 OK

{
    "id": "aaaa-bbbb",
    "firstName": "name",
    "lastName": "name",
    "email": "real@mail.no",
    "password": "password"
}
```


### Register service

```
POST api/service
```

#### Request
```
{
    "name": "cool-app"
}
```

#### Response
```
200 OK

{
    "id":   "aaaa-bbbb",
    "name": "cool-app",
    "ownerId": "aaaa-bbbb"
}
```