---
layout: profiles
permalink: /people/
title: 团队成员
description: members of the lab or group
nav: true
# nav_order: 7

profiles:
  # if you want to include more than one profile, just replicate the following block
  # and create one content file for each profile inside _pages/
  - align: right
    image: members/qh.jpg
    content: > 
      2015年于湘潭大学信息工程学院获得硕士学位。目前在湖南大学电气与信息工程学院攻读博士学位。
      他的研究方向为智能机器人感知、计算机视觉和机器学习。
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>555 your office number</p>
      <p>123 your address street</p>
      <p>Your City, State 12345</p>
  - align: left
    image: members/dsy.jpg
    content: 
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>555 your office number</p>
      <p>123 your address street</p>
      <p>Your City, State 12345</p>

  - align: right
    image: members/yy.jpg
    content: 
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>555 your office number</p>
      <p>123 your address street</p>
      <p>Your City, State 12345</p>
---


<!-- 导师信息 -->
<hr>
<div class="profile float-left">
    {% assign profile_image_path = "prof_pic.jpg" | prepend: 'assets/img/' %}
    {% capture sizes %}(min-width: {{ site.max_width }}) {{ site.max_width | minus: 30 | times: 0.1}}px, (min-width: 576px) 30vw, 95vw{% endcapture %}
    {% include figure.liquid 
        loading="eager" 
        path=profile_image_path 
        class="img-fluid z-depth-1 rounded" 
        alt="prof_pic.jpg" 
        sizes=sizes
    %}

    <div class="more-info">
        电子邮件： qiaokang@hnu.edu.cn <br>
        通信地址：湖南省长沙市岳麓区湖南大学机器人视觉国家工程研究中心501<br>
        邮政编码：410082 
    </div>
</div>

<div class="clearfix">
    <p style="text-indent: 2em;">
        <span style="font-weight: bold;">个人简介：</span>
        湖南省杰出青年基金获得者，入选湖南省优秀青年骨干教师，被授予湖南省优秀党务工作者、湖南省教育系统优秀党务工作者、湖南大学双带头人标兵、湖南大学优秀教师、湖南大学我心目中最敬爱的老师、湖南省挑战杯学科竞赛优秀指导老师、全国研究生大数据人工智能竞赛优秀指导老师，获湖南大学教学比赛一等奖、湖南省教学成果一等奖、国家级教学成果二等奖。
    </p>
    <p style="text-indent: 2em;">
        <span style="font-weight: bold;">研究方向：</span>
        机器人智能感知与控制、人工智能及其应用技术、机器人力触觉感知与应用。
        面向典型工业、医学、农业、运动竞技等场景对智能感知与控制技术的实际需求，聚焦复杂场景下感知与处理新方法和关键技术，实现力触觉感知、图像分割、识别、分类、检测等高效高精度信息处理，在复杂工业场景自动化检测、医学图像判读、农业病害信息辅助诊断的基础算法、支持精准诊断和治疗的图像处理方法等方面为促进工业现场自动化智能化、疾病诊断与治疗精细化、农业智能化水平提升发挥重要作用。
    </p>
</div>


<!-- 其他成员信息将通过 profiles layout 自动渲染 -->