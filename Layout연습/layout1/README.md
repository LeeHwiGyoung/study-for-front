<h1>사용한 CSS 의미 정리</h1> <br>
width = 가로 영역<br>
height = 세로 영역<br>
margin : 0 auto => 위쪽 아래 0, 양 옆 가운데 정렬<br>
color : 글자의 색깔<br>
text-align : 글자의 정렬<br>
line-height : 문장과 문장 사이의 간격<br>
float : 이미지와 텍스트의 배치를 위해서 이미지를 띄우는 용도로 사용되었음 크기를 지정하여 레이아웃에서도 사용됨<br>
float 사용으로 인해 영역깨짐(height가 0이 되는 현상)이 발생하였는데 여기선 footer에 float:left를 줘서 해결하였다.<br>
그러나 float : left를 줘서 해결하는 방법은 불필요한 박스에도 float 속성을 주어야하며 구조가 복잡해질시 속성을 넣어야 하는 박스를 파악하기 어려워 비효율적이다.
