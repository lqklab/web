---
layout: about
title: 主页
permalink: /


selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts

images:
  compare: true
  slider: true
---

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" loop="true" autoplay="true" autoplay-delay="3000" autoplay-disable-on-interaction="false">
  {% assign image_files = site.static_files | where_exp: "file", "file.path contains 'assets/img/slideshow'" %}
  {% for image in image_files %}
    {% if image.extname == '.jpg' or image.extname == '.jpeg' or image.extname == '.png' or image.extname == '.gif' %}
      <swiper-slide>{% include figure.liquid loading="eager" path=image.path class="img-fluid rounded z-depth-1" %}</swiper-slide>
    {% endif %}
  {% endfor %}
</swiper-container>



<div>
  <h4 class="title-home">常用网站</h4>

  <div class="link-container">
    <a href="http://www.nature.com/siteindex/index.html" class="link-item" target="_blank" title="Nature / 自然">
      <img src="https://media.springernature.com/full/nature-cms/uploads/product/nature/header-86f1267ea01eccd46b530284be10585e.svg" alt="" />
    </a>
    <a href="http://webofknowledge.com" class="link-item" target="_blank" title="Web of Science / SCI">
      <img src="https://customimages.webofknowledge.com/clarivate_82x57.png" alt="" />
    </a>
    <a href="http://onlinelibrary.wiley.com/" class="link-item" target="_blank" title="Wiley">
      <img src="https://onlinelibrary.wiley.com/pb-assets/hub-assets/pericles/logo-header-1690978619437.png" alt="" />
    </a>
    <a href="https://www.elsevier.com/" class="link-item" target="_blank" title="Elsevier ">
      <img src="https://www.elsevier.cn/images/elsevier-logo.svg" alt="" />
    </a>
    <a href="http://www.scibull.com:8080/EN/volumn/home.shtml" class="link-item" target="_blank" title="Science Bulletin / 科学通报">
      <img src="http://12742044.s21i-12.faiusr.com/2/ABUIABACGAAgl-WQxQUo2KyY6wMw-gw4kQc.jpg" alt="" />
    </a>
    <a href="http://www.sciencemag.org/journals" class="link-item" target="_blank" title="Science / 科学">
      <img src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAgi4XgxQUokJjV2gYwsgI4pQE.png" alt="" />
    </a>
    <a href="http://www.most.gov.cn/" class="link-item" target="_blank" title="科技部">
      <img src="https://www.most.gov.cn/images/header-title.png" alt="" />
    </a>
    <a href="http://www.cas.cn/" class="link-item" target="_blank" title="中国科学院">
      <img src="https://www.cas.cn/images/z19_logo.png" alt="" />
    </a>
    <a href="http://www.nsfc.gov.cn/" class="link-item" target="_blank" title="自然科学基金委">
      <img src="https://i4.antpedia.com/attachments/2019/12/202148_201912161441361.jpg" alt="" />
    </a>
      <!-- 添加更多链接 -->
  </div>

</div>