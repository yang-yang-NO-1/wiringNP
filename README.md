# 这是一个将香橙派的wiringOP库移植到nanopi Neo的程序，弥补nanopi官方库不能使用外部中断的影响，能力有限。
## 香橙派 zero plus2和nanopi neo的主控都为全志H3，而wiringNP库使用中断会直接返回wiringPiISR: Not implemented
![alt ]( 1.png)
## 其次，本库更改了iic函数，望后来者注意.