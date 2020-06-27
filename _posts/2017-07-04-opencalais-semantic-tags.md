---
layout: post
title: "OpenCalais and semantic tags"
date: 2017-07-04
description: "The more content is created, the harder is to tag them all. Whenever an user needs to tag some kind of content the big and important..."
banner_image: post/opencalais_1.jpg
category: Coding
tags: [contrib, drupal, module]
---
![post_cover]({{site.baseurl}}/assets/post_img/opencalais_1.jpg){: .full width .post_img}
The more content is created, the harder is to tag them all. Whenever an user needs to tag some kind of content the big and important task of giving a meaning in the relation content-tag is run.  
In Drupal PKM, when an user adds notes (a notes post gonna be released soon) they should be able to create relations with the assigned tags, this is only possible with meaningful semantic tags.
Quoting to Miro Dietiker (MD Systems’ CEO):
<blockquote>
Risks are that people use tags without strategy, resulting in similar tags with different writing - being disconnected from each other, having many tags that are only used once, or other tags that are broadly used and meaningless because of their genericity.
</blockquote>

## What is OpenCalais?
The Calais module lets you configure which Content Types should be analyzed by Calais for metadata extraction on update. The metadata returned can then be automatically assigned to vocabularies, or it can only suggest terms allowing full user control of the tagging. The module has versions for Drupal 7 and Drupal 6.
## What is being done?
With the idea of improving the tagging task for the user, the OpenCalais tagging module is being ported to Drupal 8. It will only add the basic functionality and will allow the user to create a vocabulary with all the needed terms for the OpenCalais API. Then when the user adds the needed fields in any content type, they will also be able to check the node content and add the identified tags.
This will not be the final expected functionality for tagging but it will be taken as the first step for providing a semantically meaningful tag system.
You can follow the drupal.org issue [here](https://www.drupal.org/node/2890779)
