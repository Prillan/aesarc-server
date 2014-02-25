# AESARC Live StarCraft Data System #

*Everything* here is currently a work-in-progress. Including the
 name. Don not expect anything to work at the moment.
 
 
## Server ##

The server is the main interface of the live data. It provides a way
to access the data uploaded by the client and provides means to keep
track of the different matches and games.

Might contain a useful view for viewers in the future but so far this
is left to tournament organizers.

## Client ##

The client is a small program running on the observer's machine
reading data from the StarCraft extension mod "GameHeart Live Data"
and uploading it to the server.


## Server Interface ##

The server interface consists of a REST API where the configuring
takes place via a HTML interface. 

### HTML ###

Set-up tournaments, manage keys, create players and other admin things.

### REST API ###

Read the data from the server. Which might include things as

 - Get a list of all running tournaments/matches/games.
 - Get detailed updates from running games.
 - Get data from replays from completed games.


## Installing ##

TBA
