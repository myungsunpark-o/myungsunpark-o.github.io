---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

제 연구 목표는 정확한 동작, 정교한 감각 및 고차원 지능을 활용하여 불확실하고, 동적이고, 접촉이 복잡한 환경에서도 다양한 작업을 수행하는 **사람의 조작 능력을 로봇 핸드에 구현**하는 것입니다. 보다 구체적으로는, **사람 손의 동작 분석**과 **로봇의 촉각 센싱**을 활용한 **사람을 닮은 물리적 인공지능**을 구현하고자 합니다.

<hr style="margin: 30px 0;" />

# 정확한 손 동작 측정과 로봇 핸드의 제어

<div style="display: block; margin-bottom: 15px;">
  <span style="display: inline;">
    사람은 여러 손가락의 협동을 통해 복잡한 매니퓰레이션 작업을 수행합니다. 이와 같은 수준의 다자유도 로봇 매니퓰레이션을 physical AI로 구현하기 위해서는 양질의 데이터 확보가 필요하지만, 이를 확보하는 데 어려움이 있습니다. 저는 이 문제를 사람 손가락의 모든 자유도를 정확하게 측정하는 웨어러블 디바이스로 해결하고자 합니다. 이 접근은 다자유도 로봇 핸드의 쉽게 시연하기 어려운 복잡한 작업 수행을 손쉽게 가능하게 합니다. 
  </span>

  <details style="display: inline; cursor: pointer; margin-left: 5px;">
    <summary style="display: inline; font-weight: bold; color: #666; list-style: none; font-size: 0.9em;">
      [View details]
    </summary>
    
    <div style="display: block; margin: 15px 0; padding: 15px; background: #f9f9f9; border-left: 4px solid #ccc; border-radius: 4px; box-shadow: inset 0 0 5px rgba(0,0,0,0.02); cursor: default;">
      <div style="font-size: 1.0em; font-weight: bold; color: #333; margin-bottom: 5px;">정확한 동작 측정을 위한 모션 캡쳐 및 후처리</div>
      <p style="margin-top: 0; margin-bottom: 15px;">위치 기반 마커 추정에 비해 오차에 강건한 회전 기반 모션 캡쳐 방식 고안. 캡쳐 데이터를 개인별 서로 다른 손의 형상에 대해 user-independent, user-dependent variables로 분리하여 ___ 문제를 해결. </p>

      <div style="font-size: 1.0em; font-weight: bold; color: #333; margin-bottom: 5px;">손 모양과 동작을 동시에 측정하는 데이터 장갑</div>
      <p style="margin-top: 0; margin-bottom: 15px;">착용 순간 손 모양에 알맞게 늘어나는 Highly stretchable strain sensors를 통한 캘리브레이션-프리, state-of-the-art accuracy로 손의 동작을 실시간 추정. 다양한 가상 현실 어플리케이션에 활용. </p>

      <div style="font-size: 1.0em; font-weight: bold; color: #333; margin-bottom: 5px;">로봇 핸드의 직관적인 원격 조작</div>
      <p style="margin-top: 0; margin-bottom: 0;">여러 손가락의 협동과 손 끝의 정밀한 제어가 필요한 로봇 핸드의 dexterous manipulation 구현.</p>
    </div>
  </details>
</div>

<div style="display: flex; gap: 10px; align-items: flex-start; margin-top: 15px; flex-wrap: nowrap;">
  <img src="/images/research/1_1_glove.png" style="height: 120px; width: auto; object-fit: contain; border-radius: 8px; border: 1px solid #eee;">
  <img src="/images/research/1_2_handtracking.png" style="height: 120px; width: auto; object-fit: contain; border-radius: 8px; border: 1px solid #eee;">
  <img src="/images/research/1_3_shadow.png" style="height: 120px; width: auto; object-fit: contain; border-radius: 8px; border: 1px solid #eee;">
  <img src="/images/research/1_4_robothand.png" style="height: 120px; width: auto; object-fit: contain; border-radius: 8px; border: 1px solid #eee;">
</div>

<hr style="margin: 30px 0;" />

# 정교한 물리적 상호작용을 위한 멀티 모달 촉각 센서와 햅틱 피드백

