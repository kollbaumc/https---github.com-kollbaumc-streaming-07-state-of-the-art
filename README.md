# streaming-07-state-of-the-art

## Streaming Game Data
## Chris Kollbaum 2/25/2023

# What is this project?

I am a big sports fan and a big Iowa fan, so when a classmate reminded me of this data on our discussion board, this seemed like a good option for this custom project.  This project is streaming the progress of the Iowa-Indiana Basketball Game.  It will send the score updates to the "Game" queue and will be received by a listener.  This listener will give score alerts that will alert the person receiving these updates to whether the game may turn into a blowout or whether the game is getting close and you need to tune in.  The data was from ESPN.com https://www.espn.com/mens-college-basketball/playbyplay/_/gameId/401484874

## Game Emitter

This code captures data from a file and sends it to the game queue.

![game](Gameemitter.png)

## RabbitMQ Admin Site and Game Queue