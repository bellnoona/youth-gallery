# youth-gallery(유스갤러리)

## 1. 소개와 기능

### 1.1 프로젝트 소개

***youth gallery***는 미술 대학 학생들이 자신의 작품을 전시하고, 판매하고 있는 작품을 등록하여 홍보할 수 있는 SNS입니다.

회원 가입과 로그인을 하면, 상품을 등록하지 않아도 작품과 일상을 공유하며 즐거운 SNS 활동을 할 수 있습니다.
사용자는 글과 사진과 함께 게시물을 작성하고, 이를 공유할 수 있습니다.
다른 사용자를 팔로우하면 팔로우한 사용자가 올린 게시물을 홈 피드에서 확인할 수도 있습니다.

피드를 구경하다가 마음에 드는 게시물을 발견했다면 좋아요를 누를 수 있고, 댓글을 남길 수도 있습니다.

### 1.2 기능

1.2.1 기능 분류

    - 🔐 인증
        - 로그인
        - 회원가입
        - 회원 정보 수정
        - 유효성 평가

    - 🎨 상품
        - 상품 목록 / 등록 / 수정 / 삭제
        - 이미지 파일 업로드 / 수정 / 미리보기
        - 유효성 평가

    - 🏞 게시글
        - 게시글 목록 / 등록 / 수정 / 삭제
        - 다중 이미지 파일 업로드 / 수정 / 미리보기

    - 💬 댓글
        - 댓글 등록 / 삭제

    - 🔍 검색

    - 👩🏻‍🎨🧑🏻‍🎨 follow / unfollow

    - 💙 좋아요
        - 좋아요 등록 / 취소

    - 📰  소식
        - 미술계의 새소식 목록

1.2.2 UI Interaction

    - 이미지 슬라이드
    - 모달
    - splash animation
    - 버튼 활성화

### 1.3 팀원소개

