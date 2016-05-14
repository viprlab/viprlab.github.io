---
layout: page
permalink: /readinggroup/
title: Reading Group
reads:

    - date:   "Paper title in 3-7 words that sound like Clingon"
      venue:  "M. McFly, D. Kirk, L. Skywalker, H.J. Potter, I. Jones, H. Houdini"
      presenter: "Transactions on Black Magic"
      paper:    "(presented at Oz)"
      details:    "2016"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"

    - date:   "Paper title in 3-7 words that sound like Clingon"
      venue:  "M. McFly, D. Kirk, L. Skywalker, H.J. Potter, I. Jones, H. Houdini"
      presenter: "Transactions on Black Magic"
      paper:    "(presented at Oz)"
      details:    "2015"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"

    - date:   "Paper title in 3-7 words that sound like Clingon"
      venue:  "M. McFly, D. Kirk, L. Skywalker, H.J. Potter, I. Jones, H. Houdini"
      presenter: "Transactions on Black Magic"
      paper:    "(presented at Oz)"
      details:    "2014"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"

    - date:   "Paper title in 3-7 words that sound like Clingon"
      venue:  "M. McFly, D. Kirk, L. Skywalker, H.J. Potter, I. Jones, H. Houdini"
      presenter: "Transactions on Black Magic"
      paper:    "(presented at Oz)"
      details:    "2013"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"

    - date:   "Paper title in 3-7 words that sound like Clingon"
      venue:  "M. McFly, D. Kirk, L. Skywalker, H.J. Potter, I. Jones, H. Houdini"
      presenter: "Transactions on Black Magic"
      paper:    "(presented at Oz)"
      details:    "2012"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"

---

## Reading Group Schedule

| Date | Location | Presenter | Description |
|--|--|--|--| 
{% for read in page.reads %}| {{read.date}} | {{read.venue}} | {{read.presenter}} | {{read.paper}}<br>{{read.details}} | 
{% endfor %}

