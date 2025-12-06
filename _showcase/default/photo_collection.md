---
show: true
width: 4
#date: 2021-09-12 00:01:00 +0800
height: 295px
images:
- src: ./assets/images/photos/home.JPG
  title: Shanghai
  desc: my hometown.
- src: ./assets/images/photos/cuhk1.png
  title: CUHK
  desc: beautiful scene
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
