---
layout: default
title: Analysis
number: 2
---

# Analysis
## Japan 
Japan’s aggressive and fascistic actions after World War I laid the groundwork for their imperial ambitions across Asia. From the early 30s to the end of the war, Japan invaded and annexed territories throughout all of Asia, even reaching into US territories and Australia, claiming to be the liberators from the east. This claim came from the belief that Japan alone was capable of leading Asia, an idea that soon tied itself to their national rhetoric and a key reason for war. This ideology traces back to Pan-Asianism, a 19th-century movement advocating for Asian unity 

# Embedding a Single Image

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'BunmeiMovement'" %}
{% include media.html pages=media %}

# Embedding a Single Video
{% assign media = site.media_metadata | where_exp: "item", "item.name == 'RiseOfPrussia'" %}
{% include media.html pages=media %}

# Linking to a PDF File

[Download PDF file]({{ site.baseurl }}/media_files/pdfs/newspaper1942.pdf)
