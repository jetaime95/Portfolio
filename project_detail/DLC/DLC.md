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
![68747470733a2f2f76656c6f672e76656c63646e2e636f6d2f696d616765732f6d6172696e7265642f706f73742f35356330386266362d376430322d346439382d616361642d6266663835353662383230302f696d6167652e706e67](https://user-images.githubusercontent.com/113073974/225834453-e344ec39-0ec3-43c2-802a-f258cf44c506.png)

- 메인 페이지
![68747470733a2f2f76656c6f672e76656c63646e2e636f6d2f696d616765732f6d6172696e7265642f706f73742f30613439626434322d663361662d346235622d623639612d3331626264363364386530622f696d6167652e706e67](https://user-images.githubusercontent.com/113073974/225834849-44a86958-1f5c-44ce-bb5f-c10e40fd20e3.png)

- 노래 상세 페이지
![68747470733a2f2f76656c6f672e76656c63646e2e636f6d2f696d616765732f6d6172696e7265642f706f73742f65363033383766632d643530632d343839362d386231622d3432303830643566363433322f696d6167652e706e67](https://user-images.githubusercontent.com/113073974/225834936-56990bc1-dd3c-4b1b-bf1d-3d21d3d906e6.png)

- 프로필 상세 페이지
![68747470733a2f2f76656c6f672e76656c63646e2e636f6d2f696d616765732f6d6172696e7265642f706f73742f39386533343163622d643339322d346166612d393331632d3532323039333637393037332f696d6167652e706e67](https://user-images.githubusercontent.com/113073974/225834943-c186b096-c3b2-4145-91e2-855cc01bd7ef.png)


## 5. ERD 설계

![ERD1](https://user-images.githubusercontent.com/113073974/225834809-69b81772-580a-4e38-8653-2c2d8754c93d.jpg)

## 6. API 설계

[API 명세서](https://documenter.getpostman.com/view/23810621/2s8Z73xATR)

## 8. 프로젝트 시연영상

- 시연영상 촬영자: 임동근



[![프로젝트 시연영상]()](https://www.youtube.com/watch?v=dH_CHanu6E4)
## 9. 회고 및 느낀점
이번 프로젝트를 진행하면서 비밀번호 변경을 위해 장고 auth를 사용한다던지 검색기능을 위해 페이지네이션을 제공하는 ListAPIView를 사용한다던지 장고나 DRF에서는 참 많은 기능들을 제공해준다는걸 새삼 느낄 수 있었다. 다만 기본적으로 세팅 되어있는 값을 내가 원하는 대로 커스텀 하려면 해당 기능들을에 대해 조금 더 이해가 필요하였고, 현재는 정말 간단한 커스텀만을 활용하여 해당 기능들을 사용중에 있지만 리팩토링 기간 때는 좀 더 찾아보고 내 입맛에 맞게 커스텀하여 사용할 수 있었으면 좋겠다.
중간발표까지 좋은 결과물이 뽑혀서 다행이라고 생각이 들었다.

## 10. 머신러닝 데이터셋

[Spotify Dataset](https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset)
