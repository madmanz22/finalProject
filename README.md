# Project Liminality

For the final project I chose to make a roblox game. The theme of the game is inspired by the Backrooms. About a year ago I decided to start this game ,but I never finished it. So when I started back working on I already had half the map modeled. This project has been a decent challenge for me as I had very little experience with Lua. The map in pretty much a large maze that is made to look like level 0 of the backrooms. When the player loads into the game, there are three possible spawn locations, a Gui screen message appears on the screen introducing the game and tells the player to find an exit. In this message the player is also warned of enemy npcs that will kill the player if interacted with. These npcs have a scipt in each of them that allows them to track the player if they have been spotted. There are variables that decide how long the npc's "memory is" meaning how long after not seeing the player will they still track. The npc's also have "patrol routes" which makes them go to certian "patrol parts" when they do not detect an enemy. This makes the Npc's feel as if they are roaming around the maze looking for the player. If a npc touches a player they die and recive a jumpscare. Also I decided to implement a player kick when the player dies as I have seen it in other roblox horror games and thought it was cool. When a player is near the exit a Gui screen message apears telling them they are close. After reaching the end the player is teleported to the winner area and a message pops up saying they reached the exit. I found the npcs to be the most challenging task I faced when doing this project. Since I have little experinece in lua I followed some tutorials which most of which had outdated code. Implementing the jumpscare into the npcs was also pretty difficult as a had to learn what folder to put objects in to make them accesible. If I had more time on this project I would definetly change and refine the map and npc models to make the game feel more scary. I also would work on getting the npcs tracking to be fully fluid and not as janky. Overall I enjoyed the experince this project gave and I think I will continue to develop this game.

Video Demostration: https://youtu.be/CQhWS35Z3UI


LOG:
    not sure how to connect roblox studio with github so i will just upload the code thats used in the project 

    4/14 I went back today and found out the first video helping me did not work so i will try another one.
    Updated the enemy tracking and started to finish up modeling the map
    still working on enemy tracking all the guides are old

    4/15 going to figure out how to teleport the player when they finish the maze. This will teleport them to a winners type roome letting the player know they have beat the game.

    Also going to try and find out how to add a jumpscare to when the monster kills the player 

    the first teleporting tutorial did not work so I have to find another one (I think roblox has this thing where old tutorials just don't work)

    4/16 adding a background sound effect for the buzz of the lights
    also updated the enemy pathfinding and going to add a sound effect when player is killed
    going to look into how i could add a jumpscare and other cut scenes 

    4/24 Made the server size to one player. changed a setting to lock the player into first person while playing. I also changed the graphics settings of the studio to make the game visualy better. Still need to find out how to make a jump scare and effects on the player's screen. I am also going to look into how to make the eneimes appear as the player in the lobby. Wrote a little story for the game nothing too crazy. I also want to add a playlist of songs for the background music that plays the songs in a random order but i will wait until the end to do that.
    I added a guiscript that changes the origninal mouse into a smaller one

    2/25 going to see how to change the enemy model. Try and figure out how to add animations to the enimies tracking. I also will maybe try and improve the enemy tracking as of right now its clunky and not smooth. Tweaked the graphics settings to improve the look of the game. I am also going to edit the winner area to make it feel less rushed. I added varients of the eneimies (I just tweaked some of the stats like detection range and speed)
