```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Insert title here</title>
</head>
<body>
    <h1>행렬의 수가 다른 표 만들기</h1>
    <!-- 
        colspan : 칸을 합친다.
        rowspan : 줄을 합친다.
     -->
     <table border="1">
         <tr>
             <td>AAAAAA</td>
             <td>BBBBBB</td>
             <td colspan="2">CCCCCC</td>
         </tr>
         <tr>
             <td colspan="2">DDDDDD</td>
             <td>EEEEEE</td>
             <td>FFFFFF</td>
         </tr>
         <tr>
             <td>GGGGGG</td>
             <td rowspan="2">HHHHHH</td>
             <td rowspan="2">IIIIII</td>
             <td>JJJJJJ</td>
         </tr>
         <tr>
             <td>KKKKKK</td>
             <td>LLLLLL</td>
         </tr>


     </table>

</body>
</html>
```
