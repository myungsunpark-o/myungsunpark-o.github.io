---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
My research focuses on implementing **human-like Physical AI in dexterous robot hands** by integrating **human hand motion** and **robot tactile sensing**. My ultimate goal is to enable robots to perform complex tasks in uncertain, dynamic, and contact-rich environments through precise motion, sophisticated sensing, and high-level intelligence.

<style>
  /* 1. 미디어 컨테이너: 웹에서 한 줄 고정 */
  .media-container {
    display: flex;
    flex-wrap: nowrap;     /* 웹에서는 줄바꿈 금지 */
    gap: 15px;
    width: 100%;
    justify-content: center; 
    align-items: center;   /* 영상들 높이가 같으므로 수직 중앙 정렬 */
    margin: 25px 0;
    background: transparent !important;
  }

  /* 2. 확대 링크: 영상 크기에 딱 달라붙게 설정 (Shrink-wrap) */
  .enlarge-link {
    display: inline-block; /* 핵심: 자식(영상) 너비만큼만 크기를 가짐 */
    flex: 0 0 auto;        /* 억지로 늘어나지 않음 */
    cursor: zoom-in;
    text-decoration: none;
    line-height: 0;        /* 영상 하단 미세 공백 제거 */
    
    /* 부드러운 전환 효과 */
    transition: box-shadow 0.2s ease, border-color 0.2s ease;
    
    /* 기본 상태: 테두리를 투명하게 설정 */
    border: 2px solid transparent;
    border-radius: 4px;
    overflow: hidden;      /* 영상이 테두리를 넘지 않게 */
  }

  /* 3. 개별 미디어 아이템: 높이 고정, 너비는 비율대로 자동 */
  .media-item {
    height: 180px;         /* 웹 기준 고정 높이 */
    width: auto;           /* 비율에 따른 자동 너비 인식 */
    max-width: 100%;
    display: block;
    background: transparent !important;
    border: none !important;
  }

  /* 마우스를 올렸을 때: 연한 회색 테두리와 은은한 음영 */
  .enlarge-link:hover {
    border-color: #d3d3d3; /* 연한 회색 테두리 */
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.12); /* 은은한 음영 */
  }

  /* 4. 모바일 대응: 768px 이하에서 2줄 격자 정렬 */
  @media (max-width: 768px) {
    .media-container {
      flex-wrap: wrap;     /* 모바일에서는 줄바꿈 허용 */
      gap: 10px;
    }
    .enlarge-link {
      flex: 1 1 45%;       /* 모바일에서 한 줄에 2개씩 배치 */
    }
    .media-item {
      height: auto;        /* 모바일은 너비에 맞춰 높이 자동 조절 */
      width: 100%;         /* 할당된 45% 너비를 꽉 채움 */
    }
    /* 모바일 터치 시 이펙트 제거 */
    .enlarge-link:hover {
      box-shadow: none;
      border-color: transparent;
    }
  }
</style>

<hr style="margin: 30px 0;" />

# Dexterous Motion Capture using Wearable Glove

