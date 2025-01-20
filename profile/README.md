# 🐶 댕댕어디가 - 반려동물 동반 가능 시설 공유 플랫폼
<img width="1438" alt="댕댕어디가" src="https://github.com/user-attachments/assets/e9fa6e63-1ad6-44d0-9232-81a347004747" />

## 🩷 댕댕어디가 플렛폼 소개
<strong>반려동물과 함께 갈 수 있는 장소만 확인할 수는 없을까?🧐</strong><br>
댕댕어디가는 반려동물과 함께 외출할 수 있는 시설 정보를 공유함으로써 , 견주들이 보다 편리하고 쾌적하게 외출을 즐길 수 있도록 돕습니다.<br>
이를 통해 반려동물과 함께하는 활동의 범위가 넓어지고,외출 시의 부담을 줄여주는 서비스를 제공합니다✨.<br>

- 🔗 <a href="https://fronttest.daengdaeng-where.link/"> 서비스 둘러보기 : 댕댕어디가 공식 웹사이트</a>
- 🔗 <a href="https://github.com/WHERE-ARE-YOU-GOING-DAENG-DAENG/WHERE_ARE_YOU_GOING_DAENG_DAENG_FE"> Frontend Repository</a>
- 🔗 <a href="https://github.com/WHERE-ARE-YOU-GOING-DAENG-DAENG/WHERE_ARE_YOU_GOING_DAENG_DAENG_-"> Backend Repository</a>

## 🩷 프로젝트 기간 
**2024.11.12 ~ 2024.12.19**

