# 💉중간이들 (Gannies)

> ### **"중앙대 간호학과 동문 커뮤니티"**

> **재학생부터 현직 간호사까지,**
> **중앙대 간호인의 지식과 경험이 모이는 공간입니다.**
>
> - 학업 및 실습 정보 공유
> - 취업/진로 멘토링
> - 동문 네트워킹
>
> 함께 성장하는 중앙대 간호인들의 커뮤니티에 오신 것을 환영합니다.
> 
> ### 👉 <b>https://www.caugannies.com</b>

![최상위메인](https://github.com/user-attachments/assets/ec5145e3-660b-4a1e-aaf3-e655b53404ab)

---

# 바로가기

### 1. [서비스 소개](https://github.com/Gannies#1-서비스-소개-1)
### 2. [프로젝트 개요](https://github.com/Gannies#2-프로젝트-개요-1)
### 3. [페이지 구성](https://github.com/Gannies#3-페이지-구성-1)
### 4. [주요 구현 내용](https://github.com/Gannies#4-주요-구현-내용-1)
### 5. [기능 설명](https://github.com/Gannies#5-기능-설명-1)
### 6. [참고 링크](https://github.com/Gannies#6-참고-링크-1)

---

# 1. 서비스 소개

- ## 요약
  - **중앙대학교 간호학과 동문들을 위한 정보 공유 플랫폼**입니다.  
  - 재학생과 졸업생 간 효과적인 정보 교류를 위해 기획되었으며, 특히 장문의 정보글과 다양한 형태의 파일 공유에 중점을 두었습니다.

- ## 기획 배경

  ### 현재 문제점
    - 기존 플랫폼(에브리타임)의 정보 저장/공유 한계
    - 학과 특화 플랫폼 부재로 인한 정보 격차 발생
    - 파일 공유 제한, 체계적 분류 부재, 검색 기능 미흡

  ### 해결 방안

    - **인증 시스템**: OCR 기반 동문 인증 (학과 DB 연동 예정)
    - **정보 관리**: 이론/실습/취업 등 체계적 카테고리 분류
    - **기술 특징**:
      - **통합 검색 시스템**: 제목 + 내용 검색 지원
      - **게시판 에디터**: TinyMCE를 활용하여 사용자가 편리하게 게시물 작성 가능
      - **다양한 파일 형식 지원**: 이미지, PDF, DOC, HWP, PPT 등
      - **직관적인 UI/UX 구현** : 사용자 친화적이고 정보 공유에 최적화된 디자인

- ## 이름에 담긴 의미
    - **'중간이들'** 은 중앙대 간호학과의 정체성을 담은 이름으로,  
      함께 성장하는 커뮤니티를 지향합니다.

---

# 2. 프로젝트 개요

- ## 기간 <br>

  | 단계           | 기간                  | 기간(주) |
  |----------------|-----------------------|----------|
  | 기획 · 디자인 | 24.07.04 - 24.08.11    | 4주      |
  | 개발 · 배포     | 24.08.12 - 24.10.23    | 11주      |

- ## 인원 및 역할 <br>

  - 5명<br>
    - <b>`디자인`</b> 1명, <b>`기획`</b> 1명, <b>`프론트엔드`</b> 2명, <b>`백엔드`</b> 1명<br>
    - 프로젝트 중반부 기획에는 모든 개발자가 참여함. <br>

  | 이름 | 역할 | 포지션 | 담당 업무 | 깃허브 계정 |
  |----------------------------|---------------------------|---------------------------|--------------------------|-----|
  | 엽유정 | 팀원 | Design | • 디자인 | - |
  | 문채영 | 팀원 | Product Managing | • 기획 | [yoocho](https://github.com/yoocho) |
  | 김승현 | 팀원 | FrontEnd | • 프론트엔드 | [VaIice](https://github.com/VaIice) |
  | 윤서환 | 팀원 | FrontEnd | • 프론트엔드 | [neptune588](https://github.com/neptune588) |
  | 이가린 | 팀장 | BackEnd | • 기획, 백엔드 | [devellybutton](https://github.com/devellybutton) |

- ## 관련 링크

  | 항목                 | 링크           |
  |---------------------|--------------|
  | 📌 **피그마**            | [https://www.figma.com/design/KLSDKGLKEsdlgksdtb/Gannies](https://www.figma.com/design/KtYfyQYBhLqffJ3gfB2Xtb/%EC%A4%91%EA%B0%84%EC%9D%B4%EB%93%A4(Gannies)?m=auto&t=RFgVvVYsp8YSQ3AW-1) |
  | 📌 **기획안** | 업로드 예정    |
  | 📌 **기능명세서** | 업로드 예정    |
  | 📌 **Swagger 배포 문서** | 업로드 예정    |
  | 📌 **API 테스트 문서**   | 업로드 예정     |
  | 📌 **포지션별 GitHub 저장소** |                |
  | - 프론트엔드    | [https://github.com/Gannies/Gannies_FrontEnd](https://github.com/Gannies/Gannies_FrontEnd)       |
  | - 백엔드       | [https://github.com/Gannies/Gannies_BackEnd](https://github.com/Gannies/Gannies_BackEnd)       |

- ## 기술 스택
  - **프론트엔드** :
    ![JavaScript](https://img.shields.io/badge/JavaScript-yellow?logo=javascript&logoColor=white)
    ![React.js](https://img.shields.io/badge/React-blue?logo=react&logoColor=white)
    ![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?logo=redux&logoColor=white)
    ![Redux Persist](https://img.shields.io/badge/Redux_Persist-0076F3?logo=redux&logoColor=white)
    ![Styled Components](https://img.shields.io/badge/Styled_Components-DB7093?logo=styled-components&logoColor=white)

  - **백엔드**:
  ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
  ![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white)
  ![TypeORM](https://img.shields.io/badge/TypeORM-1F2A56?logo=typeorm&logoColor=white)

  - **배포**: 
  ![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)
  ![AWS Route 53](https://img.shields.io/badge/AWS_Route_53-232F3E?logo=aws&logoColor=white)
  ![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?logo=aws&logoColor=white)
  ![PM2](https://img.shields.io/badge/PM2-2B2D3E?logo=pm2&logoColor=white)

  - **클라우드 저장소**: 
  ![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?logo=amazonaws&logoColor=white)
  ![AWS RDS](https://img.shields.io/badge/AWS_RDS-527FFF?logo=amazonaws&logoColor=white)
  ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
---

# 3. 페이지 구성

|                                                                          메인 페이지                                                                          |                                                                       로그인 페이지 페이지                                                                       |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------: |
|    <div style="text-align: center;"></div>    | <div style="text-align: center;"></div> |
|                                               <b><div style="text-align: center;">회원가입 페이지</div></b>                                                |                                                 <b><div style="text-align: center;">이메일/비밀번호 찾기 페이지</div></b>                                                 |
| <div style="text-align: center;"></div> |  <div style="text-align: center;"></div>  |
|                                                <b><div style="text-align: center;">게시물 목록 페이지</div></b>                                                 |                                                 <b><div style="text-align: center;">게시물 상세 페이지</div></b>                                                 |
|  <div style="text-align: center;"></div>  |  <div style="text-align: center;"></div>  |
|                                                   <b><div style="text-align: center;">게시물 작성 페이지</div></b>                                                    |                                                     <b><div style="text-align: center;">검색 결과 페이지</b>                                                     |
|    <div style="text-align: center;"></div>    |   <div style="text-align: center;"></div>   |
|                                                  <b><div style="text-align: center;">마이 페이지</div></b>                                                  |                                                    <b><div style="text-align: center;">관리자 페이지</b>                                                    |
|   <div style="text-align: center;"></div>   |  <div style="text-align: center;"></div>  |

---

# 4. 주요 구현 내용

- ## 프론트엔드

  | **항목**             | **내용**                                                       |
  |----------------------|---------------------------------------------------------------|
  | **페이지 레이아웃**    | 기획된 디자인에 맞게 일관된 페이지 레이아웃 구성                   |
  | **검색 및 정렬**       | 검색, 페이지네이션, 정렬 기능을 통해 사용자 경험을 개선            |
  | **관리자 페이지**      | 관리자 페이지를 통한 사이트 관리                               |
  | **상태 관리**          | Redux Persist로 상태 영속성 관리                                 |
  | **스타일링**           | Styled-components로 컴포넌트 단위 스타일링 구현                   |
  | **라우팅 제어**        | Private Router를 통한 인증 상태에 따른 라우팅 제어                |
  | **유효성 검사**        | 정규식을 활용한 유효성 검사                                     |
  | **배포 및 도메인 관리** | Vercel 배포 및 AWS Route 53을 통한 도메인 관리                   |

- ## 백엔드

  | **항목**             | **내용**                                                       |
  |----------------------|---------------------------------------------------------------|
  | **서버 개발**         | Node.js와 NestJS 프레임워크를 사용한 서버 개발                  |
  | **데이터베이스**      | MySQL과 TypeORM을 사용한 데이터베이스 설계 및 관리                |
  | **API 개발**          | RESTful API 설계 및 Swagger를 통한 API 문서화                   |
  | **세션 인증**         | express-session, connect-redis, passport를 사용한 세션 관리 및 인증 구현 |
  | **보안**              | JWT 인증을 통한 보안 강화                                      |
  | **파일 처리**         | AWS S3를 활용한 파일 업로드 및 관리                              |
  | **캐시 관리**         | Redis를 활용한 캐시 처리로 성능 최적화                          |
  | **배포 및 관리**      | AWS EC2를 통한 서버 배포 및 관리                                |
  | **외부 API 활용**     | Nodemailer, Twilio (SMS 인증), Google Vision OCR API를 사용하여 외부 서비스 연동 |

---

# 5. 기능 설명

### 💡 마이페이지 서비스

---

# 6. 참고 링크

사이트 제작시 참고한 레퍼런스
- 블라인드 : https://www.teamblind.com/kr/
- 너스케입 : https://www.nurscape.net/
