---
permalink: /portfolio/
title: "作品集"
layout: single
author_profile: true
---

<style>
.portfolio-page .portfolio-intro {
  margin-bottom: 28px;
  line-height: 1.9;
}

.portfolio-page .project-list {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 22px;
}

.portfolio-page .project-card {
  display: flex;
  flex-direction: column;
  padding: 26px;
  border: 1px solid #e8ebed;
  border-radius: 12px;
  background: #ffffff;
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.03);
}

.portfolio-page .project-number {
  margin-bottom: 16px;
  color: #929ba1;
  font-size: 0.8em;
  letter-spacing: 2px;
}

.portfolio-page .project-title {
  margin: 0 0 14px;
  padding: 0;
  border: 0;
  color: #494e52;
  font-size: 1.15em;
  line-height: 1.6;
  overflow-wrap: anywhere;
}

.portfolio-page .project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 18px;
}

.portfolio-page .project-tag {
  padding: 4px 10px;
  border-radius: 5px;
  background: #f0f4f7;
  color: #526a7b;
  font-size: 0.7em;
}

.portfolio-page .project-description {
  margin: 0;
  color: #626a70;
  font-size: 0.9em;
  line-height: 1.9;
}

.portfolio-page .project-status {
  margin-top: auto;
  padding-top: 22px;
  color: #929ba1;
  font-size: 0.75em;
}

@media (max-width: 700px) {
  .portfolio-page .project-list {
    grid-template-columns: 1fr;
  }

  .portfolio-page .project-card {
    padding: 22px;
  }
}
</style>

<div class="portfolio-page">

  <p class="portfolio-intro">
    这里整理了我在学习和实习期间参与的四个项目，
    从 C++ 搜索引擎到 Agent 系统，再到移动端功能接入。
    后续会陆续补充实现思路、个人负责的部分和演示。
  </p>

  <div class="project-list">

    <!-- 项目一 -->
    <article class="project-card">
      <div class="project-number">01</div>

      <h2 class="project-title">C++ 小型搜索引擎</h2>

      <div class="project-tags">
        <span class="project-tag">C++</span>
        <span class="project-tag">搜索引擎</span>
      </div>

      <p class="project-description">
        使用 C++ 编写的小型搜索引擎。
        这里将介绍项目的整体结构、搜索流程，以及实现过程中遇到的问题。
      </p>

      <div class="project-status">
        项目详情与演示整理中
      </div>
    </article>

    <!-- 项目二 -->
    <article class="project-card">
      <div class="project-number">02</div>

      <h2 class="project-title">车载仲裁 Agent 系统</h2>

      <div class="project-tags">
        <span class="project-tag">Agent</span>
        <span class="project-tag">车载场景</span>
      </div>

      <p class="project-description">
        面向车载场景的仲裁 Agent 系统。
        这里将介绍具体的仲裁任务、系统工作流程，以及我负责的部分。
      </p>

      <div class="project-status">
        项目详情与演示整理中
      </div>
    </article>

    <!-- 项目三 -->
    <article class="project-card">
      <div class="project-number">03</div>

      <h2 class="project-title">标书生成 Agent 系统</h2>

      <div class="project-tags">
        <span class="project-tag">Agent</span>
        <span class="project-tag">四象实习</span>
      </div>

      <p class="project-description">
        在北京四象网讯科技有限公司实习期间参与的项目。
        围绕标书生成场景，后续将补充业务流程、技术实现及个人贡献。
      </p>

      <div class="project-status">
        项目介绍整理中
      </div>
    </article>

    <!-- 项目四 -->
    <article class="project-card">
      <div class="project-number">04</div>

      <h2 class="project-title">QQ 闪传接入灵动岛</h2>

      <div class="project-tags">
        <span class="project-tag">移动端</span>
        <span class="project-tag">腾讯实习</span>
      </div>

      <p class="project-description">
        在深圳腾讯计算机系统有限公司实习期间参与的项目，
        将 QQ 闪传接入灵动岛。后续将补充功能效果、接入过程及个人负责的内容。
      </p>

      <div class="project-status">
        项目介绍整理中
      </div>
    </article>

  </div>

</div>
