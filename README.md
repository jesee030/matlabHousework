# matlabHousework

# 1

## .1)<img src="file:///C:\Users\keyter\AppData\Roaming\Tencent\Users\853650711\QQ\WinTemp\RichOle\S8UAFCBC7@[V%G{KCBZ%RN9.png" alt="img" style="zoom: 50%;" />

## 2）<img src="file:///C:\Users\keyter\AppData\Roaming\Tencent\Users\853650711\QQ\WinTemp\RichOle\0T[MCO1XQ$FOGHO]VQ3{3`I.png" alt="img" /><img src="file:///C:\Users\keyter\AppData\Roaming\Tencent\Users\853650711\QQ\WinTemp\RichOle\0T[MCO1XQ$FOGHO]VQ3{3`I.png" alt="img" style="zoom:50%;" />

## 3）<img src="file:///C:\Users\keyter\AppData\Roaming\Tencent\Users\853650711\QQ\WinTemp\RichOle\RIEYS683_JU4M1EIMRQSSM3.png" alt="img" style="zoom:50%;" />



## 4)![image-20210306114854817](housework01.assets/image-20210306114854817.png)

5）![img](file:///C:\Users\keyter\AppData\Roaming\Tencent\Users\853650711\QQ\WinTemp\RichOle\A[D[8176NM`P_S7UQK1SI`5.png)

6）![image-20210306114908201](housework01.assets/image-20210306114908201.png)

7）![img](file:///C:\Users\keyter\AppData\Roaming\Tencent\Users\853650711\QQ\WinTemp\RichOle\R2%@ZBZ[Y[}BYFQQU~TO[PQ.png)

# 2



```matlab
function[meter, hight] = ballBounce(hight_q,times)
hight = hight_q/2^times;
meter = 0;
if (times > 1)
    meter = meter + hight_q;
end
times=times-1;
while(times-2 > 0)
    meter=meter + 2*(hight_q/2);
    hight_q = hight_q / 2;
    times=times-2;
end
meter=meter + hight_q / 2;
end
```

![d73dcf2fd9de2947b763fecea44cc88](housework01.assets/d73dcf2fd9de2947b763fecea44cc88.png)

# 3

```
x=[-2*pi:0.1*pi:2*pi];
y=cos(tan(pi*x));
plot(x,y)
fplot(@(x)cos(tan(pi*x)))
```

![image-20210306114656221](housework01.assets/image-20210306114656221.png)

![image-20210306114717943](housework01.assets/image-20210306114717943.png)



# 4

```
x=linspace(-100,100);
y1=x.^2;
y2=x.^3;
y3=x.^4;
y4=x.^5;
plot(x,y1,x,y2,x,y3,x,y4);
legend({'y1=x.^2','y2=x.^3','y3=x.^4','y4=x.^5'},'Location','southwest')
```

![image-20210306114500591](housework01.assets/image-20210306114500591.png)
