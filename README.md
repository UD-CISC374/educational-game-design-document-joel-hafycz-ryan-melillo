# educational-game-design-document-joel-hafycz-ryan-melillo

+# Game Name

## Elevator Pitch

Computer science is a growing industry. Now that there is much demand for computer scientists, better programmers are wanted. The best way for better programmers is to start children learning early. Our game will teach children important concepts regarding computer science. Starting them young will make them better programmers later in life.

## Influences (Brief)

- *Influence #1*:
  - This Is The Only Level (game)
  - Explanation: While thinking through game ideas, I was drawn to games I enjoyed growing up, something I used to play. This game is a platformer in which you complete puzzles. I thought and interesting way to present these learning objectives would be working through puzzles in a way similar to that game.
- *Influence #2*:
  - LightBot (game)
  - Explanation: This game essentially teaches functional decomposition in reverse. The game limits the amount of commands that you can give to the robot(with the goal of having him reach the light bulb). Some levels are impossible to complete if you do not combine commands into groups and use these groups multiple times(for loops).
- *Influence #3*:
  - Medium: IDES
  - Explanation: We hope to design the game to at least have a similar feel to that of an IDE, or something similar to that

## Core Gameplay Mechanics (Brief)

*Give a very high-level description of any core gameplay mechanics*

- Platforming
  - Using arrow keys (or WASD) to navigae through the levels and using spacebar to jump
- Puzzles
  - Tasks emulating the theme of coding ideas, such as for loops
- Power-ups / pick-ups
  -Aspects of the level changing for the level for the benefit of the player

# Learning Aspects

## Learning Domains

This game uses analyzing applying and understanding concepts that are comonplace in the world of programming, such as scope, loops, and recursion. 

## Target Audiences

Those in k-12 playing these games during computer lab to gain interest in computer science, as well as those in college struggling with certain ideas in programming

## Target Contexts

K-12 computer labs during free time, high school labs during free time, possibly college 

## Learning Objectives

- *Short Name*: By the end of the game, players will be able to predict the behavior of a for loop in the context of the game, and match the in-game components to components of a real coding for loop
- *Short Name*: By the end of the game, players will be able to predict the behavior of a for while loop in the context of the game, and match the in-game components to components of a real coding for loop
- *Short Name*: By the end of the game, players will be able to identify whether a variable is global or local

## Prerequisite Knowledge

*What do they need to know prior to trying this game?*

- Participants should have knowledge of highschool level math
- Participants would have a much easier time with basic programming knowledge

## Assessment Measures

- Pre game, participants will be assessed through a quiz that we have made
- Post game, participants will be assessed through a similar quiz that we have made

# What sets this project apart?

- This game presents a visual representation of programming logic that is underutilized or poorly executed upon when trying to introduce coding concepts to new learners. The player engages in a fun game to later have the game mechanics equated to programming components, which generally results in better retention.
- Not many games growing up involve any sort of programming, or major logic puzzles, so children are introduced to these concepts at an earlier age, and can become interested in the field
- Students in early computer labs class tend to play games on coolmathgames.com, or adventuregames.com etc, and could come into contact with this game instead

# Player Interaction Patterns and Modes

## Player Interaction Pattern

You begin in a level selector, where each level is a few lines of code representing a function. Most of these levels will be locked and can only become unlocked through completing a previous level. Each level is a function which is used in an overarching Main function. You play as a variable in an array of variables, traversing each function through platforming and puzzles. Your final goal is to complete each level in the fastest amount of time with the most points.

## Player Modes

- Single player mode: Play through mode, where the player is able to play through the game like normal, completeing puzzles and platforming.

# Gameplay Objectives

- *Primary Objective #1*:
    - Description: Finish the level
    - Alignment: Finishing the level will allow the player to progress the game, reaching new functions and learning more
- *Primary Objective #2*:
    - Description: Complete puzzles
    - Alignment: These puzzles introduce concepts of coding compontents. For example, 
- *Primary Objective #3*

# Procedures/Actions

- left -> left movement
- right -> right movement
- up -> jump action
- down -> crouch action?
- e -> use/interact with action
- r -> possible shoot action


# Rules

