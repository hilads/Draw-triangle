# Draw-triangle
CSS Draw triangle

Relevant Problems in Drawing Triangle with CSS.   CSS画三角形的相关问题  

The Principle of Drawing Triangle.  CSS画三角形的原理

![image](https://github.com/hilads/Draw-triangle/blob/master/images/image.png)

画三角形的原理为利用div盒模型 通过设置div的4个border边的颜色宽度来达到的效果.

like this


div {

    width: 50px;
		
    height: 50px;
		
    border: 40px solid;
		
    border-color: orange blue red green;
}

show:
![image](https://github.com/hilads/Draw-triangle/blob/master/images/borderDiv.png)

如果我们把中间内容尺寸设为0 like this 

div {

    width: 0;
    
    height: 0;
    
    border: 40px solid;
    
    border-color: orange blue red green;
    
}

我们可以得到：

![image](https://github.com/hilads/Draw-triangle/blob/master/images/borderDiv1.png)

如果我们只要下面红色的三角形 we can do it 

like this

div {

    width: 0;
    
    height: 0;
    
    border: 40px solid;
    
    border-color: transparent transparent red;
    
}

将border的其他边的颜色设为透明，我们可以得到：

![image](https://github.com/hilads/Draw-triangle/blob/master/images/red.png)


