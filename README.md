# Prophecy
Prophecy is a tabletop roleplaying game about fate and destiny.
During the game, the players receive a prophecy that describes an impending catastrophe for some fictional world.
They create characters who inhabit that world, write an outline that describes how their characters will try to prevent the catastrophe, and tell the story of their characters' adventures.

Throughout these rules, a variety of common words are used as technical terms to describe how the game is played.
These terms will be Capitalised when they appear in the text and _Italicised_ when they are first introduced.

## Mechanics    
_Mechanics_ are the systems that govern how players interact with the game.
They provide a way for players to describe a fictional world by populating it with [Objects and Aspects](#objects-and-aspects), compose a story set in that world that is comprised of [Scenes](#scenes), and decide how that story plays out by making [Checks](#checks).

### Objects and Aspects
An _Object_ is a person, place, or thing that appears in the story.
An _Aspect_ is a word or short phrase that describes something noteworthy about an Object.
Each Aspect is _Attached_ to a single Object.

#### Characters
A _Character_ is a person who appears in the story and whose actions will be controlled by a single player throughout the game. Characters are Objects. As such, Aspects can be attached to Characters. An Aspect that is Attached to a Character is a _Character Aspect_.
An Aspect that is Attached to any Object that is not a Character is an _Environment Aspect_.

#### Matching Aspects
A pair of _Matching Aspects_ is a set of two Aspects, one Character Aspect and one Environment Aspect, that together allow the Characters to manipulate a Scene to their advantage.
<!-- Pairs of Matching Aspects are used to determine the size of the Dice Pool when making a Check. -->

<!-- #### Example
Recall that in the previous example, the Characters were trying to convince a guard to let them through a checkpoint and that the Aspect "Sterling Reputation" is Attached to the guard who is on duty when the Characters arrive.
The Aspect "Silver Tongue" is Attached to one of the Characters.
If the Players agree that this combination of Aspects might allow the characters to manipulate the Scene to their advantage, perhaps by suggesting that he guard might be amenable to accepting a bribe offered by the Character, then together they would constitute a pair of Matching Aspects. -->

### Scenes
A _Scene_ is a part of the story that describes the events that happen at single time and place.
Every Scene has the following components:
  - ___Setting___ -
    The time and place at which the Scene occurs. The Setting includes the Objects and Aspects that appear in the Scene.
  - ___Objective___ -
    A narrative description of what the Characters are trying to accomplish during the Scene.
  - ___Difficulty Rating___ -
    A number _1 <= d <= 4_ that describes how difficult it is for the Characters to accomplish the Scene's Objective.
  - ___Outcome___ -
    A description of whether the Characters accomplish the Scene's Objective. If so, then the Outcome is a _Success_ and the Scene is resolved successfully. Otherwise, the Outcome is a _Failure_ and the Scene is resolved unsuccessfully.
  - ___Precursors___ -
    Other Scenes which, if resolved successfully, make it easier for the Characters to accomplish the Scene's Objective.

<!-- #### Example
The Characters want to cross the border between two neighbouring kingdoms. It is dusk when they make their way to a "Remote" border crossing on the outskirts of a small town. The border is patrolled by a detachment of soldiers from the "Local Militia". The soldier on duty when the Characters arrive is well-known in town to have a "Sterling Reputation". The guards are on "High Alert" and it will be fairly difficult for the Characters to convince the guard on duty to let them through the checkpoint. The Difficulty Rating of the scene is _d = 3_. -->

#### Sketching Scenes
The players _Sketch_ Scenes when they [Write an Outline](#write-an-outline) describing the how the Characters will try to prevent the impending catastrophe. To Sketch a Scene the players will establish the Setting, define the Objective, and assign the Difficulty Rating for the Scene.

#### Performing Scenes
The players _Perform_ Scenes when they [Tell the Story](#tell-the-story) of the Characters' adventures.
To Perform a Scene the players will describe what happens during the Scene, determine the Outcome of the Scene (see [Checks](#checks)), and describe the narrative consequences of the Characters' actions.

### Checks
The players make a _Check_ to determine the Outcome of each Scene. To make a Check, the players will:
  1. __Assemble a Dice Pool__ -
     A dice pool is made up of one or more six-sided dice.
     One die is added to the dice pool for each pair of Matching Aspects that characters could use to manipulate the scene to their advantage.
     In addition, one die is added to the dice pool for each of the current Scene's Precursors that was resolved successfully.
  2. __Roll the Dice__ -
     The dice in the dice pool are exploding dice.
     That is, for every die that yields a value of `6` one additional die is added to the dice pool.
  3. __Compute the Result__ -
     Any die that yields a value of `1`, `2`, or `3` is a _Miss_.
     Any die that yields a value of `4`, `5`, or `6` is a _Hit_.
     The _Result_ of a roll is the total number of Hits.
  4. __Determine the Outcome__ -
     If the Result of the players' roll meets or exceeds the Scene's Difficulty Rating, then the Outcome is a _Success_, the Characters accomplish the Scene's Objective, and the Scene is resolved successfully.
     Otherwise, the Outcome is a _Failure_, the Characters do not accomplish their Objective, and the Scene is resolved unsuccessfully.

<!-- ##### Example
The Players are making a Check to determine the Outcome of a Scene that has a Difficulty Rating of _d = 3_.
The Players have identified three pairs of [Matching Aspects](#objects-and-aspects) while Performing the Scene and earned two Reward Dice in the Scenes immediately upstream of the current Scene.
Therefore, the Dice Pool consists of five dice.
When rolled, these dice yield the values {`3`, `6`, `5`, `1`, `6`}.
Because two of the dice yielded a value of `6`, two additional dice are added to the pool.
When rolled, these dice yield the values {`2`,`6`}.
Because one of the dice yielded a value of `6`, one additional die is added to the pool.
When rolled, this die yields the value {`4`}.
So, this roll yields the values {`3`, `6`, `5`, `1`, `6`, `2`, `6`, `4`}.
The Result of this roll is five Hits.
This Result exceeds the Difficulty Rating of the Scene so the Outcome of the Check is a Success.    -->

## Gameplay
The game is divided into four phases.
The first three phases are about fate.
The players will [Receive a Prophecy](#receive-a-prophecy) that describes an impending catastrophe for some fictional world, [Create Characters](#create-characters) who inhabit that world, and [Write an Outline](#write-an-outline) of the story that they will tell about those characters.
The fourth phase is about destiny.
The players will [Tell the Story](#tell-the-story) of the Characters' adventures and discover how that story ends.

### Receive a Prophecy
During this phase, the players receive a _Prophecy_ that describes a _Catastrophe_ that is destined to wreak havoc on some fictional world.

To Receive a Prophecy the players describe the the world in which the story is set and the nature of the Catastrophe.
The players should create a situation that the Characters will be able to affect, but doing so will be both difficult and dangerous.

<!-- To Receive the Prophecy, the Players will roll a six-sided die (1d6) to select a random Genre from the [Genre Table](#genre-table) and then roll a six-sided die (1d6) to select a random Catastrophe from the [Catastrophe Table](#catastrophe-table).

### Genre Table
  1. Fantasy
  2. Science Fiction
  3. Horror
  4. Romance
  5. Adventure
  6. Mystery

### Catastrophe Table
  1. War
  2. Revolution
  3. Disease
  4. Natural Disaster
  5. Resource Depletion
  6. Climate Change -->

### Create Characters
During this phase, the players create Characters.
Later in the game, the players will assume the identities of these Characters when they Perform Scenes.

To Create Characters, each player will first choose a name for their Character and then Attach one Aspect from each of the following categories to their Character:
   - __Occupation__ -
     An Aspect that describes a Character's profession, hobbies, or other interests.
   - __Physical or Mental Characteristic__ -
     An Aspect that describes a Character's body or mind.
   - __Psychological Characteristic__ -
     An Aspect that describes a Character's personality.
   - __Relationship__ -
     An Aspect that describes a Character's connection with another Character.
   - __Affiliation__ -
     An Aspect that describes a Character's connection with an organisation.

During the game additional Aspects can be Attached to a Character and existing Aspects can be modified to reflect how a Character changes in response to the events that occur as the players [Tell the Story](#tell-the-story).

### Write an Outline
During this phase, the players will write an _Outline_ that describes how their Characters will try to prevent the Catastrophe.
The Outline describes a collection of Scenes that are arranged in a hierarchical tree-like structure.

To Write an Outline, the players will first Sketch a Scene called the _Finale_.
The Finale will be the last Scene that the players Perform when they [Tell the Story](#tell-the-story).
The Objective of the Finale should describe how the Characters intend to prevent the Catastrophe.
The Difficulty Rating of the Finale is always _d = 4_.

Then, the Players will Sketch additional Scenes that describe the events that will lead to the Finale.
Each new Scene must be a Precursor of an existing Scene.
That is, accomplishing the Objective of the new Scene must make it easier for the Characters to accomplish the Objective in the existing Scene.
The Difficulty Rating of the new Scene is always one less than that of the existing Scene and must be greater than zero.


<!-- #### Example
```mermaid
graph TB;
  n0("Destroy the Death Star (4)");
  n0 ---- n1("Engage the enemy fighters (3)");
  n0 ----- n2("Find a critical weakness (3)");
           n2 --- n4("Rescue Princess Leia (2)");
           n2 ---- n5("Deliver the schematics to the rebels (2)");
                   n5 ---- n7("Find Obi-Wan Kenobi (1)");
  n0 --- n3("Use The Force (3)");
         n3 ------- n6("Train to become a Jedi (2)");
```

--- -->

### Tell the Story
During this phase, the players will tell the story of their Characters' adventures as they try to enact their plan to prevent the Catastrophe.

To Tell the Story, the players will Perform the Scenes described in the Outline. A Scene cannot be Performed until after all of its Precursors have been Performed. Other than this restriction, however, the Scenes can be Performed in any order.

<!-- To Perform a Scene, the players will:
   1. __Investigate the Scene__ -
     The players describe the Objects and Aspects that the Characters might encounter in the Scene.
   2. __Make a Check__ -
     The players identify pairs of Matching Aspects and make a Check to determine the Outcome of the Scene.
   3. __Interpret the Outcome__ -
     The players describe the Characters' actions in the Scene, how they led to the specified Outcome, and the narrative consequences of their actions.   -->

<!-- ## Time Limits
The Story should be tightly focused on the Finale.
To encourage this kind of storytelling, the Players should adhere to the following guiding principles:
   - __Short Scenes__ -
     Each Scene should be Performed in no more than eight minutes of real time.
   - __Simple Structures__ -
     The [Outline](#outline) should consist of no more than eight [Scenes](#scenes).

--- -->

<!-- ## Acknowledgements
Thanks to everyone who helped refine the design of Prophecy:
  - Keydan Bruce
  - Farzana Choudhury
  - Michael Cromer
  - Dannielle Harden
  - Sarah Hewat
  - Scott Joblin
  - Kira Purcell
  - Luke Purcell
  - Jo Stephenson
  - Brett Witty -->
