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
allBrowser ()   ---->  判断是否需要全兼容  ---->  返回true/false; <br/>
isNum($num)   ---->   判断num是否为数值型   ---->返回true/false;  <br/>
testUnit ($args)   ---->   检查参数是否带有单位   ---->返回添加单位后的参数;  <br/>
addUnit ($args)   ---->   给参数添加单位   ---->返回添加单位后的参数;  <br/>
###字体
f ()   ---->   字体综合属性    ----> 1~n个值;  <br/>
fz ()---->   字体大小  ----> 数值;  <br/>
ff ()---->   字体样式  ----> 字体样式;  <br/>
c ()---->   前景色  ----> 颜色,hover颜色(默认无);  <br/>
fs ()---->   字体样式  ----> 倾斜 加粗等;  <br/>
fw ()---->   字体粗细  ----> 0～700;  <br/>
fi  ---->   文本斜体  ---->   无;  <br/>
fw-no   ---->   去除文字加粗 <br/>
fs-no   ---->   去除文字样式 <br/>
lh ()   ---->   设置行高  ----> 数值;  <br/>
f-no    ---->   恢复正常文字 <br/>
###文本
overDot   ---->   1行超出显示...   ;  <br/>
overDot-M ()   ---->   多行超出显示...   ---->  显示的行数;  <br/>
break   ---->   强制断行  <br/>
wd-wp ()   ---->   断行   ---->  断行风格;  <br/>
tin ()   ---->   文本缩进   ---->-999-999;  <br/>
thi ()   ---->   隐藏文字 <br/>
show-pic ()   ---->   显示图片   ---->图片,x,y;  <br/>
tj ()   ---->   单词间隔 <br/>
ta ()   ---->   文字对齐方式   ---->对齐,间隔;  <br/>
tal   ---->   文字居左   <br/>
tar  ---->   文字居右    <br/>
tac  ---->   文字居中    <br/>
td  ---->   文本样式   ---->样式;  <br/>
line-top   ---->   上划线;  <br/>
line-del    ---->   删除线;  <br/>
line-bot   ---->   下划线;  <br/>
line-bli   ---->   闪烁;  <br/>
line-no  ---->   取消下划线;  <br/>
beauty-pla () ---->   美化占位符   ---->字号,颜色，对齐  <br/>
beauty-sel ()   ---->   美化选中文本   ---->背景，前景;  <br/>
###CSS3
c3Pre ()   ---->   css3前缀   ---->样式名,样式内容    ;  <br/>
cnt ()   ---->   内容   ---->内容    ;  <br/>
trs ()   ---->   过渡   ---->过渡属性    ;  <br/>
trs-p ()   ---->   过度属性   ---->属性    ;  <br/>
trs-d ()   ---->   过度时间   ---->时间    ;  <br/>
trs-fun ()   ---->   过渡效果   ---->效果    ;  <br/>
trs-del ()   ---->   过度延迟时间   ---->时间    ;  <br/>
bd-r ()   ---->   css3圆角   ---->大小    ;  <br/>
box-s ()   ---->   阴影   ---->阴影    ;  <br/>
txt-s ()   ---->   文字阴影   ---->阴影    ;  <br/>
box-s-no ()   ---->   去除阴影      ;  <br/>
txt-s-no ()   ---->   去除文字阴影      ;  <br/>
usr-s ()   ---->   是否允许用户选中文本   ---->文本    ;  <br/>
user-s-no ()   ---->   禁止文本被选择      ;  <br/>
tsf ()   ---->   transform   ---->值    ;  <br/>
tsf-o ()   ---->   元素的基点位置   ---->值    ;  <br/>
tsf-s ()   ---->   3D 转换   ---->preserve-3d默认    ;  <br/>
bf-v ()   ---->  隐藏背面;   ---->hidden   ;  <br/>
pep ()   ---->   视距   ---->none    ;  <br/>
pep-o ()   ---->   3D 元素的基点位置   ---->50% 50%    ;  <br/>
pep-o-x ()   ---->   3D 元素的基点X位置   ---->值   ;  <br/>
pec-o-y ()   ---->   3D 元素的基点Y位置   ---->值   ;  <br/>
rotate ()   ---->   旋转   ---->角度    ;  <br/>
pe ()   ---->   禁用元素事件   ---->none    ;  <br/>
filter ()   ---->   filter   ---->值    ;  <br/>
blur ()   ---->   模糊   ---->数值    ;  <br/>
grayscale ()   ---->   将彩色照片显示为黑白照片;   ---->百分比    ;  <br/>

