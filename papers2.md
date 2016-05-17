---
layout: page
permalink: /papers2/
title: Papers
pubs:
    - year: "2016"
      groups:
        - title:   "A Survey of Aesthetics-Driven Image Recomposition"
          author:  "Md Baharul Islam, Wong Lai Kuan, Wong Chee Onn"
          pub:     "Multimedia Tools and Applications"
          type:     j
          url:     "http://link.springer.com/article/10.1007/s11042-016-3561-5"	
          note:    "Accepted"
          doi:     "https://dx.doi.org/10.1007/s11042-016-3561-5"
        - title:   "Deep CNN Object Features for Improved Action Recognition in Low Quality Videos"
          author:  "Saimunur Rahman, John See, Chiung Ching Ho"
          pub:     "ICCSE 2016"
          type:     c 
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/deepobjfeat_iccse16.pdf"
          note:    "Accepted"		  
        - title:   "Spatio-temporal Mid-Level Feature Bank for Action Recognition in Low Quality Video"
          author:  "Saimunur Rahman, John See"
          pub:     "ICASSP 2016"
          type:     c 
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/stem_icassp16.pdf"
        - title:   "Leveraging Textural Features for Recognizing Actions in Low Quality Videos"
          author:  "Saimunur Rahman, John See, Chiung Ching Ho"
          pub:     "ROVISP 2016"
          type:     c
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/leverage_rovisp16.pdf"
        - title:   "Automatic Detection and Counting of Circular and Rectangular Steel Bars"
          author:  "Muhammad Faiz Ghazali, Wong Lai Kuan, John See"
          pub:     "ROVISP 2016"
          type:     c
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/steel_rovisp16.pdf"
    - year: "2015"
      groups:	
        - title:   "Lost and Found: Identifying Objects in Long-Term Surveillance Videos"
          author:  "Mohamad Mahdi Saemi, John See, Suyin Tan" 
          pub:     "ICSIPA 2015"
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/lostfound_icsipa15.pdf"
          type:     c
          doi:     "http://dx.doi.org"
		- title:   "Action recognition in low quality videos by jointly using shape, motion and texture features"
          author:  "Saimunur Rahman, John See, Chiung Ching Ho" 
          pub:     "ICSIPA 2015"
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/lowquality_icsipa15.pdf"
          type:     c
          doi:     "http://dx.doi.org"
		- title:   "Obscura: A mobile game with camera based mechanics "
          author:  "Albert Quek, John See" 
          pub:     "GAMEPEC 2015"
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/obscura_gamepec15.pdf"
          type:     c
          doi:     "http://dx.doi.org"
		- title:   "The Invoker: Intuitive gesture mechanics for motion-based shooter RPG "
          author:  "Albert Quek, John See" 
          pub:     "GAMEPEC 2015"
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/invoker_gamepec15.pdf"
          type:     c
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
