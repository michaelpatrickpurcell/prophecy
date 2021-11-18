# Prophecy
Prophecy is a tabletop roleplaying game about fate and destiny.
During the game, the players receive a prophecy that describes an impending catastrophe for some fictional world.
They create characters who inhabit that world, write an outline that describes how their characters will try to deal with the catastrophe, and tell the story of their characters' adventures.

Throughout these rules, a variety of common words are used as technical terms to describe how the game is played.
These terms will be Capitalised when they appear in the text and _Italicised_ when they are first introduced.
Occasionally, the rules described in one section will refer to rules described in another section. When this happens, the reference will consist of a [hyperlink](#prophecy) to the target section. The link text will be the title of the target section.

## Materials
To play the game, the players will need a few _Materials_ that they will use to take notes and generate random numbers.
They will need:
  - __Index Cards__ - Approximately fifty index cards should placed within easy reach of all players.
  - __Sticky Notes__ -  Approximately one hundred sticky notes should placed within easy reach of all players.
  - __Butcher Paper__	 One large sheet of butcher paper should be placed in the middle of the play area.  This is the _Story Board_. A whiteboard can be used instead if desired.
  - __Markers__ - Each player should have a marker that they can use to write on the index cards, sticky notes, and butcher paper.
  - __Dice__ Approximately twelve six-sided dice should be placed within easy reach of all players.

## Mechanics    
_Mechanics_ are the systems that govern how players interact with the game.
They provide a way for players to describe a fictional world by populating it with [Objects and Aspects](#objects-and-aspects), compose a story set in that world by describing [Scenes](#scenes), and determine how that story plays out by making [Checks](#checks).

### Objects and Aspects
An _Object_ is a person, place, or thing that appears in the story.
An _Aspect_ is a word or short phrase that describes something noteworthy about an Object.
Each Aspect is _Attached_ to a single Object.

Players should use an index card to represent each Object and a sticky note to represent each Aspect.  If an Aspect is Attached to an Object, then the players should stick the sticky note representing that Aspect to the index card representing that Object.

<!-- __Example__

A guard who appears in the story is an Object. If the Aspect "Sterling Reputation" was Attached to him, it might indicate that he is highly regarded.
Alternatively, it might indicate that he is independently wealthy. It might even be used ironically to indicate that he is known to accept bribes. -->

#### Characters
A _Character_ is a person who appears in the story and whose actions will be controlled by a single player throughout the game.
An Aspect that is Attached to a Character is a _Character Aspect_.
An Aspect that is Attached to any Object that is not a Character is an _Environment Aspect_.

<!-- __Example__

Ruth is a Character. If the Aspect "Silver Tongued" was attached to her, it would be a Character Aspect that might indicate that she is particularly persuasive. Alternatively, it might suggest that she is charming, eloquent, or even deceitful. -->

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
    A number that describes how difficult it is for the Characters to accomplish the Scene's Objective.
  - ___Outcome___ -
    A description of whether the Characters accomplish the Scene's Objective. If so, then the Outcome is a _Success_ and the Scene is resolved successfully. Otherwise, the Outcome is a _Failure_ and the Scene is resolved unsuccessfully.
  - ___Precursors___ -
    Other Scenes which, if resolved successfully, make it easier for the Characters to accomplish the Scene's Objective.

#### Sketching Scenes
The players _Sketch_ Scenes when they [Write an Outline](#write-an-outline) describing the story that they will tell about the Characters. To Sketch a Scene the players will establish the Setting, define the Objective, and assign the Difficulty Rating for the Scene.

The players should use an oval drawn on the Story Board to represent each Scene.
The oval that represents a Scene should be labelled with that Scene's Objective and Difficulty Rating.  
The players should draw lines connecting the oval that represents each Scene to the ovals that represent its Precursors.

<!-- __Example__

Ruth wants to cross the border between two neighbouring kingdoms. It is "Dusk" when she makes her way to a "Remote" border crossing on the outskirts of a small town. The border is defended by a garrison of soldiers from the "Local Militia" and the guard on duty when Ruth arrives is well-known to have a "Sterling Reputation". The garrison is on "High Alert" and it will be fairly difficult for Ruth to convince the guard to let her pass. The Difficulty Rating of the scene is _d = 3_. -->

#### Performing Scenes
The players _Perform_ Scenes when they [Tell the Story](#tell-the-story) of the Characters' adventures.
To Perform a Scene the players will describe what happens during the Scene, determine the Outcome of the Scene (see [Checks](#checks)), and describe the narrative consequences of the Characters' actions.

After performing each Scene, the players should cross out the oval representing that Scene on the Story Board. If the Scene is resolved successfully, the players should place a die on the oval that represents that Scene's Parent.
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
     If the Result of the players' roll meets or exceeds the Scene's Difficulty Rating, then the Outcome is a Success, the Characters accomplish the Scene's Objective, and the Scene is resolved successfully.
     Otherwise, the Outcome is a Failure, the Characters do not accomplish their Objective, and the Scene is resolved unsuccessfully.

__Example__

The Players are making a Check to determine the Outcome of a Scene that has a Difficulty Rating of (`3`).
The Players have identified three pairs of Matching Aspects while Performing the Scene.
Two of the Scene's precursors were resolved successfully.
Therefore, the Dice Pool consists of five dice.

When rolled, these dice yield the values {`3`, `6`, `5`, `1`, `6`}.
Because two of the dice yielded a value of {`6`}, two additional dice are added to the pool.
When rolled, these dice yield the values {`2`,`6`}.
Because one of the dice yielded a value of {`6`}, one additional die is added to the pool.
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

The game should be tightly focused on the question of how the Characters will try to deal with the prophesied catastrophe.
To encourage this, the story should consist of no more than eight Scenes and each Scene should be Performed in no more than eight minutes of real time.

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
During this phase, the players will write an _Outline_ that describes how the Characters will try to deal with the Catastrophe.
The Outline describes a collection of Scenes that are arranged in a hierarchical tree-like structure.

To Write an Outline, the players will first Sketch a Scene called the _Finale_.
The Finale will be the last Scene that the players Perform when they [Tell the Story](#tell-the-story).
The Objective of the Finale should describe how the Characters intend to deal with the Catastrophe.
The Difficulty Rating of the Finale is always (`4`).

Then, the players will Sketch additional Scenes that describe the events that will lead to the Finale.
Each new Scene must be a Precursor of an existing Scene.
The Difficulty Rating of the new Scene is always one less than that of the existing Scene and must be greater than zero.

A Scene that is a Precursor of the Finale is a _Primary Scene_.
A Scene that is a Precursor of a Primary Scene is a _Secondary Scene_.
A Scene that is a Precursor of a Secondary Scene is a _Tertiary Scene_.

__Example__

A tree view of one possible Outline is:
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
The numbers in parentheses indicate the Difficulty Rating of the corresponding Scenes.

### Tell the Story
During this phase, the players will tell the story of their Characters' adventures as they try to enact their plan to deal with the Catastrophe.
While the overall structure of the story is established when the players [Write an Outline](#write-an-outline), when they Perform Scenes the players discover how the story unfolds and how the Characters are affected.

To Tell the Story, the players will Perform the Scenes described in the Outline.
A Scene cannot be Performed until after all of its Precursors have been Performed. Other than this restriction, however, the Scenes can be Performed in any order.

Before they make a Check to determine the Outcome of a Scene, the players should roleplay interactions between the Characters and the Objects that populate the Scene.
This is the players' opportunity to add new Objects to the Scene and Attach new Aspects to existing Objects.

After the Outcome of a Scene has been determined, the players should describe the Characters' actions in the Scene, how they led to the specified Outcome, and the narrative consequences of their actions.
This description should be informed by the pairs of Matching Aspects that the Characters attempted to use to manipulate the Scene to their advantage.
If the Scene was resolved successfully, then the players should describe which pairs of Matching Aspects they were able to exploit.
Otherwise, the players should describe what went wrong.

## The Moderator
Optionally, one of the players can assume the role of _Moderator_. The Moderator's job is to help the other players play the game. This assistance can take a variety of forms: from answering questions about the rules, managing logistics,  to ensuring that everyone agrees about various details of the story.

The Moderator should encourage the other players to tell an interesting story by asking them questions.  If the Moderator is curious about something in the story and wants to learn more,  then they should ask for more information.  Similarly, if the Moderator is confused then they should ask for clarification.

Importantly, however, the Moderator's role is not prescriptive.  The Moderator should not narrate any part of the story. The Moderator can make suggestions or present alternatives, but ultimately the other players should decide what happens.

## Modules
The first thing that the players do in the game is Receive a Prophecy.  
This is the inciting incident for everything that happens in the story.
It's important!
By describing the prophesied Catastrophe, the players establish the foundation on which the rest the game will be built.

A _Module_ is a pre-written Prophecy designed  to help the players get started.
Each Module describes a Catastrophe as it might be presented to Characters who are hearing the Prophecy for the first time.  The players should read the Module aloud when they Receive the Prophecy and create Objects and Aspects to populate the fictional world that it implies.

### Return of the Dragon
Long ago, in the first age of men, the world was filled with wonders.
The people of that time thought themselves safe from the fury of the natural world.
Then She came.
The great Dragon emerged from the sea and laid waste to the land.
Only the grandest works of those once great civilizations remain to mark their passage.

Or so the story goes.
Most scholars believe that the Dragon is a myth and that the Ancients were somehow responsible for their own demise.
Others believe that while the Dragon was real, She must surely have died long ago.
They are mistaken.

After one thousand years of slumber, the Dragon wakes.
The earth shakes as She begins to stir.
The oceans froth and swell as She shakes off the last vestiges of sleep.
Now we face the same fate as that which befell our forebears.

### Deep Impact
My fellow Americans, it is with a heavy heart that I come to you tonight.
As you are doubtless aware, last year the initial survey conducted as a part of Project Spaceguard discovered a large Near Earth Object that was projected to collide with the Earth later this month.
Ever since, the primary focus of this administration has been to prevent that from occurring. Earlier this evening, the director of Project Spaceguard informed me that we have failed.

Now, we must shift our focus from preventing a collision to surviving its aftermath.
Effective immediately, I am declaring a nationwide state of emergency.  National Guard units will be activated and deployed in support of local law enforcement.

Going forward, the Federal Emergency Management Agency will be leading our response.
I'll turn the microphone over to the director of that agency now and he can provide details about what you can expect.
Goodnight and Godspeed.

### She's Having a Baby
Congratulations! It looks like you're at about eight weeks now.
Everything looks great, both mum and baby are doing fine.
So, We'll plan on seeing you again in about four weeks.

While you're here I should tell you about the course that the hospital offers for new mums.
It's a great way to learn about what to expect and a chance talk to other new parents about the whole experience.
The teachers are all former maternity ward nurses and they really do a great job.

I know that this can be overwhelming. If you have any concerns, please give us a call at any time.  OK?

## Acknowledgements
Thanks to everyone who helped refine the design of Prophecy:
  - Keydan Bruce
  - Farzana Choudhury
  - Michael Cromer
  - Dannielle Harden
  - Andrew Hellyer
  - Sarah Hewat
  - Scott Joblin
  - David McKenzie
  - Paul Murray
  - Kira Purcell
  - Luke Purcell
  - Jo Stephenson
  - Brett Witty
  - Bevis Worchester
