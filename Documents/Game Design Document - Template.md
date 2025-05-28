---
Creation Date: 2025-05-15T17:01:00
Last Updated: 2025-05-22T13:20:00
---
---
# Game Design Document - Template
This file will be divided in two section one [explaining](#Explanation) the #GDD and one focused on showing some kind of [template](#Template).
## Explanation
### Importance of Documentation
The Game Design Document or #GDD is to be used as a **roadmap** for the game development, it should be used to mark every decision made for a game so it can be shown to both:

- Stakeholders
- Developers

With the document, in the future one will be able to make decisions and assert old decisions with ease without having to think "twice" (_design trashing_) to make a choice for the game.

- [n] Design documentation is important even when alone, since it will help to not forget decisions that you alone made six months from now. 

It's to be seen as both a _backward-looking_ and *forward-looking* document and **it will be** modified as time passes. 
### Guidelines to Follow
The documentation should be build using the best method to make it understandable be it **pictures, diagrams, flow models, etc.** Whatever can make it, use it, not always is text the best wat to describe something.

Treat it as a blueprint for a building, precise, detailed without being vague. **If you don't know how something will be made yet describe it as so.**

- [!] Do not use qualitative phrases like "_this enemy moves fast_", "_this results in a big explosion_" or "_this turret turns left and right_".

**How fast? How big? How far?** Every time a quantity is called for, supply a number, define a range, reference an equation or another determining factor. 

Be careful about documentation to much as this can be as detrimental to the game as creating to little. If you know something and are sure about it document it and move on, if you're not aware how to do something document what you want to achieve, the best ideas you had, and what has been discarded. Test and create prototypes (paper or electronic) and move on when the path is clear saying why such path has been chosen. 
### The Goal
By using all the methods described before the aim of the documentation is to provide enough information so that anyone concern can understand. This being:

- What the game is;
- What the player's experience is - why they will play it;
- What your goals are for it - why are you making it;
- what its current status is;
- how, in precise detail, to build it

Anything not correlated with this must be avoided or removed and seen as wasted effort.
### Keep it Current
> "**Any design document is only as good as it is current.**"

It's important that the documentations is not seem as a "design bible", it will and must be changed as the game is being made, seem as challenges and changes will occur. So with this is mind it's important to have a place to comment and discuss changes for the document and when such changes are made they should be put in the document. 

- [n] The design docs themselves contain only the current state of the design, not any conversations or commentary.

With this in mind, it's interesting to keep a log of the changes with dates and short commentary of what has been changed. 
### Divide and Conquer
In a multi-person team %% (not our personal case hahaha) %%, each person would be assigned particular partes of the documentation to maintain and keep current. It's a good idea to assign more general parts to more senior members of the design team, and the more detailed parts to more juniors members.
### Organization and Adaptation
It's important to note that there isn't a best way to organize the docs, it's really something that should be adapted and changed based on the needs of the game and the team.

One way to make it is so that the first page shows the most important information and then it links to more detailed pages.

---
## Template
As said before this is a template, not a rule of how it should be done.

One needs to remember before starting is that the process of making a game isn't as simple as it seems.

![[game-design-iceberg.png]]
### Main Page
- [n] First things first, the main page can be seem as a multiple of pages, but the first ones were the information is said in more of a "generic" way than extra detailed, if there is another part of the document that is more detailed link to it when explaining something.

The main page must contain:
#### Working Title
Self explanatory, the game's title can be something that correlates with the gameplay and style of the game.
#### Current Status
In a short brief, explain the current situation the game is at like:

- still being designed;
- parts being prototyped;
- ready for greenlight;
- ready for production
- on schedule?;
- significant issues;
- etc.

Some good questions that can be used at the game Scrum report are:

- What parts of the design are complete or have been reviewed?;
- Which parts are being worked on?;
- What if any blockers to progress are there?;
- What if any debt (tech or not) or major issues have arisen?
#### Concept Statement
Like the short brief of the [[#Current Status]], describe the most important aspects of the game ("_your game in a tweet_" or "_a few words that create a question_").

Some good questions to answer in this short statement are:

- What is it's theme and setting?;
- What makes the game fun?;
- How many players are there?;
- Is it a quick pick-up game or a huge epic?;
- Why would someone want to play the game?

Do not try to put to much information in quick statement, but don't forget to leave vital parts.  Expect to spend some time iterating and polishing this section.
#### Genre
State what game genre is the gameplay about, avoiding to use vague statements that don't inform the reader what actually is it about, like "_this is a Castlevania-like game_". While this information may be a good way to correlate to something what does it actually mean?

- [n] Single-genre games are often less interesting as the space has likely been well-explored. This doesn't mean they are inherently wrong but sometimes exploring with a hybrids of genre can create something interesting and from a new angle on existing gameplay.
#### Target Audience
Think of this as who do would be the specific person this is made for, it does not mean that only this kind of people will play the game, but gives a direction who is aimed at. Some good questions are:

- Who is the target player?; 
- Are there other games that they might have played?;
- What age range or other relevant interests or attributes do they have? 
#### Concept Paragraph and Unique Selling Points
This is an expansion of the [[#Concept Statement]], this brief should provide an overview of the gameplay, game's core loops, player progression, setting, look and feel and anything else that can explain.

The focus points should be the game's _unique selling points_ USPs. What are the things that makes your game fresh, intriguing, new, and worth someone's time?
The game's USPs should be clearly understood by anyone that reeds the docs.

- [!] A link/video to a prototype should go here when it exists.
#### Player Experience
This section should focus on answering the following questions:

- Who is the player in the game?;
- What is the setting?;
- How long does the game last?;
- What is the fantasy or aspiration the game grants the player?;
- What emotions does the player feel by playing the game?;
- What are the major phases of the player's experience in the game?

This part can link to a future section [[#Player Objectives and Progression]] with more detailed information.
#### Key Moments
Briefly describe a few "_key moments_" in the game. Some examples are the initial positive experience in the first minutes of the game, key struggles to overcome, major victories or achievements or resolutions points trough the game arc.
#### Art, Sound and Music
Here high-level information related do the game style should be displayed with links to more detailed sections, this sections that can be even to different docs instead of sections to the main doc. It's important that these information be shown in **complete detail** in their own doc.

High-level information includes:

- References;
- Concept arts;
- Music (if possible)

Giving the reader an idea of visual style of the game. One important aspect is showing references from other media and most importantly not use then in the game, only be used for reference.
#### Current Target Platform (and any system requirements)
Keep it simple, what is the **first** or current platform for the game. Even if the game is aimed for multiple platforms (that are inherently different like web, PC, console, mobile), leave this to one and the current platform, leaving off any "future" desired platforms. 
#### Competition
What games are similar from **the player's point of view**, or would compete with the game? Show their information from manpower to revenue, any information that can be found. Include a brief description of each game and what sets your game apart.
#### Monetization
Explain how the game is expected to make revenue, nothing is free to be made (unless it's the point of the game), will it be "free to play"? Will it contain in-game purchases? Will it contain ads? The game design need to take this information in account.
### Detailed Sections
From the main page(s) the reader needs to be linked to detailed information they want about something by following the links. These can be their own docs or their own chapters inside the same document.

Below there will be most of the needed detailed sections and main questions that the reader must be able to answer by accessing them.

- [n] It's important to note that more sections can be created, one should remember that this is only an template example and the design document must adapt to the reality of the game. This are only main sections that should be created.
#### Player Objectives and Progression
 - Who is the player in the game?;
 - Synopsis of what the player knows when the game starts, and any following in game narrative;
 - Player's primary goals and how they progress to them, including which parts are linear or based on player choices;
 - Moment-by-moment gameplay (with links to[[#User Interface | UI]] and prototypes/screenshots);
 - core loops and outer loops;
 - reference back to [[#Key Moments]]
#### Game World
- Backstory overview - important elements of the world fiction that set the stage for the game, but **do not directly affect the gameplay**
	- Link to full world fiction;
- World organization: MVP levels, locations, zones, chapters - including introductory or tutorial areas;
- Game world physics: running, flying, falling, etc., -- anything of note for the design;
- How does the player move trough the game in terms of location, chapters, etc.;
- Easter Eggs planned, if any
#### User Interface
- Specifics of all needed control schemes (selection, activation, radial or context menu use, tapping, dragging, etc.), ensuring that these are consistent across the game;
- Screen flow mockups: each screen/menu in full functional detail (wireframe, no art), showing the player's flow through all aspects of the game;
- Mockups for on-screen controls (with links to individual features and systems);
- Help system details;
- Game options: audio, visual, game save, etc.

#### MVP Systems and Features
- All major features such as character creation, crafting, combat, dialog, etc., including areas for monetization (if any), and specific puzzles or similar
	- Intent, the "why" behind the feature;
	- The moment-by-moment gameplay for each feature or system;
	- The monetization aspects of each system or feature (if applicable);
	- Lots of pictures and diagrams - give the reader the feel for the feature or system;
	- Links to technical docs for programmer consumption
		- Math, data structures, format of external data docs;
		- Naming schemes for external directories and files;
	- Break down into Epics and User Stories for implementation;
- Include a description of the UI for each (with links back to the main[[#User Interface | UI]] section)
#### Game Objects
- Listing of all NPCs and monsters, including
	- NPC backstory, narrative, dialog (links to specific dialog data files);
	- Attributes, attacks, special powers;
- Game objects
	- Attributes and their values/ranges;
	- Behaviors;
- Link to external spreadsheet containing each object's data and attribute information
#### Localization
- Description of the initial localization plan: English-only, EFIGS, or other;
- Technical description of localization syntax for strings;
- Technical description for localization string name conventions;
- Link to external localization string files
#### Tools
A description of tools needed for designers, programmers, and others to create the game. 

- World creation and layout;
- Object definition;
- Missions/quests;
- Others as needed to implement the game;
#### Technical documentation
- Major technical areas and risks;
- Target hardware and specific requirements/assumptions;
- Infrastructure
	- directory structure and file naming conventions;
	- data file format;
- Server, client, and network architecture (as needed);
- Artificial intelligence and other autonomous/procedural systems
	- Procedural world creation;
	- Pathfinding;
	- Economy;
- Technical (programming doc for each major feature or system, linked to the design doc for each above. These docs are for programmers, and focus on implementation details rather than the design itself or its rationale.;
- Game cheats for testing
#### Ideas and Expansions
Non-MVP feature ideas for future expansion are kept here.
#### Unresolved Questions
As questions and concerns arise, they are listed here. When resolved, the question or concern is not deleted, but is moved to a “Resolved” section along with a link to the document that describes the design that answers the concern.
#### Prototypes
Links to prototypes not already referenced, if any, are here.