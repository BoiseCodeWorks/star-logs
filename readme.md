## STAR LOGS

![starfleet](starfleet.png)

## Welcome to Starfleet!

We need you to build a new system for starfleet to use to keep track of the captains logs.

### What this means for you

You will need the following schema's:

- Ship
- Log
- Comment

Relationships are as follows

- Logs will have an author (string) and a ship (shipID)
- Comments will have a log they are attached to (logId) and author (string)

Extended challenges

- see if you can emulate the sandbox by taking in the author from the url
- only the author can edit and delete the post
- authors can get all their logs specifically
