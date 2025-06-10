# 🌸 PiBoo: 성분부터 궁합까지, 똑똑한 화장품 도우미

# 👥 팀 소개
> SK네트웍스 Family AI 캠프 11기 4차 프로젝트 <br/>
> 팀 명: 미피 (美Pi, MePi)🐰 <br/>
> 기간: 2025.05.16 - 2025.06.11 <br/>

## 👤팀원 소개

<table align="center">
  <thead>
    <td align="center">
      <img src="https://github.com/kimseoungji0801.png" width=200 alt="seongji"/><br />
      <a href='https://github.com/kimseoungji0801'>김성지</a><br />
    </td>
    <td align="center">
      <img src="https://github.com/yugyeongh.png" width=200 alt="yugyeong"/><br />
      <a href='https://github.com/yugyeongh'>현유경</a><br />
    </td>
    <td align="center">
      <img src="https://github.com/Ohjunghh.png" width=200 alt="junghyun"/><br />
      <a href='https://github.com/Ohjunghh'>오정현</a><br />
    </td>
    <td align="center">
      <img src="https://github.com/misong-hub.png" width="200" alt="misong"/><br />
      <a href='https://github.com/misong-hub'>백미송</a><br />
    </td>
  </thead>
</table>

<br/><br/>

# 🩷 프로젝트 개요

> 사용자의 피부 타입, 피부 고민, 보유 중인 화장품 등의 정보를 바탕으로, 궁합이 잘 맞는 기초 화장품이나 스킨케어 제품을 추천 서비스를 개발해 단순한 제품 매칭을 넘어, 화장품 성분 분석과 실제 사용자 리뷰 데이터를 기반으로 한 신뢰도 높은 정보를 제공하는 챗봇 

<br/>

## ☝🏻 프로젝트 필요성
최근 화장품을 선택할 때 제품의 성분을 중요시하는 소비자가 급격히 증가했습니다. 하지만 대다수의 소비자들은 화장품 성분의 구체적인 효능과 서로 다른 제품 간의 궁합에 대해서 명확하게 이해하지 못하고 있습니다. 성분에 대한 잘못된 정보나 부적절한 제품 조합은 피부 트러블 등의 문제를 유발할 수 있습니다. 이에 정확한 성분 정보 제공과 올바른 화장품 사용 가이드를 제공할 수 있는 도구의 필요성이 대두되었습니다.
<br/>

