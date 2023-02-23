# TDD - Tech Desing Document

## Who I am?
I am an student of UPC CITM. This research was for a project of the university with the objective to teach to all my partners how toto a good TDD.

My [Github](https://github.com/AndreuMiroSabate)

The [Repository](https://github.com/AndreuMiroSabate/TDD_Technical-Desing-Document)

## 1. Introduction

### What is a TDD?
A TDD or Tech Design Document, is a document that companies use to explain in a detailed form the technical features from their project, like what tools are the team gonna use for the project, the objectives of the project, how to implement those objectives, what the team needs to implement…
It is important that the document is well done, because it will be useful for the people out of the project to understand why you did something in a way, but it could be useful for the people inside the team too.
This document can have changes along the process. Many times, these changes are made to show how to solve a problem, like a bad implementation of a mechanic. 

### Why we use a TDD?
In video games, we use it to have a detailed guide of the technical features that will help us to have an organized project. To be more clear, if one person on the team looks at the document, he can quickly understand how to implement a feature or how to solve a problem.


## Inside of the TDD

### Game concept
This is the first part of the document and the use of it is to give context on what you are making. Is important to give some background to clarify all the concepts that will appear later. Here you must put what type of game you're gonna do, what engine you will use and on what platform you will release it.

### Development Requirements
This part is not essential, but will help to make an idea what you use to make the project. Here you have to clarify what tools will you use to make the project (art software, coding program, where you find the information, etc)

### Schedule
The plan that the team is going to follow during the process.

![shedule](https://github.com/AndreuMiroSabate/TDD_Technical-Desing-Document/blob/59be5981c93f908aa6264b048e54afd463f70cf6/docs/scheme.PNG)

Schedule from: [TDD ComputersGames MMU](https://computergamesmmu.files.wordpress.com/2012/10/technical-design-document-final.pdf)

### Technical Goals
This is one of the most important parts of the TDD. In this part the team has to specify what technical objectives are planned to achieve by the end of the project or the problems to solve. A few examples can be some features of the game like enemies IA, immersive sound…

### Technical Risks
This part exists because it is good to have in mind what problems could we find when we pretend to accomplish an objective, to be prepared to solve it or don’t be surprised if they happen. This problem can be: game go slow, don’t have enough time, can generate bugs, etc. 
#### Performance Budgets
Many of the problem could be from limitations of the material we use, like lack of memory, so is important to have this limitations in our mind.

### Structure
If you search some examples of TDD, this part sometimes is but sometimes is not. Here you define how the project will be organized, like what will be in every carpet of the project. At the same time you can define de naming rules for the documentents, like this:

![roses](https://github.com/AndreuMiroSabate/TDD_Technical-Desing-Document/blob/0fde01561bcef5071bda713a85debecef510f95f/docs/roses.PNG)

This fragment is from the TDD of [Unworthy Roses](https://hell-and-back.fandom.com/wiki/Technical_Design_Document)

### Levels
As the name says, it is convenient to explain technical aspects of your game. These aspects can be, what will the player have to do in that level and what mechanics are required. You can do a brief explanation of each level.

### Coding rules or guidelines
This is another of the importants parts of the project. Here developers must write code conventions with the objective of having an organized and homogeneous code, in other words, all the code needs to be with the same structure and names, to make it more understandable.
Some examples could be:
- All variables need to start with mayus
- All global variables must be in capital letters
- Preferibly use while for loops
- When use classes or structs

For more examples click here: [TDD of Unworthy Roses](https://hell-and-back.fandom.com/wiki/Technical_Design_Document), [Narbacular Drop - Technical Design Document](http://www.nuclearmonkeysoftware.com/documents/narbacular_drop_technical_design_document.pdf)

#### Code UML
As an extra for coding, you can add an UML of the code, that would help to have all organized.


![UML](https://github.com/AndreuMiroSabate/TDD_Technical-Desing-Document/blob/main/docs/IMAGES/general_UML.png)


Image from [TDD Warcraft II by Dev Crumbs]([https://dlorenzolaguno17.github.io/TDD/](https://github.com/DevCrumbs/Warcraft-II/wiki/7.-Tech-Design-Document))

### Project technical features
This part is the most extend in the document. Here you have to write all the features that need a technical explanation. Examples can be mechanics, the physics of the game, the AI of the NPC or enemies or the UI.
  
### Test Plan
This is the final part of the TDD. In this section, you need to describe how you are going to test the results of the different versions and when.


## References
Pages used to do the research:

[Unworthy Roses TDD](https://hell-and-back.fandom.com/wiki/Technical_Design_Document)

[dlorenzolaguno research of a TDD](https://dlorenzolaguno17.github.io/TDD/)

[Better Tech Specs](https://www.range.co/blog/better-tech-specs)

[Machine Words (by Tailin)](https://medium.com/machine-words/writing-technical-design-docs-71f446e42f2e)

[DEV Community](https://dev.to/mage_ai/how-to-write-technical-design-docs-c02)

[Narbacular Drop TDD](http://www.nuclearmonkeysoftware.com/documents/narbacular_drop_technical_design_document.pdf)

[TDD Watcraft II bu Dev Crumbs](https://github.com/DevCrumbs/Warcraft-II/wiki/7.-Tech-Design-Document)

[ComputersGame MMU](https://computergamesmmu.files.wordpress.com/2012/10/technical-design-document-final.pdf)
