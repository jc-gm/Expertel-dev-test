## How to complete the test

- Clone this repository
- Run composer to install the dependencies
- Run the migrations to create the tables
- Modify the code as you see fit (see below for input format)
- Commit your code and send us a link to your repository
- Important: Do not modify the routes


## Endpoint Input

The endpoint will receive a JSON object as the body.  Meeting name is a string, start_time and end_time are both datetimes represented as strings, and users is an array of all users that are required to attend the meeting.

The input to this endpoint will be similar to the following JSON  object. The values will change, but keep the properties the same

    {
        "meeting_name": "Meeting 1",
        "start_time": "2023-10-29 20:30:00",
        "end_time": "2023-10-29 21:30:00",
        "users": [1,2,3]
    }
