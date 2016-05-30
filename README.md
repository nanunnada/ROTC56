ROTC 56

•아이디어
◦학생차트

•동기
◦평소에 학생들이 여러 가지 불편한 점을 말하는 데, 우리도 그 점에 대해서 불편함을 느껴서 “어떻게 하는 것이 좋겠다“라고 생각하다가, 마침 이번 프로젝트가 있어서 여기에 그 생각을 구현하게 되었다. 


•내용
◦처음에 로그인 관련 GUI화면이 뜨고, 거기서 로그인에 성공하면 각종 기능이 있는 화면이 출력이 된다. 그 화면에서 원하는 기능을 선택하면 그 기능에 관련된 GUI화면이 나온다. 학생들이 자주 불편한 점을 느꼈던 것 위주로 기능을 구성했다. 

 첫 번째, 공강 시간에 밥을 먹을 때 무엇을 먹을지 고민하는 학생들이 많다. 그 학생들은 각각 여유시간도 다르고, 소지하고 있는 돈의 양도 다르고, 입맛 또한 다르다. 그래서 그 모든 조건을 충족하는 메뉴를 쉽게 고르게 하기 위해 (What's Eat?)라는 기능을 추가하였다. 
 두 번째, 컨디션이 좋지 않다고 생각될 때 그 증상의 원인을 모르는 사람이 많다. 그 증상을 알려고 병원을 가자니 여건이 마땅치 않아서 가지 못하고 혼자서 앓고 있는 경우가 많다. 그래서 전문적이지는 않겠지만 어느 정도 자신의 상태를 체크할 수 있는 기능인 (My Health?)을 만들 것이다.
 세 번째, 개개인에 따라 다르겠지만, 각자 자주 사용하는 사이트가 있을 것이다. 그래서 사이트 주소들을 모아서 한 번에 볼 수 있게 (Favorite Site!)를 추가하였다.
 네 번째, 마찬가지로 이 시스템을 사용 중 메모지가 필요한 경우 바로 사용할 수 있게 (Note)를 추가하였다. UML에서의 표현은 각각 Eat Class, Health Class, FavoriteSite Class, Note Class로 하겠다.


•기능

•What's Eat? ◦checkbox라는 GUI기능을 이용하여 해당 체크박스들이 선택됐을 때 값을 출력하도록 한다. (ex: (5분거리, 10분거리...), (4천원 이내, 8천원 이내...), (국수, 밥.....) )

•My Health? ◦JOptionPane이라는 GUI기능을 이용하여 상태를 진단하도록 한다. (ex: 몸이 으슬으슬하다, 인후통이 있다.... )

•Favorite Site! ◦TextArea 같은 기능을 이용하여 만든다.

•Note ◦TextArea 같은 기능을 이용하여 만든다.
