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
이번 프로젝트엔 팀원들 모두 DRF에 좀 더 익숙해져 백엔드 작업은 크게 어려움 없이 진행될 수 있었던 것 같다. 나 또한 serializer 부분에 대해 좀 더 이해할 수 있는 시간이였다.
아쉬운 점은 프론트 부분에서 문제점들이 많이 발생하였고, 그 문제점들을 잡는데 시간이 많이 소요가 되었다. 또한 백엔드 기능 구현시 큰 틀로만 생각하고 세부적인 기능들을 추가하지 못한 것 같다.
예를 들면 커스텀한 옷 삭제나 장바구니 삭제등 프로젝트가 끝나고 발표를 진행하는 도중 발견했었다. 저번 프로젝트 보단 좀 더 발전했던 프로젝트지만 최종 프로젝트때는 더욱 꼼꼼히 진행해야겠다고 생각했다.

## 10. 딥러닝 모델
[style-transfer-pytorch](https://github.com/crowsonkb/style-transfer-pytorch)