|                                                         **FE 김수현**                                                         |                                                               **FE 김아름**                                                               |                                                  **FE 정예지**                                                   |                                                    **FE 조민경**                                                     |
| :---------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------: |
|                     <img width="180" alt="logo" src="https://user-images.githubusercontent.com/76866502/180384109-76e9d195-419c-49f2-879c-e2ef0f7adf9e.png">                    |                           <img width="180" alt="logo" src="https://user-images.githubusercontent.com/76866502/180384109-76e9d195-419c-49f2-879c-e2ef0f7adf9e.png">                           |              <img width="180" alt="logo" src="https://user-images.githubusercontent.com/76866502/180384109-76e9d195-419c-49f2-879c-e2ef0f7adf9e.png">               |                <img width="180" alt="logo" src="https://user-images.githubusercontent.com/76866502/180384109-76e9d195-419c-49f2-879c-e2ef0f7adf9e.png">                 |
|      **blog**: [bellnoona.log](https://velog.io/@tngusglaso) </br> **github**: [bellnoona](https://github.com/bellnoona)      |                **blog**: [areumz.log](https://velog.io/@tngusglaso) </br> **github**: [areumz](https://github.com/areumz)                 | **blog**: [sabit1997.log](https://m122.tistory.com/) </br> **github**: [sabit1997](https://github.com/sabit1997) | **blog**: [minkyeongJ.log](https://velog.io/@jisu243) </br> **github**: [minkyeongJ](https://github.com/minkyeongJ)  |
| ![FrontEnd](https://img.shields.io/badge/FrontEnd-3f97fb) ![Team%20leader](https://img.shields.io/badge/-Team%20leader-green) | ![FrontEnd](https://img.shields.io/badge/FrontEnd-3f97fb) ![Functional%20Design](https://img.shields.io/badge/Functional%20Design-f8b62d) | ![FrontEnd](https://img.shields.io/badge/FrontEnd-3f97fb) ![Design](https://img.shields.io/badge/-Design-orange) | ![FrontEnd](https://img.shields.io/badge/FrontEnd-3f97fb) ![Planning](https://img.shields.io/badge/-Planning-f67280) |

## 2. 개발 환경 및 배포 URL

### 2.1 개발 환경

-   Web Framework
    -   React.js
-   서비스 배포 환경
    -   vercel 또는 heroku

### 2.2 배포 URL

-   (배포 url)

## 3. 프로젝트 구조와 개발 일정

### 3.1 프로젝트 구조

```bash
  └─ aaa
      │  bbb
      │  bbb
      │
      ├─bbb
      │  │  bbb.py
      │  │  bbb.py
...중략...
```

### 3.1 개발 일정(WBS)

-   2022.06.09 ~ 20022.08.01
    (googld docs 일정 첨부) [임시]     
    <img width="900" alt="wbs" src="https://media.discordapp.net/attachments/991989630935244807/999939062595063928/unknown.png">


## 4. 역할 분담

김수현 - splash / 로그인 / 회원가입 / 프로필 수정

김아름 - 게시글 작성 / 댓글 리스트 / 댓글 작성 / 소식 페이지

정예지 - 프로필 페이지 / 팔로워 목록 / 팔로잉 목록 / 상품 등록

조민경 - 피드 / 검색 / 하단 탭 메뉴 / 좋아요 / 모달

## 5. 전체 UI 기획

-   피그마 캡쳐
    <img src="ui.png" width="40%">

## 6. 메인 기능

(gif 추가해서, 표로 정리)

<div align='center'>
</div>

-   splash

    -   서비스 접속 초기 화면
    -   splash 화면이 잠시 나온 뒤 다음 페이지(로그인 x : 로그인 화면 / 로그인 o : 홈 피드)

-   로그인

    -   이메일과 비밀번호를 사용하여 로그인 할 수 있음
    -   이메일 주소와 로그인에 대한 유효성 검사를 진행하여 일치하지 않을 경우 경고 문구

-   회원 가입

    -   이메일 주소와 비밀번호를 입력하여 회원 가입 할 수 있음
    -   input창에 입력시 유효성 검사가 진행되며, 통과 시 프로필 설정으로 연결됨
    -   프로필 설정에 필요한 사진, 사용자 이름, 계정 id, 소개를 입력할 수 있음
        계정 id는 중복 불가

-   홈 피드

    -   사용자들이 올린 게시물이 표시됨
    -   자신이 팔로우한 사용자의 게시물만 확인 가능함
    -   팔로우한 사용자가 없을 경우 or 내가 팔로우한 사용자가 게시물이 없을 경우 검색하기 버튼이 뜸

-   검색

    -   홈 피드에 돋보기 버트검색 버튼 클리하면 표시되는 페이지
    -   사용자 이름을 검색하여 계정을 찾을 수 있음

-   사용자 프로필 페이지

    -   사용자 프로필 페이지에서는 사용자 이름, 계정 ID, 소개, 팔로워 및 팔로잉 수, 판매 상품,  
        사용자가 업로드한 게시글을 확인할 수 있음
    -   사용자 정보 하단에는 팔로우 버튼이 있고, 클릭할 때마다 팔로우 <-> 언팔로우로 상태 변경됨
    -   팔로워 및 팔로잉 수를 클릭하면 팔로워, 팔로잉 사용자 목록 표시
    -   판매 중인 상품 섹션은 등록한 상품이 없을 경우에는 표시 되지 않음
    -   게시글 섹션에서는 목록형과 앨범형으로 게시글을 확인할 수 있음  
        기본형은 목록형이며, 이미지가 없는 게시글인 경우 앨범에서는 표시되지 않음
    -   사용자가 올린 게시글이 없을 경우 게시글이 나타나지 않음
    -   나의 프로필 페이지일 경우 프로필 수정 버튼과 상품 등록 버튼이 표시됨

-   팔로워, 팔로잉 목록

    -   사용자 프로필 사진, 이름, 계정 ID, 팔로우 버튼으로 구성된 목록
    -   내가 팔로우한 사용자일 경우 취소 버튼이, 내가 팔로우 하지 않은 사용자의 경우 팔로우 버튼이 표시

-   내 프로필 수정
    -   나의 프로필 페이지에서 프로필 수정을 누르면 프로필 수정 페이지가 뜸
    -   입력창에 대한 명세는 회원 가입에서의 설정과 동일함
-   상품 등록

    -   상품 이미지, 상품명, 가격, 판매 링크를 입력할 수 있으며 모든 입력 완료시 저장 버튼 활성화됨
    -   상품명은 2~15자 이내로 입력되게 하고, 가격은 숫자를 입력하면 자동으로 원단위로 변환됨

-   게시글 댓글 페이지

    -   게시글 하단에 말풍선 아이콘을 클릭하면 댓글을 확인하고 입력할 수 있는 페이지가 뜸
    -   댓글 입력창에 텍스트를 입력하면 버튼이 활성화됨

-   게시글 작성 페이지

    -   하단 메뉴바에 게시글 작성을 누르면 페이지가 뜸
    -   글이 입력되거나 사진이 업로드되면 업로드 버튼이 활성화되고, 버튼을 누르면 게시글이 업로드됨
    -   사진은 우측 하단 버튼을 클릭하면 업로드할 수 있으며, 최대 3장까지 업로드 가능함

-   새로운 소식 페이지

    -   하단 메뉴바에 소식을 누르면 페이지가 뜸
    -   최신 미술계 소식을 볼 수 있음

-   하단 탭 메뉴

    -   하단 탭 메뉴는 홈, 채팅, 게시물 작성, 프로필 4개의 메뉴로 구성
    -   모든 페이지는 페이지에 해당하는 탭 메뉴가 활성화
    -   탭 메뉴 클릭 시 활성화 된 탭에 해당하는 페이지로 이동

-   좋아요 버튼

    -   게시글이 나타나는 모든 페이지에 해당
    -   게시글 하단에 하트 모양에 좋아요 버튼 위치
    -   빈 하트를 클릭하면 색이 칠해진 하트로 변경
    -   색이 칠해진 하트를 누르면 빈 하트로 변경
    -   좋아요 개수는 카운트 되어 하트모양 우측에 표시

-   모달

    -   헤더에 있는 버튼을 클릭하면 설정 및 개인정보와 로그아웃 표시
    -   게시글 우측 상단에 위치한 버튼을 클릭했을 경우
        -   내가 작성한 게시글일 경우 : 삭제, 수정 버튼
        -   다른 사용자가 작성한 게시글일 경우 : 신고하기 버튼
    -   댓글 우측 상단에 위치한 버튼을 클릭했을 경우
        -   내가 작성한 댓글일 경우 : 삭제 버튼
        -   다른 사용자가 작성한 댓글일 경우 : 신고하기 버튼
    -   로그아웃, 삭제, 신고 버튼을 누르면 확인 메시지 모달창이 나타나야 하고, 취소 버튼을 누르면 모달은 사라짐

    -   댓글 우측 상단에 위치한 버튼을 클릭했을 경우
        -   내가 작성한 댓글일 경우 : 삭제 버튼
        -   다른 사용자가 작성한 댓글일 경우 : 신고하기 버튼
    -   로그아웃, 삭제, 신고 버튼을 누르면 확인 메시지 모달창이 나타나야 하고, 취소 버튼을 누르면 모달은 사라짐

## 7. 개발 문화

-   프로젝트 시작전 주간 회의 통해 기획, 환경 셋팅, 역할 분담
-   프로젝트 시작후 매일 아침 작업 현황 브리핑
-   브랜치 전략 : GitHub Branch  
     PR로 코드 리뷰 받고, main에 merge  
     PR시, 해결하지 못한 부분은 공유하고 페어프로그래밍 및 댓글로 함께 해결
-   공동 notion에 회의록 작성, 작업 일정 google docs로 공유, 참고할 문서 공유

## 8. 개발하면서 겪은 이슈와 해결

-   코딩 컨벤션, 커밋 컨벤션
-   axios vs fetch
-   각자 작업하는 부분이 겹칠 때가 있어 충돌이 일어남
    매일 오전 브리핑으로 작업 상황과 오늘 작업 예정을 공유하여, 겹치지 않도록 함
    매 작업 전 pull 받는 것을 필수로 함

## 9. 개발하며 느낀점

-
