---
layout: page
permalink: /readinggroup/
title: Reading Group
reads:

    - date:   "26 April 2016"
      venue:  "ViPr Lab"
      presenter: "Magzhan"
      paper:    "Rapid: Rating pictorial aesthetics using deep learning"
      details:    "Lu, X., Lin, Z., Jin, H., Yang, J., & Wang, J. Z. MM 2014"
      url:     "http://www.personal.psu.edu/xxl5086/paper/fp245-lu.pdf"
      doi:     "http://dx.doi.org"

    - date:   "3 May 2016"
      venue:  "ViPr Lab"
      presenter: "Saimun"
      paper:    "Action recognition with trajectory-pooled deep-convolutional descriptors"
      details:    "Wang, L., Qiao, Y., Tang, X. CVPR 2015"
      url:     "http://wanglimin.github.io/papers/WangQT_CVPR15.pdf"
      doi:     "http://dx.doi.org"

    - date:   "10 May 2016"
      venue:  "ViPr Lab"
      presenter: "John"
      paper:    "What makes an image popular?"
      details:    "Khosla, A., Das Sarma, A., Hamid, R. WWW 2014"
      url:     "http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.464.6890&rep=rep1&type=pdf"
      doi:     "http://dx.doi.org"

    - date:   "17 May 2016"
      venue:  "ViPr Lab"
      presenter: "-"
      paper:    "(presented at Oz)"
      details:    "2013"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"

    - date:   "24 May 2016"
      venue:  "ViPr Lab"
      presenter: "Transactions on Black Magic"
      paper:    "(presented at Oz)"
      details:    "2012"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"

---

## Reading Group Schedule

| Date | Location | Presenter | Description |
|-|:-|:-:|-: 
{% for read in page.reads %}| {{read.date}} | {{read.venue}} | {{read.presenter}} | {{read.paper}}<br>{{read.details}} | 
{% endfor %}

