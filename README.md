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
      <td>25.05.04-25.05.08</td>
      <td>김성지, 백미송</td>
    </tr>
    <tr>
      <td>2</td>
      <td>데이터 전처리 및 정제</td>
      <td>25.05.08-25.05.10</td>
      <td>김성지</td>
    </tr>
    <tr>
      <td>3</td>
      <td>QLoRA 학습 데이터 생성</td>
      <td>25.05.10</td>
      <td>백미송, 현유경</td>
    </tr>
    <tr>
      <td>4</td>
      <td>백엔드 장고 변환</td>
      <td>25.05.11-25.05.13</td>
      <td>김성지, 오정현</td>
    </tr>
    <tr>
      <td>5</td>
      <td>QLoRA 세팅 및 파인튜닝</td>
      <td>25.05.14-25.05.15</td>
      <td>백미송, 현유경</td>
    </tr>
    <tr>
      <td>6</td>
      <td>HTML/CSS를 활용한 UI 설계 및 구현</td>
      <td>25.05.12-25.05.14</td>
      <td>김성지, 오정현</td>
    </tr>
<tr>
      <td>8</td>
      <td>AWS 배포</td>
      <td>25.05.14-25.05.15</td>
      <td>김성지,현유경</td>
    </tr>
    <tr>
      <td>10</td>
      <td>통합 테스트 및 튜닝</td>
      <td>25.05.14-25.05.15</td>
      <td>ALL</td>
    </tr>
    <tr>
      <td>11</td>
      <td>발표 자료 / 코드 정리</td>
      <td>25.05.15</td>
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
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><strong>Backend</strong></td>
      <td>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white">
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

## 스킨케어 질문 크롤링
<div>
  <img width="500" alt="cafe_skincare" src="https://github.com/user-attachments/assets/d6373551-6c21-456d-9a08-75638a596df3" />
  <img width="500" alt="cafe_skincare_text" src="https://github.com/user-attachments/assets/7c952580-ca61-4f1c-a805-0899ca89cc9d" />
</div>

<br/>

## ☝🏻 전처리 과정

### 🫒 skincare_qa.csv </br> 
- 원본 데이터  </br> 
<img width="800" src="https://github.com/user-attachments/assets/03f7d5ea-19a9-4730-83bb-41142f4e9b41"> </br>

**1. usage 전처리**  
  - 특수기호 (■) 제거   
<img width="800" src="https://github.com/user-attachments/assets/3e329f19-d1c3-4f90-b80e-cd0b76fe31b7"> </br> 

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
      <td>질문 의도에 적합한 답변 반환</td>
      <td>건성 피부가 겨울철에 사용할만한 크림 추천해줘</td>
      <td>화장품 목록 + 실제 사용자의 리뷰</td>
      <td><img src='https://github.com/user-attachments/assets/1059344b-d9b7-4189-a4b9-03fb6ed5966b'></td>
    </tr>
    <tr>
      <td>CASE02</td>
      <td>화장품의 성분을 참고한 답변 반환</td>
      <td>잡티 제거에 좋은 성분을 가진 화장품은?</td>
      <td>질문에 알맞는 성분 추천 + 화장품 추천 + 화장품의 주요 성분</td>
      <td><img src='https://github.com/user-attachments/assets/f099b5a8-4e0e-4a0c-a549-6eab0d7ef1e0'></td>
    </tr>
    <tr>
      <td>CASE03</td>
      <td>사용자가 실제 사용하고 있는 화장품과의 궁합 반환</td>
      <td>내가 넘버즈인 글루타치온 흔적 앰플을 가지고 있는데 이거랑 비타민이 함량된 세럼을 같이 써도 돼?</td>
      <td>질문 의도에 적합한 답변 + 궁합이 좋은 화장품 추천 + 화장품과의 궁합</td>
      <td><img src='https://github.com/user-attachments/assets/1dd1b90c-c024-4634-b168-bb8e777ca706'></td>
    </tr>
    <tr>
      <td>CASE04</td>
      <td>특정 기능에 대한 시각화</td>
      <td>세척력 좋은 클렌징폼 추천해줘</td>
      <td>세척력이 좋은 화장품 + 화장품의 성분 설명과 함께 추천 이유 전달 + 세정력 시각화</td>
      <td><img src='https://github.com/user-attachments/assets/2723220b-4cb0-4ef6-8b21-76b59969c516'></td>
    </tr>
  </tbody>
</table>



<br/><br/>

# 수행결과(테스트/시연 페이지)
## 🎨 Frontend  
Figma로 설계된 디자인 시안을 바탕으로,  HTML,CSS 사용자 인터페이스를 구현
</br> 

<img src="https://github.com/user-attachments/assets/f50c330b-b149-4292-a4c7-43cec7108e08" width=990/>

</br>

<img src="https://github.com/user-attachments/assets/7896afd1-8502-40e8-a0cd-6adc14651583" width=990/>

<div align="center">
  <img src="https://github.com/user-attachments/assets/fe4ee735-fa8a-4b76-8e96-a896aa84f788" width="330"/>
  <img src="https://github.com/user-attachments/assets/8a03da95-a7f9-4cc3-8449-f58b3ecef668" width="330"/>
  <img src="https://github.com/user-attachments/assets/c6781acd-399d-4f57-881a-3e9f2e8b1a25" width="330"/>
</div>

</br> </br> 

## 🛠️ Backend

#### 주요 기능 및 처리 흐름
##### ...

</br></br>

# 🚨 개선 사항

(이전꺼 캡쳐해놓고 어떻게 향상시켰는지 쓰기)

1. **QLoRA 파인튜닝 모델 성능 한계**  
   현재 사용된 QLoRA 파인튜닝 모델은 약 100개의 QA 데이터셋으로 학습되었기 때문에,  
   다양한 질문에 대한 일반화 성능에 한계가 있습니다.  
   향후에는 보다 많은 데이터를 추가하여 학습시킴으로써 모델의 응답 품질을 향상시킬 예정입니다.

2. **웹 버전 UI 개선 계획**   -> 장고로 바꾸면서 어쩌구 한계 극복 어케 했는지 쓰기
   현재 PiBoo의 사용자 인터페이스는 모바일 최적화된 휴대폰 화면 형태로 디자인되어 있습니다.  
   하지만 다음 프로젝트에서는 Django와 HTML 기반의 웹사이트 제작을 배우게 되어,  
   웹 버전 형태로 구현하여 다양한 환경에서도 원활하게 사용할 수 있도록 개선할 계획입니다.

3. **문서 임베딩 처리 오류 개선**  
   현재 문서 임베딩 과정에서 토큰 수가 많은 리뷰 데이터가 포함될 경우,  
   임베딩 처리 중 오류가 발생하거나 VectorDB에 저장되지 않는 문제가 발생합니다.  
   이를 해결하기 위해 리뷰 데이터를 요약하여 토큰 수를 줄이고, 오류를 최소화하는 방안을 적용할 예정입니다.
</br> 

# ✅ 한 줄 회고
| 팀원  | 한 줄 회고                 |
|-------|----------------------------|
| 미송  | - |
| 정현  | - |
| 유경  | - |
| 성지  | - |
