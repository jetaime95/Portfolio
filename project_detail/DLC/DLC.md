# 🎵 DLC

#### 음악을 좋야요 했을 떄 좋아요 한 음악 리스트 기반으로 음악 추천을 해주는 서비스입니다.

<br/>

## 1. 제작 기간, 맡은 역할

- 기간: 2022년 11월 02일 ~ 11월 08일 (1주)
- 팀 프로젝트

- 역할

  - User 회원가입
  - access token을 이용한 로그인 기능 구현
  - SIMPLE JWT를 이용한 User Custom
  - 위 항목의 API 구축을 바탕으로 프론트 연동 진행

## 2. 사용 기술

> Backend

- Python
- Django
- DjangoRestFramework
- Django simple JWT

> Frontend

- Vanilla JS
- html
- css

> Management

- Git/Github
- Notion
- Slack

## 3. 주요 기능

DLC의 주요 기능은 아래와 같습니다.

- [Spotify Dataset](https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset)을 이용한 음악 추천 시스템
- 음악 순위별 리스트 크롤링 및 곡명으로 Spotify API 검색 후 DB 저장
- 좋아요 누른 음악 기반으로 음악 추천 및 추천

## 4. 와이어프레임

- 로그인 / 회원가입 페이지
![]()
- 메인 페이지
![]()
- 노래 상세 페이지
![]()
- 프로필 상세 페이지
![]()

## 5. ERD 설계

![]()

## 6. API 설계


[API 명세서](https://documenter.getpostman.com/view/23810621/2s8Z73xATR)

## 8. 프로젝트 시연영상

- 시연영상 촬영자: 임동근




[![프로젝트 시연영상]()](https://www.youtube.com/watch?v=dH_CHanu6E4)
## 9. 회고 및 느낀점
- DRF를 이용한 첫 프로젝트였는데, 이전까지 Django로만 이용하다가 DRF를 사용하니 이전보다 좀 더 편리하게 작성할 수 있었다.
- 머신러닝이 생각보다 어려웠지만, 추천 시스템이 되고나니 만족스러웠다.
- Python에 대한 이해가 아직 부족했던 것 같다. Python과 Django에 대하여 좀 더 공부할 수 있도록 해야겠다.

> [프로젝트 개발 회고 게시물]()

## 10. 머신러닝 데이터셋

[Spotify Dataset](https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset)
