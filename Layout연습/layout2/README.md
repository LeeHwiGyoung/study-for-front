<h1> layout2에서 추가로 사용된 부분</h1> <br>
<h5>layout1에서 사용한 float:left로 영역깨짐이 발생하면 그 밑의 블록에 다 float:left 속성값을 주어야하는데
이를 해결하기 위한 방법중 하나로 clear : both라는 속성이 있다.<br>
clear는 속성값으로 left ,right ,both , none 을 갖고 있는데 각각 차례대로 
float left 취소 ,right 취소, left right 취소 , clear 값 설정 안 함과 같다.</h5>
<img width="1021" alt="스크린샷 2022-08-04 오후 5 24 50" src="https://user-images.githubusercontent.com/77186025/182800382-5b995a51-119c-45f4-b0a4-3eba391c8388.png"> 
<h5> footer 박스의 다음으로 나오는 박스의 경우에 어떻게 영향을 받나 확인을 해봤는데 footer에 clear를 하면 test에서는 clear 값을 주지 않아도 영역깨짐이 발생하지 않았다.</h5>
<img width="1021" alt="스크린샷 2022-08-04 오후 5 27 29" src="https://user-images.githubusercontent.com/77186025/182800918-7cc19d09-fd76-41b7-a6c9-44a0e7a8fa35.png">
<h5>그러나 float : left로 footer의 영역깨짐을 해결해주었을 때는 그 뒤에 생기는 박스가 영역깨짐이 발생하였다. </h5>
