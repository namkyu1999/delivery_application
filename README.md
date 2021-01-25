
# Orange!
실시간 배달 웹사이트 입니다.


# 사용계층
1. customer(소비자)
2. seller(판매자)
3. carrier(유통자,배달원)
4. admin(관리자)

# 유스 케이스
1. 회원가입 하여 자신이 customer인지, seller인지, carrier인지 정한다.
2. customer가 자신의 지역을 검색하여 찾는다.
3. customer가 음식의 종류별, 거리순, 혹은 검색을 통해 음식점을 찾는다.
4. customer가 수량과 개수, 특이사항을 입력하여 음식을 주문한다
5. customer가 자신의 주문한 이력을 확인한다.
6. customer가 자신이 주문한 음식의 배달현황을 확인한다.(주문요청->주문확인/조리->배달중->배달완료)
7. customer가 주문 하였던 음식점에 리뷰를 작성한다.
8. seller가 자신의 음식점 정보를 등록요청한다.
9. seller가 음식점의 메뉴, 가격 등의 정보를 수정한다.
10. seller가 요청받은 주문 정보를 승인, 혹은 취소 한다.
11. seller가 자신과 인접한 carrier를 찾아 선택한다.
12. seller가 완성한 음식을 carrier에게 전달한다.
13. seller가 customer에 의해 작성된 리뷰에 답글을 단다.
14. carrier가 현재 자신의 상태임을 알린다.(배달 가능/ 불가능)
15. carrier가 seller를 선택한다.(seller 먼저 선택 후, carrier의 동의)


# 화면 설계
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FTYh4In9epZj7XotSpPCaJZ%2F%25EB%25A6%25AC%25EC%2595%25A1%25ED%258A%25B8-%25EC%258A%25A4%25ED%2594%2584%25EB%25A7%2581%25EB%25B6%2580%25ED%258A%25B8%3Fnode-id%3D0%253A1" allowfullscreen></iframe>

# Tech stack
## frontend
- react
## backend
- spring boot
