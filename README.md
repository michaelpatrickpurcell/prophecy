# Prophecy
Prophecy is a tabletop roleplaying game about fate and destiny.
During the game, the players receive a prophecy that describes an impending catastrophe for some fictional world.
They create characters who inhabit that world, write an outline that describes how their characters will try to prevent the catastrophe, and tell the story of their characters' adventures.

Throughout these rules, a variety of common words are used as technical terms to describe how the game is played.
These terms will be Capitalised when they appear in the text and _Italicised_ when they are first introduced. Occasionally, the rules described in one section will refer to rules described in another section. When this happens, the reference will consist of a [hyperlink]() to the target section. The link text will be the title of the target section.

## Mechanics    
_Mechanics_ are the systems that govern how players interact with the game.
They provide a way for players to describe a fictional world by populating it with [Objects and Aspects](#objects-and-aspects), compose a story set in that world by describing [Scenes](#scenes), and determine how that story plays out by making [Checks](#checks).

### Objects and Aspects
An _Object_ is a person, place, or thing that appears in the story.
An _Aspect_ is a word or short phrase that describes something noteworthy about an Object.
Each Aspect is _Attached_ to a single Object.

<!-- __Example__

A guard who appears in the story is an Object. If the Aspect "Sterling Reputation" was Attached to him, it might indicate that he is highly regarded.
Alternatively, it might indicate that he is independently wealthy. It might even be used ironically to indicate that he is known to accept bribes. -->

#### Characters
A _Character_ is a person who appears in the story and whose actions will be controlled by a single player throughout the game. Characters are Objects. As such, Aspects can be attached to Characters. An Aspect that is Attached to a Character is a _Character Aspect_.
An Aspect that is Attached to any Object that is not a Character is an _Environment Aspect_.

__Example__

Ruth is a Character. If the Aspect "Silver Tongued" was attached to her, it would be a Character Aspect that might indicate that she is particularly persuasive. Alternatively, it might suggest that she is charming, eloquent, or even deceitful.

#### Matching Aspects
A pair of _Matching Aspects_ is a set of two Aspects, one Character Aspect and one Environment Aspect, that together allow the Characters to manipulate a Scene to their advantage.
<!-- Pairs of Matching Aspects are used to determine the size of the Dice Pool when making a Check. -->

<!-- __Example__

Ruth is trying to convince a guard to let her through a checkpoint.
The Aspect "Silver Tongued" is attached to Ruth and the Aspect "Sterling Reputation" is Attached to the guard.
If the players agree that this pair of Aspects might allow the Ruth to manipulate the Scene to her advantage,
perhaps by suggesting that she might be able to bribe the guard,
then together they would constitute a pair of Matching Aspects. -->

### Scenes
A _Scene_ is a part of the story that describes the events that happen at a single time and place.
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

#### Sketching Scenes
The players _Sketch_ Scenes when they [Write an Outline](#write-an-outline) describing the how the Characters will try to prevent the impending catastrophe. To Sketch a Scene the players will establish the Setting, define the Objective, and assign the Difficulty Rating for the Scene.

<!-- __Example__

Ruth wants to cross the border between two neighbouring kingdoms. It is "Dusk" when she makes her way to a "Remote" border crossing on the outskirts of a small town. The border is defended by a garrison of soldiers from the "Local Militia" and the guard on duty when Ruth arrives is well-known to have a "Sterling Reputation". The garrison is on "High Alert" and it will be fairly difficult for Ruth to convince the guard to let her pass. The Difficulty Rating of the scene is _d = 3_. -->

#### Performing Scenes
The players _Perform_ Scenes when they [Tell the Story](#tell-the-story) of the Characters' adventures.
To Perform a Scene the players will describe what happens during the Scene, determine the Outcome of the Scene (see [Checks](#checks)), and describe the narrative consequences of the Characters' actions.

<!-- __Example__

Test -->

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

__Example__

The Players are making a Check to determine the Outcome of a Scene that has a Difficulty Rating of _d = 3_.
The Players have identified three pairs of Matching Aspects while Performing the Scene.
Two of the Scene's precursors were resolved successfully.
Therefore, the Dice Pool consists of five dice.

When rolled, these dice yield the values {`3`, `6`, `5`, `1`, `6`}.
Because two of the dice yielded a value of `6`, two additional dice are added to the pool.
When rolled, these dice yield the values {`2`,`6`}.
Because one of the dice yielded a value of `6`, one additional die is added to the pool.
When rolled, this die yields the value {`4`}.
So, this roll yields the values {`3`, `6`, `5`, `1`, `6`, `2`, `6`, `4`}.

The Result of this roll is five Hits.
This Result exceeds the Difficulty Rating of the Scene so the Outcome of the Check is a Success.   

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

### Create Characters
During this phase, the players create Characters.
Later in the game, the players will assume the identities of these Characters when they Perform Scenes.

To Create Characters, each player will first choose a name for their Character and then Attach one Aspect from each of the following categories to their Character:
   - __Occupation__ -
     An Aspect that describes the Character's profession, hobbies, or other interests.
   - __Physical or Mental Characteristic__ -
     An Aspect that describes the Character's body or mind.
   - __Psychological Characteristic__ -
     An Aspect that describes the Character's personality.
   - __Relationship__ -
     An Aspect that describes the Character's connection with another Character.
   - __Affiliation__ -
     An Aspect that describes the Character's connection with an organisation.

During the game additional Aspects can be Attached to a Character and existing Aspects can be modified to reflect how a Character changes in response to the events that occur as the players [Tell the Story](#tell-the-story).

### Write an Outline
During this phase, the players will write an _Outline_ that describes how the Characters will try to prevent the Catastrophe.
The Outline describes a collection of Scenes that are arranged in a hierarchical tree-like structure.

To Write an Outline, the players will first Sketch a Scene called the _Finale_.
The Finale will be the last Scene that the players Perform when they [Tell the Story](#tell-the-story).
The Objective of the Finale should describe how the Characters intend to prevent the Catastrophe.
The Difficulty Rating of the Finale is always _d = 4_.

Then, the players will Sketch additional Scenes that describe the events that will lead to the Finale.
Each new Scene must be a Precursor of an existing Scene.
The Difficulty Rating of the new Scene is always one less than that of the existing Scene and must be greater than zero.

A Scene that is a Precursor of the Finale is a _Primary Scene_.
The Difficulty Rating of a Primary Scene is _d = 3_.
A Scene that is a Precursor of a Primary Scene is a _Secondary Scene_.
The Difficulty Rating of a Secondary Scene is _d = 2_.
A Scene that is a Precursor of a Secondary Scene is a Tertiary Scene. The Difficulty Rating of a Tertiary Scene is _d = 1_.

__Example__

<!-- After they [Receive a Prophecy](#receive-a-prophecy), The players [Write an Outline](#write-an-outline).
  - The players first Sketch the Finale.
    Because it is the Finale, its Difficulty Rating is _d = 4_.
     -  The players Sketch two Primary Scenes called `Primary Scene 1` and
        `Primary Scene 2`. Both Scenes are Primary Scenes, so the Difficulty Rating of both Scenes is _d = 3_.
        - The players decide to dig a bit deeper.
          They Sketch two Precursors of `Primary Scene 2` called `Secondary Scene 2.1` and `Secondary Scene 2.2`.
          Both Scenes are Secondary Scenes, so the Difficulty Rating of both Scenes is _d = 2_.
           - Again, the players decide to dig deeper.
             They Sketch a Precursor of `Secondary Scene 2.2` called `Tertiary Scene 2.2.1`.   
             Because it is a Tertiary Scene, its Difficulty Rating is _d = 1_.
     - The players then return their attention to the Finale.
       They Sketch a third Primary Scene called `Primary Scene 3`.
       Because it is a Primary Scene, its Difficulty Rating is _d = 3_.
        - Lastly, the players Sketch a Precursor of `Primary Scene 3` called `Secondary Scene 3.1`.
          Because it is a Secondary Scene, its difficulty is _d = 2_. -->

The players first Sketch the Finale.
Because it is the Finale, its Difficulty Rating is _d = 4_.

The players Sketch two Primary Scenes called `Primary Scene 1` and `Primary Scene 2`.
Because they are Primary Scenes, their Difficulty Ratings are _d = 3_.

The players decide to dig a bit deeper.
They Sketch two Precursors of `Primary Scene 2` called `Secondary Scene 2.1` and `Secondary Scene 2.2`.
Because they are Secondary Scenes, their Difficulty Ratings are _d = 2_.

Again, the players decide to dig deeper.
They Sketch a Precursor of `Secondary Scene 2.2` called `Tertiary Scene 2.2.1`.
Because it is a Tertiary Scene, its Difficulty Rating is _d = 1_.

The players then return their attention to the Finale.
They Sketch a third Primary Scene called `Primary Scene 3`.
Because it is a Primary Scene, its Difficulty Rating is _d = 3_.

Lastly, the players Sketch a Precursor of `Primary Scene 3` called `Secondary Scene 3.1`.
Because it is a Secondary Scene, its difficulty is _d = 2_.


A tree view of the resulting Outline is:
```
Finale (4)
|- Primary Scene 1 (3)
|- Primary Scene 2 (3)
|  |- Secondary Scene 2.1 (2)
|  |- Secondary Scene 2.2 (2)
|     |- Tertiary Scene 2.2.1 (1)
|- Primary Scene 3 (3)
   |- Secondary Scene 3.1 (2)
```

### Tell the Story
During this phase, the players will tell the story of their Characters' adventures as they try to enact their plan to prevent the Catastrophe.
While the overall structure of the story is established when the players [Write an Outline](#write-an-outline), when they Perform Scenes the players discover how the story unfolds and how the Characters are affected.

To Tell the Story, the players will Perform the Scenes described in the Outline.
A Scene cannot be Performed until after all of its Precursors have been Performed. Other than this restriction, however, the Scenes can be Performed in any order.

Before they make a Check to determine the Outcome of a Scene, the players should roleplay interactions between the Characters and the Objects that populate the Scene.
This is the players' opportunity to add new Objects to the Scene and Attach new Aspects to existing Objects.

After the Outcome of a Scene has been determined, the players should describe the Characters' actions in the Scene, how they led to the specified Outcome, and the narrative consequences of their actions.
This description should be informed by the pairs of Matching Aspects that the Characters attempted to use to manipulate the Scene to their advantage.
If the Scene was resolved successfully, then the players should describe which pairs of Matching Aspects they were able to exploit.
Otherwise, the players should describe what went wrong.

<!-- ## Time Limits
The Story should be tightly focused on the Finale.
To encourage this kind of storytelling, the Players should adhere to the following guiding principles:
   - __Short Scenes__ -
     Each Scene should be Performed in no more than eight minutes of real time.
   - __Simple Structures__ -
     The [Outline](#outline) should consist of no more than eight [Scenes](#scenes).

--- -->

## Acknowledgements
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
  - Brett Witty
