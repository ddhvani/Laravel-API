# twitterapp-

Laravel Twitter API Documentation

Functionality Description:
Develop an API endpoint that returns data used to graph the number of tweets per hour for a
given user over a 48 hour period.

API Endpoint
 GET api/tweets/{screen_name}
 
 
Returns hourly tweets count for the tweets posted by the user indicated by the screen_name
for past 48 hours from now.

Path Parameters
screen_name: required

Resource URL (Test Server)
http://twitterapp.tp-team.com/api/tweets/{screen_name}


Example
Using svhsydney as a screen_name to test the API
http://twitterapp.tp-team.com/api/tweets/svhsydney



Response

Correct screen_name

Status: 200 OK
{
"from": "Sun, 09 Jun 2019 06:00:00 +0000",
"to": "Tue, 11 Jun 2019 06:59:59 +0000",
"by_hour": 
[
{
"time": "11/06/2019 06:00 AM - 11/06/2019 07:00 AM",
"count": 4
},

{
"time": "11/06/2019 05:00 AM - 11/06/2019 06:00 AM",
"count": 17
},

{
"time": "11/06/2019 04:00 AM - 11/06/2019 05:00 AM",
"count": 11
},

{
"time": "11/06/2019 03:00 AM - 11/06/2019 04:00 AM",
"count": 11
},

{
"time": "11/06/2019 02:00 AM - 11/06/2019 03:00 AM",
"count": 7
},

{
"time": "11/06/2019 01:00 AM - 11/06/2019 02:00 AM",
"count": 1
},

{
"time": "11/06/2019 12:00 AM - 11/06/2019 01:00 AM",
"count": 2
},

{
"time": "10/06/2019 11:00 PM - 11/06/2019 12:00 AM",
"count": 2
},

{
"time": "10/06/2019 10:00 PM - 10/06/2019 11:00 PM",
"count": 3
},

{
"time": "10/06/2019 09:00 PM - 10/06/2019 10:00 PM",
"count": 2
},

{
"time": "10/06/2019 08:00 PM - 10/06/2019 09:00 PM",
"count": 1
},

{
"time": "10/06/2019 07:00 PM - 10/06/2019 08:00 PM",
"count": 3
},

{
"time": "10/06/2019 06:00 PM - 10/06/2019 07:00 PM",
"count": 6
},

{
"time": "10/06/2019 05:00 PM - 10/06/2019 06:00 PM",
"count": 13
},

{
"time": "10/06/2019 04:00 PM - 10/06/2019 05:00 PM",
"count": 11
},

{
"time": "10/06/2019 03:00 PM - 10/06/2019 04:00 PM",
"count": 9
},

{
"time": "10/06/2019 02:00 PM - 10/06/2019 03:00 PM",
"count": 10
},

{
"time": "10/06/2019 01:00 PM - 10/06/2019 02:00 PM",
"count": 12
},

{
"time": "10/06/2019 12:00 PM - 10/06/2019 01:00 PM",
"count": 14
},

{
"time": "10/06/2019 11:00 AM - 10/06/2019 12:00 PM",
"count": 19
},

{
"time": "10/06/2019 10:00 AM - 10/06/2019 11:00 AM",
"count": 15
},

{
"time": "10/06/2019 09:00 AM - 10/06/2019 10:00 AM",
"count": 16
},

{
"time": "10/06/2019 08:00 AM - 10/06/2019 09:00 AM",
"count": 16
},

{
"time": "10/06/2019 07:00 AM - 10/06/2019 08:00 AM",
"count": 14
},

{
"time": "10/06/2019 06:00 AM - 10/06/2019 07:00 AM",
"count": 13
},

{
"time": "10/06/2019 05:00 AM - 10/06/2019 06:00 AM",
"count": 11
},

{
"time": "10/06/2019 04:00 AM - 10/06/2019 05:00 AM",
"count": 18
},

{
"time": "10/06/2019 03:00 AM - 10/06/2019 04:00 AM",
"count": 18
},

{
"time": "10/06/2019 02:00 AM - 10/06/2019 03:00 AM",
"count": 5
},

{
"time": "10/06/2019 01:00 AM - 10/06/2019 02:00 AM",
"count": 2
},

{
"time": "10/06/2019 12:00 AM - 10/06/2019 01:00 AM",
"count": 1
},

{
"time": "09/06/2019 11:00 PM - 10/06/2019 12:00 AM",
"count": 1
},

{
"time": "09/06/2019 10:00 PM - 09/06/2019 11:00 PM",
"count": 1
},

{
"time": "09/06/2019 09:00 PM - 09/06/2019 10:00 PM",
"count": 2
},

{
"time": "09/06/2019 08:00 PM - 09/06/2019 09:00 PM",
"count": 1
},

{
"time": "09/06/2019 07:00 PM - 09/06/2019 08:00 PM",
"count": 3
},

{
"time": "09/06/2019 06:00 PM - 09/06/2019 07:00 PM",
"count": 5
},

{
"time": "09/06/2019 05:00 PM - 09/06/2019 06:00 PM",
"count": 10
},

{
"time": "09/06/2019 04:00 PM - 09/06/2019 05:00 PM",
"count": 10
},

{
"time": "09/06/2019 03:00 PM - 09/06/2019 04:00 PM",
"count": 6
},

{
"time": "09/06/2019 02:00 PM - 09/06/2019 03:00 PM",
"count": 10
},

{
"time": "09/06/2019 01:00 PM - 09/06/2019 02:00 PM",
"count": 10
},

{
"time": "09/06/2019 12:00 PM - 09/06/2019 01:00 PM",
"count": 18
},

{
"time": "09/06/2019 11:00 AM - 09/06/2019 12:00 PM",
"count": 10
},

{
"time": "09/06/2019 10:00 AM - 09/06/2019 11:00 AM",
"count": 12
},

{
"time": "09/06/2019 09:00 AM - 09/06/2019 10:00 AM",
"count": 14
},

{
"time": "09/06/2019 08:00 AM - 09/06/2019 09:00 AM",
"count": 11
},

{
"time": "09/06/2019 07:00 AM - 09/06/2019 08:00 AM",
"count": 17
},

{
"time": "09/06/2019 06:00 AM - 09/06/2019 07:00 AM",
"count": 10
}
]
}

Incorrect screen_name

Status: 500 Internal Server Error
RuntimeException (404)
[50] User not found.

