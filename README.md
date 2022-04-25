# html2canvas
用于直接在用户浏览器上截取网页或其一部分的“屏幕快照”<br>
普通属性<br>
data-html2canvasid	屏幕截图元素的唯一id值	dds<br>
data-html2canvasset	设置是否用变量截图(配合控制属性data--html2canvasstart使用)	true/false<br>
data-cutdown	设置是否用压缩截图(配合属性data-maxwidth使用)	true/false<br>
data-maxwidth	设置压缩截图宽度(配合控制属性data-cutdown使用，必填项)	500<br>
data-html2canvasscale	设置截图元素截图清晰度在pc端还是移动端使用，1代表pc端，2代表移动端	1/2<br>
控制属性<br>
data--html2canvasstart	设置变量截图(如果设置是(true)则用变量截图,配合data-html2canvasset使用)	true/false<br>
输出属性<br>
data-x-html2canvas	输出截图的base64图片格式<br>
