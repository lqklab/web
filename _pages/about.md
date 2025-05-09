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


<div style="margin: 10px">
<div class='titleText titleText837'><span class='bannerNormalTitle fk_mainTitle mainTitle mainTitle837'>常用网站</span></div>

<div class='formMiddleContent formMiddleContent837 fk-formContentOtherPadding' tabStyle='0'>
<a href="http://www.nature.com/siteindex/index.html" target="_blank" title="Nature / 自然"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAgm4XgxQUo2OmLxwQwvQE4gQE.png" alt="" /></a>
<a href="http://webofknowledge.com" target="_blank" title="Web of Science / SCI"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAgu8rUxQUoqpithQEwzQQ4qwI.png" alt="" /></a>

<a href="http://onlinelibrary.wiley.com/" target="_blank" title="Wiley"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAgkIXgxQUo9NfumwMw4wI4jgE.png" alt="" /></a>
<a href="https://www.elsevier.com/" target="_blank" title="Elsevier "><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAgv9akzAUoiqLOlQIwigU4nQM.png" alt="" /></a>
<a href="http://www.scibull.com:8080/EN/volumn/home.shtml" target="_blank" title="Science Bulletin / 科学通报"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/2/ABUIABACGAAgl-WQxQUo2KyY6wMw-gw4kQc.jpg" alt="" /></a>
<a href="http://mts-nature.nature.com/cgi-bin/main.plex" target="_blank" title="NATURE manuscript submission"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAg09PUxQUosJq0wwIwnwM4hgI.png" alt="" /></a>
<a href="http://www.editorialmanager.com/anie/default.aspx" target="_blank" title="WILEY manuscript submission"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAg9cPUxQUoiZaStgMw8AE4jAE.png" alt="" /></a>

<a href="http://www.sciencemag.org/journals" target="_blank" title="Science / 科学"><img width="110" height="60" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAgi4XgxQUokJjV2gYwsgI4pQE.png" alt="" /></a>
<a href="http://www.most.gov.cn/" target="_blank" title="科技部"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAgk4XgxQUowOC0gAcwpQI4rAE.png" alt="" /></a>

<a href="http://www.cas.cn/" target="_blank" title="中国科学院"><img width="70" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAglYXgxQUokJzu1AYw4QE44QE.png" alt="" /></a>

<a href="http://www.nsfc.gov.cn/" target="_blank" title="自然科学基金委"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/2/ABUIABACGAAgh4XgxQUosLPQRjCaAjizAQ.jpg" alt="" /></a>

<a href="http://cassi.cas.org/search.jsp" target="_blank" title="CASSI"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAgyKDGzwUo7N-FvQUw3AE4jAE.pnghttp://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAgyKDGzwUo7N-FvQUw3AE4jAE.png" alt="" /></a>
<a href="https://mc.manuscriptcentral.com/nr" target="_blank" title="Nanoscale"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAgy5KmzAUoz4PhhgYwrgU4nwM.png" alt="" /></a>
<a href="https://eeslive.elsevier.com/biomat/default.asp?pg=login.asp" target="_blank" title="Biomaterials"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAguZemzAUor7K23AcwngU4nwM.png" alt="" /></a>
<a href="https://acs.manuscriptcentral.com/acs" target="_blank" title="ACS manuscript submission"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAg-MPUxQUokNnCtQUwvAI4uQE.png" alt="" /></a>

<a href="https://www.alfa.com/zh-cn/" target="_blank" title="Alfa Aesar"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/4/ABUIABAEGAAgq97UxQUo06vsvQEwpAI4rAE.png" alt="" /></a>


<a href="http://www.nanoanalyst.org/" target="_blank" title="Nanoanalyst"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/2/ABUIABACGAAgyPLWxwUopvXPtgEwzhI4qwk.jpg" alt="" /></a>
<a href="http://www2.soopat.com/Home/IIndex" target="_blank" title="专利搜索引擎"><img width="110" height="70" src="http://12742044.s21i-12.faiusr.com/3/ABUIABADGAAgnfSSxwUouJz_4wcwngI4bg.gif" alt="" /></a>


</div>
</div>