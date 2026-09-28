---
layout: post
title: 全国研电赛一等奖
date: 2024-08-08 16:00:00-0400
related_posts: false
images:
  lightbox2: true
  photoswipe: true
  spotlight: true
  venobox: true
img: /assets/img/activities/competition/01.jpg
description: 实验室成员邓淞允、周立、裴瑞元获第十九届研电赛全国一等奖
_styles: >
  .competition-article {
    max-width: 920px;
    margin: 0 auto;
    color: var(--global-text-color);
    line-height: 1.78;
  }

  .competition-article .lead {
    margin: 0 0 1.5rem;
    padding: 1.1rem 1.25rem;
    border-left: 4px solid var(--global-theme-color);
    background: var(--global-bg-color);
    box-shadow: 0 1px 0 var(--global-divider-color);
    font-size: 1.02rem;
  }

  .competition-article h2 {
    margin-top: 2.2rem;
    padding-bottom: 0.35rem;
    border-bottom: 1px solid var(--global-divider-color);
    font-size: 1.42rem;
    font-weight: 600;
  }

  .competition-article h3 {
    margin-top: 1.8rem;
    font-size: 1.08rem;
    font-weight: 600;
  }

  .competition-meta {
    width: 100%;
    margin: 1.25rem 0 1.9rem;
    border-collapse: collapse;
    font-size: 0.96rem;
  }

  .competition-meta th,
  .competition-meta td {
    padding: 0.58rem 0.7rem;
    border-top: 1px solid var(--global-divider-color);
    vertical-align: top;
  }

  .competition-meta th {
    width: 9.5rem;
    color: var(--global-theme-color);
    font-weight: 600;
    white-space: nowrap;
  }

  .competition-list {
    margin: 1.1rem 0 1.8rem;
    padding-left: 1.2rem;
  }

  .competition-list > li {
    margin-bottom: 1.05rem;
  }

  .competition-list strong {
    font-weight: 600;
  }

  .competition-figure,
  .competition-gallery {
    margin: 1.55rem 0 2rem;
  }

  .competition-figure {
    text-align: center;
  }

  .competition-figure img,
  .competition-gallery img {
    max-width: 100%;
    height: auto;
    border-radius: 4px;
    box-shadow: 0 2px 12px rgba(0, 0, 0, 0.08);
  }

  .competition-figure img {
    width: 640px;
  }

  .competition-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1rem;
    align-items: start;
  }

  .competition-gallery figure {
    margin: 0;
  }

  .competition-caption {
    margin-top: 0.6rem;
    color: var(--global-text-color-light);
    font-size: 0.88rem;
    line-height: 1.5;
    text-align: center;
  }

  .competition-note {
    margin-top: 2.1rem;
    padding-top: 1rem;
    border-top: 1px solid var(--global-divider-color);
    color: var(--global-text-color-light);
    font-size: 0.95rem;
  }

  @media (max-width: 576px) {
    .competition-article .lead {
      padding: 0.95rem 1rem;
    }

    .competition-meta th,
    .competition-meta td {
      display: block;
      width: 100%;
      padding-left: 0;
      padding-right: 0;
    }

    .competition-meta td {
      padding-top: 0;
      border-top: 0;
    }
  }
---

<div class="competition-article" markdown="1">

## 视觉小组厨余垃圾分拣系统获研电赛全国总决赛一等奖

<p class="lead">
2024 年 8 月 8 日至 10 日，“兆易创新杯”第十九届中国研究生电子设计竞赛全国总决赛在东南大学无锡国际校区举行。实验室视觉小组成员邓淞允、周立、裴瑞元组成的 AISorter 团队，凭借面向厨余垃圾分拣场景的智能生成式快速抓取系统，荣获全国总决赛一等奖。
</p>

<table class="competition-meta">
  <tbody>
    <tr>
      <th>竞赛名称</th>
      <td>“兆易创新杯”第十九届中国研究生电子设计竞赛</td>
    </tr>
    <tr>
      <th>竞赛时间</th>
      <td>2024 年 8 月 8—10 日</td>
    </tr>
    <tr>
      <th>竞赛地点</th>
      <td>东南大学无锡国际校区</td>
    </tr>
    <tr>
      <th>参赛队伍</th>
      <td>AISorter（邓淞允、周立、裴瑞元）</td>
    </tr>
    <tr>
      <th>获奖情况</th>
      <td>全国总决赛一等奖</td>
    </tr>
  </tbody>
</table>

<figure class="competition-figure">
  <a class="spotlight" href="{{ '/assets/img/activities/competition/01.jpg' | relative_url }}" title="一等奖证书">
    <img src="{{ '/assets/img/activities/competition/01.jpg' | relative_url }}" alt="研电赛全国总决赛一等奖证书" loading="lazy">
  </a>
  <figcaption class="competition-caption">图 1. 研电赛全国总决赛一等奖证书。</figcaption>
</figure>

## 项目概述

厨余垃圾自动分类分拣对机器人视觉识别与动态抓取提出了较高要求。针对传统物体检测方法受数据规模和算法能力限制、生成式架构难以直接用于抓取任务等问题，团队面向传送带分拣场景设计了智能生成式快速抓取系统。

## 技术方案

<ol class="competition-list">
  <li><strong>数据采集与构建。</strong>采集并整理高质量训练数据，提升模型对不同形态、姿态和遮挡条件下厨余垃圾的表征能力。</li>
  <li><strong>标注数据处理。</strong>设计高效的数据标注与处理方案，降低数据准备成本并加快模型训练。</li>
  <li><strong>生成式模型轻量化。</strong>对生成式抓取模型进行轻量化设计，使其能够满足传送带场景中的实时响应需求。</li>
</ol>

## 实验结果与成果

系统在实际分拣任务中 1 小时内完成超过 1500 个固体废物的分拣，验证了方案在识别速度、抓取效率和连续运行方面的可行性。该工作也是生成式方法首次独立应用于传送带抓取任务，为厨余垃圾自动分拣中的生成式视觉与操作研究提供了实践案例。

<div class="competition-gallery">
  <figure>
    <a class="spotlight" href="{{ '/assets/img/activities/competition/02.jpg' | relative_url }}" title="比赛现场">
      <img src="{{ '/assets/img/activities/competition/02.jpg' | relative_url }}" alt="研电赛比赛现场合照" loading="lazy">
    </a>
    <figcaption class="competition-caption">图 2. 比赛现场。</figcaption>
  </figure>
  <figure>
    <a class="spotlight" href="{{ '/assets/img/activities/competition/03.jpg' | relative_url }}" title="项目展示">
      <img src="{{ '/assets/img/activities/competition/03.jpg' | relative_url }}" alt="项目展示演示文稿" loading="lazy">
    </a>
    <figcaption class="competition-caption">图 3. 项目展示。</figcaption>
  </figure>
</div>

<p class="competition-note">
赛事官网：<a href="https://cpipc.acge.org.cn/cw/hp/6">中国研究生创新实践系列大赛</a>。相关报道：<a href="https://robot.hnu.edu.cn/info/1061/1696.htm">湖南大学机器人学院</a>。
</p>

</div>
