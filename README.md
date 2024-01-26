# API_Testing

bootcamp_project
﻿

GET
https://reqres.in/..base request
https://reqres.in/
﻿

GET
get page 2 users
https://reqres.in/api/users?page=2
﻿

Query Params
page
2
GET
user 2 info
https://reqres.in/api/users/2
﻿

GET
list not found user case
https://reqres.in/api/users/23
﻿

POST
add user
https://reqres.in/api/users
﻿

Body
raw (json)
json
{
    "name": "xyz",
    "job": "leader"
}
PUT
update user with PUT
https://reqres.in/api/users/2
﻿

Body
raw (json)
json
{
    "name": "abc",
    "job": "engg"
}
PATCH
update user with PATCH
https://reqres.in/api/users/2
﻿

Body
raw (json)
json
{
    "name": "morpheus",
    "job": "tester"
}
DELETE
delete user
https://reqres.in/api/users/2
﻿

POST
register successful
https://reqres.in/api/register
﻿

Body
raw (json)
json
{
    "email": "eve.holt@reqres.in",
    "password": "pinpong"
}
POST
register unsucceful
https://reqres.in/api/register
﻿

Body
raw (json)
json
{
    "email": "sydney@fife"
}
POST
login successful
https://reqres.in/api/login
﻿

Body
raw (json)
json
{
    "email": "eve.holt@reqres.in",
    "password": "cityslicka"
}
POST
login unsuccessful
https://reqres.in/api/login
﻿

Body
raw (json)
json
{
    "email": "peter@klaven"
}
GET
delay response
https://reqres.in/api/users?delay=4
﻿

Query Params
delay