![image](https://github.com/user-attachments/assets/c9ef7647-1f9b-4564-a872-bca302756757)
![image](https://github.com/user-attachments/assets/2898b6ea-94df-4591-a18b-a7ba737a4fa5)


<br/>

## ⭐ 프로젝트 목표
1. 화장품 성분 정보를 사용자에게 명확하고 쉽게 제공하여 올바른 이해를 도움
2. 사용자가 보유한 화장품과의 궁합 분석을 통해 좋은 조합을 추천하고, 나쁜 조합에 대해서는 경고를 제공하여 피부 문제 예방에 도움
3. 맞춤형 성분 분석과 제품 추천을 통해 사용자가 더욱 건강하고 효율적인 피부 관리가 가능하도록 지원

<br/><br/>

# 📌 WBS

<table border="1">
  <thead>
    <tr>
      <th>단계</th>
      <th>주요 작업</th>
      <th>기간</th>
      <th>담당자</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>스킨케어 질문 데이터 수집</td>
      <td>25.05.24-25.05.25</td>
      <td>김성지, 백미송</td>
    </tr>
    <tr>
      <td>2</td>
      <td>데이터 전처리 및 정제</td>
      <td>25.05.26-25.05.27</td>
      <td>김성지</td>
    </tr>
    <tr>
      <td>3</td>
      <td>QLoRA 학습 데이터 생성</td>
      <td>25.05.28</td>
      <td>백미송, 현유경</td>
    </tr>
    <tr>
      <td>4</td>
      <td>백엔드 장고 변환</td>
      <td>25.05.26-25.05.28</td>
      <td>김성지, 오정현</td>
    </tr>
    <tr>
      <td>5</td>
      <td>QLoRA 세팅 및 파인튜닝</td>
      <td>25.05.29-25.06.02</td>
      <td>백미송, 현유경</td>
    </tr>
    <tr>
      <td>6</td>
      <td>HTML/CSS를 활용한 UI 구현</td>
      <td>25.06.07-25.06.09</td>
      <td>김성지, 오정현</td>
    </tr>
<tr>
      <td>8</td>
      <td>AWS 배포</td>
      <td>25.06.10</td>
      <td>김성지,현유경</td>
    </tr>
    <tr>
      <td>10</td>
      <td>통합 테스트 및 튜닝</td>
      <td>25.06.10</td>
      <td>ALL</td>
    </tr>
    <tr>
      <td>11</td>
      <td>발표 자료 / 코드 정리</td>
      <td>25.06.11</td>
      <td>ALL</td>
    </tr>
  </tbody>
</table>

<br/><br/>


# ✅ 기술 스택 & 사용한 모델

## 🔩 기술 스택

<table>
  <tbody>
    <tr>
      <td><strong>Frontend</strong></td>
      <td>
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">
        <img src="https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=CSS3&logoColor=white">
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">
      </td>
    </tr>
    <tr>
      <td><strong>Backend</strong></td>
      <td>
        <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white">
        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><strong>AI/LLM & RAG</strong></td>
      <td>
        <img src="https://img.shields.io/badge/LangChain-000000?style=for-the-badge">
        <img src="https://img.shields.io/badge/ChromaDB-FFCC00?style=for-the-badge">
        <img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black">
        <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white">
        <img src="https://img.shields.io/badge/RAG-4B8BBE?style=for-the-badge">
        <img src="https://img.shields.io/badge/QLoRA-8BC34A?style=for-the-badge">
        <img src="https://img.shields.io/badge/RunPod-EE4C2C?style=for-the-badge">
      </td>
    </tr>
  </tbody>
</table>

<br/><br/>

## 🤖 사용한 모델
<table>
  <thead>
    <tr>
      <th>역할</th>
      <th>모델</th>
      <th>플랫폼</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>문서 임베딩</td>
      <td>all-MiniLM-L6-v2</td>
      <td>
        <img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black">
      </td>
    </tr>
    <tr>
      <td>QA 데이터 생성 (RAG 기반)</td>
      <td>GPT-4o</td>
      <td>
        <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white">
      </td>
    </tr>
    <tr>
      <td>파인튜닝 사전 학습 모델</td>
      <td>llama-3-Korean-Bllossom-8B, 
mistralai/Mistral-7B-Instruct-v0.1</td>
      <td>
        <img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black">
      </td>
    </tr>
  </tbody>
</table>

<br/><br/>

# 🪼 시스템 아키텍처
![Untitled](https://github.com/user-attachments/assets/52b9f510-8926-40d2-b36b-e19023ff675d)

<br/><br/>

# 📄 요구사항 명세서
![image](https://github.com/user-attachments/assets/6472fb8e-f88b-4bc8-ad8b-72a7fab0a9b8)

<br/><br/>
<h2>🖌️ 화면 설계서(Figma)</h2>
<table cellspacing="0" cellpadding="20" style="border-collapse: collapse; width: 100%; text-align: center; margin-bottom: 40px;">
  <tr>
    <td style="width: 50%; background-color: #f2f2; border: 2px solid #ccc;">
      <img src="https://github.com/user-attachments/assets/2e5fc06e-dd30-45cb-898f-3b7e4a32e7de" width="300" ><br>
      <div><strong>메인화면</strong></div>
    </td>
    <td style="width: 50%; background-color: #f2f2f2; border: 2px solid #ccc;">
      <img src="https://github.com/user-attachments/assets/d5696fc1-0ee5-42f3-a173-4c4ce409361d" width="300"><br>
      <div><strong>로그인</strong></div>
    </td>
  </tr>
</table>

<table cellspacing="0" cellpadding="20" style="border-collapse: collapse; width: 100%; text-align: center;">
  <tr>
    <td style="width: 50%; background-color: #f2f2f2; border: 2px solid #ccc;">
      <img src="https://github.com/user-attachments/assets/7306f66c-fd80-4365-9379-4cc9a9faf1be" width="300"><br>
      <div><strong>회원가입</strong></div>
    </td>
    <td style="width: 50%; background-color: #f2f2f2; border: 2px solid #ccc;">
      <img src="https://github.com/user-attachments/assets/55f10dc2-ee47-4550-b752-034fb02a19a4" width="300"><br>
      <div><strong>챗봇</strong></div>
    </td>
  </tr>
</table>

<br/><br/>



# 📜 수집한 데이터 및 전처리 요약
> 1. `skincare_qa.csv`: 화장품 관련 카페의 스킨케어 Q&A칸에서 제목, 본문 2가지의 항목을 크롤링

<br/>


## 스킨케어 질문 크롤링

  <img width="834" alt="cafe_skincare" src="https://github.com/user-attachments/assets/5adcb03c-bce8-4fb8-91e3-14689d893c14" />

<br/>

## ☝🏻 전처리 과정

### 🫒 skincare_qa.csv </br> 
- 원본 데이터  </br> 
![image](https://github.com/user-attachments/assets/ba3df277-8d38-484a-9293-844dc4ae7722)
 </br>

**1. Title , body 전처리**  
![image](https://github.com/user-attachments/assets/725e2a43-dabe-4621-99b8-bd3fe45727d1)
 </br> 

<br/><br/>

# ☁️ 테스트 계획 및 결과 보고서
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th>Test ID</th>
      <th>목적</th>
      <th>입력 예시</th>
      <th>기대 결과</th>
      <th>실제 결과</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>CASE01</td>
      <td>메인페이지에서 회원가입 버튼 클릭시 정상적으로 이동하는지 확인</td>
      <td>회원가입 버튼 클릭</td>
      <td>회원가입 페이지로 이동</td>
      <td><img src="https://github.com/user-attachments/assets/47245cc9-6224-44c6-abb4-f5daab58aeb0"/></td>
    </tr>
    <tr>
      <td>CASE02</td>
      <td>회원가입 시 중복 검사를 통과하고 모든 조건 충족 시 로그인 창으로 이동하는지 확인</td>
      <td>사용 가능한 아이디/닉네임 + 일치하는 비밀번호 입력 후 회원가입</td>
      <td>회원가입 완료 후 로그인 창으로 이동</td>
      <td><img src="https://github.com/user-attachments/assets/49943985-ec84-4d81-bb26-b3d31a18fa6e"/></td>
    </tr>
    <tr>
      <td>CASE03</td>
      <td>로그인 성공 여부에 따라 페이지가 정상적으로 이동하는지 확인</td>
      <td>정상적인 아이디/비밀번호 입력 후 로그인</td>
      <td>로그인 성공 시 챗봇 페이지로 이동</td>
      <td><img src="https://github.com/user-attachments/assets/7896afd1-8502-40e8-a0cd-6adc14651583"></td>
    </tr>
    <tr>
      <td>CASE04</td>
      <td>챗봇이 질문 의도에 따라 RAG 문서를 활용한 적절한 답변을 반환하는지 확인</td>
      <td>예시 질문: "나는 지성피부야 끈적거리지 않는 앰플을 추천 받고 싶어"</td>
      <td>질문 의도에 맞는 답변 + 관련 문서 기반 정보 제공</td>
      <td><img src="https://github.com/user-attachments/assets/d5b24ec7-0890-422b-810b-2fb0d0764593"></td>
    </tr>
    <tr>
      <td>CASE05</td>
      <td>메시지 입력칸 비우기 버튼이 채팅창 화면이 초기화 되는지 확인</td>
      <td>입력칸 비우기 버튼 클릭</td>
      <td>입력란의 텍스트가 아닌, 채팅창 화면이 초기화</td>
      <td><img src="https://github.com/user-attachments/assets/5be6a89c-5ca3-4934-a75a-a69fa58d258b"></td>
    </tr
    <tr>
      <td>CASE06</td>
      <td>마이페이지에서 최근 대화 내용을 정확히 불러오는지 확인</td>
      <td>마이페이지 접속</td>
      <td>시간 순으로 최근 대화 내용 출력</td>
      <td><img src="https://github.com/user-attachments/assets/9ea48593-18e6-4e30-8b55-96d121cacad7"></td>
"></td>
    </tr>
  </tbody>
</table>


<br/><br/>

# 수행결과(테스트/시연 페이지)
## 🎨 Frontend  
Figma로 설계된 디자인 시안을 바탕으로,  HTML,CSS 사용자 인터페이스를 구현
</br> 


</br> </br> 



# 🖌️ 화면 설계서(Figma) & 구현 결과 비교

| 메인화면 설계서 | 현재 구현 결과 |
|-----------------|----------------|
| ![메인화면](https://github.com/user-attachments/assets/2e5fc06e-dd30-45cb-898f-3b7e4a32e7de) | ![](https://github.com/user-attachments/assets/f50c330b-b149-4292-a4c7-43cec7108e08) |
| **로그인 화면 설계서** | **로그인 화면 구현** |
| ![로그인](https://github.com/user-attachments/assets/d5696fc1-0ee5-42f3-a173-4c4ce409361d) | <img src="https://github.com/user-attachments/assets/8a03da95-a7f9-4cc3-8449-f58b3ecef668" width="330"/> 
| **회원가입 화면 설계서** | **회원가입 화면 구현** |
 <img src="https://github.com/user-attachments/assets/7306f66c-fd80-4365-9379-4cc9a9faf1be" width="300"> | <img src="https://github.com/user-attachments/assets/fe4ee735-fa8a-4b76-8e96-a896aa84f788" width="330"/>
| **챗봇 화면 설계서** | **챗봇 화면 구현** |
   <img src="https://github.com/user-attachments/assets/55f10dc2-ee47-4550-b752-034fb02a19a4" width="300"><br>|<img src="https://github.com/user-attachments/assets/7896afd1-8502-40e8-a0cd-6adc14651583" width=990/>
---

## 📱 새로 추가된 화면

<div align="center">
  <img src="https://github.com/user-attachments/assets/c6781acd-399d-4f57-881a-3e9f2e8b1a25" width="330"/>
</div>

---

위와 같이 Figma의 예시 화면과 실제 구현된 화면을 나란히 비교하여 한눈에 볼 수 있도록 정리했습니다.

## 🛠️ Backend

#### 주요 기능 및 처리 흐름
##### ...

</br></br>

# 🚨 개선 사항
<img src="https://github.com/user-attachments/assets/018e5918-d92b-4038-8519-d84c576f7ae7" width=750/>

> ※ 3차 때 개선 사항

---
## 1. 모델 성능 개선

기존 QLoRA 파인튜닝 모델은 약 100개의 QA 데이터로 학습되어 **일반화 성능에 한계**가 있었습니다.  
이를 개선하기 위해 `EleutherAI/polyglot-ko-1.3b` 모델로 교체하고,  
**약 3,000개의 QA 쌍**을 새롭게 구축하여 재학습을 진행했습니다.

- ✅ **결과**: Loss는 일부 감소했으나, 응답 정확도와 일관성은 여전히 부족함
- 🔧 **계획**: 더 많은 **고품질 QA 데이터 확보** 및 **추가 학습** 진행 예정

---

## 2. 웹 버전 UI 개선

기존 UI는 **모바일에 최적화된 화면**만 제공되어 다양한 환경에서 사용하기 어려웠습니다.  
이를 해결하기 위해 **Django + HTML 기반 웹 UI**로 전환하여,  
**데스크탑 환경에서도 접근이 용이하도록 개선** 했습니다.

---

## 3. 문서 임베딩 처리 오류 개선

리뷰 데이터가 길어 토큰 수가 많은 경우,  
임베딩 과정에서 오류가 발생하거나 VectorDB에 저장되지 않는 문제가 있었습니다.

- 🔍 **기존 문제**: 긴 리뷰 데이터 → 처리 오류 발생
- ✅ **개선 방향**:  
  - 긴 리뷰 100개를 분석하여  
    **핵심 리뷰 약 5개**, **중요 키워드 5개**, **전체 요약 1개**를 생성  
  - 토큰 수를 줄여 **오류 최소화** 및 **요약 기반 응답 품질 향상** 시도
    
</br> </br>  

# ✅ 한 줄 회고
| 팀원  | 한 줄 회고                 |
|-------|----------------------------|
| 미송  | - |
| 정현  | - |
| 유경  | - |
| 성지  | - |
