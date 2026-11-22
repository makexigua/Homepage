---
permalink: /
title: "关于我"
author_profile: true
---

<style>
/* 首页各区域 */
.personal-home {
  --timeline-dot: #a1b4c1;
  --timeline-line: #eeeeee;
  --card-bg: #f7f7f7;
  --text-color: #494e52;
}

.personal-home .home-intro {
  line-height: 1.9;
}

.personal-home .home-section {
  margin-top: 40px;
}

.personal-home .home-section > h2 {
  margin-bottom: 24px;
}

.personal-home .interest-list {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.personal-home .interest-tag {
  padding: 6px 14px;
  border-radius: 6px;
  background: #f2f4f5;
  color: #494e52;
  font-size: 0.85em;
}

/* 时间线 */
.personal-home .personal-timeline {
  position: relative;
  margin: 30px 0;
  padding: 28px 0 0;
}

.personal-home .personal-timeline::before {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: 50%;
  width: 2px;
  background: var(--timeline-line);
  transform: translateX(-50%);
}

.personal-home .tl-item {
  position: relative;
  width: 50%;
  box-sizing: border-box;
  padding: 12px 36px 44px 0;
}

.personal-home .tl-item:nth-child(even) {
  margin-left: 50%;
  padding: 12px 0 44px 36px;
}

/* 中线上的圆点 */
.personal-home .tl-item::before {
  content: "";
  position: absolute;
  top: 21px;
  right: -8px;
  width: 16px;
  height: 16px;
  border: 3px solid #ffffff;
  border-radius: 50%;
  background: var(--timeline-dot);
  box-sizing: border-box;
  z-index: 1;
}

.personal-home .tl-item:nth-child(even)::before {
  right: auto;
  left: -8px;
}

/* 日期 */
.personal-home .tl-date {
  margin-bottom: 12px;
  color: #929ba1;
  font-size: 0.78em;
  line-height: 1.5;
  text-align: right;
}

.personal-home .tl-item:nth-child(even) .tl-date {
  text-align: left;
}

/* 经历卡片 */
.personal-home .tl-card {
  display: flex;
  align-items: flex-start;
  gap: 16px;
  padding: 24px;
  border-radius: 8px;
  background: var(--card-bg);
  box-shadow: 0 2px 2px rgba(0, 0, 0, 0.12);
}

.personal-home .tl-icon {
  display: flex;
  align-items: center;
  justify-content: center;
  flex: 0 0 48px;
  width: 48px;
  height: 48px;
  border-radius: 50%;
  background: #ffffff;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.15);
  font-size: 24px;
}

/* 换成 Logo 图片时使用 */
.personal-home img.tl-icon {
  padding: 7px;
  margin: 0;
  box-sizing: border-box;
  object-fit: contain;
}

.personal-home .tl-text {
  flex: 1;
  min-width: 0;
  color: var(--text-color);
  line-height: 1.7;
  overflow-wrap: anywhere;
}

.personal-home .tl-item:nth-child(odd) .tl-text {
  text-align: right;
}

.personal-home .tl-title {
  font-size: 1em;
  font-weight: 600;
}

.personal-home .tl-role {
  margin-top: 4px;
  font-size: 0.9em;
}

.personal-home .tl-description {
  margin-top: 10px;
  color: #71777b;
  font-size: 0.76em;
}

/* 作品卡片 */
.personal-home .project-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 18px;
}

.personal-home .project-card {
  padding: 22px;
  border: 1px solid #eeeeee;
  border-radius: 8px;
  background: #ffffff;
}

.personal-home .project-card h3 {
  margin: 0 0 12px;
  font-size: 1em;
}

.personal-home .project-card p {
  margin: 0 0 14px;
  color: #71777b;
  font-size: 0.85em;
  line-height: 1.8;
}

.personal-home .project-card a {
  font-size: 0.85em;
}

.personal-home .contact-box {
  padding: 22px;
  border-radius: 8px;
  background: #f7f7f7;
  line-height: 1.9;
}

.personal-home .contact-box p {
  margin: 0;
}

.personal-home .contact-box a {
  overflow-wrap: anywhere;
}

