# nctuLinear 
## Lecture1
[Lec01-簡介](https://www.youtube.com/watch?v=AfY1ak89fwU&list=PLX-rcsgr94FwFmgWimK21VJ9BFefZMIEZ)
<br>
[Lec01 ex](https://github.com/r07521706/nctuLinear/tree/master/lecture1-part2)
* introuduction
* 線性函數
    *     高中學的那些都不是ex.f(x) = sin(x)  f(x)=x**2
          f(努力)=成果 一分的努力得到 0.01 的成果 二分的努力得到 0.02的成果
    *     線性函數定義在有限維的線性空間=>與矩陣有關係
          線性函數作用在向量空間可用矩陣表示
          (工學院 常常不解釋向量空間就直接用矩陣了)
* 向量空間(VS virtual space)
    *     線性函數的故鄉(定義在這上面)
    *     要滿足十個條件(可以想成平面向量的集合)
    *     要有三個東西
          V: a set,a vector space over a field F
          F: Field-體(實數,有理數,複數)
              所有實數所成的集合是一個體
              所有有理數的集合也是一個體
              所有複數的集合也是一個體
              but 所有整數的集合不是一個體
              **F裡面的元素叫做scalar**
          運算性質: +號表示向量加向量
                    * 號(乘號表示 向量乘實數 or 向量乘複數)
                      (scalar multiplication)
                      
* 十大條件
    *     (vs-1)加法有封閉性:向量加向量還是向量
    *     (vs 0)純量乘法有封閉性:a 屬於 F , x 屬於 V ;ax還是屬於V
    *     (vs 1)可交換性 x+y = y+x 當x,y屬於V
    *     (vs 2)向量之間可以結合 (x+y)+z = x+(y+z) 當 x,y,z屬於向量
           注意這個性質:不是每一個都可以成立
           ex:1-1+1-1+1-1....結合方式不一樣的話就會不一樣 ans可以是0 or 1
    *     (vs 3) 存在加法的單位元素 (要有零向量)
           即:存在 0 屬於 V 使得 0+x = x for all x 屬於 V (0向量就是加法的單位元素)
    *     (vs 4)存在加法的反元素:存在y屬於V 使得 x+y=0 for any x 屬於 V
    *     (vs 5)存在乘法的單位元素:存在1屬於F 使得 1x=x for all x 屬於 V
    *     (vs6,vs7,vs8)純量和向量的分配律
    *     (vs 6) a(bx)=(ab)x,for all x屬於V,a,b屬於F
    *     (vs 7) a(x+y) = ax+ay , for all x,y 屬於V and a 屬於F
    *     (vs 8) (a+b)x = ax+bx , for all x 屬於 V and a,b屬於F
**若能滿足 則我們可以說 a vector space over a field F**
