#css-name

>CSS 命名规范


##CSS class 命名方案

###原子类

```css
/* font-style */
.n{font-weight:normal; font-style:normal;}.b{font-weight:bold;}.i{font-style:italic;}
/* text-align */
.tc{text-align:center;}.tr{text-align:right;}.tl{text-align:left;}.tj{text-align:justify;}
/* text-decoration */
.tdl{text-decoration:underline;}.tdn,.tdn:hover,.tdn a:hover,a.tdl:hover{text-decoration:none;}
/* letter-spacing */
.lt-1{letter-spacing:-1px;}.lt0{letter-spacing:0;}.lt1{letter-spacing:1px;}
/* white-space */
.nowrap{white-space:nowrap;}
/* word-wrap */
.bk{word-wrap:break-word;}
/* vertical-align */
.vm{vertical-align:middle;}.vtb{vertical-align:text-bottom;}.vb{vertical-align:bottom;}.vt{vertical-align:top;}.vn{vertical-align:-2px;}
/* clear */
.cl{clear:both;}
/* position */
.rel{position:relative;}.abs{position:absolute;}
/*z-index*/
.zx1{z-index:1;}.zx2{z-index:2;}
/* cursor */
.poi{cursor:pointer;}.def{cursor:default;}
/* overflow */
.ovh{overflow:hidden;}.ova{overflow:auto;}
/* visibility */
.vh{visibility:hidden;}.vv{visibility:visible;}
/* zoom */
.z{*zoom:1;}
```

###工具类

```css

/*浮动*/
.fl{float:left;}.fr{float:right;}
/*清除浮动*/
.clearfix{
    *zoom:1;
}
.clearfix:before,.clearfix:after {
    display: table;
    content: '';
}
.clearfix:after {
    clear: both;
    overflow: hidden;
}
/*显示*/
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
  visibility: hidden !important;
}
/*响应式图片*/
.img-responsive {
  display: block;
  height: auto;
  max-width: 100%;
}
/*圆形图片*/
.img-circle {
  border-radius: 50%;
}
/* 块状元素水平居中 */
.auto{margin-left:auto; margin-right:auto;}
/* 基于display:table-cell的自适应布局 */
.cell{display:table-cell; *display:inline-block; width:2000px; *width:auto;}
/* 双栏自适应cell部分连续英文字符换行 */
.cell_bk{display:table; width:100%; table-layout:fixed; word-wrap:break-word;}
/* 单行文字溢出虚点显 示*/
.ell{text-overflow:ellipsis; white-space:nowrap; overflow:hidden;}
/* css3过渡动画效果 */
.trans{
    -webkit-transition:all 0.3s;    
            transition:all 0.3s;
}
/* 大小不定元素垂直居中 */
.dib_vm{display:inline-block; width:0; height:100%; vertical-align:middle;}
/* 加载中背景图片 - 如果您使用该CSS小库，务必修改此图片地址 */
.loading{background:url(http://www.zhangxinxu.com/study/image/loading.gif) no-repeat center;}
/* 无框文本框文本域 */
.bd_none{border:0; outline:none;}
/* 绝对定位隐藏 */
.abs_out{position:absolute; left:-999em; top:-999em;}
.abs_clip{position:absolute; clip:rect(0 0 0 0);}
/* 按钮禁用 */
.disabled{color:#acacac!important; border-color:#acacac!important; text-shadow:1px 1px #fff!important; outline:0!important; cursor:default!important; pointer-events:none;}
.disabled:hover{text-decoration:none!important;}
```
###模块类

```
导航菜单：nav-menu
轮播图：carousel
模式视图：modal
按钮：btn
下拉菜单：dropdown-menu
分页导航：pagination
工具提示：tooltips
分享工具：share
提示窗口：alert
进度条：progress-bar
用户头像：avtar
卡片：card
面板：panel
图片：img
```


###名称类


```
头：header
内容：content .container
尾：footer
导航：nav
侧栏：sidebar
栏目：column
页面外围布局：wrapper
左右中：left right center
登录条：loginbar
标志：logo
广告：banner
页面主体：main
热点：hot
新闻：news
下载：download
子导航：subnav
菜单：menu
子菜单：submenu
搜索：search
友情链接：friendlink
页脚：footer
版权：copyright
滚动：scroll
内容：content
标签页：tab
文章列表：list
提示信息：msg
小技巧：tips
栏目标题：title
加入：joinus
指南：guild
服务：service
注册：regsiter
状态：status
投票：vote
合作伙伴：partner
```


###CSS 文件命名

```
主要   master.css
模块   module.css
公用   base.css
布局   layout.css
主题   themes.css
专栏   columns.css
文字   font.css
图标   icon.css
表单   forms.css
补丁   mend.css
打印   print.css
```


