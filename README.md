# QR
**详细参数**

text: 二维码对应的网址

e  : 容错级别(errorLevel)，可选参数如下(缺省值 L)：

     L水平 7%的字码可被修正
     M水平 15%的字码可被修正
     Q水平 25%的字码可被修正
     H水平 30%的字码可被修正
     
p  : 二维码尺寸，可选范围1-10(具体大小和容错级别有关)（缺省值：5）

m  : 二维码白色边框尺寸,缺省值: 2

常规请求方法：http://你的域名/api.php?e=L&p=5&m=2&text=二维码内容
