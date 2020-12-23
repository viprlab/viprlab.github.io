---
layout: page
permalink: /readinggroup/
title: Reading Group
reads:
    - date: "18 Dec"
      time: "1100"
      presenter: "Nelson, JY Ching"
      paper: "Computational Aesthetics: Moving Forward"
      details: "Kim et al. PieNet: Personalized Image Enhancement Network (ECCV 2020)<br>Zhan et al. Self-Supervised Scene De-occlusion (CVPR 2020)" 

---
{% include imagethumbnailblock.html align="right" url="/images/rg-pic1.jpg" height="150px" padding="left" %}{% include imagethumbnailblock.html align="right" url="/images/rg-pic2.jpg" height="150px" padding="left" %}
We have a paper reading group for all faculty, postgraduates and undergraduates who are affiliated with our lab, where we take turns to present a paper, lead a discussion, or even share interesting topics apart from work. 
We usually meet every week/fortnight at ViPr Lab although we are currently meeting virtually. Drop us an email if you wish to join our sessions. <br><br>   

## Schedule

| Date | Time | Presenter | Description |
|:-|:-:|:-:|:- 
{% for read in page.reads %}| {{read.date}} | {{read.time}} | {{read.presenter}} | [{{read.paper}}]({{read.url}}){:target="_blank"}<br>{% if read.details %}*{{read.details}}*{:.rgdetails}{% endif %}<br>{% if read.proj %} &nbsp;[![project site](/images/website-icon.png)]({{read.proj}}){% endif %}{% if read.slides %}{% if read.slides %} &nbsp;[![slides](/images/slides-icon.png)]({{read.slides}}){% endif %}{% endif %} | 
{% endfor %}