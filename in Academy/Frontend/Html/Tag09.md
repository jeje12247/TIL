```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Insert title here</title>
</head>
<body>
<h1>Audio 재생하기</h1>
<pre>
    src : 재생할 사운드파일
    autoplay : 자동재생
    loop : 반복 (숫자 상관없이 무한루프가 된다.)
    preload : 전송완료 후 재생
</pre>
<audio src="../audio_video/Kalimba.mp3" controls autoplay loop="2"></audio>

<audio controls>
    <source src="../audio_video/Kalimba.mp3" type="audio/mp3"/>
    <source src="../audio_video/Kalimba.ogg" type="audio/ogg"/> <!-- 위에 mp3가 안왰을때 ogg가 실행되게 함 -->
</audio>

<img src="../img/02.jpg"/>
</body>
</html>
```
