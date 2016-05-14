---
layout: page
permalink: /readinggroup/
title: Reading Group
reads:

    - date:   "2016-04-26"
      venue:  "ViPr Lab"
      presenter: "Magzhan"
      paper:    "Rapid: Rating pictorial aesthetics using deep learning"
      details:    "Lu, X., Lin, Z., Jin, H., Yang, J., & Wang, J. Z. MM 2014"
      url:     "http://www.personal.psu.edu/xxl5086/paper/fp245-lu.pdf"
      doi:     "http://dx.doi.org"

    - date:   "2016-05-03"
      venue:  "ViPr Lab"
      presenter: "Saimun"
      paper:    "Action recognition with trajectory-pooled deep-convolutional descriptors"
      details:    "Wang, L., Qiao, Y., Tang, X. CVPR 2015"
      url:     "http://wanglimin.github.io/papers/WangQT_CVPR15.pdf"
      doi:     "http://dx.doi.org"

    - date:   "2016-05-10"
      venue:  "ViPr Lab"
      presenter: "John"
      paper:    "What makes an image popular?"
      details:    "Khosla, A., Das Sarma, A., Hamid, R. WWW 2014"
      url:     "http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.464.6890&rep=rep1&type=pdf"
      doi:     "http://dx.doi.org"

    - date:   "2016-05-17"
      venue:  "ViPr Lab"
      presenter: "-"
      paper:    "Video tutorial screening"
      details:    "TBC"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"

    - date:   "2016-05-24"
      venue:  "ViPr Lab"
      presenter: "TBC"
      paper:    "TBC"
      details:    ""
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"

---

## Reading Group Schedule

| Date | Location | Presenter | Description |
|:-|:-|:-:|:- 
{% for read in page.reads %}| {{read.date}} | {{read.venue}} | {{read.presenter}} | {{read.paper}}<br>{{read.details}} | 
{% endfor %}

