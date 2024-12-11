---
layout: default
title: Supplements
number: 4
---

# Supplements

Do you have supplementary materials (such as media files) or links for further information for the reader? (minimum 3 additional media files or links)

# Timeline

<iframe class='timeline-iframe' src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1loYsJVTFK_boNf1vc-EU727NoGtHMitATjUC7YdQWiQ&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>

# Supplementary Websites

[WWII Propaganda:The Influence of Racism](https://cwp.missouri.edu/2012/wwii-propaganda-the-influence-of-racism/)

[Racial, Ethnic, and Religious Minorities in World War II: A Resource Guide](https://guides.loc.gov/racial-ethnic-and-religious-minorities-in-world-war-ii/introduction)

# Supplementary Media Files

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'racial'" %} {% include media.html pages=media %}
