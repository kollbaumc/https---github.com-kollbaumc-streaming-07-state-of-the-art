# streaming-07-state-of-the-art

# What is this project?

This project is streaming the progress of the Iowa-Indiana Basketball Game.  It will send the score updates to the "Game" queue and will be received by a listener.  This listener will give score alerts that will alert the person receiving these updates to whether the game may turn into a blowout or whether the game is getting close and you need to tune in.  The data was from ESPN.com https://www.espn.com/mens-college-basketball/playbyplay/_/gameId/401484874

## Game Emitter

This code captures data from a file and sends it to the game queue.

![game_emitter](Gameeitter.png)