#目录文档
 * @描述: 一个scss的函数库
 * @作者: chenjiujiu
 * @创建日期: 2018/3/21
###全局参数设置
$unit   ---->   全局单位   ---->px/em/rem;  <br/>
$ieLow   ---->   IE678兼容开关   ---->true/false;    <br/>
$browsers   ---->   浏览器前缀集合   ---->webkit moz ms o;   <br/>
$prefixOpen   ---->   前缀开关   ---->true/false;  <br/>
$prefixW   ---->   谷歌前缀   ---->true/false;  <br/>
$prefixM   ---->   火狐前缀   ---->true/false;  <br/>
$prefixI   ---->   IE前缀   ---->true/false;  <br/>
$prefixO   ---->   opera前缀   ---->true/false;  <br/>
###函数
allBrowser()   ---->  判断是否需要全兼容  ---->  返回true/false; <br/>
isNum($num)   ---->   判断num是否为数值型   ---->返回true/false;  <br/>
testUnit($args)   ---->   检查参数是否带有单位   ---->返回添加单位后的参数;  <br/>
addUnit($args)   ---->   给参数添加单位   ---->返回添加单位后的参数;  <br/>
###字体
f   ()   ---->   字体综合属性    ----> 1~n个值;  <br/>
fz  ()---->   字体大小  ----> 数值;  <br/>
ff  ()---->   字体样式  ----> 字体样式;  <br/>
c   ()---->   前景色  ----> 颜色,hover颜色(默认无);  <br/>
fs  ()---->   字体样式  ----> 倾斜 加粗等;  <br/>
fw  ()---->   字体粗细  ----> 0～700;  <br/>
fi  ---->   文本斜体  ---->   无;  <br/>
fw-no   ---->   去除文字加粗 <br/>
fs-no   ---->   去除文字样式 <br/>
lh ()   ---->   设置行高  ----> 数值;  <br/>
f-no    ---->   恢复正常文字 <br/>
###文本
overDot   ---->   1行超出显示...   ;  <br/>
overDot-M   ()   ---->   多行超出显示...   ---->  显示的行数;  <br/>
break   ---->   强制断行  <br/>
wd-wp   ()   ---->   断行   ---->  断行风格;  <br/>
tin ()   ---->   文本缩进   ---->-999-999;  <br/>
thi ()   ---->   隐藏文字 <br/>
show-pic    ()   ---->   显示图片   ---->图片,x,y;  <br/>
tj  ()   ---->   单词间隔 <br/>
ta  ()   ---->   文字对齐方式   ---->对齐,间隔;  <br/>
tal   ---->   文字居左   <br/>
tar  ---->   文字居右    <br/>
tac  ---->   文字居中    <br/>
td  ---->   文本样式   ---->样式;  <br/>
line-top   ---->   上划线;  <br/>
line-del    ---->   删除线;  <br/>
line-bot   ---->   下划线;  <br/>
line-bli   ---->   闪烁;  <br/>
line-no  ---->   取消下划线;  <br/>
beauty-pla   () ---->   美化占位符   ---->字号,颜色，对齐  <br/>
beauty-sel  ()   ---->   美化选中文本   ---->背景，前景;  <br/>
###CSS3
0   ---->   0   ---->返回true/false;  <br/>

###浮动
0   ---->   0   ---->返回true/false;  <br/>

###C3动画
0   ---->   0   ---->返回true/false;  <br/>

###定位
0   ---->   0   ---->返回true/false;  <br/>

###间距/填充
0   ---->   0   ---->返回true/false;  <br/>

###宽高
0   ---->   0   ---->返回true/false;  <br/>

###缩写
0   ---->   0   ---->返回true/false;  <br/>

###背景
0   ---->   0   ---->返回true/false;  <br/>

###块
0   ---->   0   ---->返回true/false;  <br/>

###零碎项
0   ---->   0   ---->返回true/false;  <br/>

###样式重置






