---
layout: post
title: "Week 2: Project Management"
date: 2019-10-25
---

**Day 1 - 25 October 2019 (Friday)**

To kickstart the project management week, I first watched a video on project management on the [fabacademy website](https://vimeopro.com/academany/fab-2019/video/314004299).

In this tutorial, Neil covered the basics of tools that we’ll be using during our project work -- this may be for synchronisation, version control or web development.

However, the main focus was on how to manage your project well. For this he covered 7 basic principles:


**1. Triage** - while working through the project, I need to pick projects that lie at the intersection of my ambition and what can be accomplished.

**2. Demand and supply side time management** - I need to balance between tasks that are necessary but take a lot of time, or fix the time and decide the tasks and schedule work around that.

**3. Serial versus parallel development** - when each project is broken down into tasks, in the interest of time, work on parallel tasks most of the time and serial tasks only when necessary. This is to make sure that anyone task does not block you from completing the project.

**4. Spiral development** - do not think of projects as something that will develop in a linear fashion. Think of it as a spiral or a loop - where each task finishes and opens into the next task. 

**5. Bottom up versus top down debugging** - bottom up debugging is starting from scratch and adding few parts at a time to a task to test if its working, while top down is removing parts from a system to see what should be removed for the task to work.

**6. Hierarchy and modularity** - projects should be as modular as possible.

**7. Document as you work** - don’t wait until the end of the week to finish your documenting your learnings and your work.

Markdown tutorials that I used to learn markdown syntax:

* [Markdown tutorial](https://www.markdowntutorial.com/lesson/5/) 
* [Mastering Markdown on Github](https://guides.github.com/features/mastering-markdown/)
* [Wikipedia for Markdown](https://en.wikipedia.org/wiki/Markdown#Example) 
* [Markdown guide](https://www.markdownguide.org/)

All these tutorials and guides on markdown have the same information, but reading it repetitively has helped me recollect the syntax for text formatting a lot more quickly. 

After reading the tutorial, I fixed some formatting issues on my website. For this, I downloaded [Github Desktop](https://desktop.github.com/) and [sublime text editor](https://www.sublimetext.com/3). The advantages of downloading these two are as follows:
firstly, Github desktop will allow me to clone a local version of my online repository, making it available for me offline -- even enabling me to add files and documents to the local file, which will synchronise with the online website when I enable it, and secondly sublime text editor will allow me to edit the content of the website offline -- so I don't have to have a steady internet connection while working.

In the first version of my website, for Day 1, I had listed out the machinery in the digital fabrication workshop, with a description of the capabilities of these machines, and a picture. However, the list was not working on the website. While I wanted them to be listed 1,2,3,4... it was showing as 1,1,1,1. For some reason that wasn't immediately obvious to me, the code was not able to read it as a continuous list.

After multiple iterations and attempts, I finally realised that there was an empty line between the list item title and the description. So I removed the empty line between the title and the description and between the description and the picture. This solved one problem -- so now the list was working, with the numbers in a neat progression. However, because of the lack of a gap between the description and the picture, the picture was coming up in between the description making it difficult to read continuously. To correct this, I inserted two spaces after the last sentence of the description. This automatically pushed the picture into a new line. I also indented the description and the picture with a >.

For integrating github, the online version, with githu desktop, there are a number of steps:
1. You have to.