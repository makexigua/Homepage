---
permalink: /portfolio/
title: "作品集"
layout: single
author_profile: true
---

<style>
.project-page {
  --project-line: #e5e9ed;
  --project-dot: #8fa9ba;
  --project-text: #494e52;
  --project-muted: #727b83;
  --project-border: #e8ecf0;
  --project-background: #ffffff;
  --project-soft: #f5f7f9;
}

.project-page .portfolio-intro {
  margin-bottom: 36px;
  color: var(--project-muted);
  line-height: 1.9;
}

/* 时间轴 */
.project-page .project-timeline {
  position: relative;
  padding: 4px 0;
}

.project-page .project-timeline::before {
  content: "";
  position: absolute;
  top: 16px;
  bottom: 32px;
  left: 9px;
  width: 2px;
  background: var(--project-line);
}

/* 每个项目都是独立卡片 */
.project-page .project-item {
  position: relative;
  padding: 0 0 36px 42px;
}

.project-page .project-item:last-child {
  padding-bottom: 0;
}

/* 时间轴圆点 */
.project-page .project-item::before {
  content: "";
  position: absolute;
  top: 27px;
  left: 2px;
  width: 16px;
  height: 16px;
  box-sizing: border-box;
  border: 3px solid #ffffff;
  border-radius: 50%;
  background: var(--project-dot);
  box-shadow: 0 0 0 1px var(--project-line);
  z-index: 1;
}

.project-page .project-card {
  overflow: hidden;
  padding: 28px;
  border: 1px solid var(--project-border);
  border-radius: 12px;
  background: var(--project-background);
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.035);
}

/* 卡片标题区域 */
.project-page .project-meta {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 8px 14px;
  margin-bottom: 12px;
  color: var(--project-muted);
  font-size: 0.75em;
  line-height: 1.6;
}

.project-page .project-category {
  padding: 3px 9px;
  border-radius: 5px;
  background: #edf3f7;
  color: #526f83;
}

.project-page .project-title {
  margin: 0 0 18px;
  padding: 0;
  border: 0;
  color: var(--project-text);
  font-size: 1.25em;
  line-height: 1.5;
  overflow-wrap: anywhere;
}

/* 项目正文 */
.project-page .project-block {
  margin-top: 22px;
}

.project-page .project-block h3 {
  margin: 0 0 10px;
  padding: 0;
  border: 0;
  color: var(--project-text);
  font-size: 0.9em;
  line-height: 1.6;
}

.project-page .project-block p,
.project-page .project-block ul {
  margin: 0;
  color: var(--project-muted);
  font-size: 0.85em;
  line-height: 1.9;
}

.project-page .project-block ul {
  padding-left: 1.3em;
}

.project-page .project-block li + li {
  margin-top: 6px;
}

/* 未填写内容的提示 */
.project-page .project-placeholder {
  padding: 14px 16px;
  border-radius: 8px;
  background: var(--project-soft);
}

/* 视频 */
.project-page .project-video {
  margin-top: 24px;
  padding-top: 22px;
  border-top: 1px solid var(--project-border);
}

.project-page .project-video h3 {
  margin: 0 0 12px;
  padding: 0;
  border: 0;
  color: var(--project-text);
  font-size: 0.9em;
}

.project-page .project-video video {
  display: block;
  width: 100%;
  height: auto;
  max-height: 520px;
  border-radius: 8px;
  background: #111111;
}

.project-page .video-placeholder {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  min-height: 130px;
  padding: 20px;
  box-sizing: border-box;
  border: 1px dashed #d5dde4;
  border-radius: 8px;
  background: var(--project-soft);
  color: var(--project-muted);
  font-size: 0.8em;
  text-align: center;
}

.project-page .video-placeholder span {
  font-size: 1.4em;
}

/* 手机端 */
@media (max-width: 640px) {
  .project-page .portfolio-intro {
    margin-bottom: 28px;
  }

  .project-page .project-item {
    padding-left: 30px;
    padding-bottom: 26px;
  }

  .project-page .project-card {
    padding: 20px;
  }

  .project-page .project-title {
    font-size: 1.1em;
  }
}
</style>

