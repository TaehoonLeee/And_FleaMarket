# 벼룩시장 어플(FM24MHz)
> 벼룩시장을 여는 판매자와 벼룩시장을 방문하여 물건을 사고 싶은 구매자가 이용하는 어플입니다.
- GPS기능을 이용하여 판매자는 지도에 자신의 벼룩시장 위치와 날짜를 표시하고, 구매자는 GPS로 현재 위치에서 가까운 곳을 찾거나, 날짜를 정해서 확인 할 수 있습니다.
- 판매자에 대한 리뷰, 피드백 등과 같은 Communication 기능을 마이페이지 댓글을 통해 사용할 수 있습니다.
- 판매자의 물건 제작 영상 등을 유튜브를 통해 볼 수 있습니다.

## 목차
- [제작 배경](#제작-배경)  
- [세부 기능](#세부-기능)  
  - [Firebase를 이용한 데이터베이스 관리](#Firebase를-이용한-데이터베이스-관리)  
  - [장소 예약, 예약된 장소 확인](#Naver-Maps-API를-이용한-장소-예약과-예약된-장소-확인)  
  - [판매자의 물건 홍보 영상 포스팅](#Youtube-API를-이용한-판매자의-물건-홍보-영상-포스팅)  
  - [소통이 가능한 마이페이지](#판매자와-구매자가-소통이-가능한-mypage)  

## 제작 배경
최근에 여행을 다니다 보면 벼룩시장이 열린 광경을 종종 볼 수 있는데, 언제 어디서 어떤 품목을 파는 벼룩시장이 열리는지 알 수 있으면 좋을 것 같아 만들게 되었습니다.  

## 세부 기능  
### Firebase를 이용한 데이터베이스 관리
![스크린샷 2021-01-08 오전 12 53 26](https://user-images.githubusercontent.com/48707020/103913562-03ea8e80-514c-11eb-951b-b2ba9c2f35de.png)  
- Firebase의 realtime database를 이용하여 회원 정보, 회원의 댓글, 회원의 유튜브 주소를 관리한다.  
### Naver Maps API를 이용한 장소 예약과 예약된 장소 확인
![noname](https://user-images.githubusercontent.com/48707020/103914274-ebc73f00-514c-11eb-9809-08ee0e0d62c6.png) 
![noname1](https://user-images.githubusercontent.com/48707020/103914280-ed910280-514c-11eb-9902-f6df7c7e380a.png)  
- 판매자는 벼룩시장을 개장할 일정과 장소를 선택한 후 예약한다.  
![noname2](https://user-images.githubusercontent.com/48707020/103914284-eec22f80-514c-11eb-8d94-c1ffaaf26872.png)  
- 구매자는 벼룩시장 일정을 확인할 수 있다.  
### Youtube API를 이용한 판매자의 물건 홍보 영상 포스팅
![noname4](https://user-images.githubusercontent.com/48707020/103914288-eff35c80-514c-11eb-88f8-227979688ef7.png) 
![noname5](https://user-images.githubusercontent.com/48707020/103914289-eff35c80-514c-11eb-9b6f-f77fd1a7c71c.png)  
- 판매자는 자신의 물건 홍보 유튜브 영상을 포스팅할 수 있고, 좋아요를 받을 수 있다.  
- 좋아요 버튼 기능은 구현했지만, 유튜브 영상 주소를 넣어도 영상이 제대로 나오지 않는 오류가 있음.  
### 판매자와 구매자가 소통이 가능한 mypage
![noname3](https://user-images.githubusercontent.com/48707020/103914285-ef5ac600-514c-11eb-8315-9efdedccbead.png)
- 댓글을 이용하여 소통이 가능하다.

