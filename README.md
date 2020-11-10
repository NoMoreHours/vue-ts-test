## NoMore 2020 Vue / JS developer code test
### Introduction
These tests centers around a small simple Vue application. The app is very simple and in many ways poorly written (we wrote it in 60 min with this aim in mind). 
Think of this as a PR from a junior intern who just started using Vue :) 
Now your job is to show the intern how it should have been done by improving the code - both in terms of code quality and experience for the user.

### About the app
The application is a very simple tool - a form of mixture between a "news generator" and a "to-do list" app. The functionality is very limited:
- The app has to database or persistence layer (no backend)
- It allows the user to randomly generate a news source for the user to read (and adding it to a "to read" list)
- It gives the ability to go to the given site via the "to read list"
- The ability to mark a news source as "read" from the "to read list"

### How the app is written
The app is written in plain Vue.js 2.0+ and Tailwind (CDN) and can be "run" by simply running: 

`npm run serve`

Please note: The code is not well written and have a lot of improvement potential. Furthermore, the code is not implementing TypeScript or vue-decorators.

## Picking the right task

There two different tasks below - one aimed at front-end developers (TypeScript + Vue) and one aimed at Fullstack developers (Laravel + Vue).
Feel free to pick the task in which you believe you can best demonstrate your skills. 

## Task Option 1: Front-end (TypeScript + Vue)
### What you need to do:
- rewrite the application with the same basic functionality
- use TypeScript
- use Vue-decorators instead of basic JS approach https://www.npmjs.com/package/vue-property-decorator
- apply "clean code" principles as you would on a proper project (google "uncle bob - clean code" in case you want our take on what we mean by clean code - e.g. https://www.youtube.com/watch?v=7EmboKQH8lM)
- improve the existing functionality in order to handle common egde cases 
- improve the different methods as you see fit
- make further adjustments assuming the code had to go into production and that this is part of a larger vue application that might re-use some of this code elsewhere
- make selective improvements to the design and UX
- if you have time: add extra functionality that you think improve the UX
- optional: build a back-end as described in Task Option 2

## Task Option 2: Fullstack (Laravel + Vue)
- improve the existing Vue code by adding components, improving method logic, comments etc.
- write a Laravel based back-end using TDD which support the functionality of the simple app
- write the migrations to support the functionality as you see fit
- make selective improvements to the design and UX as you see fit
- in general: apply "clean code" principles as you would on a proper project (google "uncle bob - clean code" in case you want our take on what we mean by clean code - e.g. https://www.youtube.com/watch?v=7EmboKQH8lM)
- optional: implement TypeScript as presented in Task Option 1


### How to proceed with the test
- fork the code into your own Github repository
- commit changes similar to how you would do on normal team
- write a new README.md file that presents your solutions including potential assumptions, documentation.
- the README must also include a list of "what you would do if you had more time"
- make a short Loom (loom.com) video in which you present your solution (add link in the new README file)
- let know how much time you have used
- once "ready to share" provide access to the repository to klaus1993@live.com and write a short email to klaus.andrade@nomorehours.com