###浮动
float ()   ---->   浮动   ---->方向;  <br/>
fl ()   ---->   左浮动 <br/>
fr ()   ---->   右浮动 <br/>
clearfix ()   ---->   清除浮动  <br/>

###C3动画
keyf ()   ---->   关键帧   ---->动画名;  <br/>
ani ()   ---->   animation动画   ---->动画属性;  <br/>
ani-name ()   ---->   动画   ---->动画名;  <br/>
ani-time ()   ---->   一个周期所需要的时间   ---->time;  <br/>
ani-style ()   ---->   速度形式   ---->形式;  <br/>
ani-num ()   ---->   播放次数   ---->次数;  <br/>
ani-dir ()   ---->   轮流反向播放动画   ---->normal/alternate;  <br/>
ani-play ()   ---->   "播放"或"暂停"   ---->动画名;  <br/>
ani-del ()   ---->   延迟时间   ---->时间;  <br/>
ani-fill ()   ---->   运动完成后的状态    ---->状态;  <br/>
trf-fix ()   ---->   三维闪动 bug 处理;  <br/>

###定位
position_each   ( $args )   ---->   遍历数组该值有没该单位   ---->有单位的值;  <br/>
pos ()   ---->   定位   ---->定位种类,定位值;  <br/>
abs ()   ---->   绝对定位   ---->值;  <br/>
rel ()   ---->   相对定位   ---->值;  <br/>
fix ()   ---->   固定定位:   ---->值;  <br/>
z   ()   ---->   层级   ---->值;  <br/>z
t   ()   ---->   top值  ---->值;  <br/>
l   ()   ---->   left值   ---->值;  <br/>
b   ()   ---->   bottom值   ---->值;  <br/>
r   ()   ---->  right值;   ---->值;  <br/>
tl  ()   ---->   top/left值   ---->值;  <br/>
tr  ()   ---->   top/right值;   ---->值;  <br/>
bl  ()   ---->   bottom/left值;   ---->值;  <br/>
br  ()   ---->   //bottom/right值;   ---->值;  <br/>
trbl()   ---->  top/left/bottom/right值;   ---->返回true/false;  <br/>


###间距/填充
mg ()   ---->   margin   ----> 大小 <br/>
pd ()   ---->   padding   ----> 大小<br/>
mgt ()   ---->   上margin   ----> 大小 <br/>
mgr ()   ---->  右margin   ----> 大小 <br/>
mgb ()   ---->   下margin   ----> 大小 <br/>
mgl ()   ---->   左margin   ----> 大小 <br/>
mgtb ()   ---->   上下margin   ----> 宽度,宽度 <br/>
mglr ()   ---->   左右margin   ----> 宽度,宽度 <br/>
pdr ()   ---->   右padding   ----> 大小 <br/>
pdb ()   ---->   下padding   ----> 大小 <br/>
pdl ()   ---->   左padding   ----> 大小 <br/>
pdtb ()   ---->  上下margin   ----> 宽度,宽度 <br/>
pdlr ()   ---->   左右margin   ----> 宽度,宽度<br/>

###宽高
0   ---->  margin   ---->返回true/false;  <br/>

###缩写
0   ---->  padding   ---->返回true/false;  <br/>

###背景
0   ---->   #e94333   ---->返回true/false;  <br/>

###块
db ()   ---->   块  ---->true/false;  <br/>
dn ()   ---->   隐藏   ---->true/false;  <br/>
din   ---->   行内    <br/>
dinb   ---->   行内快  <br/>
dtb   ---->   table     <br/>
bsz   ---->   怪异盒模型   ---->border-box/content-box;  <br/>

###零碎项
vertical-align ()   ---->   垂直对齐方式   ---->对齐方式;  <br/>
vat   ---->   顶端对齐 <br/>
vac   ---->   中间对齐  <br/>
vab   ---->   底部对齐   <br/>
ofh   ---->   超出隐藏   <br/>
ofv   ---->   超出显示   <br/>
cu ()   ---->   鼠标样式   ---->样式;  <br/>
cup   ---->小手  <br/>
cud   ----> 默认 <br/>
cun   ----> 隐藏 <br/>
opa ()   ---->   透明度   ---->0~1;  <br/>
no-resize  ---->   禁止拖动大小  <br/>

###样式重置
reset  ---->   重置  <br/>






