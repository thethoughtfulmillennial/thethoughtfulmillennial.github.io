---
layout: post
title: "Introducing: Drupal PKM"
date: 2017-05-22
description: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua Ut enim..."
banner_image: blog-banner.jpg
category: Coding
tags: [contrib, drupal, pkm]
---
Drupal is an open source CMS with great standard features, great flexibility, amazing performance and modularity for improving the core experience.

Drupal PKM is a project that started along with [MD Systems](https://www.md-systems.ch), a Switzerland based company that works with Drupal 8 and it is one of the top contributors for Drupal. We had long conversations for defining the goal of this project and we defined it as being a Personal Knowledge Management platform based on Drupal 8.
The project will be developed as a Drupal distribution.

## Project purpose, scope and objectives
This project will develop a Personal Knowledge Management tool based on Drupal 8. It will allow students to add information from trusted parties to let them add thoughts, ideas and more info around the gathered resources. Then, the users will build their own knowledge graph.

There will be other techniques of knowledge management implemented in the system and they will be added in the software through development iterations.
There has been a lot of research around the concept of “Social learning” and its various approaches. This project will be based on the “Bottom-up” approach that let people manage their knowledge at an individual level.
## System overview
Users will able to install the system on their computers and all the information will be stored locally. The user, then, can add notes to internet cloned resources to express ideas, thoughts and old acquired knowledge that is related. When a note is created, they will be displayed as a reference to the main source and they can also be seen as a graph knowledge that links all nodes (concepts or main ideas) with the references created by the user. Each note can have tags that are also created hierarchically. A Personal wiki will be available to the user with all the knowledge and information that the system has.

Since this project targets university students, another way to organizing the data can be through university subjects so when an user adds a new concept or resource it can be immediately linked to a subject. The user should also be able to set reminders for adding “learning reviews” when needed so they can check what they have learned. Also, users can add “job aids”, to have manuals or guides for processes or things that the user has learned.
## Overview of software development
All people around this project has made exhaustive research for selecting the most useful tools for managing knowledge, the first idea that will be implemented and will be used as base for other elements of the system is the “ZettelKasten” concept, and the first step for implementing it is adding third party resources as cloned in the system so user can link notes to them.

The first approach will be node-driven where all references will be at node level. When the functionality is provided the next step will add references at paragraph level. After that, since the knowledge representation is an important part of this project, the graph view for references and concepts will be added along with a historic view of all the gathered resources.
When all three components are added (graph view, ZettelKasten and references) the project will get a personal wiki that will include all information and knowledge in the system.

The project, then, will add content types for “job aids” and “learning reviews” for completing the first concept of the project. 

Please note, that all this process will be made with a test-driven approach to ensure the correct functionality of the system.
## From now on
I will be creating blogpost each week or when needed about the new features implemented and the main ideas for adding the mentioned concepts.
