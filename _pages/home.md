---
layout: about
title: "." #home
permalink: /
nav: false
nav_order: 0
subtitle:  #Integração Geotecnológica para Variáveis Dendrométricas, Qualitativas e Tecnológicas da Madeira

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
<style>
.video-background {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  z-index: -1;
  overflow: hidden;
}

.video-background video {
  width: 100%;
  height: 100%;
  object-fit: cover; /* 保证视频全屏填充 */
}

.video-overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  z-index: -1;
  /* 已移除蒙皮遮罩的 backdrop-filter 模糊效果 */
}

/* 已移除深浅模式下的遮罩颜色 */
[data-theme='dark'] .video-overlay {
  background: transparent;
}

[data-theme='light'] .video-overlay {
  background: transparent;
}

.hero-container {
  position: relative;
  z-index: 1;
  height: calc(100vh - 220px);
  display: flex;
  align-items: center;
  justify-content: center;
  padding-top: 1rem;
  padding-left: 2rem;
  padding-right: 2rem;
  padding-bottom: 2rem;
  overflow: hidden;
}

.hero-content {
  max-width: 1200px;
  width: 100%;
  height: 100%;
  display: grid;
  grid-template-columns: 1fr 350px;
  gap: 3rem;
  align-items: center;
  animation: fadeInUp 1.2s ease-out;
}

@media (max-width: 768px) {
  .hero-content {
    grid-template-columns: 1fr;
    gap: 1.5rem;
    text-align: center;
    height: auto;
  }
  .hero-container {
    height: auto;
    min-height: calc(100vh - 120px);
  }
}

.hero-profile {
  display: flex;
  flex-direction: column;
  align-items: center;
  animation: slideInRight 1s ease-out 0.6s both;
  height: fit-content;
}

/* 保持卡片容器，但移除磨砂感 */
.profile-card {
  background: transparent; 
  border-radius: 20px;
  padding: 1.5rem;
  border: none;
  text-align: center;
  max-height: 400px;
}

.profile-image {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  margin: 0 auto 1rem;
  border: 4px solid rgba(255, 255, 255, 0.3);
  box-shadow: 0 8px 25px rgba(0,0,0,0.2);
  transition: all 0.3s ease;
}

/* 保持动画定义不变 */
@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(30px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes slideInLeft {
  from { opacity: 0; transform: translateX(-50px); }
  to { opacity: 1; transform: translateX(0); }
}

@keyframes slideInRight {
  from { opacity: 0; transform: translateX(50px); }
  to { opacity: 1; transform: translateX(0); }
}

/* 保持粒子效果 */
.particles {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 0;
  pointer-events: none;
}

.particle {
  position: absolute;
  width: 4px;
  height: 4px;
  background: rgba(255, 255, 255, 0.6);
  border-radius: 50%;
  animation: float 6s infinite ease-in-out;
}

@keyframes float {
  0%, 100% { transform: translateY(100vh) rotate(0deg); opacity: 0; }
  10%, 90% { opacity: 1; }
  50% { transform: translateY(-10vh) rotate(180deg); }
}
</style>

<div class="video-background">
  <video autoplay loop muted playsinline>
    <source src="assets/video/video_2.mp4" type="video/mp4">
  </video>
</div>
<div class="video-overlay"></div>

<div class="particles">
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
  <div class="particle"></div>
</div>

<div class="hero-container">
  <div class="hero-content">
    <div class="hero-text">
      </div>
    
    <div class="hero-profile">
      <div class="profile-card">
        </div>
    </div>
  </div>
</div>
