---
permalink: /
title: "Hello! I am Myungsun Park."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am currently a postdoctoral scholar at University of California San Diego, working with Prof. [Michael T. Tolley](https://bioinspired.ucsd.edu/home) and Prof. [Geno Pawlak](https://efdlab.ucsd.edu/home). I earned my PhD from Seoul National Universiy with Prof. [Yong-Lae Park](https://softrobotics.snu.ac.kr/) (Dissertation: *Enhanced Human-Robot-Environment Interactions Enabled by Multi-Stiffness Soft Sensors and Interactive Control*).

2x2 격자(Grid) 형태로 배치하면서 전체 너비를 맞추는 것은 연구 데이터를 보여줄 때 가장 안정감 있는 구도입니다.

이 경우 flex-wrap: wrap;을 사용하고, 각 영상의 너비를 **calc(50% - 간격)**으로 설정하면 두 줄에 걸쳐 깔끔하게 2개씩 들어갑니다.

🛠️ 2x2 격자 배치 코드 (전체 너비 일치)
HTML
<div style="display: flex; flex-wrap: wrap; gap: 10px; width: 100%; justify-content: center; margin: 30px 0;">
  
  <div style="flex: 0 0 calc(50% - 5px);">
    <video autoplay loop muted playsinline style="width: 100%; height: 180px; object-fit: cover; display: block;">
      <source src="/images/research/Main1.mp4" type="video/mp4">
    </video>
  </div>

  <div style="flex: 0 0 calc(50% - 5px);">
    <video autoplay loop muted playsinline style="width: 100%; height: 180px; object-fit: cover; display: block;">
      <source src="/images/research/Main2.mp4" type="video/mp4">
    </video>
  </div>

  <div style="flex: 0 0 calc(50% - 5px);">
    <video autoplay loop muted playsinline style="width: 100%; height: 180px; object-fit: cover; display: block;">
      <source src="/images/research/Main3.mp4" type="video/mp4">
    </video>
  </div>

  <div style="flex: 0 0 calc(50% - 5px);">
    <video autoplay loop muted playsinline style="width: 100%; height: 180px; object-fit: cover; display: block;">
      <source src="/images/research/Main4.mp4" type="video/mp4">
    </video>
  </div>

</div>

My research focuses on enhancing adaptability and dexterity of robots during physical interactions within complex environments. I draw inspiration from **human motion, sensing, and intelligence**, embodying these principles into real-world robotic systems. My recent work addresses irregular, unsteady, and contact-rich environments through **exteroceptive sensing** (e.g., tactile and flow sensing) and **human–robot interfaces** (e.g., motion-capture gloves and haptic feedback devices) that enable **physical AI for robot manipulation**.

---

When I am not in the lab, I enjoy swimming (which provides great inspiration for my underwater robotics research!), painting, and binge-watching K-dramas.

