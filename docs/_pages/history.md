---
permalink: /history
hidden: false
---

## History of the RPG Squire

### The Beginnings....
RPG Squire started out in the beginning of 2019 as a small application that Ken Moore started writing up for himself and some of his friends while they played a game of Pathfinder. This original application was written in C++/Qt5, and was originally called "a glorified calculator". It was an experiment in a dynamic calculation system that utilized JSON-formatted text to determine how to reference items and perform calculations. Over the course of the next year, it continued to evolve and change. A way to write up compaign logs. Then a way to dynamically keep track of items, how many uses a skill had remaining. A way to automatically make changes to stats and skill when an item was equipped or unequipped. Dice rollers, icons for skills and items, and all sorts of other visual elements. 

![RPG Squire v1](/assets/images/rpgsquire-v1_1.png)

### The Issues Arise...
While Ken could make items and abilities really easily, how could he easily send those to his friends? At the moment, the only way to make it work for them was for them to bring their laptops over to Ken to update the app and add items as needed. He created a public GitHub repository in September of 2019 to host the JSON items in a loose "database" that he could easily have his friends pull new items and changes from. This helped solve the distribution of items, but a new issue quickly arose... How to get the app on all his friends' computers? He was using a Linux laptop for developing, one friend had a Mac (which he got the app working on, with great difficulty). The friend with a netbook was completely out of luck.

![RPG Squire v1](/assets/images/rpgsquire-v1_2.png)

### The Transformation...
In the beginning of 2020, Ken began to experiment with newer types of applications, specifically, Ken started working a lot more with the "go" programming language and putting together websites using various frameworks. He knew that go could easily build static binaries for pretty much all operating systems available, the only thing missing was a graphical layer to let him rebuild the interface. After a couple months of experimentation, he realized that while go was extremely cross-platform, graphical systems were not. The only "standard" graphical interface that worked everywhere was browser-based, and Go provided several ways to generate websites. The vision of RPG Squire as a browser-based web service started to come together. He would never have to worry about updating the app on people's systems, the database of pre-built items would always be available, and with all the COVID lockdowns going on, this would provide a way for GM's to easily run games while everybody was connected remotely (something Ken had in mind for a while).

### The Web App Rises...
Being an application developer primarily, but already maintaining several go-based websites and network-services, Ken realized that he needed to find a go-framework that would let him write the entire app within golang only. Maintaining sites written in 3 different programming languages (go, HTML, and Javascript) could be done - but the transitions between the languages were rough. Enter [go-app](https://go-app.dev/). This framework was perfect, it let Ken write go exclusively, while generating a web-assembly binary that ran in the browser faster than Javascript sites! Over the next several months, Ken started re-creating the application using go-app for the interface. The entire app got a makeover - not just graphically, but also cleaning up the backend systems. The app became less of a front-end for a Pathfinder characters only, and became a general RPG character manager for any kind of ruleset.

## Timeline
* October 2018 - Started experimenting with JSON-based calculation system.
* March, 2019 - Create a GitHub repository to store the source files
* September, 2019 - Create a public GitHub repository to act as the database of JSON files.
* February, 2020 - Start re-writing the calculation systems in Golang
* May, 2020 - Picked go-app framework for the web app and started writing the site
* January, 2021 - Starting to finish up the non-character interactions.

