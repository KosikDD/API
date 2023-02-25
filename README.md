# API

Registration
request: 
{
  "user": {
    "username": "KosikDD",
    "email": "danilakosik.of@gmail.com",
    "password": "123"
  }
}

response: 
{
  "user": {
    "email": "Kosikdd@gmail.com",
    "username": "KosikDanila",
    "bio": null,
    "image": "https://api.realworld.io/images/smiley-cyrus.jpeg",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6Iktvc2lrZGRAZ21haWwuY29tIiwidXNlcm5hbWUiOiJLb3Npa0RhbmlsYSIsImlhdCI6MTY3NzMzMTA4NCwiZXhwIjoxNjgyNTE1MDg0fQ.5q917HBdIy0MXO8s7uYifo_R-ogyx2IOLdJ1__cYPqA"
  }
}

Authentication


request:
{
  "user": {
    "email": "Kosikdd@gmail.com",
    "password": "123"
  }
}

response: 
{
  "user": {
    "email": "Kosikdd@gmail.com",
    "username": "KosikDanila",
    "bio": null,
    "image": "https://api.realworld.io/images/smiley-cyrus.jpeg",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6Iktvc2lrZGRAZ21haWwuY29tIiwidXNlcm5hbWUiOiJLb3Npa0RhbmlsYSIsImlhdCI6MTY3NzMzMTMwMSwiZXhwIjoxNjgyNTE1MzAxfQ.3SKwJx4XnGR5PRyhVx34IR1uJ5rh68twMtJemRTLC_A"
  }
}


Endpoints -> Get Current User

request: 
'-H Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6Iktvc2lrZGRAZ21haWwuY29tIiwidXNlcm5hbWUiOiJLb3Npa0RhbmlsYSIsImlhdCI6MTY3NzMzMTMwMSwiZXhwIjoxNjgyNTE1MzAxfQ.3SKwJx4XnGR5PRyhVx34IR1uJ5rh68twMtJemRTLC_A'

response:
{
  "user": {
    "email": "Kosikdd@gmail.com",
    "username": "KosikDanila",
    "bio": null,
    "image": "https://api.realworld.io/images/smiley-cyrus.jpeg",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6Iktvc2lrZGRAZ21haWwuY29tIiwidXNlcm5hbWUiOiJLb3Npa0RhbmlsYSIsImlhdCI6MTY3NzMzMTU2NiwiZXhwIjoxNjgyNTE1NTY2fQ.vwOxn1ScavJEMlWb5XAVf1bflAW3HGNXWTlbvl4TpzI"
  }
}
