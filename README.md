# 정보처리산업기사 문제풀기

## Q1.페이지는 몇개를 생성해야될까 ?
A.약 10개를 생성해야됩니다 <br><br>
그 이유로는 index페이지,layout페이지,


![image](https://user-images.githubusercontent.com/97486300/201585689-b137ee11-ebe6-4188-ac8e-2901262d342f.png)


백신예약을 받아줄 join과 받은 예약을 DB로 전송시켜줄 join_p페이지,

![image](https://user-images.githubusercontent.com/97486300/201587200-d26ec093-d3fd-4563-9f5a-faf3eb1c6d63.png)

그리고 백신예약을 조회해주는 seach,

![image](https://user-images.githubusercontent.com/97486300/201587397-c0ec8256-0ac3-4bbf-bdd7-d4f91c659f43.png)

백신예약 현황을 보여주는 result 페이지

![image](https://user-images.githubusercontent.com/97486300/201587763-6ee84b5d-7b13-46fe-93d3-d7fd5b6b86d6.png)

약10개 정도 필요하다

## Q2.테이블은 몇개를 생성해야되는가 ?
A.3개가 필요함

TBL_JUMIN_202108

![image](https://user-images.githubusercontent.com/97486300/201588250-8013a5ff-c282-4ac5-9a4d-d056edf90933.png)

TBL_HOSP_202108

![image](https://user-images.githubusercontent.com/97486300/201588496-101f5197-1adc-4ac8-8070-7542e3dc6da8.png)

TBL_VACCRESV_202108

![image](https://user-images.githubusercontent.com/97486300/201588558-c4f571df-9e44-46a8-943e-56e226303753.png)


# 산업기사 백신프로그램 

## 실행화면

첫페이지는 index입니다
![image](https://user-images.githubusercontent.com/97486300/201933964-95e6818c-ef02-4269-a3d0-e583330e23f4.png)

## 백신예약 페이지 입니다 (view)

![image](https://user-images.githubusercontent.com/97486300/201939691-0f622693-0127-4424-9bf1-a68d47c9bfb3.png)

예약번호는 자동으로 생성됩니다

![image](https://user-images.githubusercontent.com/97486300/201939997-58557681-265c-42f1-a2c5-2ee58248c90e.png)

널값이 있다면 유효성 검사에서 걸러져 예약이 불가합니다


![image](https://user-images.githubusercontent.com/97486300/201940154-1893a131-5bd7-41e7-90e0-b43cb4e69da9.png)

## 유효성 검사 코드


![image](https://user-images.githubusercontent.com/97486300/201940407-224e48bb-4bd0-4ced-8ed2-15239c9e2255.png)


테이블

![image](https://user-images.githubusercontent.com/97486300/201940761-01d48cb9-1a07-429e-8276-be2d59a86ef4.png)


## insert_reservtion (back)

DB에 스트링형식으로 값을 넣어줍니다


![image](https://user-images.githubusercontent.com/97486300/201942020-4057b812-b20c-41ef-81ff-f447defc599d.png)


## 예약조회 화면입니다 (view)

![image](https://user-images.githubusercontent.com/97486300/201938986-e0b788f6-c50d-4983-ba92-337e30a13883.png)

## saerch_reservation_table (back)

값을 조회하는 코드입니다

!![image](https://user-images.githubusercontent.com/97486300/201941578-8ad1a3a9-7188-4aca-bd21-74462719ebb5.png)

아래는 테이블입니다

![image](https://user-images.githubusercontent.com/97486300/201843491-b3cd5464-721e-4bfb-bcde-2f7c2813ca21.png)

