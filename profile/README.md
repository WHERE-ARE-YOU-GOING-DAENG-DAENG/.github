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
| **FE**   | 박상희 | Figma 작업, 소셜 로그인, 회원정보 CRUD,선호도 등록&수정, 메인페이지&장소추천, 페스티벌 배너, 스토리 업로드 및 삭제   |
| **FE**   | 송수빈 | Figma 작업, 반려동물 CRUD&마이페이지, 리뷰, How-to-guide 페이지 및 배너, 알림(FCM), Admin, 스토리 업로드 및 삭제 |
| **FE**  | 지연우 | Figma 작업, 검색 & 시설 상세 & 즐겨찾기, 땅따먹기, 에러 퍼블리싱, 방문등록 & 실시간 리뷰, 구글 맵 API, FE 배포 & CI/CD|
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




