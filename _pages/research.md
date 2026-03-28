<style>
  /* 1. 미디어 컨테이너 */
  .media-container {
    display: flex;
    flex-wrap: nowrap;
    gap: 15px;
    width: 100%;
    justify-content: center; 
    align-items: center; /* 영상들 높이가 같으므로 중앙 정렬 */
    margin: 25px 0;
  }

  /* 2. 확대 링크: 영상 크기에 딱 달라붙게 설정 */
  .enlarge-link {
    display: inline-block; /* 핵심: 자식(영상) 너비만큼만 크기를 가짐 */
    flex: 0 0 auto;        /* 억지로 늘어나지 않음 */
    cursor: zoom-in;
    text-decoration: none;
    line-height: 0;        /* 하단 미세 공백 제거 */
    
    transition: box-shadow 0.2s ease, border-color 0.2s ease;
    border: 2px solid transparent;
    border-radius: 4px;
  }

  /* 3. 개별 미디어 아이템: 높이만 고정, 너비는 비율대로 */
  .media-item {
    height: 180px;         /* 박사님이 원하시는 고정 높이 */
    width: auto;           /* 원래 비율에 따른 자동 너비 */
    max-width: 100%;
    display: block;
    background: transparent !important;
  }

  /* 마우스를 올렸을 때: 연한 회색 테두리와 은은한 음영 */
  .enlarge-link:hover {
    border-color: #d3d3d3; /* 연한 회색 */
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  }

  /* 4. 모바일 대응: 2열 격자 */
  @media (max-width: 768px) {
    .media-container {
      flex-wrap: wrap;
      gap: 10px;
    }
    .enlarge-link {
      flex: 1 1 45%;       /* 모바일은 2개씩 꽉 채움 */
    }
    .media-item {
      height: auto;        /* 모바일은 너비에 맞춰 높이 조절 */
      width: 100%;
    }
  }
</style>

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
