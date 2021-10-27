# Tool Code Cleanup
Tools developed for cleanup of the android app source code before initiating the conversion.

Based on our experience of code conversion for various products, we have observed that through out the life of product development the some portion of the code base becomes out dated and not used any more in the project. Generally it is called as 'Dead Code' and it just occupies space. The portion of such dead code can be any where from 10% to as high as 50% 

This also creates problem in conversion because it increase conversion efforts and cost. 

## What is Dead code?


## Objective
The objective of this tool is to identify classes and resources which are not used in the project so that product owner can do code cleanup.

## Scope
* This tool is developed for Andoid Studio projects using Java language only.
* This tool will scan the project and identify following areas which are not referenced in the project -
  - Libraries
  - Classes
  - Methods
  - Android resources (xml, images, fonts files etc.)
  - Permissions


## Not in scope
* The dead code at path level
* Projects developed using Kotlin language
* This tool will just identify the dead code and provide report in suitable format, it will not make any changed to the source code

## Approach
WIP...