/* 小屏幕：时间线改为单侧 */
@media (max-width: 640px) {
  .personal-home .personal-timeline::before {
    left: 8px;
  }

  .personal-home .tl-item,
  .personal-home .tl-item:nth-child(even) {
    width: 100%;
    margin-left: 0;
    padding: 12px 0 30px 34px;
  }

  .personal-home .tl-item::before,
  .personal-home .tl-item:nth-child(even)::before {
    left: 0;
    right: auto;
  }

  .personal-home .tl-date,
  .personal-home .tl-item:nth-child(even) .tl-date,
  .personal-home .tl-item:nth-child(odd) .tl-text {
    text-align: left;
  }

  .personal-home .tl-card {
    gap: 12px;
    padding: 18px;
  }

  .personal-home .project-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="personal-home">

  <!-- 个人介绍：修改下面的文字 -->
  <div class="home-intro">
    <h2>你好，我是小明 👋</h2>
    <p>
      欢迎来到我的个人主页。我目前生活在上海，
      喜欢摄影、旅行、技术，以及探索生活中有趣的小事。
    </p>
    <p>
      这里记录我的经历、作品和想法。
      希望通过这个小小的网站，让你更了解我。
    </p>
  </div>

  <!-- 兴趣：可以自由增删 -->
  <section class="home-section">
    <h2>我的兴趣</h2>
    <div class="interest-list">
      <span class="interest-tag">📷 摄影</span>
      <span class="interest-tag">✈️ 旅行</span>
      <span class="interest-tag">💻 编程</span>
      <span class="interest-tag">📚 阅读</span>
      <span class="interest-tag">🎵 音乐</span>
    </div>
  </section>

  <!-- 时间线：以下日期和经历均为示例，请替换 -->
  <section class="home-section">
    <h2>Timeline</h2>

    <div class="personal-timeline">

      <!-- 第 1 条：左侧 -->
      <div class="tl-item">
        <div class="tl-date">2025.08 — 至今</div>
        <div class="tl-card">
          <span class="tl-icon" aria-hidden="true">💼</span>
          <div class="tl-text">
            <div class="tl-title">某某公司</div>
            <div class="tl-role">你的职位</div>
            <div class="tl-description">
              在这里写一两句话，介绍你正在做的工作。
            </div>
          </div>
        </div>
      </div>

      <!-- 第 2 条：右侧 -->
      <div class="tl-item">
        <div class="tl-date">2025.02 — 2025.06</div>
        <div class="tl-card">
          <span class="tl-icon" aria-hidden="true">🚀</span>
          <div class="tl-text">
            <div class="tl-title">个人项目</div>
            <div class="tl-role">设计与开发</div>
            <div class="tl-description">
              从一个想法出发，完成了自己的第一个作品。
            </div>
          </div>
        </div>
      </div>

      <!-- 第 3 条：左侧 -->
      <div class="tl-item">
        <div class="tl-date">2024.06 — 2024.09</div>
        <div class="tl-card">
          <span class="tl-icon" aria-hidden="true">🌱</span>
          <div class="tl-text">
            <div class="tl-title">某某公司</div>
            <div class="tl-role">实习生</div>
            <div class="tl-description">
              在这里写你的实习内容、收获或难忘的经历。
            </div>
          </div>
        </div>
      </div>

      <!-- 第 4 条：右侧 -->
      <div class="tl-item">
        <div class="tl-date">2020.09 — 2024.06</div>
        <div class="tl-card">
          <span class="tl-icon" aria-hidden="true">🎓</span>
          <div class="tl-text">
            <div class="tl-title">某某大学</div>
            <div class="tl-role">你的专业 · 本科</div>
            <div class="tl-description">
              在这里写你的学习经历、社团活动或毕业项目。
            </div>
          </div>
        </div>
      </div>

      <!-- 第 5 条：左侧 -->
      <div class="tl-item">
        <div class="tl-date">2020.06</div>
        <div class="tl-card">
          <span class="tl-icon" aria-hidden="true">✨</span>
          <div class="tl-text">
            <div class="tl-title">一个值得记录的时刻</div>
            <div class="tl-role">新的起点</div>
            <div class="tl-description">
              时间线也可以记录旅行、搬家或人生中的重要瞬间。
            </div>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- 作品 -->
  <section class="home-section" id="projects">
    <h2>我的作品</h2>

    <div class="project-grid">
      <div class="project-card">
        <h3>💻 我的第一个项目</h3>
        <p>
          在这里介绍作品的用途、特点，以及你为什么想做它。
        </p>
        <a href="https://github.com/你的GitHub用户名">
          查看项目 →
        </a>
      </div>

      <div class="project-card">
        <h3>📷 我的摄影记录</h3>
        <p>
          用照片记录日常与旅途，收集那些值得记住的瞬间。
        </p>
        <a href="mailto:yourname@example.com">
          联系我了解更多 →
        </a>
      </div>
    </div>
  </section>

  <!-- 联系方式 -->
  <section class="home-section" id="contact">
    <h2>联系我</h2>

    <div class="contact-box">
      <p>如果你想交流、合作，或者只是打个招呼，欢迎联系我。</p>
      <p>
        📧 邮箱：
        <a href="mailto:yourname@example.com">
          yourname@example.com
        </a>
      </p>
      <p>
        🐙 GitHub：
        <a href="https://github.com/你的GitHub用户名">
          你的GitHub用户名
        </a>
      </p>
    </div>
  </section>

</div>
