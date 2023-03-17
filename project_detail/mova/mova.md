# ✒ MOVA

#### 웹툰 커뮤니티, 팬아트 서비스
#### 링크: https://mo-va.site/
![mova main](https://user-images.githubusercontent.com/113073174/210253267-852c4c7d-81d4-46cf-8826-283d52110b05.png)


<br/>

## 1. 제작 기간, 맡은 역할

- 기간: 2022년 11월 30일 ~ 12월 28일
- 팀 프로젝트

- 역할


  - ORM을 이용하여 DB를 설계하고 DRF를 활용하여 오늘의 웹툰, 관심웹툰,  관심웹툰,  좋아요웹툰, 댓글 기능 구현
  - ListAPI의 SearchFilter를 활용한 웹툰 및 작가 검색 기능 구현
  - OAuth를 이용한 카카오 소셜 로그인 구현게시글 CRUD(공지사항, 팬 게시판)
  - 게시글 카테고리 기능 구현
  - 배포 및 운영(Docker, AWS)
  - 위 항목의 API 구축을 바탕으로 프론트 연동 진행

  
## 2. 사용 기술
  
  > Backend
  
    - Python
    - Django
    - DjangoRestFramework
    - Django simple JWT
    - Dj-rest-auth
    - django-allauth
     
    
  > Database
      
    
  
    - PostgreSQL
        
    
  > Infra
  
    - AWS EC2
    - AWS Route 53
    - AWS CloudFront
    - AWS S3
    - Docker
    - Docker compose
    - Nginx
    - Gunicorn
      
    
  > Frontend
    
    - Vanilla JS
    - html
    - css
    - toast UI
        
    
  > Management
  
    - Git/Github
    - Notion
    - Slack
    
  
    
 ## 3. 주요 기능
  
- 게시글 작성/수정/삭제 및 검색 기능
- 게시글 작성/수정 시 웹툰, 게시글 카테고리 기능
- [Colorization_tool_on_web](https://github.com/yangco-le/Colorization_Tool_on_Web)을 활용한 팬아트 기능


## 4. Architecture

![mova_art](https://user-images.githubusercontent.com/113073174/210240826-dd23a2bf-212c-4128-9bfa-062a1600c7e5.png)



## 5. ERD 설계


   ![mova_erd](https://user-images.githubusercontent.com/113073174/210240686-8703f3df-64b8-4de7-94d9-28b57e5c18a8.jpg)



## 6. API 설계

  - Postman 활용하여 만든 api 명세서

    https://documenter.getpostman.com/view/24027867/2s8Z6x2Z38
    
  
## 7. 핵심 트러블 슈팅 및 피드백


### 트러블 슈팅

- 이미지 고용량 업로드 해결 문제
- 비밀번호 초기화 이메일 인증 시 url 오류
- user DELETE 중 오류

### 피드백

- 소셜 로그인

[Wiki로 이동](https://github.com/jetaime95/MOVA_BACKEND/wiki/%ED%8A%B8%EB%9F%AC%EB%B8%94-%EC%8A%88%ED%8C%85-%EB%B0%8F-%ED%94%BC%EB%93%9C%EB%B0%B1)

 
 
 ## 9. 회고 및 느낀점
이번 프로젝트를 진행하면서 비밀번호 변경을 위해 장고 auth를 사용한다던지 검색기능을 위해 페이지네이션을 제공하는 ListAPIView를 사용한다던지 장고나 DRF에서는 참 많은 기능들을 제공해준다는걸 새삼 느낄 수 있었다. 다만 기본적으로 세팅 되어있는 값을 내가 원하는 대로 커스텀 하려면 해당 기능들을에 대해 조금 더 이해가 필요하였고, 현재는 정말 간단한 커스텀만을 활용하여 해당 기능들을 사용중에 있지만 리팩토링 기간 때는 좀 더 찾아보고 내 입맛에 맞게 커스텀하여 사용할 수 있었으면 좋겠다.
중간발표까지 좋은 결과물이 뽑혀서 다행이라고 생각이 들었다.
