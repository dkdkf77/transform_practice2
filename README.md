# transform_practice2
패스트 캠퍼스 front-end 강의 중 transform 속성에 대한 공부2


### perspective 

	하위 요소를 관찰하는 원근 거리를 지정 
		- 단위 px

### perspective 속성과 함수 차이점

	속성의 경우 우리가 일반적으로 적는 속성을 작성하듯이 하면 된다.
		- perspecive:600px;
		- 적용대상 : 부모요소
![스크린샷 2021-11-16 오전 9 50 39](https://user-images.githubusercontent.com/88579497/141877037-4a362b5e-1faa-4764-a7be-7851d0959086.png)

			
	함수의 경우 
		- transform:perspecive(600px)
		- 적용대상 : 관찰대상에 직접 부여
![스크린샷 2021-11-16 오전 9 52 02](https://user-images.githubusercontent.com/88579497/141877053-6cc315e8-2810-40ad-9c00-37865bee4c3c.png)

			

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
![스크린샷 2021-11-16 오전 9 55 31](https://user-images.githubusercontent.com/88579497/141877070-8d39618e-9a85-42d0-8512-c73c57fe339c.png)
![스크린샷 2021-11-16 오전 9 56 24](https://user-images.githubusercontent.com/88579497/141877072-b54f4ab1-1d56-46d1-82ab-4459efa73bf0.png)

			
