```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>tag03</title>
</head>
<body>
<h1>1개의 이미지를 여러 곳으로 링크 걸<img src="../img/jeju_map.jpg" usemap="#jejuMap"/>


<pre>
    map태그, area태그
    shape : 링크모양(rect, circle, poly)
    coords : 좌표
    href : 이동할 페이지    
</pre>

<!-- map태그는 항상 맨 마지막에 (픽셀 크기때문에 밀릴 수도 있어서) -->
<map name="jejuMap">
    <!-- 사각형            좌표순서: x1,y1,x2,y2 -->
    <area shape="rect"    coords="170,115,300,160"
          href="https://www.airport.co.kr/jeju/index.do" target="_blank" title="제주국제공항"/>
    <area shape="circle"    coords="330,260,50"
          href="https://visithalla.jeju.go.kr/main/main.do" target="_blank" title="한라산국립공원"/>
    <!-- 다각형            좌표순서: x1,y1,x2,y2,x3,y3....계속 필요한만큼 들어간다. 단, 시작 정하고 시계방향으로 설정해야한다. -->
    <area shape="poly"    coords="70,210,160,240,100,270,10,265"
          href="../index.html" target="_blank" title="협재해수욕장"/>
</map>

</body>
</html>

</body>
</html>
```
