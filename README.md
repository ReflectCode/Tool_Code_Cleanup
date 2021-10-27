<h1 align="center">
  <a href="http://www.reflectcode.com">
    ReflectCode
  </a>
</h1>
<p align="center">
  <strong>Automated Source Code Transformation service</strong><br>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android%20%7C%20iOS-green" alt="Platform - Android | iOS" />
 
  <a href="https://twitter.com/intent/follow?screen_name=reflectcode">
    <img src="https://img.shields.io/twitter/follow/reflectcode.svg?label=Follow%20@reflectcode" alt="Follow @reflectcode" />
  </a>
  
</p>

-----

# Code Cleanup tool
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