<div style="display: block; margin-bottom: 15px;">
  <span style="display: inline;">
    Humans perform complex manipulation tasks through the coordination of multiple fingers. Implementing this level of dexterous robotic manipulation via <b>Physical AI requires high-quality motion datasets</b>, which are often challenging to acquire. I address this issue by developing wearable devices that accurately measure all degrees of freedom in human fingers. This approach enables intuitive teleoperation of dexterous robotic hands, facilitating complex tasks that are otherwise difficult to demonstrate.
  </span>

  <details style="display: inline; cursor: pointer; margin-left: 5px;">
    <summary style="display: inline; font-weight: bold; color: #268bd2; list-style: none; font-size: 1em;">
      [View details]
    </summary>
    <div style="display: block; margin: 15px 0; padding: 15px; background: rgba(128, 128, 128, 0.05); border-left: 4px solid #268bd2; border-radius: 4px; cursor: default; color: inherit !important;">
      <div style="font-size: 1.0em; font-weight: bold; color: inherit; margin-bottom: 5px;">Hand Motion Capture and Post-processing with Enhanced Accuracy</div>
      <p style="margin-top: 0; margin-bottom: 15px;"><i>Robust rotation-based visual motion capture</i> outperformed position-based counterpart in accuracy. <i>Geometry decoupling</i> solved the retargeting problem by separating user-independent and dependent variables. </p>
      <div style="font-size: 1.0em; font-weight: bold; color: inherit; margin-bottom: 5px;">Wearable Motion Capture Glove</div>
      <p style="margin-top: 0; margin-bottom: 15px;"><i>Calibration-free sensing</i> achieved state-of-the-art accuracy using highly stretchable strain sensors that conform and auto-calibrate to diverse hand shapes. <i>Versatile application</i> demonstrated high performance in various virtual reality and human-robot interaction scenarios. </p>
      <div style="font-size: 1.0em; font-weight: bold; color: inherit; margin-bottom: 5px;">Intuitive Teleoperation of Multi-finger Robotic Hands</div>
      <p style="margin-top: 0; margin-bottom: 0;"><i>Seamless human-robot interface</i> enables intuitive control of multi-DoF robot hands. <i>Dexterous manipulation</i> implemented precise fingertip control and multi-finger coordination for complex tasks. </p>
    </div>
  </details>
</div>

<div class="media-container">
  <a href="/images/research/Research1-1.mp4" target="_blank" class="enlarge-link">
    <video autoplay loop muted playsinline class="media-item" style="pointer-events: none;"><source src="/images/research/Research1-1.mp4" type="video/mp4"></video>
  </a>
  <a href="/images/research/Research1-2.mp4" target="_blank" class="enlarge-link">
    <video autoplay loop muted playsinline class="media-item" style="pointer-events: none;"><source src="/images/research/Research1-2.mp4" type="video/mp4"></video>
  </a>
  <a href="/images/research/Research1-3.mp4" target="_blank" class="enlarge-link">
    <video autoplay loop muted playsinline class="media-item" style="pointer-events: none;"><source src="/images/research/Research1-3.mp4" type="video/mp4"></video>
  </a>
  <a href="/images/research/Research1-4.mp4" target="_blank" class="enlarge-link">
    <video autoplay loop muted playsinline class="media-item" style="pointer-events: none;"><source src="/images/research/Research1-4.mp4" type="video/mp4"></video>
  </a>
</div>

<hr style="margin: 30px 0;" />

# Tactile Sensing and Haptic Feedback for Sophisticated Interaction

<div style="display: block; margin-bottom: 15px;">
  <span style="display: inline;">
    Humans perceive and interact with uncertain objects and environments using not only complex finger movements but also sophisticated tactile sensations. My research focuses on developing haptic feedback devices and tactile/environmental sensing technologies to implement this level of refined interaction in robots. This approach enables the development of multimodal <b>tactile sensors for enhanced manipulation and adaptive robots</b> in diverse environments.
  </span>

  <details style="display: inline; cursor: pointer; margin-left: 5px;">
    <summary style="display: inline; font-weight: bold; color: #268bd2; list-style: none; font-size: 1em;">
      [View details]
    </summary>
    <div style="display: block; margin: 15px 0; padding: 15px; background: rgba(128, 128, 128, 0.05); border-left: 4px solid #268bd2; border-radius: 4px; cursor: default; color: inherit !important;">
      <div style="font-size: 1.0em; font-weight: bold; color: inherit; margin-bottom: 5px;">Haptic Feedback Devices for Teleoperation</div>
      <p style="margin-top: 0; margin-bottom: 15px;"><i>IPMC actuator-based haptic feedback</i> achieved enhanced remote grasping using a miniature gripper.</p>
      <div style="font-size: 1.0em; font-weight: bold; color: inherit; margin-bottom: 5px;">Benchmarking Tactile Sensors for Imitation Learning</div>
      <p style="margin-top: 0; margin-bottom: 15px;"><i>Visuo-tactile policy evaluation</i> identified the impact of six different tactile modalities on imitation learning for various manipulation tasks. </p>
      <div style="font-size: 1.0em; font-weight: bold; color: inherit; margin-bottom: 0;">Development of Multimodal Sensors and Underwater Applications</div>
      <p style="margin-top: 0; margin-bottom: 0;"><i>Multi-modal flow sensors</i> enabled simultaneous estimation of complex flow structures and robotic movement via shear and high-frequency components in fluid-structure interaction. </p>
    </div>
  </details>
