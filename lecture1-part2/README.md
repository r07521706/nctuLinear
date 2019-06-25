# 判斷是否為向量空間

*    當F是複數的時候?
*       V={(a,b):a,b 屬於實數}
        F=C(複數)
        Is V a vector space over the Filed C ?
        ans:(x)
        因為 當x屬於V ,a屬於F,a * x 其值有可能超出實數域
        進入複數域 此時 我們違反vs0
        
*       V={(a,b):a,b 屬於複數}
        F=C(複數)
        Is V a vector space over the Filed C ?
        ans:(V)
        因為 當x屬於V ,a屬於F,a * x 其值都在複數域

*       Ex1當 加法 減法的定義 不同的時候 會導致vs不成立
        ex: 定義 x+y = (x1+y1,x2-y2)
        在這個情況下會發現不滿足 vs0 因為 x+y != y+x
        
        ans:不是vs
        
*       Ex2 (要建立向量空間 要先定好 V,F,+,*)
        V={(a1,a2...an),ai屬於 R ,1<= i <= n}
        F=R
        + :a,b 屬於 V a+b=(a1+b1,a2+b2,....,an+bn) where b = (b1,b2...bn)
        * :alpha 屬於 R ,a 屬於 V ,define alpha * a=(alpha * a1,alpha * a2 , ... ,alpha * an)
        
        ====================================
        ans:這是vs
        因為V算是比較嚴格的條件 如果V是Q(有理數)此時就會失敗了
        在知道是vs的條件下 我們可以寫成 
        V=F**n ; V=R**n
        意思為 F**n is vector space over the R (架構於實數域的向量空間)
       
