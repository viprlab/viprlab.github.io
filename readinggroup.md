---
layout: page
permalink: /readinggroup/
title: Reading Group
reads:

    - date:   "2016-05-31"
      venue:  "ViPr Lab"
      presenter: "Magzhan"
      paper:    "Studying aesthetics in photographic images using a computational approach<br>Assessing the aesthetic quality of photographs using generic image descriptors"
      details:    "Datta, R., Joshi, D., Li, J., & Wang, J. Z. (ECCV 2006)<br>Marchesotti, L., Perronnin, F., Larlus, D., & Csurka, G (ICCV 2011)"
      url:     "http://infolab.stanford.edu/~wangz/project/imsearch/Aesthetics/ECCV06/datta.pdf"  

    - date:   "2016-05-24"
      venue:  "ViPr Lab"
      presenter: "Fahmid"
      paper:    "Kinect based calling gesture recognition for taking order service of elderly care robot"
      details:    "Zhao, X., Naguib, A.M., Lee, S. (ISRC 2014)"
      url:     "http://isrc.skku.ac.kr/publication/file/CP/ISRC-2014-CP-006-EN.pdf"

    - date:   "2016-05-17"
      venue:  "ViPr Lab"
      presenter: "-"
      paper:    "Video Tutorial: Deep learning, self-taught learning and unsupervised feature learning"
      details:    "Graduate Summer School 2012, Andrew Ng"
      url:     "https://www.youtube.com/watch?v=n1ViNeWhC24"
      slides: "http://helper.ipam.ucla.edu/publications/gss2012/gss2012_10595.pdf"	  

    - date:   "2016-05-10"
      venue:  "ViPr Lab"
      presenter: "John"
      paper:    "What makes an image popular?"
      details:    "Khosla, A., Das Sarma, A., Hamid, R. (WWW 2014)"
      url:     "http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.464.6890&rep=rep1&type=pdf"
      proj:    "http://popularity.csail.mit.edu" 

    - date:   "2016-05-03"
      venue:  "ViPr Lab"
      presenter: "Saimun"
      paper:    "Action recognition with trajectory-pooled deep-convolutional descriptors"
      details:    "Wang, L., Qiao, Y., Tang, X. (CVPR 2015)"
      url:     "http://wanglimin.github.io/papers/WangQT_CVPR15.pdf"
      proj:     "http://wanglimin.github.io/tdd/index.html"

    - date:   "2016-04-26"
      venue:  "ViPr Lab"
      presenter: "Magzhan"
      paper:    "Rapid: Rating pictorial aesthetics using deep learning"
      details:    "Lu, X., Lin, Z., Jin, H., Yang, J., & Wang, J. Z. (MM 2014)"
      url: "http://www.personal.psu.edu/xxl5086/paper/fp245-lu.pdf"

---

We have weekly paper reading group meet-ups. Feel free to join us, or if you would like to be part of the reading rotation. 
Current T3-1516 Term meets at **11.00am on Tuesdays**. 

## Schedule

| Date | Location | Presenter | Description |
|:-|:-:|:-:|:- 
{% for read in page.reads %}| {{read.date}} | {{read.venue}} | {{read.presenter}} | [{{read.paper}}]({{read.url}}){:target="_blank"}<br>{{read.details}}{% if read.proj %}<br>[Project site]({{read.proj}}){:target="_blank"}{% endif %}{% if read.slides %}<br>[Slides]({{read.slides}}){:target="_blank"}{% endif %} | 
{% endfor %}