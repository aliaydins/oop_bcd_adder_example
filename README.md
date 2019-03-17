### oop_bcd_adder_example 

using oop create bcd adder <br>

![](https://github.com/aliaydins/oop_bcd_adder_example/blob/master/BCD-Adder.png)


adder1 [10001 0111] that is 1001 + 0111 binary collection + carry  =1  adder out : 0000  <br>
and1 gate= x3+x2 (0+0) =0 carry out =0 <br>
<br>
and2 gate =x1+x0 (0+0) =0 carry out =0 <br>
<br>
or1 gate =and1 out + and2 out (0+0) =0 <br>
<br>
or2 gate =or1 gate + carry out (0 + 1) = 1  <br>

adder2 out : <br>
s3=(adder1 out x3 + 0) : 0+0 = 0 <br>

s2=(adder1 out x2 + carry out ) : 0+1 =1 <br>

s1=(adder1 out x1 + carry out ) : 0+1 =1 <br>

s0= (adder1 out x0 + 0)  : 0 +0 = 0 <br>

so adder 2 carry out 0 




![](https://github.com/aliaydins/oop_bcd_adder_example/blob/master/exe.png)
