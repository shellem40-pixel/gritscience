---
layout: single
title: "시간표 및 커리큘럼"
permalink: /services/
header:
  overlay_color: "#333"
  overlay_filter: "0.5"
  overlay_image: /assets/images/about_title.png
---

<style>
  /* 상단 메인 배너 텍스트 중앙 정렬 */
  .page__hero--overlay .wrapper { text-align: center; }

  /* 각 과목별 묶음을 나누고 아래쪽에 연한 회색 구분선 추가 */
  .curriculum-section {
    margin-bottom: 3em;
    padding-bottom: 2em;
    border-bottom: 1px solid #e0e0e0;
  }
  .curriculum-section:last-child {
    border-bottom: none; /* 마지막 단락은 선을 없앰 */
  }

  /* 시안과 똑같은 푸른색의 얇고 세련된 대제목 스타일 */
  .section-title {
    color: #2471a3; 
    text-align: center;
    font-size: 2.2em;
    font-weight: 300;
    margin-bottom: 1.5em;
    letter-spacing: -0.5px;
  }

  /* 중등부: 글씨는 왼쪽, 버튼은 오른쪽에 오도록 Flexbox 적용 */
  .flex-row {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1em;
  }
  .flex-row p {
    margin: 0;
    font-weight: bold;
    color: #333;
    font-size: 1.05em;
  }
  .flex-row span {
    font-weight: normal;
    color: #555;
    margin-left: 10px;
  }

  /* 원장님 시안에 맞춘 세련된 푸른색 버튼 */
  .btn-custom {
    background-color: #2471a3;
    color: #ffffff !important;
    padding: 10px 24px;
    border-radius: 4px;
    text-decoration: none;
    font-weight: bold;
    font-size: 0.9em;
    text-align: center;
    transition: background-color 0.2s;
    min-width: 150px;
  }
  .btn-custom:hover {
    background-color: #1a5276; /* 마우스 올렸을 때 짙어지는 효과 */
  }

  /* 고등부: 가로로 꽉 차는 블록형 버튼 */
  .btn-block {
    display: block;
    width: 100%;
    margin-top: 1.5em;
    padding: 12px 0;
    font-size: 1em;
  }

  /* 고등부 시간표 및 개요 텍스트 줄간격 */
  .info-text {
    line-height: 2;
    font-size: 1.05em;
    color: #333;
  }
  .info-text strong {
    color: #000;
  }
</style>

<!-- 1. 중등 과학 내신대비 -->
<div class="curriculum-section">
  <h2 class="section-title">중등 과학 내신대비</h2>
  
  <div class="flex-row">
    <p>중등 3학년 : <span>일요반 &nbsp; 토요반 &nbsp; 화요반 &nbsp; 수요반</span></p>
    <a href="#" class="btn-custom">중등3 커리큘럼</a>
  </div>
  
  <div class="flex-row">
    <p>중등 2학년 : <span>일요반 &nbsp; 토요반 &nbsp; 화요반 &nbsp; 수요반</span></p>
    <a href="#" class="btn-custom">중등2 커리큘럼</a>
  </div>
  
  <div class="flex-row">
    <p>중등 1학년 : <span>일요반 &nbsp; 토요반 &nbsp; 화요반 &nbsp; 수요반</span></p>
    <a href="#" class="btn-custom">중등1 커리큘럼</a>
  </div>
  
  <div class="flex-row" style="margin-top: 2em; justify-content: flex-start;">
    <p>개인 수준별 첨삭 수업 : <span style="margin-left: 20px;">▪ 화요일 &nbsp;&nbsp;&nbsp;&nbsp; ▪ 수요일</span></p>
  </div>
</div>

<!-- 2. 고1 통합과학 내신대비 -->
<div class="curriculum-section">
  <h2 class="section-title">고1 통합과학 내신대비</h2>
  
  <div class="info-text">
    <strong>시간 :</strong> 
    <strong>토요반</strong> 오후 2:30-5:00 &nbsp;&nbsp;&nbsp; 
    <strong>토요반</strong> 오후 7:30-10:00 &nbsp;&nbsp;&nbsp; 
    <strong>일요반</strong> 오후 5:00-7:30<br>
    
    <strong>수업 개요 :</strong> ▪ 고1 통합과학 내신 1등급반
  </div>
  
  <a href="#" class="btn-custom btn-block">고1 통합과학 커리큘럼</a>
</div>

<!-- 3. 고2 물리학 내신대비 -->
<div class="curriculum-section">
  <h2 class="section-title">고2 물리학 내신대비</h2>
  
  <div class="info-text">
    <strong>시간 :</strong> 
    <strong>토요반</strong> 오후 2:30-5:00 &nbsp;&nbsp;&nbsp; 
    <strong>토요반</strong> 오후 7:30-10:00 &nbsp;&nbsp;&nbsp; 
    <strong>일요반</strong> 오후 5:00-7:30<br>
    
    <strong>수업 개요 :</strong> ▪ 고2 물리학 내신 1등급반
  </div>
  
  <a href="#" class="btn-custom btn-block">고2 물리학 커리큘럼</a>
</div>