# ios-term-3-portfolio-2020-BurritoConqueror
ios-term-3-portfolio-2020-BurritoConqueror created by GitHub Classroom


During this term I learned a lot about Xcode. My first project the pooltest app I was experimenting and
refreshing my knowledge of xcode. I learned how to launch the ball in a certain direction by pulling back on the ball.
I also refreshed my knowledge on how collisions work and detecting the collisions. I researched how ot use SKActions
in order to have the balls shrink down in size and remove their physicsbody to make it look like they were falling down
a hole. My next project was air hockey. At first I ran into a problem with being able to hit the puck. The usual way I
moved thing to where people were touching was to set the position of the sprite equal to the location of the touch. However,
this didn't carry any momentum with it so when the hitter contacted the puck, the puck didn't actually get hit it just
stuck to the hitter. To solve this I used a similar method to how I launched the ball in my pool test app. Instead of applying
impulses I changed the velocity of the hitters to the difference between the x and the y of the hitter and the touch location.
This solved the problem because the puck now actaully moved rather than just being placed on the location. After solving
that problem I learned how to switch scenes in order to make a main menu. After I finished learning about switching screens
I improved the game by adding a score system and making it the first player to 7 points wins.
