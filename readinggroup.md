---
layout: page
permalink: /readinggroup/
title: Reading Group
reads:

    - date:		"26 April 2016"
      location:  "ViPr Lab"
      presenter: "Magzhan"
      paper:    "Rapid: Rating pictorial aesthetics using deep learning"
	  pub: "Lu, X., Lin, Z., Jin, H., Yang, J., & Wang, J. Z. MM 2014" 
	  url: "http://www.personal.psu.edu/xxl5086/paper/fp245-lu.pdf"
	  projsite: ""
	  slides: "/files/magzhan-RAPID-compressed.pdf"

    - date:		"3 May 2016"
      location:  "ViPr Lab"
      presenter: "Saimunur"
      paper:    "Action recognition with trajectory-pooled deep-convolutional descriptors"
	  pub: "Wang, L., Qiao, Y., Tang, X. CVPR 2015"
	  url: "http://wanglimin.github.io/papers/WangQT_CVPR15.pdf"
	  projsite: "http://wanglimin.github.io/tdd/index.html"
	  slides: "/files/saimun-tdd-readinggroup.pdf"
	  
	- date:		"10 May 2016"
      location:  "M. McFly, D. Kirk, L. Skywalker, H.J. Potter, I. Jones, H. Houdini"
      presenter: "John"
      paper:    "What makes an image popular?"
	  pub: "WWW 2014"
	  url: ""
	  projsite: ""
	  slides: ""

---

## Reading Group

| Date | Location | Presenter | Description |
|--|--|--|--| 
{% for read in page.reads %}| {{read.date}} | {{read.location}} | {{read.presenter}} | {{read.paper}} | 
{% endfor %}