</div>

<div class="media-container">
  <a href="/images/research/Research2-1.mp4" target="_blank" class="enlarge-link">
    <video autoplay loop muted playsinline class="media-item" style="pointer-events: none;"><source src="/images/research/Research2-1.mp4" type="video/mp4"></video>
  </a>
  <a href="/images/research/Research2-2.mp4" target="_blank" class="enlarge-link">
    <video autoplay loop muted playsinline class="media-item" style="pointer-events: none;"><source src="/images/research/Research2-2.mp4" type="video/mp4"></video>
  </a>
  <a href="/images/research/Research2-3.mp4" target="_blank" class="enlarge-link">
    <video autoplay loop muted playsinline class="media-item" style="pointer-events: none;"><source src="/images/research/Research2-3.mp4" type="video/mp4"></video>
  </a>
</div>

<hr style="margin: 30px 0;" />

# Human-Inspired Physical AI for Dexterous Manipulation

<div style="display: block; margin-bottom: 15px;">
  <span style="display: inline;">
    Human intelligence, characterized by semantic reasoning and purposeful action based on accurate motion and sophisticated sensing, can be implemented in robots. My research focuses on <b>modeling human manipulation strategies and developing corresponding robotic sensing and control systems</b>. Beyond mere demonstration or data dependency, I aim to realize efficient Physical AI for robots that mimics human-level decision-making and dexterity.
  </span>

  <details style="display: inline; cursor: pointer; margin-left: 5px;">
    <summary style="display: inline; font-weight: bold; color: #268bd2; list-style: none; font-size: 1em;">
      [View details]
    </summary>
    <div style="display: block; margin: 15px 0; padding: 15px; background: rgba(128, 128, 128, 0.05); border-left: 4px solid #268bd2; border-radius: 4px; cursor: default; color: inherit !important;">
    <div style="font-size: 1.0em; font-weight: bold; color: inherit; margin-bottom: 5px;">Hybrid System Modeling for Vision-Free Manipulation</div>
    <p style="margin-top: 0; margin-bottom: 15px;"><i>Defining hybrid variables</i> modeled human semantic decision-making processes in grasping tasks. <i>Proprioceptive sensing</i> enabled complex manipulation without visual feedback. </p>
    <div style="font-size: 1.0em; font-weight: bold; color: inherit; margin-bottom: 0;">State Estimation and Autonomous Gripper Systems</div>
    <p style="margin-top: 0; margin-bottom: 0;"><i>Proprioceptive sensor model</i> guided the control system to robustly predict discrete physical events and contacts along with continuous poses of the robot and object. </p>
    </div>
  </details>
</div>

<div class="media-container">
  <a href="/images/research/Research3-1.mp4" target="_blank" class="enlarge-link">
    <video autoplay loop muted playsinline class="media-item" style="pointer-events: none;"><source src="/images/research/Research3-1.mp4" type="video/mp4"></video>
  </a>
  <a href="/images/research/Research3-2.mp4" target="_blank" class="enlarge-link">
    <video autoplay loop muted playsinline class="media-item" style="pointer-events: none;"><source src="/images/research/Research3-2.mp4" type="video/mp4"></video>
  </a>
  <a href="/images/research/Research3-3.mp4" target="_blank" class="enlarge-link">
    <video autoplay loop muted playsinline class="media-item" style="pointer-events: none;"><source src="/images/research/Research3-3.mp4" type="video/mp4"></video>
  </a>
</div>

<hr style="margin: 30px 0;" />