<div style="display: block; margin-bottom: 15px;">
  <span style="display: inline;">
    우리는 손가락의 복잡한 동작뿐 아니라 피부의 정교한 촉각 감각 활용해 불확실한 물체 및 환경을 인식하고 상호작용합니다. 저는 사람 수준의 정교한 감각과 상호작용을 로봇에 구현하기 위한 햅틱 피드백 디바이스와 촉각 및 환경 센싱에 대한 연구를 수행합니다. 이는 향상된 조작을 위한 멀티 모달 촉각 센서의 개발과 이를 활용한 환경에 적응적인 로봇 기술을 가능하게 합니다.    
  </span>

  <details style="display: inline; cursor: pointer; margin-left: 5px;">
    <summary style="display: inline; font-weight: bold; color: #666; list-style: none; font-size: 0.9em;">
      [View details]
    </summary>
    
    <div style="display: block; margin: 15px 0; padding: 15px; background: #f9f9f9; border-left: 4px solid #ccc; border-radius: 4px; box-shadow: inset 0 0 5px rgba(0,0,0,0.02); cursor: default;">
      <div style="font-size: 1.0em; font-weight: bold; color: #333; margin-bottom: 5px;">원격 조작을 위한 햅틱 피드백 디바이스</div>
      <p style="margin-top: 0; margin-bottom: 15px;">모션 캡쳐 글러브 및 IPMC 액추에이터 기반 햅틱 피드백 디바이스를 활용한 저전압, miniature 그리퍼의 원격 물체 파지.</p>

      <div style="font-size: 1.0em; font-weight: bold; color: #333; margin-bottom: 5px;">모방학습을 위한 촉각 모달리티 벤치마킹</div>
      <p style="margin-top: 0; margin-bottom: 15px;">Visuo-tactile 모방학습 정책 기반 다양한 조작 작업을 수행하기 위한 다양한 촉각 모달리티를 벤치마킹.</p>

      <div style="font-size: 1.0em; font-weight: bold; color: #333; margin-bottom: 5px;">멀티모달 센서의 개발과 수중 로봇 어플리케이션</div>
      <p style="margin-top: 0; margin-bottom: 0;">전단력과 고주파 진동을 동시에 측정하는 멀티모달 유속 센서의 개발. 수중 로봇 표면의 유체-구조 상호작용의 측정을 통한 운동 및 환경의 정확한 측정.</p>
    </div>
  </details>
</div>

<div style="display: flex; gap: 10px; align-items: flex-start; margin-top: 15px; flex-wrap: nowrap;">
  <img src="/images/research/2_1_hapticteleop.png" style="height: 130px; width: auto; object-fit: contain; border-radius: 8px; border: 1px solid #eee;">
  <img src="/images/research/2_2_tactilebenchmark.png" style="height: 130px; width: auto; object-fit: contain; border-radius: 8px; border: 1px solid #eee;">
  <img src="/images/research/2_3_flowsensor.png" style="height: 130px; width: auto; object-fit: contain; border-radius: 8px; border: 1px solid #eee;">
  <img src="/images/research/2_5_robotestimation.png" style="height: 130px; width: auto; object-fit: contain; border-radius: 8px; border: 1px solid #eee;">
</div>

<hr style="margin: 30px 0;" />

# 사람을 닮은 로봇 핸드 physical AI

<div style="display: block; margin-bottom: 15px;">
  <span style="display: inline;">
    정확한 동작과 정교한 감각을 기반으로 의미적인 판단과 행동을 하는 사람의 지능을 로봇에 구현할 수 있습니다. 저는 복잡한 사람의 조작 전략을 모델링하고, 이를 모사한 로봇의 센싱 및 제어 시스템에 관해 연구합니다. 이를 통해 단순히 시연이나 데이터에 의존하는 것을 넘어 사람과 같이 효율적인 로봇의 physical AI를 구현하는 것을 목표로 합니다.
  </span>

  <details style="display: inline; cursor: pointer; margin-left: 5px;">
    <summary style="display: inline; font-weight: bold; color: #666; list-style: none; font-size: 0.9em;">
      [View details]
    </summary>
    
    <div style="display: block; margin: 15px 0; padding: 15px; background: #f9f9f9; border-left: 4px solid #ccc; border-radius: 4px; box-shadow: inset 0 0 5px rgba(0,0,0,0.02); cursor: default;">
      <div style="font-size: 1.0em; font-weight: bold; color: #333; margin-bottom: 5px;">비전 프리 조작을 위한 하이브리드 시스템 모델</div>
      <p style="margin-top: 0; margin-bottom: 15px;">정밀한 동작 측정을 위한 알고리즘과 데이터 처리를 연구합니다.</p>

      <div style="font-size: 1.0em; font-weight: bold; color: #333; margin-bottom: 5px;">로봇의 상태 추정과 자동 파지 작업</div>
      <p style="margin-top: 0; margin-bottom: 15px;">손 모양과 동작을 동시에 측정하는 웨어러블 장치 연구입니다.</p>
    </div>
  </details>
</div>

<div style="display: flex; gap: 10px; align-items: flex-start; margin-top: 15px; flex-wrap: nowrap;">
  <img src="/images/research/3_1_hybridmodel.png" style="height: 150px; width: auto; object-fit: contain; border-radius: 8px; border: 1px solid #eee;">
  <img src="/images/research/3_2_kinematics.png" style="height: 150px; width: auto; object-fit: contain; border-radius: 8px; border: 1px solid #eee;">
  <img src="/images/research/3_3_control.png" style="height: 150px; width: auto; object-fit: contain; border-radius: 8px; border: 1px solid #eee;">
</div>

<hr style="margin: 30px 0;" />
