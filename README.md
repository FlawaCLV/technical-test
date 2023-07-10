### Setup

No issues except having to revert to Node v16.13.0 so I addded a `.nvmrc` file.

### Bug fixs

While going through the workflow I fixed a few bugs:

- fix the input `name` & `user.username` to `user.name`
- fix the disabled input for the user `name` update
- fix the query for `/project/:id` which was returning an array
- fix react warnings & memory leaks

### Nice to have

After playing a little with the app I added a few nice to have:

- Project edition: the project lead is now a selector of users
- Activity: I added 2 new fields to give more context to the Activity: `Milestone` to declare a release for exemple, `Repository URL` to set a link to a PR, a commit, a tag, etc.

### Features

I've picture myself buying this software for my (fake) agency and I thought that it could be cool to be able to import my user database into this app so I created an **import users by csv feature** that enable an admin to bulk import users into the system. We can imagine doing the same for projects and why not the ablity to export users/projects.

### TDDR

- Fix: user edit, project findOne, react warnings
- Nice to have: project lead selector, activity milestone & repository url
- Feature: user imports by csv

---

# Technical test

## Introduction

Fabien just came back from a meeting with an incubator and told them we have a platform “up and running” to monitor people's activities and control the budget for their startups !

All others developers are busy and we need you to deliver the app for tomorrow.
Some bugs are left and we need you to fix those. Don't spend to much time on it.

We need you to follow these steps to understand the app and to fix the bug :

- Sign up to the app
- Create at least 2 others users on people page ( not with signup )
- Edit these profiles and add aditional information
- Create a project
- Input some information about the project
- Input some activities to track your work in the good project
  
Then, see what happens in the app and fix the bug you found doing that.

## Then

Time to be creative, and efficient. Do what you think would be the best for your product under a short period.

### The goal is to fix at least 3 bugs and implement 1 quick win feature than could help us sell the platform

## Setup api

- cd api
- Run `npm i`
- Run `npm run dev`

## Setup app

- cd app
- Run `npm i`
- Run `npm run dev`

## Finally

Send us the project and answer to those simple questions :

- What bugs did you find ? How did you solve these and why ?
- Which feature did you develop and why ?
- Do you have any feedback about the code / architecture of the project and what was the difficulty you encountered while doing it ?
