## Parking_Map

###### 사실 매년 나오던 스마트서울 모바일 앱 공모전에 내기 위해 만들었지만, 올해는 개최되지 않았다ㅜㅜ

### :white_check_mark:목표
#### 내 주변의 **주차장**을 찾아주고, 주차 시간과 금액을 입력하면 **요금 계산**도 해주도록 만들자!

### :white_check_mark:방법
+ Google map api를 사용
+ GPS 기능을 탑재하여 사용자의 현재 위치를 파악
+ 주변의 주차장 탐색에는 적당히 500m 정도로 설정해 구글맵에 포함된 사용자의 현재 위치의 500m 이내에 있는 주차장을 모두 마크하여 표시
+ 요금 계산은 주차한 시간과 주차 요금을 입력받으면 반올림해 계산 결과를 밑에 출력하도록 만듦

### :white_check_mark:With
+ 같은 과 동기(혜지)

### :white_check_mark:What I Did?
+ Google map api를 받아와 앱의 메인 화면에 나올 수 있도록 만듦
+ 메인 화면 구상

### :white_check_mark:Images

![Parkingmap_main](https://user-images.githubusercontent.com/57928612/99361012-cc522980-28f4-11eb-879f-904271622e2b.jpg)

![Parkingmap_price01](https://user-images.githubusercontent.com/57928612/99361020-ce1bed00-28f4-11eb-9bc7-a83f50262f61.jpg)

![Parkingmap_price02](https://user-images.githubusercontent.com/57928612/99361029-d07e4700-28f4-11eb-8334-6d03183f1a14.jpg)


### :white_check_mark:아쉬운 점
+ 아는 것이 거의 없는 상태에서 주먹구구식으로 프로젝트를 시작했기 때문에 구글에 의존하여 코딩을 했어서 직접적으로 짠 코드가 거의 없었다. 앞으로는 충분한 공부를 한 뒤 개발을 시도해야겠다.
+ api를 중심으로 여러 기능을 구현해야 했으나 단지 api를 불러왔다는 것만으로 만족하여 프로젝트를 조기종료한 점이 가장 아쉬운 것 같다. 다음부터는 여러 기능을 구현하는 서비스를 만들어 봐야겠다.
