---
layout: layout.njk
title: Sad Robot
---

# Sad Robot

I don't consider myself a novelist. Not even a writer. But I like stories and visions of the future. Though I am quite picky and can't really find many stories that I consider to be positive Sci-Fi. Optimistic views on the fututre and technology. And maybe there isn't a market for those kind of stories. The 20th century conditioned us for a skeptic view on technology and a bleak view of the future. 

Just to keep sane in this eternal dismal view of the work I sometimes think of nice future perspectives. Now I start dropping them into this repository. No Idea if this ever will become a coherent story or will for ever be a collection of random snippets. 

I call this repository “sad robot” because of pub-philosophical questions that once popped into my head. What would cause my my Robot Vacuum Cleaner to be sad? I fondly call him Robbie. And yes he is male. What would I do to cheer him up. Spill an extra portion of crubs on the floor? 

So dear visitor who just happened to stumble over these files be warned. Don't expect exiting penmenship. Read along if you like. 


## Drafts

<ul>
{%- for chapter in collections.chapter -%}
  <li><a href="{{ chapter.url | url }}">{{ chapter.data.title }}</a></li>
{%- endfor -%}
</ul>