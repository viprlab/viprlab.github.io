---
layout: page
permalink: /readinggroup/
title: Reading Group
reads:

    - date:   "26 April 2016"
      venue:  "ViPr Lab"
      presenter: "Transactions on Black Magic"
      paper:    "(presented at Oz)"
      details:    "2016"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"

    - date:   "3 May 2016"
      venue:  "ViPr Lab"
      presenter: "Transactions on Black Magic"
      paper:    "(presented at Oz)"
      details:    "2015"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"

    - date:   "10 May 2016"
      venue:  "ViPr Lab"
      presenter: "Transactions on Black Magic"
      paper:    "(presented at Oz)"
      details:    "2014"
      url:     "http://publish-more-stuff.org"
      doi:     "http://dx.doi.org"

    - date:   "17 May 2016"
      venue:  "ViPr Lab"
      presenter: "Transactions on Black Magic"
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
|--|--|--|--| 
{% for read in page.reads %}| {{read.date}} | {{read.venue}} | {{read.presenter}} | {{read.paper}}<br>{{read.details}} | 
{% endfor %}

