---
show: true
width: 4
date: 2021-09-12 00:01:00 +0800
height: 250px
images:
- src: /assets/images/photos/cambridge.pic.jpg
  desc: Cambridge
- src: /assets/images/photos/macau.pic.jpg
  desc: Macau
- src: /assets/images/photos/sanya.pic.jpg
  desc: Sanya
- src: /assets/images/photos/sewu.pic.jpg
  desc: Surabaya
- src: /assets/images/photos/sg.pic.jpg
  desc: Singapore
- src: /assets/images/photos/guangxi.pic.jpg
  desc: Chongzuo
- src: /assets/images/photos/edinburgh.pic.jpg
  desc: Edinburgh
- src: /assets/images/photos/manchester.pic.jpg
  desc: Manchester
- src: /assets/images/photos/hangzhou.pic.jpg
  desc: Hangzhou

---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
