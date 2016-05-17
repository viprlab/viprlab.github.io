---
layout: page
permalink: /papers2/
title: Papers
pubs:
    - year: "2016"
      groups:
	    - title:   "A Survey of Aesthetics-Driven Image Recomposition"
          author:  "Md Baharul Islam, Wong Lai Kuan, Wong Chee Onn"
          pub:     "ROVISP 2016"
          type:     j
          url:     "http://link.springer.com/article/10.1007/s11042-016-3561-5"	
          note:    "Accepted"
          doi:     "10.1007/s11042-016-3561-5"	  
        - title:   "Spatio-temporal Mid-Level Feature Bank for Action Recognition in Low Quality Video"
          author:  "Saimunur Rahman, John See"
          pub:     "ICASSP 2016"
          type:     c 
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/stem_icassp16"
        - title:   "Deep CNN Object"
          author:  "Saimunur Rahman, John See, Chiung Ching Ho"
          pub:     "ICASSP 2016"
          type:     c 
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/stem_icassp16"
        - title:   "Leveraging Textural Features for Recognizing Actions in Low Quality Videos"
          author:  "Saimunur Rahman, John See, Chiung Ching Ho"
          pub:     "ROVISP 2016"
          type:     c
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/leverage_rovisp16"
        - title:   "Automatic Detection and Counting of Circular and Rectangular Steel Bars"
          author:  "Muhammad Faiz Ghazali, Wong Lai Kuan, John See"
          pub:     "ROVISP 2016"
          type:     c
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/steel_rovisp16.pdf"
    - year: "2015"
      groups:	
        - title:   "Paper title in 3-7 words that sound like Clingon"
          author:  "M. McFly, D. Kirk, L. Skywalker, H.J. Potter, I. Jones, H. Houdini" 
          pub:     "Transactions on Black Magic"
          note:    "(presented at Oz)"
          year:    "2015"
          url:     "http://publish-more-stuff.org"
          type:     j
          doi:     "http://dx.doi.org"
---

## Publications

{% for pub in page.pubs %}
### {{pub.year}}
{% for entry in pub.groups %}
{% if entry.internal %}[{{entry.title}}]({{entry.url | prepend: site.baseurl}}){% else %}[{{entry.title}}]({{entry.url}}){% endif %}<br />
{{entry.author}}<br />
{{entry.pub}}
{% if entry.note %} **({{entry.note}})**{: style="color: maroon"}
{% endif %} {% if entry.doi %} [[doi]]({{entry.doi}}) {% endif %} 
{% endfor %}
{% endfor %}
