### Frog游戏对flex布局练习
#### 第一关
```
/*容器的排列方向水平逆序*/
flex-direction:row-reverse
```
![](leanote://file/getImage?fileId=59b66377198a884933000003)

----------


![](leanote://file/getImage?fileId=59b66380198a884933000004)
#### 第二关
```
/*富裕空间在两边*/
justify-content:center;
```
![](leanote://file/getImage?fileId=59b663e5198a884933000005)

----------
![](leanote://file/getImage?fileId=59b663f1198a884933000006)

#### 第三关
```
/*富裕空间在项目两边*/
justify-content:space-around
```
![](leanote://file/getImage?fileId=59b66446198a884933000007)

----------
![](leanote://file/getImage?fileId=59b66455198a884933000008)

#### 第四关
```
/*富裕空间在项目之间*/
justify-content:space-between
```
![](leanote://file/getImage?fileId=59b664a1198a884933000009)

----------
![](leanote://file/getImage?fileId=59b664aa198a88493300000a)

#### 第五关
```
/*富裕空间在侧轴的反方向*/
align-items:flex-end
```
![](leanote://file/getImage?fileId=59b66501198a88493300000b)

----------
![](leanote://file/getImage?fileId=59b6650a198a88493300000c)

#### 第六关
```
/*富裕空间分别在主轴侧轴的两边*/
justify-content:center;
align-items:center;
```
![](leanote://file/getImage?fileId=59b66569198a88493300000d)

----------
![](leanote://file/getImage?fileId=59b66572198a88493300000e)

#### 第七关
```
/*主轴上富裕空间在项目两边，侧轴上富裕空间在侧轴的反方向*/
justify-content:space-around;
align-items:flex-end;
```
![](leanote://file/getImage?fileId=59b665c4198a88493300000f)

----------
![](leanote://file/getImage?fileId=59b665cd198a884933000010)

#### 第八关
```
/*主轴上容器排列方向的逆序*/
flex-direction:row-reverse;
```
![](leanote://file/getImage?fileId=59b66678198a884933000011)

----------
![](leanote://file/getImage?fileId=59b66682198a884933000012)

#### 第九关
```
/*容器的布局方向 主轴为Y轴*/
flex-direction:column;
```
![](leanote://file/getImage?fileId=59b666f8198a884933000013)

----------
![](leanote://file/getImage?fileId=59b66706198a884933000014)

#### 第十关
```
/*容器的排列方向在主轴上逆序排列 富裕空间在主轴的反方向*/
flex-direction:row-reverse;
justify-content:flex-end;
```
![](leanote://file/getImage?fileId=59b6670f198a884933000015)

----------
![](leanote://file/getImage?fileId=59b66719198a884933000016)

#### 第十一关
```
/*容器的布局方向确定主轴为Y轴 富裕空间在主轴的反方向*/
flex-direction:column;
justify-content:flex-end;
```
![](leanote://file/getImage?fileId=59b6677a198a884933000017)

----------
![](leanote://file/getImage?fileId=59b66784198a884933000018)

#### 第十二关
```
/*容器主轴确定为Y轴且排列空间为逆序排列 富裕空间在项目之间*/
flex-direction:column-reverse;
justify-content:space-between;
```
![](leanote://file/getImage?fileId=59b667e0198a884933000019)

----------
![](leanote://file/getImage?fileId=59b667e9198a88493300001a)

#### 第十三关
```
/*主轴为X轴逆序排列 主轴的富裕空间在两边 侧轴的富裕空间在反方向*/
flex-direction:row-reverse;
justify-content:center;
align-items:flex-end;
```
![](leanote://file/getImage?fileId=59b66a47198a884933000028)

----------
![](leanote://file/getImage?fileId=59b66a50198a884933000029)

#### 第十四关
```
/*黄色的调到第三位*/
order:3;
```
![](leanote://file/getImage?fileId=59b66a91198a88493300002a)

----------
![](leanote://file/getImage?fileId=59b66a9c198a88493300002b)

#### 第十五关
```
order:-1
```
![](leanote://file/getImage?fileId=59b66ae1198a88493300002c)

----------
![](leanote://file/getImage?fileId=59b66aea198a88493300002d)

#### 第十六关
```
/*对齐flex中的项目 覆盖align-items的值*/
align-self:flex-end;
```
![](leanote://file/getImage?fileId=59b66b2c198a88493300002e)

----------
![](leanote://file/getImage?fileId=59b66b35198a88493300002f)

#### 第十七关
```
order:2;
align-self:flex-end;
```
![](leanote://file/getImage?fileId=59b66ba0198a884933000030)

----------
![](leanote://file/getImage?fileId=59b66ba9198a884933000031)

#### 第十八关
```
/*换行*/
flex-wrap:wrap;
```
![](leanote://file/getImage?fileId=59b66bb1198a884933000032)

----------
![](leanote://file/getImage?fileId=59b66bb9198a884933000033)

#### 第十九关
```
/*先调整主轴为Y轴  然后换行*/
flex-direction:column;
flex-wrap:wrap;
```
![](leanote://file/getImage?fileId=59b669f0198a884933000026)

----------
![](leanote://file/getImage?fileId=59b669f8198a884933000027)

#### 第二十关
```
/*使用flex-flow将flex-direction和flex-wrap简写*/
flex-flow:column wrap;
```
![](leanote://file/getImage?fileId=59b669a6198a884933000024)

----------

![](leanote://file/getImage?fileId=59b669b0198a884933000025)
#### 第二十一关
```
/*使用align-content将侧轴的富裕空间按侧轴的正方向排列*/
align-content:flex-start;
```
![](leanote://file/getImage?fileId=59b66957198a884933000022)

----------
![](leanote://file/getImage?fileId=59b66962198a884933000023)

#### 第二十二关
```
/*使用align-content将侧轴的富裕空间按侧轴的反方向排列*/
align-content:flex-end;
```
![](leanote://file/getImage?fileId=59b668da198a884933000020)

----------
![](leanote://file/getImage?fileId=59b668e4198a884933000021)

#### 第二十三关
```
/*确定主轴以及排列方向 然后将侧轴用align-content:center容器中心填充*/
flex-direction:column-reverse;
align-content:center;
```
![](leanote://file/getImage?fileId=59b66889198a88493300001e)

----------
![](leanote://file/getImage?fileId=59b66896198a88493300001f)

#### 第二十四关
```
/*确定主轴以及换行方向切均为逆序
  主轴的富裕空间在两边
  侧轴的富裕空间在项目之间
*/
flex-flow:column-reverse wrap-reverse;
justify-content:center;
align-content:space-between;
```
![](leanote://file/getImage?fileId=59b66832198a88493300001b)

----------

![](leanote://file/getImage?fileId=59b66841198a88493300001d)
###GitHub首页
https://github.com/jiarongGitHub



