# DiagonalRotateAnimation
Android animation

matrix2.setConcat(matrix, matrix2);//图顺时针旋转45度和X轴旋转相加
matrix2.setConcat(matrix3, matrix2);//在之前的基础上图和X轴都逆时针旋转45度
这两个的作用刚开始是图形如图
![first](https://github.com/ckenergy/DiagonalRotateAnimation/tree/master/image/first.png) 
matrix2.setConcat(matrix, matrix2);//图顺时针旋转45度和X轴旋转相加
加上这步以后图就变成这样
![second](https://github.com/ckenergy/DiagonalRotateAnimation/tree/master/image/second.jpg) 
![second](https://github.com/ckenergy/DiagonalRotateAnimation/tree/master/image/11.gif) 
这时还是沿着X轴翻转，只不过图逆时针旋转45度
然后这时在加上顺时针旋转45度
matrix2.setConcat(matrix3, matrix2);//在之前的基础上图和X轴都逆时针旋转45度
变成了
![thrid](https://github.com/ckenergy/DiagonalRotateAnimation/tree/master/image/Thrid.png) 
![thrid](https://github.com/ckenergy/DiagonalRotateAnimation/tree/master/image/22.gif) 
