# transform_practice2
패스트 캠퍼스 front-end 강의 중 transform 속성에 대한 공부2


### perspective 

	하위 요소를 관찰하는 원근 거리를 지정 
		- 단위 px

### perspective 속성과 함수 차이점

	속성의 경우 우리가 일반적으로 적는 속성을 작성하듯이 하면 된다.
		- perspecive:600px;
		- 적용대상 : 부모요소

			스크린샷 
	함수의 경우 
		-	transform:perspecive(600px)
		- 적용대상 : 관찰대상에 직접 부여

			스크린샷

### backface-visibility 

	3D 변환으로 회전된 요소의 뒷면 숨김 여부
		- visible = 뒷면 보임
		- hidden = 뒷면 숨김

### transform: rotateY(180deg)
	
	180도 뒤집기 
		- 류가 Y축으로 뒤집어짐 
	backface-visibility 사용 
		- 기본 값 visible;
		- hidden 사용시 뒤집어진 요소는 더 이상 보이지 않게 된다.
		- rotateY 값을 0도로 바꾸면 다시 보이게 되는데 
		- 요소의 뒷면이 안보이는 거고 앞면은 보여 준다.
		⭐️ 스타벅스 페이지
		 	- 스크린샷
			- 스크린샷