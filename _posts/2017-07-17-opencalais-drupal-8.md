---
layout: post
title: "OpenCalais and Drupal 8"
date: 2017-07-17
description: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua Ut enim..."
banner_preview: blog1.jpg
banner_image: oc_d8_banner.jpeg
category: Coding
tags: [contrib, drupal, module]
---
OpenCalais is a web service that analyses text for extracting “SocialTags”. As the OpenCalais documentation says: “SocialTags” are associations of the text with Wikipedia categories or articles. SocialTags attempt to emulate how a person would tag a specific piece of content”. 
The service can also extract “Entities” such as people, companies, organizations and others.

When I first tested the module it worked pretty well but it was only available for Drupal 7. As Drupal PKM will be developed based on Drupal 8, I needed to start the work of porting the module. 
Testing between the available modules I saw that there were a lot of them that are deprecated and no longer supported.

## OpenCalais UI
It’s based on the OpenCalais API module which is the most recent between the ones that use the service. At the time when I started to work on it, the module had some dependencies on third party libraries that were barely supported. Thankfully, the new documentation removes all no-longer-used dependencies and uses json responses for the analysis result.
Since I need this module actively maintained I create OpenCalais UI as a sandbox project in Drupal.org. OpenCalais UI thus, adds some very basic stuff for making the module work on Drupal 8.

## Guide through config and functionality
The module adds a configuration form where users should add their API Key:
![post_cover]({{site.baseurl}}/assets/post_img/oc_d8_1.png){: .post_img}

Then, in each Content Type Form a select element is added where the user should choose the field where to add the new taxonomy terms.
![post_cover]({{site.baseurl}}/assets/post_img/oc_d8_2.png){: .post_img}

Now, a new tab is displayed when editing a node with the title “OpenCalais Tags”:
![post_cover]({{site.baseurl}}/assets/post_img/oc_d8_3.png){: .post_img}

Inside the tab, users will find a simple form where the node is shown and a “Suggest Tags” button is added, when clicked, the service will analyze the text and display all the suggested tags as checkboxes. Every checkbox that is selected will be added as a Taxonomy term to the node when the button “Save” is clicked.
![post_cover]({{site.baseurl}}/assets/post_img/oc_d8_4.png){: .post_img}

With that, the basic functionality of the module has been added. For now, it does not use all the options from the web service and any patch with new features is welcome. If you want to contribute with issues and patches, you can check the issue queue of the module [here](https://www.drupal.org/project/issues/2894247).
