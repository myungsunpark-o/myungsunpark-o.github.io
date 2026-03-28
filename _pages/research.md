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
    border-color: #d3d3d3; /* 연한
