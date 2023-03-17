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
모든 팀원들이 열심히 했던만큼 아쉬움도 큰 프로젝트인거 같다. 프론트와 백으로 작업공간을 나누면서 진행하는 첫 프로젝트이다 보니, javascript로 연동 하는 부분에 있어 큰 어려움이 있었으며
내가 맡은 파트도 제대로 구현을 못했다는 부분에 개인적으로도 아쉬움이 많이 남는 프로젝트이다.
그래도 팀원들이 함께 협업하는 좋은 분위기여서 프로젝트를 마무리 할 수 있어서 감사하며 너무 좋았다. 이번 프로젝트를 통해 부족한 부분을 더욱 확실하게 느낄 수 있는 시간이여서
앞으로 다가올 프로젝트엔 좀 더 성장한 모습으로 임할 수 있을거 같다.

## 10. 머신러닝 데이터셋

[Spotify Dataset](https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset)
