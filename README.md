# Select-Shop
##
실행 url: http://son.lolcalii.com:8888/

## 개발환경
1. 인텔리제이
2. arc
3. java1.8

## 세팅
- spring web
- mysql
- h2 database
- spirng data jpa
- lombok
- spring security

## 개발설명및 기능
- 로그인,회원가입
- Naver open api를 통해 상품을 검색가능
- 카카오 로그인기능 구현
- 최저가 설정가능
- 사용자가 찜한 상품을 모아보기에서 한눈에 볼수있음.
## 실행 화면
![로그인 화면](https://user-images.githubusercontent.com/80336750/131959343-ab0941f0-14ba-4def-9448-fc76554ad041.PNG)
- 회원가입 화면입니다 소셜로그인은 카카오만 구현을 했습니다.
![로그인된 메인화면](https://user-images.githubusercontent.com/80336750/131959480-ddc22287-f1c6-41a1-9d25-b9527fe1e095.PNG)
- 로그인을 완료한 메인화면인데요 기능은 검색기능과 찜한 상품을 모아보는 모아보기 기능이 있습니다.
![검색창에 단어 검색시화면](https://user-images.githubusercontent.com/80336750/131959605-4d6e0adc-c54b-47b6-9236-6956e81cd06f.PNG)
- 자신이 원하는 상품이름으로 검색시 네이버 api를 이용해 검색결과를 가져올수있습니다.
- 정렬 순서는 네이버인기상품순 입니다.
![최저가 설정화면](https://user-images.githubusercontent.com/80336750/131959852-5c1952c8-541e-4313-8f65-a86830890919.PNG)
- 오른쪽에 찜하기 버튼을 누르면 최저가를 설정할수도있고 안할수도있는데요 최저가를 설정하면 해당상품이 자신이 설정한 최저가 아래로 내려갈경우 '최저가' 라고 표시를 해줍니다.
![최저가 설정후 모아보기 화면](https://user-images.githubusercontent.com/80336750/131960001-bd48cb00-4707-4e94-ba47-9f2e55d19b54.PNG)
- 마지막으로 본인이 찜한 상품을 모아볼수있는 모아보기 화면입니다. 