## 🩷 팀 소개
| 김가은[조장] | 김승환 | 김지윤 | 박상희 |송수빈|지연우[부조장]|하진서|
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
| <img src="https://avatars.githubusercontent.com/u/63792723?v=4" alt="김가은" width="150"> | <img src="https://avatars.githubusercontent.com/u/101561741?v=4" alt="김승환" width="170"> | <img src="https://avatars.githubusercontent.com/u/147837947?v=4" alt="김지윤" width="170"> | <img src="https://avatars.githubusercontent.com/u/175171101?v=4" alt="박상희" width="170"> |<img src="https://avatars.githubusercontent.com/u/134045937?v=4" alt="송수빈" width="170"> |<img src="https://avatars.githubusercontent.com/u/110551002?v=4" alt="지연우" width="150"> |<img src="https://avatars.githubusercontent.com/u/131326799?v=4" alt="하진서" width="170"> |
| BE | BE | BE | FE |FE|FE|BE|
| [@13wjdgk](https://github.com/13wjdgk) | [GitHub](https://github.com/lixxce5017) | [GitHub](https://github.com/jiyun829) | [GitHub](https://github.com/tkdgml1241) |[GitHub](https://github.com/subinsong01) | [GitHub](https://github.com/wldusdn) | [GitHub](https://github.com/xnfnfnr) |



## 🩷 각 멤버 작업 내역
| 파트 | 이름   | 역할                                                                                     |
|------|--------|------------------------------------------------------------------------------------------|
|**BE** | 김가은 | AWS 서버 구성, 리뷰 시스템, 알림 시스템, 땅따먹기 시스템 |
|**BE**  |  김승환| 장소 추천, aws 서버 & CI/CD, oauth & 쿠키 관리, 시큐리티 |
| **BE** | 김지윤 | 메인페이지 장소 api, 장소 조회, 장소 검색, AI 리뷰 요약  
| **FE**   | 박상희 | 소셜 로그인, 회원정보 CRUD,선호도 등록&수정, 메인페이지&장소추천, 페스티벌 배너, 스토리 업로드 및 삭제   |
| **FE**   | 송수빈 | 반려동물 CRUD&마이페이지, 리뷰, How-to-guide 페이지 및 배너, 알림(FCM), Admin, 스토리 업로드 및 삭제 |
| **FE**  | 지연우 | 검색 & 시설 상세 & 즐겨찾기, 땅따먹기, 에러 퍼블리싱, 방문등록 & 실시간 리뷰, 구글 맵 API, FE 배포 & CI/CD|
| **BE**  | 하진서| 반려동물 API, 선호도 API, 즐겨찾기 API, 스토리 API, 알림 목록 조회 API                                  |

## 🩷 주요 기능 
- **장소 검색**
  -   반려동물 동반 가능 시설 목록 제공
  -   사용자는 위치 & 키워드로 장소 검색 가능
  -   사용자 맞춤 필터링 기능 제공

- **장소 추천**
  - **우리 댕댕이가 좋아할 것 같아요** : 선호장소타입과 현위치와의 거리차 등을 종합한 장소 3곳 추천
  - **요즘 뜨는 장소 알려드려요** : 즐겨찾기 수가 많은 인기 장소 3곳 추천
  - **댕댕어디가 추천 장소** : 유저의 실시간 위치 고려 및 별점 높은 장소 3곳 추천

- **땅따먹기**
  - 리뷰 등록을 일반 리뷰와 실시간 리뷰로 구분
  - 실시간 리뷰 작성 시, 지역 시설을 가장 많이 방문한 유저가 그 지역의 땅을 획득
  - 보상으로 땅 주인은 스토리 업로드 가능(땅 주인은 실시간으로 변경 가능) 

## 🩷 Software Architecture
<img width="1100" alt="SW Architecture" src="https://github.com/user-attachments/assets/74470a5f-9985-4344-b6ef-1e1bf66fb8ac" />

## 🩷 프로젝트 설계

- **AWS 1차**
<img width="1100" alt="aws1" src="https://github.com/user-attachments/assets/143c4b39-a148-49f4-a16c-e372261aa82c" />


- **AWS 2차**
<img width="1100" alt="aws2" src="https://github.com/user-attachments/assets/803c4e95-2be0-4e74-a709-9137f6bfeb24" />

## 🩷 ERD
<a href="https://www.erdcloud.com/d/ZxgjWWypDkE9sGXf9">**🔗 ERD 확인하기**</a>
<br />
<br />
<img width="1062" alt="erd" src="https://github.com/user-attachments/assets/2e855e37-15b6-4f93-8761-aff95cc9d898" />

## 🩷 Figma
<a href="https://www.figma.com/design/0cGW8rkHYLpa2Q2tDC7uSY/%EC%82%B0%EC%B1%85%EC%8B%9C%EC%BC%9C%EC%A1%B0?node-id=2142-228&t=TZzNLFFZLisTf3yL-1">**🔗 Figma 확인하기**</a>
<br />
<br />
<img width="1048" alt="figma" src="https://github.com/user-attachments/assets/b3994d96-ecb2-4a4c-9bac-a62b2a482c55" />

## 🩷 API 명세서
<a href="https://www.notion.so/swgani/API-15839d11ffe78149a3e4ddff526b6e1f">**🔗 API 명세서 확인하기**</a>


## 🩷 프로젝트 폴더 구조

### Frontend
<details>
  <summary><strong> ✨ 확인하기</strong> </summary>


```plaintext
daeng/
├── .storybook            // Storybook 설정 및 파일
├── node_modules          // Node.js 패키지
├── public                // 정적 리소스
│   ├── data/             // 정적 JSON 데이터
│   │   └── sig.json.gz
│   ├── alarm_logo.png    // 알람 로고 이미지
│   ├── favicon.svg       // 파비콘 파일
│   └── firebase-messaging-sw.js  // Firebase 메시징 스크립트
├── src/
  ├── components/      // UI 컴포넌트
  │   └── commons/      // 공통 컴포넌트
  ├── pages/           // 페이지 단위 컴포넌트
  ├── firebase/        // 파이어베이스(FCM)
  ├── hooks/           // 커스텀 훅
  ├── stores/          // Zustand 스토어 파일
  ├── utils/           // 유틸리티 함수
  ├── data/            // 더미데이터
  ├── routes/          // 라우트 관련
  ├── stories/         // 스토리북 파일
  ├── style/           // 스타일 관련 (CSS 등)
  ├── services/        // API 요청 및 데이터 처리
  └── assets/          // 이미지, 폰트 등 정적 리소스
      └── icons/       // icon 파일
```
<br />
</details>

### Backend
<details>
  <summary><strong> ✨ 확인하기</strong> </summary>
</details>

## 🩷 구현 과정 및 성과

### Frontend
<details>
  <summary><strong>📚 확인하기</strong> </summary>
  
---
#### 1️⃣ Storybook
- **UI 일관성 유지**: 스토리북을 활용해 컴포넌트 스타일 및 기능 테스트.
- **컴포넌트 관리와 재사용성 향상**: 프로젝트 내에서 공통 UI를 효율적으로 관리.

---

#### 2️⃣ 지도 API 성능 개선
- **실시간 위치 추적 정확도 개선**:
  - 기존 `getCurrentPosition()` → 개선된 `watchPosition()`으로 변경.
  - 실시간 위치 추적 시 정확도를 높임.
- **시군구 경계 데이터 최적화**:
  - 시군구 JSON 데이터를 `gzip`으로 압축.
  - 압축 데이터를 사용하여 로딩 속도 개선.

---

#### 3️⃣ Debounce 적용
- API 호출 시 서버 과부하를 방지하기 위해 **Debounce** 개념 도입.
- VALUE 값 변경마다 API 호출 대신, 일정 시간 간격으로 호출 처리
---
</details>


### Backend
<details>
  <summary><strong>📚 확인하기</strong> </summary>
  
---
#### 1️⃣ Full-Text Search 
- **Text Indexing**: 텍스트를 개별 단어(토큰)로 나눈 후 각 단어에 대한 색인을 생성
- **검색 우선순위**: 일치하는 키워드는 우선순위로 표시 이후 생성된 색인으로 검색 후 결과 출력
---
#### 2️⃣ 리뷰 조회 - 동적 쿼리
- **🧐 문제점**
  - 최신순 , 평점 높은순, 평점 낮은순 으로 정렬
  - 정렬 개수만큼 조회 쿼리가 필요
  - 쿼리 수정이 필요할때마다 3개의 쿼리 수정 
- **🥳 해결 방안**
  - 검색 조건에 따라 실행 시점에서 쿼리를 생성하기 위해 동적쿼리 필요
  <br/>
  <table>
    <th>Criteria</th>
    <td> 쿼리가 복잡하여 생성될 쿼리를 파악하기 어려움</td>
    <th>QueryDSL</th>
    <td> 쉽고 간결하여 쿼리 파악하기 쉬움</td>
  </table>
---
#### 3️⃣ 리뷰 조회 - 무한 스크롤
- **Offset**
  - 데이터가 많을 경우 뒤로갈 수록 조회 성능 저하
  - count 쿼리 필요
- **No Offset**
  - 기준 Key가 중복된다면 중복된 결과를 전달
  - 페이징 방식에서 적용 불가
  - **92.3%** 개선
---
#### 4️⃣ 실시간 땅 유저 조회 
- **🧐 문제점**
  - 최신 땅 주인을 조회하기 위해 Region_owner_log 테이블을 매번 정렬해서 조회
  - 실행 계획 분석 결과, Using Filesort 진행
    
- **🥳 해결 방안**
  - [시/도,시군구읍,생성날짜]를 복합 인덱스 처리하여 인덱싱기반 조회
  - Redis의 Set 자료형으로 최근 땅 주인을 캐싱
---
</details>


## 🩷 유저 및 피드백

### 📅 12월 10일에 1차 MVP 완성
- 이후 **구글 광고 및 카페 홍보글 작성(강사모)** 진행 
- **네이버 애널리틱스**로 유저 및 유입 경로 분석

  
#### 1월 10일

<img width="1046" alt="광고 1차 실적" src="https://github.com/user-attachments/assets/1a46519f-5343-4c6f-9fb3-b81e412c8b60" />


  
#### 1월 15일
<img width="1046" alt="광고 2차 실적" src="https://media.discordapp.net/attachments/1306901337052676191/1317513290288730253/image.png?ex=678e6b5e&is=678d19de&hm=f89635ff39dde5ee49e3363e0a4f4d5589ef6e360a09409347729feb173f56f0&=&format=webp&quality=lossless&width=2160&height=924" />

## 🧐 네이버 애널리틱스 결과 및 서비스 설문조사 진행 결과 
<a href="https://docs.google.com/spreadsheets/d/1_Q3rmGFtDyi9_AtYuU-3TUfE_O7vSs3KGXjmlwi5PtE/edit?usp=sharing"> **🔗 설문조사 결과** </a>
<br />

<img width="1211" alt="네이버 애널리틱스 결과 및 서비스 설문조사 " src="https://github.com/user-attachments/assets/914a01d4-880c-4367-9057-73e3193fd399" />

> 유저들의 실제 피드백
<img width="1046" alt="피드백 테이블 이미지" src="https://github.com/user-attachments/assets/9633673f-4df5-4c80-a539-28db387da16e" />

## 🩷 유저들의 피드백 반영

### 1️⃣ 검색어 자동완성 
<img width="1024" alt="검색어" src="https://github.com/user-attachments/assets/627ca607-0f38-4df1-ada8-07cb285ee50a" />

### 2️⃣ 이미지 Resizing
<img width="1024" alt="Image Resizing" src="https://github.com/user-attachments/assets/606f6933-ac50-4a78-be55-d22900313ed7" />

### 3️⃣ 지도
<img width="1024" alt="지도" src="https://github.com/user-attachments/assets/11b15e75-d4e2-405e-982c-cbd02bf70df6" />

