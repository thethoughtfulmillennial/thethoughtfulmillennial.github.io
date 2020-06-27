---
layout: project
title: "Drupal"
date: 2016-01-01
banner_image: project/drupal_banner.png
thumbnail: drupal_thumbnail.png
category: Software
order: 1
---
Drupal is an open source CMS with great standard features, great flexibility, amazing performance and modularity for improving the core experience.

I started my journey with Drupal in 2015 when I was accepted for an internship at MD Systems through IAESTE Bolivia. Thanks to that I was able to be the top 15th contributor of Drupal in the world in 2017.

## Contribution
Thanks to MD Systems I was able to work on the following projects around the Drupal ecosystem.

### Paragraphs
Paragraphs is one of the most used Drupal modules at the moment. It allows users to add a replacement for the Body field (where the user usually adds the conent of a page) with a dynamic field where the user can add different types of Paragraphs with differente fields and configuration.
Around my work with Paragraphs I was lucky to implement:
1. The behavior plugin system [See more](https://www.drupal.org/project/paragraphs/issues/2828506).
    - Allows the user to create custom plugins that can alter the behavior and display of Paragraphs when being rendered.
    - Enables perspective tabs over the Paragraphs field to display the Entity field or the Plugin config.
    - Allows to set specific configuration per Paragraph type.
2. The paragraph summary [See more](https://www.drupal.org/project/paragraphs/issues/3012053)
    - Create a visual difference between the plugins config and the Paragraphs fields.
    - Is updated dinamically and display icons for better overview.
3. "Add before" button [See more](https://www.drupal.org/project/paragraphs/issues/2946514)
    - Much work with automated testing following the Drupal testing framework.
    - Working with JS for adding the button and its behavior.

### Diff
Diff displays the differences between revisions comparing the changes inline and github like. In this module, I fixed lots of bugs, changed the settings management from being field storage based to entity field based, added a new way for displaying changes named as the “Visual Inline” layout, added image display on revision comparison, added a new changes summary on the revisions listing view and make each layout a plugin so it can be extended.

## Talks
Here you can find some of the talks I've given in various Drupal events.

2019, Drupal Mountain Camp - Davos, Switzerland
{% include youtube_player.html id='bivxAHMKKf8' %}


2018, Drupal Europe - Darmstadt, Germany
{% include youtube_player.html id='tn2SxXpQvGc' %}


2016, Drupal Dev Days - Milan, Italy
{% include youtube_player.html id='mAn_YFb98pE' %}
