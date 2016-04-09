# DiagonalRotateAnimation
Android animation

matrix2.setConcat(matrix, matrix2);//图顺时针旋转45度和X轴旋转相加<br>
matrix2.setConcat(matrix3, matrix2);//在之前的基础上图和X轴都逆时针旋转45度<br>
这两个的作用刚开始是图形如图<br>
![first](https://github.com/ckenergy/DiagonalRotateAnimation/blob/master/image/first.png) <br>
matrix2.setConcat(matrix, matrix2);//图顺时针旋转45度和X轴旋转相加<br>
加上这步以后图就变成这样<br>
![second](https://github.com/ckenergy/DiagonalRotateAnimation/tree/master/image/second.jpg) <br>
![second](https://github.com/ckenergy/DiagonalRotateAnimation/tree/master/image/11.gif) <br>
这时还是沿着X轴翻转，只不过图逆时针旋转45度<br>
然后这时在加上顺时针旋转45度<br>
matrix2.setConcat(matrix3, matrix2);//在之前的基础上图和X轴都逆时针旋转45度<br>
变成了<br>
![thrid](https://github.com/ckenergy/DiagonalRotateAnimation/tree/master/image/Thrid.png) <br>
![thrid](https://github.com/ckenergy/DiagonalRotateAnimation/tree/master/image/22.gif) 
