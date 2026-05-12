---
permalink: /
title: "Hello, I am Yujia Zhang."
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral researcher at [Southeast University](https://www.seu.edu.cn/), working with [Prof. Xiaolin Meng](https://www.researchgate.net/profile/Xiaolin-Meng-2). Before that I had worked as postdoctoral research at AUSM Lab with [Professor Gunho Sohn](https://gunhosohn.me/) in [York University](https://www.yorku.ca/). I completed my PhD in Geodetic Science at [The Ohio State University](https://www.osu.edu/), with my advisor [Prof. Alper Yilmaz](https://ceg.osu.edu/people/yilmaz.15). Before that I received my bachelor's degree from [Wuhan University](https://www.whu.edu.cn/).


Research Interests
======


Education
======

* **PhD in Geodetic Science**, 2012-09-01 to 2019-01-01
* **Bachelor in Geodesy and Geomatics**, 2007-09-01 to 2011-06-30


Experience
------

* **Postdoctoral Researcher in School of Instrument Science and Engineering**, 2023-06 to present
* **Postdoctoral Researcher in Earth and Space Science and Engineering**, 2019-01-01 to 2022-12-31


Research Topics
------

* Geodesy and Geomatics
* Computer Vision
* SLAM
* Brain-inspired Navigation
* Photogrammetry
* 3D Reconstruction



Publications
------

{% assign recent_publications = site.publications | sort: "date" | reverse %}
{% for post in recent_publications limit: 8 %}
{% assign publication_url = post.url | prepend: base_path %}
{% if post.link %}{% assign publication_url = post.link %}{% endif %}
* **[{{ post.title }}]({{ publication_url }})**  
  {{ post.authors }}. _{{ post.venue }}_, {{ post.date | date: "%Y" }}.
{% endfor %}

For the full and most up-to-date list, please see [my Google Scholar profile](https://scholar.google.com/citations?hl=en&user=ww8ZXGEAAAAJ).


Blogs
------

Contact
------

Email: [yujia_zhang@seu.edu.cn](mailto:yujia_zhang@seu.edu.cn)