<div class="project-page">

  <p class="portfolio-intro">
    这里记录了我在学习和实习期间参与的项目。
    从 C++ 到 Agent 系统，再到移动端功能接入，
    每个项目都是一次把想法落到实际功能上的尝试。
  </p>

  <div class="project-timeline">

    <!-- ========================================
         项目一：QQ 闪传接入灵动岛
         ======================================== -->
    <div class="project-item">
      <article class="project-card">

        <div class="project-meta">
          <span class="project-category">腾讯实习</span>
          <span>2026.07 — 2026.09</span>
        </div>

        <h2 class="project-title">QQ 闪传接入灵动岛</h2>

        <div class="project-block">
          <h3>项目简介</h3>
          <p>
            在深圳腾讯计算机系统有限公司实习期间参与的项目，
            围绕 QQ 闪传接入灵动岛开展相关工作。
          </p>
        </div>

        <div class="project-block">
          <h3>我的工作与成果</h3>
          <p class="project-placeholder">
            待补充：我负责的功能、接入过程中解决的问题，
            以及最终实现的效果。
          </p>
        </div>

        <div class="project-video">
          <h3>项目介绍视频</h3>

          <div class="video-placeholder">
            <span aria-hidden="true">▶</span>
            视频整理中
          </div>

          <!--
          视频上传后，删除上面的 video-placeholder，
          再删除这段注释的起止标记，启用下面的播放器。

          <video controls playsinline preload="metadata">
            <source
              src="{{ '/assets/videos/qq-demo.mp4' | relative_url }}"
              type="video/mp4"
            >
            你的浏览器不支持视频播放。
          </video>
          -->

        </div>

      </article>
    </div>

    <!-- ========================================
         项目二：标书生成 Agent 系统
         ======================================== -->
    <div class="project-item">
      <article class="project-card">

        <div class="project-meta">
          <span class="project-category">四象实习</span>
          <span>2026.02 — 2026.05</span>
        </div>

        <h2 class="project-title">标书生成 Agent 系统</h2>

        <div class="project-block">
          <h3>项目简介</h3>
          <p>
            在北京四象网讯科技有限公司实习期间参与的项目，
            面向标书生成场景，使用 Agent 系统辅助完成相关任务。
          </p>
        </div>

        <div class="project-block">
          <h3>我的工作与成果</h3>
          <p class="project-placeholder">
            待补充：我负责的模块、标书生成的具体流程，
            以及最终完成的功能或改进。
          </p>
        </div>

        <div class="project-video">
          <h3>项目介绍视频</h3>

          <div class="video-placeholder">
            <span aria-hidden="true">▶</span>
            视频整理中
          </div>

          <!--
          <video controls playsinline preload="metadata">
            <source
              src="{{ '/assets/videos/bid-agent-demo.mp4' | relative_url }}"
              type="video/mp4"
            >
            你的浏览器不支持视频播放。
          </video>
          -->

        </div>

      </article>
    </div>

    <!-- ========================================
         项目三：车载仲裁 Agent 系统
         ======================================== -->
    <div class="project-item">
      <article class="project-card">

        <div class="project-meta">
          <span class="project-category">Agent 项目</span>
          <!-- 确认日期后，可在这里添加 <span>起止日期</span> -->
        </div>

        <h2 class="project-title">车载仲裁 Agent 系统</h2>

        <div class="project-block">
          <h3>项目简介</h3>
          <p>
            面向车载场景的仲裁 Agent 系统，
            探索使用 Agent 完成相关仲裁任务。
          </p>
        </div>

        <div class="project-block">
          <h3>我的工作与成果</h3>
          <p class="project-placeholder">
            待补充：具体的仲裁场景、系统如何做出决策、
            我负责的部分，以及测试或演示效果。
          </p>
        </div>

        <div class="project-video">
          <h3>项目介绍视频</h3>

          <div class="video-placeholder">
            <span aria-hidden="true">▶</span>
            视频整理中
          </div>

          <!--
          <video controls playsinline preload="metadata">
            <source
              src="{{ '/assets/videos/vehicle-agent-demo.mp4' | relative_url }}"
              type="video/mp4"
            >
            你的浏览器不支持视频播放。
          </video>
          -->

        </div>

      </article>
    </div>

    <!-- ========================================
         项目四：C++ 小型搜索引擎
         ======================================== -->
    <div class="project-item">
      <article class="project-card">

        <div class="project-meta">
          <span class="project-category">C++ 项目</span>
          <!-- 确认日期后，可在这里添加 <span>起止日期</span> -->
        </div>

        <h2 class="project-title">C++ 小型搜索引擎</h2>

        <div class="project-block">
          <h3>项目简介</h3>
          <p>
            使用 C++ 编写的小型搜索引擎，
            在实践中学习搜索系统的设计与实现。
          </p>
        </div>

        <div class="project-block">
          <h3>我的工作与成果</h3>
          <p class="project-placeholder">
            待补充：搜索引擎支持的功能、核心实现、
            我解决的问题，以及实际运行效果。
          </p>
        </div>

        <div class="project-video">
          <h3>项目介绍视频</h3>

          <div class="video-placeholder">
            <span aria-hidden="true">▶</span>
            视频整理中
          </div>

          <!--
          <video controls playsinline preload="metadata">
            <source
              src="{{ '/assets/videos/search-engine-demo.mp4' | relative_url }}"
              type="video/mp4"
            >
            你的浏览器不支持视频播放。
          </video>
          -->

        </div>

      </article>
    </div>

  </div>

</div>
