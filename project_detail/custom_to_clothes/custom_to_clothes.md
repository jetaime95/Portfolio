# 👕 Custom to Clothes

#### 딥러닝을 이용하여 옷들을 커스텀하여 옷을 주문하는 쇼핑몰 서비스


<br/>

## 1. 제작 기간, 맡은 역할

- 기간: 2022년 11월 22일 ~ 11월 28일 (1주)
- 팀 프로젝트

- 역할

  - 메인페이지에 제작한 옷 인기순위 나열 기능 구현
  - 프로필 기능 구현
  - 위 항목의 API 구축을 바탕으로 프론트 연동 진행

  
## 2. 사용 기술
  
  > Backend
  
    - Python
    - Django
    - DjangoRestFramework
    - Django simple JWT
     
        
  > Infra
  
    - AWS EC2
      
    
  > Frontend
    
    - Vanilla JS
    - html
    - css
        
    
  > Management
  
    - Git/Github
    - Notion
    - Slack
    
  
    
 ## 3. 주요 기능
 
Cutom To Clothes의 주요 기능은 아래와 같습니다.
  
1. [Style-transfer-pytorch](https://github.com/crowsonkb/style-transfer-pytorch)를 이용한 옷 제작 딥러닝 (필터를 이용하여 옷 Custom)
2. 커스텀 옷 주문 후 사이즈, 수량 선택 기능 구현
3. 커스텀 주문 클릭 시 장바구니, 주문목록 카테고리로 진행하여 상태 표시


## 4. 와이어프레임

https://www.figma.com/file/2wXsZhQlOURcWATyJzz2he/Untitled?node-id=0%3A1&t=1Sm22iCgAOGjt3Sy-0
![clc피그마](https://user-images.githubusercontent.com/113073174/210203800-a61d5423-ebac-4aee-aef4-0dbadad49f8a.png)


## 5. ERD 설계

![CTC](https://user-images.githubusercontent.com/113073174/210205145-a160275e-f7b1-4ffa-9060-83a6e7c48e01.jpg)



## 6. API 설계


[API 명세서](https://documenter.getpostman.com/view/23810621/2s8Z72VXUr)

    
  
## 7. 💣 트러블 슈팅

- Django.db.utils.OperationalError (소셜 로그인 기능 구현 중 no such table)
- UserModel 커스텀 진행 중 Login 오류 (자바스크립트 연동 도중 로그인 오류)
- 프론트엔드 연동 도중 TypeError
- 장비구니 기능 구현 중 데이터를 가져오지 못하는 오류
- 백엔드 데이터를 프론트 데이터로 가져오는 과정 중 권한이 없다고 

[Wiki 이동]()



## 8. 프로젝트 시연영상

- 시연영상 촬영자: 임동근


[![A4팀 프로젝트 시연영상](https://user-images.githubusercontent.com/113073174/204188971-949176c9-1b0e-471b-90e2-c257f54d5ac9.png)](https://www.youtube.com/watch?v=dH_CHanu6E4)
 
 ## 9. 회고 및 느낀점
 - 처음 기획을 하면서, 프로젝트 기간에 맞게 기획하는 것을 목표로 가졌습니다.
 - 기획을 진행하며, 기획은 세세하고 확실하게 해야하는 것을 깨달았습니다.
 - DRF가 전보다는 익숙해져 기획 의도대로 프로젝트 진행을 할 수 있었고, 프론트 연동까지 성공할 수 있어 뿌듯했습니다.
 
 
> [프로젝트 개발 회고 게시물]()


## 10. 딥러닝 모델
[style-transfer-pytorch](https://github.com/crowsonkb/style-transfer-pytorch)
