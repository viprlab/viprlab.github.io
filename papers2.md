---
layout: page
permalink: /papers2/
title: Papers
pubs:
    - year: "2016"
      groups:
        - title:   "Spatio-temporal Mid-Level Feature Bank for Action Recognition in Low Quality Video"
          author:  "Saimunur Rahman, John See"
          journal: "ICASSP 2016"
          note: "Accepted"
          year:    "2016"
          url:     ""
          doi:     ""
        - title:   "Paper title in 3-7 words that sound like Clingon"
          author:  "M. McFly, D. Kirk, L. Skywalker, H.J. Potter, I. Jones, H. Houdini"
          journal: "Transactions on Black Magic"
          note:    "(presented at Oz)"
          year:    "2015"
          url:     "http://publish-more-stuff.org"
          doi:     "http://dx.doi.org"
    - year: "2015"
      groups:	
        - title:   "Paper title in 3-7 words that sound like Clingon"
          author:  "M. McFly, D. Kirk, L. Skywalker, H.J. Potter, I. Jones, H. Houdini" 
          journal: "Transactions on Black Magic"
          note:    "(presented at Oz)"
          year:    "2014"
          url:     "http://publish-more-stuff.org"
          doi:     "http://dx.doi.org"
---

## Publications

{% for pub in page.pubs %}
### {{pub.year}}
{% for entry in pub.groups %}
{% if entry.internal %}[{{entry.title}}]({{entry.url | prepend: site.baseurl}}){% else %}[{{entry.title}}]({{entry.url}}){% endif %}<br />
{{entry.author}}<br />
{{entry.journal}}&nbsp;
{% if entry.note %} *({{entry.note}})*
{% endif %} [(doi)]({{entry.doi}})
{% endfor %}
{% endfor %}


