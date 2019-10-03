# liri-node-app
Home work week 10

ABOUT THE APP
LIRI is a Language Interpretation and Recognition Interface. LIRI is a command line node app that takes in parameters and gives back data. The user has the option of using four commands (listed below) in conjuntion with specific parameters associated with the commands. The Commands are:

concert-this

spotify-this-song

movie-this

do-what-it-says

HOW TO USE LIRI

Step by Step instructions
Open your terminal such as Bash.

Navigate to the folder that contains the liri.js file.

Depending on the command you run, the output will vary.

Example 1: Run the concert-this command

 node liri.js concert-this <name of artist or band>
Output: The system will display a list of all events and locations where the artist or band will perform. It can result in multiple records. The system will also log all the results in the log.txt file. See screen-shot below:
![concert](https://user-images.githubusercontent.com/52688618/66103628-3c73e380-e56b-11e9-9643-d59f4d5ef3bf.PNG)

Example 2: Run the spotify-this-song command

 node liri.js spotify-this-song <name of song>
Output: The system will display a list of information associated with the song. It can result in multiple records. The system will also log all the results in the log.txt file. See screen-shot below:

![song](https://user-images.githubusercontent.com/52688618/66103708-72b16300-e56b-11e9-9773-fa2323dafaa5.PNG)

Example 3: Run the movie-this command

 node liri.js movie-this <name of movie>
Output: The system will display information associated with the movie. The system will also log all the results in the log.txt file. See screen-shot below:
![movie](https://user-images.githubusercontent.com/52688618/66103774-95437c00-e56b-11e9-9374-d8898be6c336.PNG)

Example 4: Run the do-what-it-says command

 node liri.js do-what-it-says
Output: The system will read the text in the random.txt file, and perform the comman listed in the random.txt file.

See screen-shot below:

![do-what-it-says](https://user-images.githubusercontent.com/52688618/66103851-c15efd00-e56b-11e9-86cf-1986944762dd.PNG)

TECHNOLOGIES USED
Javascript
Nodejs
Node packages:
Node-Spotify-API
Request
Moment
DotEnv
APIs used:
Bands in Town
OMDB
Git
GitHub
