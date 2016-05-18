---
layout: page
permalink: /papers/
title: Papers
pubs:
    - year: "2016"
      groups:
        - title:   "A Survey of Aesthetics-Driven Image Recomposition"
          author:  "Md Baharul Islam, Wong Lai Kuan, Wong Chee Onn"
          pub:     "Multimedia Tools and Applications"
          type:     j
          note:    "Accepted"
          doi:     "http://dx.doi.org/10.1007/s11042-016-3561-5"
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
        - title:   "Pressure-based Touch Positioning Techniques for 3D Objects"
          author:  "Siyuan Qiu, Lu Wang, Lai-Kuan Wong"
          pub:     "SIGGRAPH Symposium on Interactive 3D Graphics and Games (i3D) 2016"
          type:     c 
          doi:     "http://dx.doi.org/10.1145/2856400.2876010"	
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
        - title:   "Semantics Preserving Warping for Stereoscopic Image Retargeting"
          author:  "Chun-Hau Tan, Md Baharul Islam, Lai-Kuan Wong, Kok-Lim Low" 
          pub:     "PSIVT 2015"
          type:     c
          doi:     "http://dx.doi.org/10.1007/978-3-319-29451-3_21"	
        - title:   "On the Effects of Low Video Quality in Human Action Recognition"
          author:  "John See, Saimunur Rahman" 
          pub:     "DICTA 2015"
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/effects_dicta15.pdf"
          type:     c
          doi:     "http://dx.doi.org/10.1109/DICTA.2015.7371292"	  
        - title:   "Stereoscopic Image Warping for Enhancing Composition Aesthetics"
          author:  "Md Baharul Islam, Lai-Kuan Wong, Chee-Onn Wong, Kok-Lim Low" 
          pub:     "ACPR 2015"
          type:     c
        - title:   "Lost and Found: Identifying Objects in Long-Term Surveillance Videos"
          author:  "Mohamad Mahdi Saemi, John See, Suyin Tan" 
          pub:     "ICSIPA 2015"
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/lostfound_icsipa15.pdf"
          type:     c
          doi:     "http://dx.doi.org/10.1109/ICSIPA.2015.7412171"
        - title:   "Action Recognition in Low Quality Videos by Jointly Using Shape, Motion and Texture Features"
          author:  "Saimunur Rahman, John See, Chiung Ching Ho" 
          pub:     "ICSIPA 2015"
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/lowquality_icsipa15.pdf"
          type:     c
          doi:     "http://dx.doi.org/10.1109/ICSIPA.2015.7412168"
        - title:   "Obscura: A Mobile Game with Camera based Mechanics"
          author:  "Albert Quek, John See" 
          pub:     "GAMEPEC 2015"
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/obscura_gamepec15.pdf"
          type:     c
          doi:     "http://dx.doi.org/10.1109/GAMEPEC.2015.7331850"
        - title:   "The Invoker: Intuitive Gesture Mechanics for Motion-based Shooter RPG"
          author:  "Albert Quek, John See" 
          pub:     "GAMEPEC 2015"
          url:     "http://pesona.mmu.edu.my/~johnsee/research/papers/files/invoker_gamepec15.pdf"
          type:     c
          doi:     "http://dx.doi.org/10.1109/GAMEPEC.2015.7331847"

---

## Publications

{% for pub in page.pubs %}
### {{pub.year}}
{% for entry in pub.groups %}
{% if entry.internal %}[{{entry.title}}]({{entry.url | prepend: site.baseurl}}){% else %} {% if entry.url %} [{{entry.title}}]({{entry.url}}){:target="_blank"} {% else %} [{{entry.title}}]({{entry.doi}}){:target="_blank"} {% endif %} {% endif %}<br />
{{entry.author}}<br />
{{entry.pub}}
{% if entry.note %} **({{entry.note}})**{: style="color: maroon"}
{% endif %} {% if entry.doi %} [[doi]]({{entry.doi}}) {% endif %} 
{% endfor %}
{% endfor %}
