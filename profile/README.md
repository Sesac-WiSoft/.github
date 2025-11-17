# PrePair - AI 기반 맞춤형 면접 코치 플랫폼

<strong>취준 루틴을 AI가 함께 만듭니다.</strong><br/>
매일, 혹은 매주 - 당신에게 꼭 맞는 면접 질문 • 답변 • 피드백 제공

<img width="1536" height="864" alt="image" src="https://github.com/user-attachments/assets/b4b5b1e5-65e7-41da-af04-985bf98f0d3a" />

</br>
</br>


## 프로젝트 소개

취준생의 **71.9%** 가 “면접이 가장 어렵다”고 말하고,  
**5명 중 3명**은 ‘면접 들러리 경험’을 겪는 현실에서 이 프로젝트는 시작되었습니다.

> "어떤 질문이 나올지 모르겠다"  
> "내 답변이 괜찮은지 확인할 사람이 없다"  
> "혼자 연습하면 점점 불안해진다"

이 문제를 해결하기 위해, 우리는 **AI 기반 면접 코치 플랫폼**을 만들었습니다.

- 사용자 직무 기반 **맞춤형 질문 생성**  
- 정기적인 **면접 루틴 형성**  
- AI 기반 **답변에 대한 객관적 평가 및 상세한 피드백과 점수 제공**  
- 답변 히스토리 관리 및 **장기 성장 추적**

당신의 면접 준비를 ‘습관’으로 바꾸고  
실전에서 흔들리지 않는 자신감을 키우는 서비스입니다.

</br>

### 주요 기능

### 1. 맞춤형 면접 질문 생성
<table>
<tr>
<td width="40%" style="vertical-align: middle;">
  <div style="min-height: 230px; display: flex; align-items: center;">
    사용자의 직업군 <br/>
    (개발자, 디자이너, 기획자 등)에 <br/>
    최적화된 AI 기반 면접 질문을 제공합니다.
  </div>
</td>

<td width="30%" align="right" style="vertical-align: middle;">
  <img src="https://github.com/user-attachments/assets/50b37405-0eaf-4058-ad09-c5c4e30b90c8"
       width="300"
       style="border-radius: 12px;" />
</td>
</tr>
</table>


### 2. 정기 알림 시스템
<table>
<tr>
<td width="40%" style="vertical-align: middle;">
  <div style="min-height: 230px; display: flex; align-items: center;">
    사용자의 설정(매일/주간)에 따라 <br/>
    이메일 또는 카카오톡으로 면접 질문을 자동 발송합니다.
  </div>
</td>
<td width="30%" align="right" style="vertical-align: middle;">
  <img src="IMAGE_URL_HERE"
       width="300"
       style="border-radius: 12px;" />
</td>
</tr>
</table>

### 3. AI 기반 피드백
<table>
<tr>
<td width="40%" style="vertical-align: middle;">
  <div style="min-height: 230px; display: flex; align-items: center;">
    AI가 사용자의 답변을 분석하여  <br/>
    점수(0~100점), 잘한 점, 개선할 점,  <br/>
    추천 학습 자료를 제공합니다.
  </div>
</td>
<td width="30%" align="right" style="vertical-align: middle;">
  <img src="https://github.com/user-attachments/assets/45ed6107-ebc3-4689-8651-0bf17add730f"
       width="300"
       style="border-radius: 12px;" />
</td>
</tr>
</table>

### 4. 리워드 시스템
<table>
<tr>
<td width="40%" style="vertical-align: middle;">
  <div style="min-height: 260px; display: flex; align-items: center;">
    답변을 통해 얻은 점수로   <br/>
    쿠폰 및 상품으로 교환 가능한  <br/>
    리워드 시스템을 제공합니다.
  </div>
</td>
<td width="35%" align="right" style="vertical-align: middle;">
  <img src="https://github.com/user-attachments/assets/002621d5-8cc4-40b3-a221-50ddb8f9c1ea"
       width="300"
       style="border-radius: 12px;" />
  <br/><br/>
  <img src="https://github.com/user-attachments/assets/9d85db33-a3cb-4c10-a17c-d034b6cdc6cc"
       width="300"
       style="border-radius: 12px;" />
</td>
</tr>
</table>

### 5. 답변 히스토리 관리
<table>
<tr>
<td width="55%" style="vertical-align: middle;">
  <div style="min-height: 230px; display: flex; align-items: center;">
    과거의 모든 질문과 답변, <br/>
    그리고 AI 피드백을   <br/>
    한눈에 확인할 수 있는   <br/>
    히스토리 페이지를 제공합니다.
  </div>
</td>
<td width="45%" align="right" style="vertical-align: middle;">
  <img src="https://github.com/user-attachments/assets/22b78087-e053-49d0-a9dc-ae5f941234e9"
       width="300"
       style="border-radius: 12px;" />
</td>
</tr>
</table>


## 기술 스택

### Backend
- Node.js / NestJS
- Java
- PostgreSQL

### Frontend
- React 
- TypeScript

### AI & External APIs
- OpenAI API (면접 질문 생성 및 피드백)
- Ollama
- [한국고용정보원 워크넷 API](https://www.data.go.kr/data/3038225/openapi.do)

## 주요 흐름

### 1. 회원가입 및 설정
1. 이메일/비밀번호로 회원가입 또는 로그인
2. 직업군 선택 (개발자, 디자이너, 기획자 등)
3. 질문 수신 주기 설정 (매일/주 1회)

### 2. 면접 질문 수신
1. 설정한 주기에 따라 이메일/카카오톡으로 면접 질문 수신
2. "답변하러 가기" 버튼을 통해 웹사이트 접속
3. 면접 질문에 대한 답변 작성

### 3. AI 피드백 및 점수 획득
1. AI가 답변을 분석하여 피드백 제공
   - 점수 (0-100점)
   - 잘한 점
   - 개선할 점
   - 추천 학습 자료
2. 획득한 점수로 리워드 누적

### 4. 리워드 및 히스토리
1. 나의 리워드 페이지에서 누적 점수 확인
2. 쿠폰 및 상품 교환
3. 과거 답변 및 피드백 히스토리 조회

## 참고 자료

- [취준생 5명 중 3명 '면접 들러리 경험'](https://www.metroseoul.co.kr/article/20210923500077)
- [잡코리아 "구직자 46%, 채용 절차 중 면접 가장 어려워해"](https://www.donga.com/news/Economy/article/all/20240508/124841140/1)
- [인잡핏 면접 실태 조사: 취준생 71.9% "면접이 가장 어렵다"](https://www.dhnews.co.kr/news/view/1065585199757801)


## 👥 팀원 소개
역할 | 팀장 | 팀원 | 팀원 | 팀원 |
|:---:|:---:|:---:|:---:|:---:|
이름 | 문동민 | 신보연 | 이은채 | 왕우민 |
GitHub | <a href="https://github.com/MoonDongmin"><img src="https://github.com/MoonDongmin.png" width="100" height="100"/></a> | <a href="https://github.com/Boyeon-Shin"><img src="https://github.com/Boyeon-Shin.png" width="100" height="100"/></a> | <a href="https://github.com/wanyam2"><img src="https://github.com/wanyam2.png" width="100" height="100"/></a> | <a href="https://github.com/Woomin-Wang"><img src="https://github.com/Woomin-Wang.png" width="100" height="100"/></a> |

이 프로젝트는 대회 출품을 목적으로 개발되었습니다.
