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
      <img src="https://seismo.berkeley.edu/press_img/nature-journal.jpg" alt="" />
    </a>
    <a href="http://webofknowledge.com" class="link-item" target="_blank" title="Web of Science / SCI">
      <img src="https://customimages.webofknowledge.com/clarivate_82x57.png" alt="" />
    </a>
    <a href="http://onlinelibrary.wiley.com/" class="link-item" target="_blank" title="Wiley">
      <img src="https://onlinelibrary.wiley.com/pb-assets/hub-assets/pericles/logo-header-1690978619437.png" alt="" />
    </a>
    <a href="https://www.elsevier.com/" class="link-item" target="_blank" title="Elsevier">
      <img src="https://www.whxb.pku.edu.cn/images/1000-6818/images/ElsevierLogo.png" alt="" />
    </a>
    <a href="http://www.sciencemag.org/journals" class="link-item" target="_blank" title="Science / 科学">
      <img src="https://www.most.org/wp-content/uploads/2020/05/Science-AAAS-300x116.png" alt="" />
    </a>
    <a href="http://www.most.gov.cn/" class="link-item" target="_blank" title="科技部">
      <img src="https://www.most.gov.cn/images/header-title.png" alt="" />
    </a>
    <a href="http://www.cas.cn/" class="link-item" target="_blank" title="中国科学院">
      <img src="https://pic.biodiscover.com/files/n/zm/201708011549196551.jpg" alt="" />
    </a>
    <a href="http://www.nsfc.gov.cn/" class="link-item" target="_blank" title="自然科学基金委">
      <img src="https://i4.antpedia.com/attachments/2019/12/202148_201912161441361.jpg" alt="" />
    </a>
    <a href="https://robot.hnu.edu.cn/index.htm" class="link-item" target="_blank" title="机器人视觉感知与控制技术国家工程研究中心">
      <img src="https://robot.hnu.edu.cn/images/logo1.png" alt="" />
    </a>
    <a href="https://eeit.hnu.edu.cn/" class="link-item" target="_blank" title="电气与信息工程学院">
      <img src="https://eeit.hnu.edu.cn/images/logo.gif" alt="" />
    </a>
    <a href="https://www.patenthub.cn/" class="link-item" target="_blank" title="专利汇">
      <img src="https://www.patenthub.cn/images/logo_lg-f1374e94dbc2a84667333ae23dd25ed9e38d3d9c.png" alt="" />
    </a>
    <a href="https://ieeexplore.ieee.org/" class="link-item" target="_blank" title="IEEExplore">
      <img src="https://faculty.eng.ufl.edu/computing-for-life/wp-content/uploads/sites/68/2020/07/Logo-IEEE-Xplore-300x52.png" alt="" />
    </a>
      <!-- 添加更多链接 -->
  </div>
</div>
