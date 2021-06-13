# 2021-1-OSSP2-SaJoChamChi-4
2021-1 공개SW프로젝트_02 4조 사조참치

## 냉장고를 정리해(냉정해)
시대가 변하고 기술이 발전해 냉장고 크기가 커져 보관할 수 있는 음식이 많아지면서 냉장고 안의 음식들을 관리하기가 어려워졌습니다. UN 통계에 따르면 매년 음식물 쓰레기 양은 증가하고 그 중 가정에서 배출되는 음식물 쓰레기가 가장 많다고 합니다.

냉장고를 정리해는 유통기한을 기반으로 사용자의 냉장고 속 식품을 관리하는 어플리케이션입니다. 사진만으로 간편한 입력을 할 수 있고 유통기한이 얼마 남지 않은 식품들을 PUSH 알림을 통해 확인할 수 있습니다. 또한, 다양한 레시피 제공을 통해 사용자가 식품을 소비하는데 도움을 줍니다. 입력만 하면 언제 어디서든 냉장고에 무엇이 있고 유통기한이 얼마나 남았는지 확인할 수 있어 불필요한 식품 소비를 줄일 수 있습니다.

## 기능
0. 로그인 화면
    + 로그인
    + 회원가입
    + 아이디 / 비밀번호 찾기

1. 메인화면
    + 냉장고
    + 레시피 추천
    + 게시판
    + 내 정보
    + 유통기한 임박식품

2. 냉장고
    + 냉장고 품목 리스트
        + 품목 추가, 수정, 삭제

3. 레시피 추천
    + 유통기한 기반 추천 레시피
    + 냉장고 재료 기반 추천 레시피
    + 전체 레시피 리스트
    + 좋아요 기능

4. 게시판
    + 나만의 레시피 게시
        + 작성, 수정, 삭제
    + 댓글
        + 작성, 삭제
    + 좋아요 기능

5. 내 정보
    + 프로필 수정
    + 좋아요 게시물 확인
    + 로그아웃

## ScreenShots
실제 어플 화면 이미지1 (로그인, 메인화면, 냉장고 리스트)

<img width="200" src="https://user-images.githubusercontent.com/79090053/121778994-82a09780-cbd4-11eb-8643-352d765acd01.png"><img width="200" src="https://user-images.githubusercontent.com/79090053/121779185-5d605900-cbd5-11eb-8559-baa1a9e01da9.png" ><img width="200" src="https://user-images.githubusercontent.com/79090053/121779265-c8119480-cbd5-11eb-9b8a-b69bf9bef6d9.jpg">

실제 어플 화면 이미지2 (게시판, 게시글, 추천 레시피)

<img width="200" src="https://user-images.githubusercontent.com/79090053/121779355-2fc7df80-cbd6-11eb-86bc-10f3b01d4c22.png"><img width="200" src="https://user-images.githubusercontent.com/79090053/121779373-49692700-cbd6-11eb-8c5c-b06b95c659e3.png"><img width="200" src="https://user-images.githubusercontent.com/79090053/121779444-9b11b180-cbd6-11eb-8c5e-64d8cac095ce.jpg">

실제 어플 화면 이미지3 (프로필 화면)

<img width="200" src="https://user-images.githubusercontent.com/79090053/121779457-a9f86400-cbd6-11eb-91b8-4e3350c1c1de.png">

## 기술스택
<img width="500" src="https://user-images.githubusercontent.com/79090053/121798324-98f43500-cc60-11eb-9c1b-84b1874ad686.PNG">

### 인식
+ React Expo Barcode Scanner
<img width="500" src="https://user-images.githubusercontent.com/79090053/121798233-1c615680-cc60-11eb-960c-ef49466c89bf.png">

+ Google Vision API
<img width="500" src="https://user-images.githubusercontent.com/79090053/121798150-a6f58600-cc5f-11eb-95c3-8cc6e2fdad59.png">

## 팀원
 * 2017112134 이호준 (팀장)
 * 2016112144 김민석
 * 2017112102 김지석
 * 2014112026 박서준
 * 2017112146 박서진
 * 2019112045 이유정