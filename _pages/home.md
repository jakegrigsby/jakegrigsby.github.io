---
layout: about
title: home
permalink: /

profile:
  align: right
  image: profile_pic.jpeg
  image_cicular: true # crops the image to make it circular

news: false  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

I am a first year CS PhD student at UT Austin, working with [Prof. Yuke Zhu](https://www.cs.utexas.edu/~yukez/) and the [Robot Perception and Learning Lab](https://rpl.cs.utexas.edu). My research focuses on deep learning and reinforcement learning. Before coming to Austin, I studied Math and CS at the University of Virginia, where my research was advised by [Prof. Yanjun Qi](https://www.cs.virginia.edu/yanjun/).


## Code

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