- 3 Lives to begin with
- Ability to find more lives around the game
- Pick up power ups to help progress through levels

# Objects/Entities

- Levels -> including puzzles, platforming, and enemies
- Enemy -> running into these enemies moving around will cause you to lose a life and reset your level
- Spikes -> same thing as enemies
- Coins -> pickup to gain points
- Levers -> open doors / passageways
- Doors -> open up with lever
- Player -> a variable that depends on the level

## Core Gameplay Mechanics (Detailed)

- *Core Gameplay Mechanic #1*: Movement
  -There are many different kinds of movement. Using the arrow keys, you can move left with left, right with right, jump with up or spacebar, and you can crouch with down. You can avoid enemies by jumping past them or running away from them. You also need to use this movement to reach the end of levels, or pull levers to complete puzzles.
- *Core Gameplay Mechanic #2*: Interactions
  -You can interact with levers and buttons by pressing the e key
  -If you touch a spike or enemy you lose a life and respawn
  -You can pick up coins to increase your points
  -You can jump on platforms to progress through the levels
- *Core Gameplay Mechanic #3*: Puzzles
  -You can complete puzzles through things like pressing levers, avoiding enemies and spikes, picking up things in a certain order, destroying things in a certain order, etc.

    
## Feedback

The shorter the time you complete the game in, the more points you will recieve. You will be able to see if players understand concepts and how well they are doing based on how many points they get. Long term wise, our mechanics and game designs build off of the lower level concepts. So you should be able to do all the puzzles if you begin to actually learn the concepts presented

# Story and Gameplay

## Presentation of Rules

The first few levels will have popups that explain the mechanics in a quick and efficient manor. There will be points displayed at the top, as well as lives so the player will understand there is a certain amount of lives and score.

## Presentation of Content

Learning Objectives will be taught through the completion of puzzles and will also be given as little interaction windows to gain more knowledge of the learning objectives

## Story (Brief)

The game begins with someone programming some simple functions. When you start the game you zoom into one of the functions and play through the level as one of the variables in the scenario, as if you were increasing in value, or having your value assigned to a different value. You progress through a set of functions that are all being called by a Main function (which is the boss), so you can see how a single variable progresses through the function, using helper functions and temporary varibles (powerups) to allow you to get through the levels more easily.

## Storyboarding

https://imgur.com/a/qI00Al2

https://imgur.com/a/iiAXZvp

# Assets Needed

## Aethestics

*Give a sense of the aesthetics of your game, the spirit and atmosphere. Use descriptive, evocative words that can help the reader understand the emotional response of your game.*

The game will put you "inside" of the code; The player will be the various elements of the loop, the enemies will be distractions or problems(video games, missing semi-colons, etc.). There will be an upbeat 8-bit feel to the game, and similar to the description of Inde the Cat, will be cartoonish and light-hearted to build a positive atmosphere. Think Cuphead aesthetically but a bit less creepy and more 8-bit style (and certainly less difficult). 

## Graphical

- Characters List
  - Elements of Array as Player moving through level
  - Enemies:
    - Video game references
    - Common Coding Errors(" missing ; ")
    - Other funny/common distractions
  - *...*
- Textures:
  - *Texture 1*
  - *Texture 2*
  - *...*
- Environment Art/Textures:
  - *Environment Texture 1*
  - *Environment Texture 2*
  - *...*


## Audio


*Game region/phase/time are ways of designating a particularly important place in the game.*

- Music List (Ambient sound)
  - General game music: https://www.youtube.com/watch?v=jHcWhQUmJ8E
  - *Game region/phase/time*: *Example 3*, *Example 4*
  
*Game Interactions are things that trigger SFX, like character movement, hitting a spiky enemy, collecting a coin.*

- Sound List (SFX)
  - Jump mario like PING sound
  - Boop sound for landing on enemies
  - Cheesey death sound for being hit by enemies
  - Some silly video-game rage sound clip for falling into the deathly clutches of video game land
  - superrrrr cheesy, overly joyous end of level sound


# Metadata

* Template created by Austin Cory Bart <acbart@udel.edu>, Mark Sheriff, Alec Markarian, and Benjamin Stanley.
* Version 0.0.3
