--- 
layout: page
permalink: /papers2/
pubs: 
  - 
    groups: 
      - 
        author: "Md Baharul Islam, Wong Lai Kuan, Wong Chee Onn"
        doi: 10.1007/s11042-016-3561-5
        note: Accepted
        pub: "ROVISP 2016"
        title: "A Survey of Aesthetics-Driven Image Recomposition"
        type: j
        url: "http://link.springer.com/article/10.1007/s11042-016-3561-5"
      - 
        author: "Saimunur Rahman, John See"
        pub: "ICASSP 2016"
        title: "Spatio-temporal Mid-Level Feature Bank for Action Recognition in Low Quality Video"
        type: c
        url: "http://pesona.mmu.edu.my/~johnsee/research/papers/files/stem_icassp16"
      - 
        author: "Saimunur Rahman, John See, Chiung Ching Ho"
        pub: "ICASSP 2016"
        title: "Deep CNN Object"
        type: c
        url: "http://pesona.mmu.edu.my/~johnsee/research/papers/files/stem_icassp16"
      - 
        author: "Saimunur Rahman, John See, Chiung Ching Ho"
        pub: "ROVISP 2016"
        title: "Leveraging Textural Features for Recognizing Actions in Low Quality Videos"
        type: c
        url: "http://pesona.mmu.edu.my/~johnsee/research/papers/files/leverage_rovisp16"
      - 
        author: "Muhammad Faiz Ghazali, Wong Lai Kuan, John See"
        pub: "ROVISP 2016"
        title: "Automatic Detection and Counting of Circular and Rectangular Steel Bars"
        type: c
        url: "http://pesona.mmu.edu.my/~johnsee/research/papers/files/steel_rovisp16.pdf"
    year: "2016"
  - 
    groups: 
      - 
        author: "M. McFly, D. Kirk, L. Skywalker, H.J. Potter, I. Jones, H. Houdini"
        doi: "http://dx.doi.org"
        note: "(presented at Oz)"
        pub: "Transactions on Black Magic"
        title: "Paper title in 3-7 words that sound like Clingon"
        type: j
        url: "http://publish-more-stuff.org"
        year: "2015"
    year: "2015"
title: Papers
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
