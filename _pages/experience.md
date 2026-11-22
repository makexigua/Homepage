---
permalink: /experience/
title: "过往经历"
layout: single
author_profile: true
---

---
permalink: /experience/
title: "过往经历"
layout: single
author_profile: true
---

<style>
.experience-page {
  --timeline-line: #eeeeee;
  --timeline-dot: #a1b4c1;
  --card-background: #f7f7f7;
  --text-color: #494e52;
}

.experience-page .experience-intro {
  margin-bottom: 32px;
  line-height: 1.9;
}

/* 时间线中轴 */
.experience-page .timeline {
  position: relative;
  margin: 32px 0;
  padding: 24px 0;
}

.experience-page .timeline::before {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: 50%;
  width: 2px;
  background: var(--timeline-line);
  transform: translateX(-50%);
}

/* 经历左右交替 */
.experience-page .timeline-item {
  position: relative;
  width: 50%;
  box-sizing: border-box;
  padding: 12px 36px 48px 0;
}

.experience-page .timeline-item:nth-child(even) {
  margin-left: 50%;
  padding: 12px 0 48px 36px;
}

/* 中轴圆点 */
.experience-page .timeline-item::before {
  content: "";
  position: absolute;
  top: 21px;
  right: -8px;
  width: 16px;
  height: 16px;
  border: 3px solid #ffffff;
  border-radius: 50%;
  box-sizing: border-box;
  background: var(--timeline-dot);
  z-index: 1;
}

.experience-page .timeline-item:nth-child(even)::before {
  right: auto;
  left: -8px;
}

/* 日期 */
.experience-page .timeline-date {
  margin-bottom: 12px;
  color: #929ba1;
  font-size: 0.8em;
  line-height: 1.6;
  text-align: right;
}

.experience-page .timeline-item:nth-child(even) .timeline-date {
  text-align: left;
}

/* 经历卡片 */
.experience-page .timeline-card {
  display: flex;
  align-items: flex-start;
  gap: 16px;
  padding: 24px;
  border-radius: 8px;
  background: var(--card-background);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
}

/* 默认表情图标，也支持替换为图片 */
.experience-page .timeline-icon {
  display: flex;
  align-items: center;
  justify-content: center;
  flex: 0 0 48px;
  width: 48px;
  height: 48px;
  border-radius: 50%;
  background: #ffffff;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.12);
  font-size: 24px;
}

.experience-page img.timeline-icon {
  margin: 0;
  padding: 7px;
  box-sizing: border-box;
  object-fit: contain;
}

.experience-page .timeline-content {
  flex: 1;
  min-width: 0;
  color: var(--text-color);
  line-height: 1.7;
  overflow-wrap: anywhere;
}

.experience-page .timeline-item:nth-child(odd) .timeline-content {
  text-align: right;
}

.experience-page .timeline-title {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 1em;
  font-weight: 600;
  line-height: 1.6;
}

.experience-page .timeline-role {
  margin-top: 6px;
  font-size: 0.9em;
}

.experience-page .timeline-description {
  margin: 12px 0 0;
  color: #71777b;
  font-size: 0.8em;
  line-height: 1.9;
}

/* 手机端改为单侧时间线 */
@media (max-width: 640px) {
  .experience-page .timeline::before {
    left: 8px;
  }

  .experience-page .timeline-item,
  .experience-page .timeline-item:nth-child(even) {
    width: 100%;
    margin-left: 0;
    padding: 12px 0 32px 34px;
  }

  .experience-page .timeline-item::before,
  .experience-page .timeline-item:nth-child(even)::before {
    left: 0;
    right: auto;
  }

  .experience-page .timeline-date,
  .experience-page .timeline-item:nth-child(even) .timeline-date,
  .experience-page .timeline-item:nth-child(odd) .timeline-content {
    text-align: left;
  }

  .experience-page .timeline-card {
    gap: 12px;
    padding: 18px;
  }

  .experience-page .timeline-icon {
    flex-basis: 40px;
    width: 40px;
    height: 40px;
    font-size: 22px;
  }
}
</style>

<div class="experience-page">

  <p class="experience-intro">
    从民航管制员到重新走进校园，再到寻找第一份程序员工作，
    我的职业方向拐了个弯。这里记录走过的路，也留一点空间给未来。
  </p>

  <div class="timeline">

    <!-- 经历一：请填写真实就读时间 -->
    <div class="timeline-item">
      <div class="timeline-date">起止时间待填写</div>

      <div class="timeline-card">
        <span class="timeline-icon" aria-hidden="true">🎓</span>

        <div class="timeline-content">
          <h2 class="timeline-title">北京邮电大学</h2>
          <div class="timeline-role">在读 · 向程序员转型</div>
          <p class="timeline-description">
            目前就读于北京邮电大学，一边学习编程、做项目，
            一边参加秋招，希望找到进入软件开发行业的机会。
          </p>
        </div>
      </div>
    </div>

    <!-- 经历二：请填写真实工作时间 -->
    <div class="timeline-item">
      <div class="timeline-date">起止时间待填写</div>

      <div class="timeline-card">
        <span class="timeline-icon" aria-hidden="true">✈️</span>

        <div class="timeline-content">
          <h2 class="timeline-title">民航管制员</h2>
          <div class="timeline-role">转行之前</div>
          <p class="timeline-description">
            曾经从事民航管制工作。
            这是我职业经历的一部分，也是走向下一段旅程的起点。
          </p>
        </div>
      </div>
    </div>

  </div>

</div>
