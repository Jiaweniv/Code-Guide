Code-Guide

标准开发灵活的、持久的和可持续的HTML和CSS,和可维护的JavaScript  


<html>

<head>
<meta http-equiv=Content-Type content="text/html; charset=gb2312">
<meta name=Generator content="Microsoft Word 15 (filtered)">
<title>网站设计制作规范手册</title>
<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:Helvetica;
	panose-1:2 11 6 4 2 2 2 2 2 4;}
@font-face
	{font-family:Courier;
	panose-1:2 7 4 9 2 2 5 2 4 4;}
@font-face
	{font-family:"Tms Rmn";
	panose-1:2 2 6 3 4 5 5 2 3 4;}
@font-face
	{font-family:Helv;
	panose-1:2 11 6 4 2 2 2 3 2 4;}
@font-face
	{font-family:"New York";
	panose-1:2 4 5 3 6 5 6 2 3 4;}
@font-face
	{font-family:System;
	panose-1:0 0 0 0 0 0 0 0 0 0;}
@font-face
	{font-family:Wingdings;
	panose-1:5 0 0 0 0 0 0 0 0 0;}
@font-face
	{font-family:"MS Mincho";
	panose-1:2 2 6 9 4 2 5 8 3 4;}
@font-face
	{font-family:Batang;
	panose-1:2 3 6 0 0 1 1 1 1 1;}
@font-face
	{font-family:宋体;
	panose-1:2 1 6 0 3 1 1 1 1 1;}
@font-face
	{font-family:PMingLiU;
	panose-1:2 1 6 1 0 1 1 1 1 1;}
@font-face
	{font-family:"MS Gothic";
	panose-1:2 11 6 9 7 2 5 8 2 4;}
@font-face
	{font-family:Dotum;
	panose-1:2 11 6 0 0 1 1 1 1 1;}
@font-face
	{font-family:黑体;
	panose-1:2 1 6 0 3 1 1 1 1 1;}
@font-face
	{font-family:MingLiU;
	panose-1:2 1 6 9 0 1 1 1 1 1;}
@font-face
	{font-family:Mincho;
	panose-1:2 2 6 9 4 3 5 8 3 5;}
@font-face
	{font-family:Gulim;
	panose-1:2 11 6 0 0 1 1 1 1 1;}
@font-face
	{font-family:Century;
	panose-1:2 4 6 4 5 5 5 2 3 4;}
@font-face
	{font-family:"Angsana New";
	panose-1:2 2 6 3 5 4 5 2 3 4;}
@font-face
	{font-family:"Cordia New";
	panose-1:2 11 3 4 2 2 2 2 2 4;}
@font-face
	{font-family:Mangal;
	panose-1:2 4 5 3 5 2 3 3 2 2;}
@font-face
	{font-family:Latha;
	panose-1:2 11 6 4 2 2 2 2 2 4;}
@font-face
	{font-family:Sylfaen;
	panose-1:1 10 5 2 5 3 6 3 3 3;}
@font-face
	{font-family:Vrinda;
	panose-1:2 11 5 2 4 2 4 2 2 3;}
@font-face
	{font-family:Raavi;
	panose-1:2 11 5 2 4 2 4 2 2 3;}
@font-face
	{font-family:Shruti;
	panose-1:2 11 5 2 4 2 4 2 2 3;}
@font-face
	{font-family:Sendnya;
	panose-1:0 0 4 0 0 0 0 0 0 0;}
@font-face
	{font-family:Gautami;
	panose-1:2 11 5 2 4 2 4 2 2 3;}
@font-face
	{font-family:Tunga;
	panose-1:2 11 5 2 4 2 4 2 2 3;}
@font-face
	{font-family:"Estrangelo Edessa";
	panose-1:3 8 6 0 0 0 0 0 0 0;}
@font-face
	{font-family:"Cambria Math";
	panose-1:0 0 0 0 0 0 0 0 0 0;}
@font-face
	{font-family:"Yu Gothic";
	panose-1:2 11 4 0 0 0 0 0 0 0;}
@font-face
	{font-family:等线;
	panose-1:2 1 6 0 3 1 1 1 1 1;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;}
@font-face
	{font-family:"Calibri Light";
	panose-1:2 15 3 2 2 2 4 3 2 4;}
@font-face
	{font-family:"Palatino Linotype";
	panose-1:2 4 5 2 5 5 5 3 3 4;}
@font-face
	{font-family:Verdana;
	panose-1:2 11 6 4 3 5 4 4 2 4;}
@font-face
	{font-family:"Arial Unicode MS";
	panose-1:2 11 6 4 2 2 2 2 2 4;}
@font-face
	{font-family:"等线 Light";
	panose-1:2 1 6 0 3 1 1 1 1 1;}
@font-face
	{font-family:"Segoe UI Emoji";
	panose-1:0 0 0 0 0 0 0 0 0 0;}
@font-face
	{font-family:微软雅黑;
	panose-1:2 11 5 3 2 2 4 2 2 4;}
@font-face
	{font-family:Cambria;
	panose-1:2 4 5 3 5 4 6 3 2 4;}
@font-face
	{font-family:"\@宋体";
	panose-1:2 1 6 0 3 1 1 1 1 1;}
@font-face
	{font-family:"\@微软雅黑";}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{margin:0cm;
	margin-bottom:.0001pt;
	text-align:justify;
	text-justify:inter-ideograph;
	font-size:10.5pt;
	font-family:"Times New Roman",serif;}
h1
	{mso-style-link:"标题 1 Char";
	margin-top:17.0pt;
	margin-right:0cm;
	margin-bottom:16.5pt;
	margin-left:0cm;
	text-align:justify;
	text-justify:inter-ideograph;
	line-height:240%;
	page-break-after:avoid;
	font-size:22.0pt;
	font-family:"Times New Roman",serif;
	font-weight:bold;}
h2
	{mso-style-link:"标题 2 Char";
	margin-top:13.0pt;
	margin-right:0cm;
	margin-bottom:13.0pt;
	margin-left:0cm;
	text-align:justify;
	text-justify:inter-ideograph;
	line-height:173%;
	page-break-after:avoid;
	font-size:16.0pt;
	font-family:"Cambria",serif;
	font-weight:bold;}
h3
	{mso-style-link:"标题 3 Char";
	margin-top:13.0pt;
	margin-right:0cm;
	margin-bottom:13.0pt;
	margin-left:0cm;
	text-align:justify;
	text-justify:inter-ideograph;
	line-height:172%;
	page-break-after:avoid;
	font-size:16.0pt;
	font-family:"Times New Roman",serif;
	font-weight:bold;}
h4
	{mso-style-link:"标题 4 Char";
	margin-top:14.0pt;
	margin-right:0cm;
	margin-bottom:14.5pt;
	margin-left:0cm;
	text-align:justify;
	text-justify:inter-ideograph;
	line-height:156%;
	page-break-after:avoid;
	font-size:14.0pt;
	font-family:"Cambria",serif;
	font-weight:bold;}
p.MsoHeader, li.MsoHeader, div.MsoHeader
	{margin:0cm;
	margin-bottom:.0001pt;
	text-align:center;
	layout-grid-mode:char;
	border:none;
	padding:0cm;
	font-size:9.0pt;
	font-family:"Times New Roman",serif;}
p.MsoFooter, li.MsoFooter, div.MsoFooter
	{margin:0cm;
	margin-bottom:.0001pt;
	layout-grid-mode:char;
	font-size:9.0pt;
	font-family:"Times New Roman",serif;}
p.MsoTitle, li.MsoTitle, div.MsoTitle
	{mso-style-link:"标题 Char";
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:3.0pt;
	margin-left:0cm;
	text-align:center;
	font-size:16.0pt;
	font-family:"Cambria",serif;
	font-weight:bold;}
a:link, span.MsoHyperlink
	{color:blue;
	text-decoration:underline;}
a:visited, span.MsoHyperlinkFollowed
	{color:purple;
	text-decoration:underline;}
p
	{margin-right:0cm;
	margin-left:0cm;
	font-size:12.0pt;
	font-family:宋体;}
code
	{font-family:宋体;}
pre
	{mso-style-link:"HTML 预设格式 Char";
	margin:0cm;
	margin-bottom:.0001pt;
	font-size:12.0pt;
	font-family:宋体;}
span.1Char
	{mso-style-name:"标题 1 Char";
	mso-style-link:"标题 1";
	font-weight:bold;}
span.Char
	{mso-style-name:"标题 Char";
	mso-style-link:标题;
	font-family:"Cambria",serif;
	font-weight:bold;}
p.lead, li.lead, div.lead
	{mso-style-name:lead;
	margin-right:0cm;
	margin-left:0cm;
	font-size:12.0pt;
	font-family:宋体;}
span.2Char
	{mso-style-name:"标题 2 Char";
	mso-style-link:"标题 2";
	font-family:"Cambria",serif;
	font-weight:bold;}
span.4Char
	{mso-style-name:"标题 4 Char";
	mso-style-link:"标题 4";
	font-family:"Cambria",serif;
	font-weight:bold;}
span.apple-converted-space
	{mso-style-name:apple-converted-space;}
span.HTMLChar
	{mso-style-name:"HTML 预设格式 Char";
	mso-style-link:"HTML 预设格式";
	font-family:宋体;}
span.cp
	{mso-style-name:cp;}
span.nt
	{mso-style-name:nt;}
span.na
	{mso-style-name:na;}
span.s
	{mso-style-name:s;}
span.c
	{mso-style-name:c;}
span.nc
	{mso-style-name:nc;}
span.o
	{mso-style-name:o;}
span.p
	{mso-style-name:p;}
span.k
	{mso-style-name:k;}
span.m
	{mso-style-name:m;}
span.n
	{mso-style-name:n;}
span.s2
	{mso-style-name:s2;}
span.sx
	{mso-style-name:sx;}
span.nb
	{mso-style-name:nb;}
span.c1
	{mso-style-name:c1;}
span.err
	{mso-style-name:err;}
span.nf
	{mso-style-name:nf;}
span.hljs-keyword
	{mso-style-name:hljs-keyword;}
span.hljs-number
	{mso-style-name:hljs-number;}
span.hljs-builtin
	{mso-style-name:hljs-built_in;}
span.hljs-comment
	{mso-style-name:hljs-comment;}
span.hljs-function
	{mso-style-name:hljs-function;}
span.hljs-title
	{mso-style-name:hljs-title;}
span.hljs-params
	{mso-style-name:hljs-params;}
span.hljs-string
	{mso-style-name:hljs-string;}
span.hljs-literal
	{mso-style-name:hljs-literal;}
span.hljs-doctag
	{mso-style-name:hljs-doctag;}
span.hljs-meta
	{mso-style-name:hljs-meta;}
span.3Char
	{mso-style-name:"标题 3 Char";
	mso-style-link:"标题 3";
	font-weight:bold;}
span.icon
	{mso-style-name:icon;}
p.masthead-links, li.masthead-links, div.masthead-links
	{mso-style-name:masthead-links;
	margin-right:0cm;
	margin-left:0cm;
	font-size:12.0pt;
	font-family:宋体;}
span.nd
	{mso-style-name:nd;}
span.kd
	{mso-style-name:kd;}
span.nx
	{mso-style-name:nx;}
span.mi
	{mso-style-name:mi;}
span.s1
	{mso-style-name:s1;}
span.cm
	{mso-style-name:cm;}
span.kc
	{mso-style-name:kc;}
span.kr
	{mso-style-name:kr;}
span.msoIns
	{mso-style-name:"";
	text-decoration:underline;
	color:teal;}
span.msoDel
	{mso-style-name:"";
	text-decoration:line-through;
	color:red;}
 /* Page Definitions */
 @page WordSection1
	{size:595.3pt 841.9pt;
	margin:72.0pt 63.7pt 72.0pt 3.0cm;
	layout-grid:15.6pt;}
div.WordSection1
	{page:WordSection1;}
 /* List Definitions */
 ol
	{margin-bottom:0cm;}
ul
	{margin-bottom:0cm;}
-->
</style>

</head>

<body bgcolor=white lang=ZH-CN link=blue vlink=purple style='text-justify-trim:
punctuation'>

<div class=WordSection1 style='layout-grid:15.6pt'>

<h1 align=center style='text-align:center;background:#2A3440'><span
style='font-family:宋体;color:white;letter-spacing:-.6pt;font-weight:normal'>编码规范</span><span
lang=EN-US style='font-family:"Helvetica",sans-serif;color:white;letter-spacing:
-.6pt;font-weight:normal'> </span></h1>

<p class=lead align=center style='text-align:center;background:#2A3440'>标准开发灵活的、持久的和可持续的<span
lang=EN-US style='font-family:"Helvetica",sans-serif'>HTML</span>和<span
lang=EN-US style='font-family:"Helvetica",sans-serif'>CSS,</span>和可维护的<span
lang=EN-US style='font-family:"Helvetica",sans-serif'>JavaScript</span></p>

<h2 style='background:#DFE1E8'><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>目录</span></h2>

<h4 style='vertical-align:top'><span lang=EN-US style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'><a href="#_命名规则"><span
lang=EN-US><span lang=EN-US>命名规则</span></span></a></span></h4>

<p class=MsoNormal align=left style='margin-left:35.7pt;text-align:left;
text-indent:-17.85pt;line-height:25%;vertical-align:top'><span lang=EN-US
style='font-size:10.0pt;line-height:25%;font-family:Symbol;color:#5A5A5A'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span lang=EN-US style='font-size:11.0pt;line-height:25%;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'><a href="#_项目命名"><span lang=EN-US><span
lang=EN-US>项目命名</span></span></a></span></p>

<p class=MsoNormal align=left style='margin-left:35.7pt;text-align:left;
text-indent:-17.85pt;line-height:25%;vertical-align:top'><span lang=EN-US
style='font-size:10.0pt;line-height:25%;font-family:Symbol;color:#5A5A5A'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span lang=EN-US style='font-size:11.0pt;line-height:25%;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'><a href="#_目录命名"><span lang=EN-US><span
lang=EN-US>目录命名</span></span></a></span></p>

<p class=MsoNormal align=left style='margin-left:35.7pt;text-align:left;
text-indent:-17.85pt;line-height:25%;vertical-align:top'><span lang=EN-US
style='font-size:10.0pt;line-height:25%;font-family:Symbol;color:#5A5A5A'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span lang=EN-US style='font-size:11.0pt;line-height:25%;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'><a href="#_JS文件命名">JS<span
lang=EN-US><span lang=EN-US>文件命名</span></span></a></span></p>

<p class=MsoNormal align=left style='margin-left:35.7pt;text-align:left;
text-indent:-17.85pt;vertical-align:top'><span lang=EN-US style='font-size:
10.0pt;font-family:Symbol;color:#5A5A5A'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'><a href="#_CSS文件命名">CSS<span lang=EN-US><span lang=EN-US>文<span
lang=EN-US>件<span lang=EN-US>命名</span></span></span></span></a></span></p>

<p class=MsoNormal align=left style='margin-left:35.7pt;text-align:left;
text-indent:-17.85pt;line-height:25%;vertical-align:top'><span lang=EN-US
style='font-size:10.0pt;line-height:25%;font-family:Symbol;color:#5A5A5A'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span lang=EN-US style='font-size:11.0pt;line-height:25%;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'><a href="#_HTML文件命名">HTML<span
lang=EN-US><span lang=EN-US>文件<span lang=EN-US>命名</span></span></span></a></span></p>

<h4 style='margin-top:0cm;background:white;vertical-align:top'><span
lang=EN-US style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:
-.6pt;font-weight:normal'><a href="#_HTML">HTML</a></span></h4>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_语法"><span lang=EN-US><span lang=EN-US>语法</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_HTML5_doctype">HTML5 doctype</a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_lang属性">lang<span lang=EN-US><span
     lang=EN-US>属性</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_字符编码"><span lang=EN-US><span lang=EN-US>字符编码</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_IE兼容模式">IE<span lang=EN-US><span lang=EN-US>兼容模式</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_引入CSS,_JS"><span lang=EN-US><span
     lang=EN-US>引<span lang=EN-US>入CSS, JS</span></span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_属性顺序"><span lang=EN-US><span lang=EN-US>属性顺序</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_boolean属性">boolean<span lang=EN-US><span
     lang=EN-US>属性</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_JS生成标签">JS<span lang=EN-US><span lang=EN-US>生成标<span
     lang=EN-US>签</span></span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_减少标签数量"><span lang=EN-US><span lang=EN-US>减少标签数量</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_实用高于完美"><span lang=EN-US><span lang=EN-US>实用高于完美</span></span></a></span></li>
</ul>

<h4 style='background:white;vertical-align:top'><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'><a href="#_CSS">CSS</a></span></h4>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_缩进"><span lang=EN-US><span lang=EN-US>缩<span
     lang=EN-US>进</span></span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_分号"><span lang=EN-US><span lang=EN-US>分号</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_空格"><span lang=EN-US><span lang=EN-US>空格</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_空行"><span lang=EN-US><span lang=EN-US>空行</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_换行"><span lang=EN-US><span lang=EN-US>换行</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_!important">!important</a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_注释"><span lang=EN-US><span lang=EN-US>注释</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_引号"><span lang=EN-US><span lang=EN-US>引号</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_命名"><span lang=EN-US><span lang=EN-US>命名</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_属性声明顺序"><span lang=EN-US><span lang=EN-US>属性声明顺序</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_颜色"><span lang=EN-US><span lang=EN-US>颜<span
     lang=EN-US>色</span></span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_媒体查询"><span lang=EN-US><span lang=EN-US>媒体查询</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_SCSS相关">SCSS<span lang=EN-US><span
     lang=EN-US>相关</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_杂项"><span lang=EN-US><span lang=EN-US>杂项</span></span></a></span></li>
</ul>

<h4 style='background:white;vertical-align:top'><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'><a href="#_JavaScript">JavaScript</a></span></h4>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_缩进_1"><span lang=EN-US><span lang=EN-US>缩进</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_单行长度"><span lang=EN-US><span lang=EN-US>单行长度</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_分号_1"><span lang=EN-US><span lang=EN-US>分号</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_空格_1"><span lang=EN-US><span lang=EN-US>空格</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_空行_1"><span lang=EN-US><span lang=EN-US>空行</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_换行_1"><span lang=EN-US><span lang=EN-US>换行</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_单行注释"><span lang=EN-US><span lang=EN-US>单行注释</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_多行注释"><span lang=EN-US><span lang=EN-US>多行注释</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_文档注释"><span lang=EN-US><span lang=EN-US>文档注释</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_引号_1"><span lang=EN-US><span lang=EN-US>引号</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_变量命名"><span lang=EN-US><span lang=EN-US>变量<span
     lang=EN-US>命名</span></span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_变量声明"><span lang=EN-US><span lang=EN-US>变量声明</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_函数"><span lang=EN-US><span lang=EN-US>函数</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_数组、对象"><span lang=EN-US><span lang=EN-US>数组、对象</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_括号"><span lang=EN-US><span lang=EN-US>括号</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_null">null</a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_undefined">undefined</a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_jshint">jshint</a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;background:white;
     vertical-align:top'><span lang=EN-US style='font-size:11.0pt;font-family:
     "微软雅黑",sans-serif'><a href="#_杂项_1"><span lang=EN-US><span lang=EN-US>杂项</span></span></a></span></li>
</ul>

<p class=MsoNormal align=left style='margin-left:36.0pt;text-align:left;
background:white;vertical-align:top'><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>&nbsp;</span></p>

<p class=MsoNormal align=left style='margin-left:36.0pt;text-align:left;
background:white;vertical-align:top'><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>&nbsp;</span></p>

<p class=MsoNormal align=left style='margin-left:36.0pt;text-align:left;
background:white;vertical-align:top'><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>&nbsp;</span></p>

<h2 style='vertical-align:top'><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>最佳原则</span></h2>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>坚持制定好的代码规范。</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>无论团队人数多少，代码应该同出一门。</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>如果你想要为这个规范做贡献或觉得有不合理的地方，请及时提出更改建议。</span></p>

<h2 style='background:#DFE1E8'><a name="_命名规则"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>命名规则</span></h2>

<h3 style='vertical-align:top'><a name="_项目命名"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>项目命名</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>全部采用小写方式， 以下划线分隔。</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>例：<span
lang=EN-US>my_project_name</span></span></p>

<h3 style='vertical-align:top'><a name="_目录命名"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>目录命名</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>参照项目命名规则；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>完整英文命名的用复数形式，缩写用单数形式</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>例：<span
lang=EN-US>scripts, js, styles, css, images, img, data_models, modules,
lego_modules, pages</span></span></p>

<h3 style='vertical-align:top'><a name="_JS文件命名"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>JS</span><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>文件命名</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>参照项目命名规则。</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>例：<span
lang=EN-US>account_model.js</span></span></p>

<h3 style='vertical-align:top'><a name="_CSS文件命名"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>CSS</span><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>文件命名</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>参照项目命名规则。</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>例：<span
lang=EN-US>retina_sprites.scss</span></span></p>

<h3 style='vertical-align:top'><a name="_HTML文件命名"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>HTML</span><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>文件命名</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>参照项目命名规则。</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>例：<span
lang=EN-US>error_report.html</span></span></p>

<h2 style='background:#DFE1E8'><a name="_HTML"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>HTML</span></h2>

<h3 style='vertical-align:top'><a name="_语法"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>语法</span></h3>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>缩进使用<span
     lang=EN-US>soft tab</span>（<span lang=EN-US>4</span>个空格）；</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>嵌套的节点应该缩进；</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>在属性上，使用双引号，不要使用单引号；</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>属性名全小写，用中划线做分隔符；</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>不要在自动闭合标签结尾处使用斜线（<span
     lang=EN-US><a
     href="http://dev.w3.org/html5/spec-author-view/syntax.html#syntax-start-tag"><span
     style='color:#0088CC'>HTML5 </span><span lang=EN-US style='color:#0088CC'><span
     lang=EN-US>规范</span></span></a><span class=apple-converted-space>&nbsp;</span></span>指出他们是可选的）；</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>不要忽略可选的关闭标签，例：</span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>&lt;/li&gt;</span></code><span
     class=apple-converted-space><span lang=EN-US style='font-size:11.0pt;
     font-family:"微软雅黑",sans-serif'>&nbsp;</span></span><span style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>和<span class=apple-converted-space><span
     lang=EN-US>&nbsp;</span></span></span><code><span lang=EN-US
     style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:
     #F7F7F9'>&lt;/body&gt;</span></code><span style='font-size:11.0pt;
     font-family:"微软雅黑",sans-serif'>。</span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=cp><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#009999'>&lt;!DOCTYPE html&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;html&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;head&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;title&gt;</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>Page title</span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;/title&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nt><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;/head&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;body&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;img</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=na><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#4F9FCF'>src=</span></span><span
class=s><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#D44950'>&quot;images/company_logo.png&quot;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>alt=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;Company&quot;</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:
#F7F7F9;vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;h1</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=na><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#4F9FCF'>class=</span></span><span
class=s><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#D44950'>&quot;hello-world&quot;</span></span><span class=nt><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&gt;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>Hello, world!</span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;/h1&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nt><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;/body&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;/html&gt;</span></span></pre>

<h3 style='vertical-align:top'><a name="_HTML5_doctype"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>HTML5 doctype</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>在页面开头使用这个简单地<span lang=EN-US>doctype</span>来启用标准模式，使其在每个浏览器中尽可能一致的展现；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>虽然<span
lang=EN-US>doctype</span>不区分大小写，但是按照惯例，<span lang=EN-US>doctype</span>大写 （<span
lang=EN-US><a
href="http://stackoverflow.com/questions/15594877/is-there-any-benefits-to-use-uppercase-or-lowercase-letters-with-html5-tagname"
target="_blank"><span lang=EN-US style='color:#0088CC'><span lang=EN-US>关于html</span></span><span
lang=EN-US style='color:#0088CC'><span lang=EN-US>属性，大写还是小写</span></span></a></span>）。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=cp><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#009999'>&lt;!DOCTYPE html&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;html&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ...</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;/html&gt;</span></span></pre>

<h3 style='vertical-align:top'><a name="_lang属性"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>lang</span><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>属性</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>根据<span lang=EN-US>HTML5</span>规范：</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><i><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#7A7A7A'>应在<span
lang=EN-US>html</span>标签上加上<span lang=EN-US>lang</span>属性。这会给语音工具和翻译工具帮助，告诉它们应当怎么去发音和翻译。</span></i></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>更多关于<span class=apple-converted-space><span lang=EN-US>&nbsp;</span></span></span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
background:#F7F7F9'>lang</span></code><span class=apple-converted-space><span
lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>&nbsp;</span></span><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>属性的说明<span
lang=EN-US><a
href="http://www.w3.org/html/wg/drafts/html/master/semantics.html#the-html-element"><span
lang=EN-US style='color:#0088CC'><span lang=EN-US>在这里</span></span></a></span>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>在<span lang=EN-US>sitepoint</span>上可以查到<span lang=EN-US><a
href="http://reference.sitepoint.com/html/lang-codes"><span lang=EN-US
style='color:#0088CC'><span lang=EN-US>语言列表</span></span></a></span>；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>但<span
lang=EN-US>sitepoint</span>只是给出了语言的大类，例如中文只给出了<span lang=EN-US>zh</span>，但是没有区分香港，台湾，大陆。而微软给出了一份更加<span
lang=EN-US><a
href="http://msdn.microsoft.com/en-us/library/ms533052(v=vs.85).aspx"><span
lang=EN-US style='color:#0088CC'><span lang=EN-US>详细的语言列表</span></span></a></span>，其中细分了<span
lang=EN-US>zh-cn, zh-hk, zh-tw</span>。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=cp><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#009999'>&lt;!DOCTYPE html&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;html</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>lang=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;en-us&quot;</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; ...</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;/html&gt;</span></span></pre>

<h3 style='vertical-align:top'><a name="_字符编码"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>字符编码</span></h3>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>通过声明一个明确的字符编码，让浏览器轻松、快速的确定适合网页内容的渲染方式，通常指定为<span
lang=EN-US>'UTF-8'</span>。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=cp><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#009999'>&lt;!DOCTYPE html&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;html&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;head&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;meta</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=na><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#4F9FCF'>charset=</span></span><span
class=s><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#D44950'>&quot;UTF-8&quot;</span></span><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;/head&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; ...</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;/html&gt;</span></span></pre>

<h3 style='vertical-align:top'><a name="_IE兼容模式"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>IE</span><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>兼容模式</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>用<span class=apple-converted-space><span lang=EN-US>&nbsp;</span></span></span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
background:#F7F7F9'>&lt;meta&gt;</span></code><span
class=apple-converted-space><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>&nbsp;</span></span><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>标签可以指定页面应该用什么版本的<span
lang=EN-US>IE</span>来渲染；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>如果你想要了解更多，请点击<span lang=EN-US><a
href="http://stackoverflow.com/questions/6771258/whats-the-difference-if-meta-http-equiv-x-ua-compatible-content-ie-edge-e"><span
lang=EN-US style='color:#0088CC'><span lang=EN-US>这里</span></span></a></span>；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>不同<span
lang=EN-US>doctype</span>在不同浏览器下会触发不同的渲染模式（<span lang=EN-US><a
href="https://hsivonen.fi/doctype/"><span lang=EN-US style='color:#0088CC'><span
lang=EN-US>这篇文章</span></span></a></span>总结的很到位）。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=cp><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#009999'>&lt;!DOCTYPE html&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;html&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;head&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;meta</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=na><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#4F9FCF'>http-equiv=</span></span><span
class=s><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#D44950'>&quot;X-UA-Compatible&quot;</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>content=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;IE=Edge&quot;</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nt><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;/head&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; ...</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;/html&gt;</span></span></pre>

<h3 style='vertical-align:top'><a name="_引入CSS,_JS"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>引入<span
lang=EN-US>CSS, JS</span></span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>根据<span lang=EN-US>HTML5</span>规范<span lang=EN-US>, </span>通常在引入<span
lang=EN-US>CSS</span>和<span lang=EN-US>JS</span>时不需要指明<span
class=apple-converted-space><span lang=EN-US>&nbsp;</span></span></span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
background:#F7F7F9'>type</span></code><span style='font-size:11.0pt;font-family:
"微软雅黑",sans-serif;color:#5A5A5A'>，因为<span class=apple-converted-space><span
lang=EN-US>&nbsp;</span></span></span><code><span lang=EN-US style='font-size:
9.0pt;font-family:"Courier New";color:#D44950;background:#F7F7F9'>text/css</span></code><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>和<span
class=apple-converted-space><span lang=EN-US>&nbsp;</span></span></span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
background:#F7F7F9'>text/javascript</span></code><span
class=apple-converted-space><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>&nbsp;</span></span><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>分别是他们的默认值。</span></p>

<h4 style='vertical-align:top'><span lang=EN-US style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>HTML5 </span><span
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>规范链接</span></h4>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'><a
     href="http://www.w3.org/TR/2011/WD-html5-20110525/semantics.html#the-link-element"><span
     lang=EN-US style='color:#0088CC'><span lang=EN-US>使用link</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'><a
     href="http://www.w3.org/TR/2011/WD-html5-20110525/semantics.html#the-style-element"><span
     lang=EN-US style='color:#0088CC'><span lang=EN-US>使用style</span></span></a></span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'><a
     href="http://www.w3.org/TR/2011/WD-html5-20110525/scripting-1.html#the-script-element"><span
     lang=EN-US style='color:#0088CC'><span lang=EN-US>使用script</span></span></a></span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>&lt;!-- External CSS --&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;link</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>rel=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;stylesheet&quot;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>href=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;code_guide.css&quot;</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:
#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#999999'>&lt;!-- In-document CSS --&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;style&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=nt><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#2F6F9F'>&lt;/style&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>&lt;!-- External JS --&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;script </span></span><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>src=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;code_guide.js&quot;</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&gt;&lt;/script&gt;</span></span></pre><pre style='background:
#F7F7F9;vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>&lt;!-- In-document JS --&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;script&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=nt><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#2F6F9F'>&lt;/script&gt;</span></span></pre>

<h3 style='vertical-align:top'><a name="_属性顺序"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>属性顺序</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>属性应该按照特定的顺序出现以保证易读性；</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>id</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>class</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>name</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>data-*</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>src</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>for</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>type</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>href</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>value</span></code><span class=apple-converted-space><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>&nbsp;</span></span><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>,<span
     class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
     style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:
     #F7F7F9'>max-length</span></code><span lang=EN-US style='font-size:11.0pt;
     font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>max</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>min</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>pattern</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>placeholder</span></code><span lang=EN-US
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>,<span
     class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
     style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:
     #F7F7F9'>title</span></code><span lang=EN-US style='font-size:11.0pt;
     font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>alt</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>aria-*</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>role</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>required</span></code><span lang=EN-US
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>,<span
     class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
     style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:
     #F7F7F9'>readonly</span></code><span lang=EN-US style='font-size:11.0pt;
     font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>disabled</span></code></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=nt><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;a</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>class=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;...&quot;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>id=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;...&quot;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>data-modal=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;toggle&quot;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>href=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;#&quot;</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&gt;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>Example link</span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;/a&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:
#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;input</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>class=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;form-control&quot;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>type=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;text&quot;</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:
#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;img</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>src=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;...&quot;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>alt=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;...&quot;</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&gt;</span></span></pre>

<h3 style='vertical-align:top'><a name="_boolean属性"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>boolean</span><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>属性</span></h3>

<p style='vertical-align:top'><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>boolean</span><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>属性指不需要声明取值的属性，<span
lang=EN-US>XHTML</span>需要每个属性声明取值，但是<span lang=EN-US>HTML5</span>并不需要；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>更多内容可以参考<span class=apple-converted-space><span lang=EN-US>&nbsp;</span></span><span
lang=EN-US><a
href="http://www.whatwg.org/specs/web-apps/current-work/multipage/common-microsyntaxes.html#boolean-attributes"><span
style='color:#0088CC'>WhatWG section on boolean attributes</span></a></span>：</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><i><span
lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#7A7A7A'>boolean</span></i><i><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#7A7A7A'>属性的存在表示取值为<span
lang=EN-US>true</span>，不存在则表示取值为<span lang=EN-US>false</span>。</span></i></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=nt><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;input</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>type=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;text&quot;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>disabled</span></span><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;input</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>type=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;checkbox&quot;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>value=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;1&quot;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>checked</span></span><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;select&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;option</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=na><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#4F9FCF'>value=</span></span><span
class=s><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#D44950'>&quot;1&quot;</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>selected</span></span><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&gt;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>1</span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&lt;/option&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=nt><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#2F6F9F'>&lt;/select&gt;</span></span></pre>

<h3 style='vertical-align:top'><a name="_JS生成标签"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>JS</span><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>生成标签</span></h3>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>在<span
lang=EN-US>JS</span>文件中生成标签让内容变得更难查找，更难编辑，性能更差。应该尽量避免这种情况的出现。</span></p>

<h3 style='vertical-align:top'><a name="_减少标签数量"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>减少标签数量</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>在编写<span lang=EN-US>HTML</span>代码时，需要尽量避免多余的父节点；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>很多时候，需要通过迭代和重构来使<span
lang=EN-US>HTML</span>变得更少。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>&lt;!-- Not well --&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;span</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>class=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;avatar&quot;</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nt><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;img</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>src=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;...&quot;</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&gt;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=nt><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#2F6F9F'>&lt;/span&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>&lt;!-- Better --&gt;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>&lt;img</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>class=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;avatar&quot;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=na><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#4F9FCF'>src=</span></span><span class=s><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#D44950'>&quot;...&quot;</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>&gt;</span></span></pre>

<h3 style='vertical-align:top'><a name="_实用高于完美"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>实用高于完美</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>尽量遵循<span lang=EN-US>HTML</span>标准和语义，但是不应该以浪费实用性作为代价；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>任何时候都要用尽量小的复杂度和尽量少的标签来解决问题。</span></p>

<h2 style='background:#DFE1E8'><a name="_CSS"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>CSS</span></h2>

<h3 style='vertical-align:top'><a name="_缩进"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>缩进</span></h3>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>使用<span
lang=EN-US>soft tab</span>（<span lang=EN-US>4</span>个空格）。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=nc><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>position</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>absolute</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>top</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>10px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>left</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>10px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>border</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>-</span></span><span class=n><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>radius</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>10px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>width</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>50px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>height</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>50px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_分号"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>分号</span></h3>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>每个属性声明末尾都要加分号。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=nc><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>width</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>20px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>height</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>20px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>background-color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nb><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#336666'>red</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_空格"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>空格</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>以下几种情况不需要空格：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>属性名后</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>多个规则的分隔符<span
     lang=EN-US>','</span>前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>!important</span></code><span
     class=apple-converted-space><span lang=EN-US style='font-size:11.0pt;
     font-family:"微软雅黑",sans-serif'>&nbsp;</span></span><span lang=EN-US
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>'!'</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>后</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>属性值中<span
     lang=EN-US>'('</span>后和<span lang=EN-US>')'</span>前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>行末不要有多余的空格</span></li>
</ul>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>以下几种情况需要空格：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>属性值前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>选择器<span
     lang=EN-US>'&gt;', '+', '~'</span>前后</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>'{'</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>!important</span></code><span
     class=apple-converted-space><span lang=EN-US style='font-size:11.0pt;
     font-family:"微软雅黑",sans-serif'>&nbsp;</span></span><span lang=EN-US
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>'!'</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>@else</span></code><span class=apple-converted-space><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>&nbsp;</span></span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>前后</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>属性值中的<span
     lang=EN-US>','</span>后</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>注释<span lang=EN-US>'/*'</span>后和<span
     lang=EN-US>'*/'</span>前</span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>color</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><span class=nb><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#336666'>red</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>!</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>important</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>background-color</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>rgba</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>,</span></span><span class=m><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>,.</span></span><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>5</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nb><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#336666'>red</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=cp><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#009999'>!important</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>background-color</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>rgba</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>.</span></span><span class=m><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>5</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=nc><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#00AA88'>.dialog</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=nc><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#00AA88'>.dialog</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>&gt;</span></span><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.dialog</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>&gt;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nc><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.dialog</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp; &nbsp;</span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>@if</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>@else</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>@if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>@else</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_空行"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>空行</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>以下几种情况需要空行：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>文件最后保留一个空行</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>'}'</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>后最好跟一个空行，包括<span
     lang=EN-US>scss</span>中嵌套的规则</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>属性之间需要适当的空行，具体见<span
     lang=EN-US><a
     href="http://imweb.github.io/CodeGuide/#css-declaration-order"><span
     lang=EN-US style='color:#0088CC'><span lang=EN-US>属性声明顺序</span></span></a></span></span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.dialog</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nb><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#336666'>red</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>&amp;:</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>after</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=err><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#AA0000;
background:#FFAAAA'>{</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=err><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#AA0000;background:#FFAAAA'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.dialog</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nb><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#336666'>red</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>&amp;:</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>after</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=err><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#AA0000;
background:#FFAAAA'>{</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=err><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#AA0000;background:#FFAAAA'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_换行"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>换行</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>以下几种情况不需要换行：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>'{'</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>前</span></li>
</ul>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>以下几种情况需要换行：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>'{'</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>后和<span lang=EN-US>'}'</span>前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>每个属性独占一行</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>多个规则的分隔符<span
     lang=EN-US>','</span>后</span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>color</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nb><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#336666'>red</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>background-color</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nb><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#336666'>black</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nb><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#336666'>red</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>background-color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nb><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#336666'>black</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nc><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.dialog</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=nc><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#00AA88'>.dialog</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_!important"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>!important</span></h3>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>不允许使用<span
lang=EN-US>!important</span>。</span></p>

<h3 style='vertical-align:top'><a name="_注释"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>注释</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>注释统一用<span lang=EN-US>'/* */'</span>（<span lang=EN-US>scss</span>中也不要用<span
lang=EN-US>'//'</span>），具体参照右边的写法；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>缩进与下一行代码保持一致；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>可位于一个代码行的末尾，与代码间隔一个空格。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* Modal header */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.modal-header</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/*</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'> * Modal header</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'> */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.modal-header</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.modal-header</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* 50px */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>width</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>50px</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>color</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nb><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#336666'>red</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=c><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>/* color red */</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_引号"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>引号</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>最外层统一使用双引号；</span></p>

<p style='vertical-align:top'><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>url</span><span style='font-size:
11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>的内容要用引号；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>属性选择器中的属性值需要引号。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=nc><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><span
class=nd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#9999FF'>:after</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>content</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>background-image</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=sx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>url(&quot;logo.png&quot;)</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>li</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>[</span></span><span class=nt><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#2F6F9F'>data-type</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><span class=s2><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#CC3300'>&quot;single&quot;</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>]</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_命名"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>命名</span></h3>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>使用小写字母，以中划线分隔</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>scss</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>中的变量、函数、混合、<span
     lang=EN-US>placeholder</span>采用驼峰式命名</span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* class */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element-content</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* id */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nf><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#CC00FF'>#myDialog</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* </span></span><span
class=c><span style='font-size:8.5pt;color:#999999'>变量</span></span><span
class=c><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'> */</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=o><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#555555'>$</span></span><span class=nt><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>colorBlack</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nf><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#CC00FF'>#000</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>/* </span></span><span class=c><span
style='font-size:8.5pt;color:#999999'>函数</span></span><span class=c><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'> */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>@function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>pxToRem</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>($</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>px</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* </span></span><span
class=c><span style='font-size:8.5pt;color:#999999'>混合</span></span><span
class=c><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'> */</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=k><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#006699'>@mixin</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>centerBlock</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* placeholder */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>%</span></span><span
class=nt><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#2F6F9F'>myDialog</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_属性声明顺序"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>属性声明顺序</span></h3>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>相关的属性声明按右边的顺序做分组处理，组之间需要有一个空行。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=nc><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.declaration-order</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>display</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>block</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>float</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>right</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>position</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>absolute</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>top</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>right</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>bottom</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>left</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>z-index</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>100</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>border</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1px</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>solid</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>#e5e5e5</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>border</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>-</span></span><span class=n><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>radius</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>3px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>width</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>100px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>height</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>100px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>font</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>normal</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>13px</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=s2><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#CC3300'>&quot;Helvetica Neue&quot;</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>sans-serif</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>line-height</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>.</span></span><span class=m><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>5</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>text-align</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>center</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>color</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>#333</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>background-color</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>#f5f5f5</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>opacity</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// </span></span><span
class=c1><span style='font-size:8.5pt;color:#999999'>下面是推荐的属性的顺序</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>[</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;display&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;visibility&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;float&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;clear&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;overflow&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;overflow-x&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;overflow-y&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;clip&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;zoom&quot;</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>],</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>[</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;table-layout&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;empty-cells&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;caption-side&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-spacing&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-collapse&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;list-style&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;list-style-position&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;list-style-type&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;list-style-image&quot;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>],</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-box-orient&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-box-direction&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-box-decoration-break&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-box-pack&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-box-align&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-box-flex&quot;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>],</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;position&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;top&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;right&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;bottom&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;left&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;z-index&quot;</span></span></pre><pre style='background:
#F7F7F9;vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>],</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;margin&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;margin-top&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;margin-right&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;margin-bottom&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;margin-left&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-box-sizing&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-box-sizing&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;box-sizing&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-width&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-style&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-color&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-top&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-top-width&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-top-style&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-top-color&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-right&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-right-width&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-right-style&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-right-color&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-bottom&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-bottom-width&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-bottom-style&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-bottom-color&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-left&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-left-width&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-left-style&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-left-color&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-border-radius&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;</span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-border-radius&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-radius&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-border-top-left-radius&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-border-radius-topleft&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-top-left-radius&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-border-top-right-radius&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-border-radius-topright&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-top-right-radius&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-border-bottom-right-radius&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-border-radius-bottomright&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-bottom-right-radius&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-border-bottom-left-radius&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-border-radius-bottomleft&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-bottom-left-radius&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-border-image&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-border-image&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-border-image&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-image&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-border-image-source&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-border-image-source&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-border-image-source&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-image-source&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-border-image-slice&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-border-image-slice&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-border-image-slice&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-image-slice&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-border-image-width&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-border-image-width&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-border-image-width&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-image-width&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-border-image-outset&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-border-image-outset&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-border-image-outset&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-image-outset&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-border-image-repeat&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-border-image-repeat&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-border-image-repeat&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;border-image-repeat&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;padding&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;padding-top&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;padding-right&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;padding-bottom&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;padding-left&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;width&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;min-width&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;max-width&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;height&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;min-height&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;max-height&quot;</span></span></pre><pre style='background:
#F7F7F9;vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>],</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font-family&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font-size&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font-weight&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font-style&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font-variant&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font-size-adjust&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font-stretch&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font-effect&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;</span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font-emphasize&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font-emphasize-position&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font-emphasize-style&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;font-smooth&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;line-height&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-align&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-text-align-last&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-text-align-last&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-text-align-last&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-align-last&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;vertical-align&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;white-space&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-decoration&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-emphasis&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-emphasis-color&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-emphasis-style&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-emphasis-position&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-indent&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-text-justify&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-justify&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;letter-spacing&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;word-spacing&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-writing-mode&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-outline&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-transform&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-wrap&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-text-overflow&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-overflow&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-overflow-ellipsis&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-overflow-mode&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-word-wrap&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;word-wrap&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-word-break&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;word-break&quot;</span></span></pre><pre style='background:
#F7F7F9;vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>],</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;color&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;background&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;filter:progid:DXImageTransform.Microsoft.AlphaImageLoader&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;background-color&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;background-image&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;background-repeat&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;background-attachment&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;background-position&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-background-position-x&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;background-position-x&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-background-position-y&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;background-position-y&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-background-clip&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-background-clip&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;background-clip&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;background-origin&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-background-size&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-background-size&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-background-size&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;background-size&quot;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>],</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;outline&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;outline-width&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;outline-style&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;outline-color&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;outline-offset&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;opacity&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;filter:progid:DXImageTransform.Microsoft.Alpha(Opacity&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;</span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-filter:\\'progid:DXImageTransform.Microsoft.Alpha&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-interpolation-mode&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-box-shadow&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-box-shadow&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;box-shadow&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;filter:progid:DXImageTransform.Microsoft.gradient&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-filter:\\'progid:DXImageTransform.Microsoft.gradient&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;text-shadow&quot;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>],</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-transition&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-transition&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-transition&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-transition&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;transition&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-transition-delay&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-transition-delay&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-transition-delay&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-transition-delay&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;transition-delay&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-transition-timing-function&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-transition-timing-function&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-transition-timing-function&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-transition-timing-function&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;transition-timing-function&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-transition-duration&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-transition-duration&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-transition-duration&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-transition-duration&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;transition-duration&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-transition-property&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-transition-property&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-transition-property&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-transition-property&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;transition-property&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-transform&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-transform&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-transform&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-transform&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;transform&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-transform-origin&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-transform-origin&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-transform-origin&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-transform-origin&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;transform-origin&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-animation&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-animation&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-animation&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-animation&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;animation&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-animation-name&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-animation-name&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-animation-name&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-animation-name&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;animation-name&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-animation-duration&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-animation-duration&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-animation-duration&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-animation-duration&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;animation-duration&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-animation-play-state&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-animation-play-state&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-animation-play-state&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-animation-play-state&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;animation-play-state&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-animation-timing-function&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-animation-timing-function&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-animation-timing-function&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-animation-timing-function&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;animation-timing-function&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-animation-delay&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-animation-delay&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-animation-delay&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-animation-delay&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;animation-delay&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-animation-iteration-count&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-animation-iteration-count&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-animation-iteration-count&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-animation-iteration-count&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;animation-iteration-count&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-animation-direction&quot;</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-animation-direction&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-animation-direction&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-animation-direction&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;animation-direction&quot;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>],</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;content&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;quotes&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;counter-reset&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;counter-increment&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;resize&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;cursor&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-user-select&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-user-select&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-ms-user-select&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;user-select&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;nav-index&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;nav-up&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;nav-right&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;nav-down&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;nav-left&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-tab-size&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-o-tab-size&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;tab-size&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-webkit-hyphens&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;-moz-hyphens&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;hyphens&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;</span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;pointer-events&quot;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>]</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>]</span></span></pre>

<h3 style='vertical-align:top'><a name="_颜色"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>颜色</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>颜色<span lang=EN-US>16</span>进制用小写字母；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>颜色<span
lang=EN-US>16</span>进制尽量用简写。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>#ABCDEF</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>background-color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>#001122</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>#abcdef</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>background-color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>#012</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_媒体查询"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>媒体查询</span></h3>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>尽量将媒体查询的规则靠近与他们相关的规则，不要将他们一起放到一个独立的样式文件中，或者丢在文档的最底部，这样做只会让大家以后更容易忘记他们。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=nc><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element-avatar</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>@media</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>(</span></span><span class=nt><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#2F6F9F'>min-width</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nt><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>480px</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nc><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#00AA88'>.element</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nc><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#00AA88'>.element-avatar</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_SCSS相关"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>SCSS</span><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>相关</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>提交的代码中不要有<span class=apple-converted-space><span lang=EN-US>&nbsp;</span></span></span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
background:#F7F7F9'>@debug</span></code><span style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>声明顺序：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>@extend</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>不包含<span
     class=apple-converted-space><span lang=EN-US>&nbsp;</span></span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>@content</span></code><span
     class=apple-converted-space><span lang=EN-US style='font-size:11.0pt;
     font-family:"微软雅黑",sans-serif'>&nbsp;</span></span><span style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>的<span class=apple-converted-space><span
     lang=EN-US>&nbsp;</span></span></span><code><span lang=EN-US
     style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:
     #F7F7F9'>@include</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>包含<span
     class=apple-converted-space><span lang=EN-US>&nbsp;</span></span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>@content</span></code><span
     class=apple-converted-space><span lang=EN-US style='font-size:11.0pt;
     font-family:"微软雅黑",sans-serif'>&nbsp;</span></span><span style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>的<span class=apple-converted-space><span
     lang=EN-US>&nbsp;</span></span></span><code><span lang=EN-US
     style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:
     #F7F7F9'>@include</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>自身属性</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>嵌套规则</span></li>
</ul>

<p style='vertical-align:top'><code><span lang=EN-US style='font-size:9.0pt;
font-family:"Courier New";color:#D44950;background:#F7F7F9'>@import</span></code><span
class=apple-converted-space><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>&nbsp;</span></span><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>引入的文件不需要开头的<span
lang=EN-US>'_'</span>和结尾的<span lang=EN-US>'.scss'</span>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>嵌套最多不能超过<span lang=EN-US>4</span>层；</span></p>

<p style='vertical-align:top'><code><span lang=EN-US style='font-size:9.0pt;
font-family:"Courier New";color:#D44950;background:#F7F7F9'>@extend</span></code><span
class=apple-converted-space><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>&nbsp;</span></span><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>中使用<span
lang=EN-US>placeholder</span>选择器；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>去掉不必要的父级引用符号<span
lang=EN-US>'&amp;'</span>。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>@import</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;_dialog.scss&quot;</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>@import</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;dialog&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.fatal</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>@</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>extend</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>.</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>error</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.fatal</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>@</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>extend</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>%</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>error</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>&amp;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>&gt;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>.</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>dialog</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=err><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#AA0000;
background:#FFAAAA'>{</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=err><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#AA0000;background:#FFAAAA'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>&gt;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>.</span></span><span class=n><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>dialog</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=err><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#AA0000;background:#FFAAAA'>{</span></span></pre><pre style='background:
#F7F7F9;vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=err><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#AA0000;background:#FFAAAA'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_杂项"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>杂项</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不允许有空的规则；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>元素选择器用小写字母；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>去掉小数点前面的<span lang=EN-US>0</span>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>去掉数字中不必要的小数点和末尾的<span lang=EN-US>0</span>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>属性值<span lang=EN-US>'0'</span>后面不要加单位；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>同个属性不同前缀的写法需要在垂直方向保持对齐，具体参照右边的写法；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>无前缀的标准属性应该写在有前缀的属性后面；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要在同个规则里出现重复的属性，如果重复的属性是连续的则没关系；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要在一个文件里出现两个相同的规则；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>用<span class=apple-converted-space><span lang=EN-US>&nbsp;</span></span></span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
background:#F7F7F9'>border: 0;</span></code><span class=apple-converted-space><span
lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>&nbsp;</span></span><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>代替<span
class=apple-converted-space><span lang=EN-US>&nbsp;</span></span></span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
background:#F7F7F9'>border: none;</span></code><span style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>选择器不要超过<span lang=EN-US>4</span>层（在<span lang=EN-US>scss</span>中如果超过<span
lang=EN-US>4</span>层应该考虑用嵌套的方式来写）；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>发布的代码中不要有<span class=apple-converted-space><span lang=EN-US>&nbsp;</span></span></span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
background:#F7F7F9'>@import</span></code><span style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>尽量少用<span
lang=EN-US>'*'</span>选择器。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>LI</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nt><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#2F6F9F'>li</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=n><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>rgba</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=m><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>.</span></span><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>5</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>);</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=n><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>rgba</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=m><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>.</span></span><span class=m><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>5</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>width</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>50.0px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>width</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>50px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>width</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>width</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>border</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>-</span></span><span class=n><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>radius</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>3px</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>webkit</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>border</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>radius</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>3px</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>-</span></span><span class=n><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>moz</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>border</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>radius</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>3px</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>background</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>linear</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>gradient</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>to</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>bottom</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>#fff</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>#eee</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>100%</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>);</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>background</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>webkit</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>linear</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>gradient</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>top</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>#fff</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>#eee</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>100%</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>background</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>-</span></span><span class=n><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>moz</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>linear</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>gradient</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>top</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>#fff</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>#eee</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>100%</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>webkit</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>border</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>radius</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>3px</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>-</span></span><span class=n><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>moz</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>border</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>radius</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>3px</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>border</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>radius</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>3px</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>background</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>-</span></span><span class=n><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>webkit</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>-</span></span><span class=n><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>linear</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>-</span></span><span class=n><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>gradient</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=k><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#006699'>top</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>#fff</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>#eee</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>100%</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>background</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>-</span></span><span class=n><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>moz</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>linear</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>gradient</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>top</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>#fff</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>#eee</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>100%</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>background</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>linear</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>-</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>gradient</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>to</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>bottom</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>#fff</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>#eee</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=m><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>100%</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>);</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>/* not good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>rgb</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=m><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>width</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>50px</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>color</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>rgba</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>.</span></span><span class=m><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>5</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* good */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nc><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#00AA88'>.element</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>color</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>rgb</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=m><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>color</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=n><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>rgba</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=m><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>.</span></span><span class=m><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>5</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h2 style='background:#DFE1E8'><a name="_JavaScript"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>JavaScript</span></h2>

<h3 style='vertical-align:top'><a name="_缩进_1"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>缩进</span></h3>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>使用<span
lang=EN-US>soft tab</span>（<span lang=EN-US>4</span>个空格）。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>y</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>&lt;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>y</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>+=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>10</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>else</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>+=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_单行长度"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>单行长度</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要超过<span lang=EN-US>120</span>，但如果编辑器开启<span lang=EN-US>word
wrap</span>可以不考虑单行长度。</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>长字符串拼接用加号。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>tpl</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=s1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>'\</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=s1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&nbsp;&nbsp;&nbsp; &lt;ul&gt;\</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=s1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#CC3300'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;li&gt;1&lt;/li&gt;\</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=s1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#CC3300'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;li&gt;2&lt;/li&gt;\</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=s1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#CC3300'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;li&gt;3&lt;/li&gt;\</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=s1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#CC3300'>&nbsp;&nbsp;&nbsp; &lt;/ul&gt;'</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>tpl</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=s1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>'&lt;ul&gt;'</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>+</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>'&lt;li&gt;1&lt;/li&gt;'</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>+</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>'&lt;li&gt;2&lt;/li&gt;'</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>+</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=s1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>'&lt;li&gt;3&lt;/li&gt;'</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>+</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=s1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#CC3300'>'&lt;/ul&gt;'</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre>

<h3 style='vertical-align:top'><a name="_分号_1"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>分号</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>以下几种情况后需加分号：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>变量声明</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>表达式</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>return</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>throw</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>break</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>continue</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>do-while</span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=cm><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* var declaration */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* expression statement */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nx><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>++</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/* do-while */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>do</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>++</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>while</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>&lt;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>10</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre>

<h3 style='vertical-align:top'><a name="_空格_1"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>空格</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>以下几种情况不需要空格：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>对象的属性名后</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>前缀一元运算符后</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>后缀一元运算符前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>函数调用括号前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>无论是函数声明还是函数表达式，<span
     lang=EN-US>'('</span>前不要空格</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>数组的<span
     lang=EN-US>'['</span>后和<span lang=EN-US>']'</span>前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>对象的<span
     lang=EN-US>'{'</span>后和<span lang=EN-US>'}'</span>前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>运算符<span
     lang=EN-US>'('</span>后和<span lang=EN-US>')'</span>前</span></li>
</ul>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>以下几种情况需要空格：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>二元运算符前后</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>三元运算符<span
     lang=EN-US>'?:'</span>前后</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>代码块<span
     lang=EN-US>'{'</span>前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>下列关键字前：</span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>else</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>while</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>catch</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>finally</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>下列关键字后：</span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>if</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>else</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>for</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>while</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>do</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>switch</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>case</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>try</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,</span><code><span lang=EN-US
     style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:
     #F7F7F9'>catch</span></code><span lang=EN-US style='font-size:11.0pt;
     font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>finally</span></code><span lang=EN-US
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>,<span
     class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
     style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:
     #F7F7F9'>with</span></code><span lang=EN-US style='font-size:11.0pt;
     font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>return</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>typeof</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>单行注释<span
     lang=EN-US>'//'</span>后（若单行注释和代码同行，则<span lang=EN-US>'//'</span>前也需要），多行注释<span
     lang=EN-US>'*'</span>后</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>对象的属性值前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>for</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>循环，分号后留有一个空格，前置条件如果有多个，逗号后留一个空格</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>无论是函数声明还是函数表达式，<span
     lang=EN-US>'{'</span>前一定要有空格</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>函数的参数之间</span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>b</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><span class=mi><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>};</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>b</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>};</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>++</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nx><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>y</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>++</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nx><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>z</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>?</span></span><span class=mi><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>++</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nx><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>y</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>++</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nx><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>z</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>?</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>[</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>];</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>[</span></span><span class=mi><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>];</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>+</span></span><span class=mi><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>*</span></span><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>3</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=mi><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>+</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>*</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>3</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// no space before '(', one space before '{', one space between function parameters</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>doSomething</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>b</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>c</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// do something</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>};</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// no space before '('</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nx><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>doSomething</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>item</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>for</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>&lt;</span></span><span class=mi><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>6</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>++</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>){</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>++</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>for</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>&lt;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>6</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>++</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>++</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_空行_1"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>空行</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>以下几种情况需要空行：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>变量声明后（当变量声明在代码块的最后一行时，则无需空行）</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>注释前（当注释在代码块的第一行时，则无需空行）</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>代码块后（在函数调用、数组、对象中则无需空行）</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>文件最后保留一个空行</span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// need blank line after variable declaration</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not need blank line when variable declaration is last expression in the current block</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>&gt;=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>var</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>y</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>+</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=kd><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// need blank line before line comment</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nx><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>++</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>b</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>()</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not need blank line when comment is first line of block</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>return</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// need blank line after blocks</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>for</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=kd><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>i</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>i</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>&lt;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>i</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>++</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=kc><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#006699'>true</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>return</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kc><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>false</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>continue</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>obj</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>foo</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>()</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>return</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>},</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>bar</span></span><span class=o><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>function</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>()</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>return</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>};</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not need blank line when in argument list, array, object</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nx><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>func</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>()</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>++</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>},</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>3</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>foo</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>[</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>()</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>++</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>},</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>3</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>];</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>foo</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>b</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>()</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>++</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>},</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>c</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>3</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>};</span></span></pre>

<h3 style='vertical-align:top'><a name="_换行_1"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>换行</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>换行的地方，行末必须有<span lang=EN-US>','</span>或者运算符；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>以下几种情况不需要换行：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>下列关键字后：</span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>else</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>catch</span></code><span lang=EN-US style='font-size:
     11.0pt;font-family:"微软雅黑",sans-serif'>,<span class=apple-converted-space>&nbsp;</span></span><code><span
     lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
     background:#F7F7F9'>finally</span></code></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>代码块<span
     lang=EN-US>'{'</span>前</span></li>
</ul>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>以下几种情况需要换行：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>代码块<span
     lang=EN-US>'{'</span>后和<span lang=EN-US>'}'</span>前</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>定义变量后</span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>b</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>c</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>};</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nx><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>y</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>?</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>b</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>c</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>};</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nx><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>y</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>?</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>y</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>?</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// no need line break with 'else', 'catch', 'finally'</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>condition</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>else</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>try</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>catch</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>e</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>finally</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>test</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>()</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>test</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>()</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>foo</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>7</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>b</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>c</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>bar</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>8</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>foo</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>7</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>b</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>c</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>bar</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>8</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre>

<h3 style='vertical-align:top'><a name="_单行注释"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>单行注释</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>双斜线后，必须跟一个空格；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>缩进与下一行代码保持一致；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>可位于一个代码行的末尾，与代码间隔一个空格。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>condition</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=c1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>// if you made it here, then all security checks passed</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>allowed</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>();</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>zhangsan</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=s1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>'zhangsan'</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=c1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>// one space after code</span></span></pre>

<h3 style='vertical-align:top'><a name="_多行注释"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>多行注释</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>最少三行<span lang=EN-US>, '*'</span>后跟一个空格，具体参照右边的写法；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>建议在以下情况下使用：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>难于理解的代码段</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>可能存在错误的代码段</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>浏览器特殊的<span
     lang=EN-US>HACK</span>代码</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>业务逻辑强相关的代码</span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=cm><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/*</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'> * one space after '*'</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'> */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre>

<h3 style='vertical-align:top'><a name="_文档注释"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>文档注释</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>各类标签<span lang=EN-US>@param, @method</span>等请参考<span lang=EN-US><a
href="http://usejsdoc.org/" target="_blank"><span style='color:#0088CC'>usejsdoc</span></a></span>和<span
lang=EN-US><a href="http://yuri4ever.github.io/jsdoc/" target="_blank"><span
style='color:#0088CC'>JSDoc Guide</span></a></span>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>建议在以下情况下使用：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>所有常量</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>所有函数</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>所有类</span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=cm><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>/**</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'> * @func</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'> * @desc </span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>一个带参数的函数</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'> * @param {string} a - </span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>参数</span></span><span
class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>a</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'> * @param {number} b=1 - </span></span><span class=cm><span
style='font-size:8.5pt;color:#999999'>参数</span></span><span class=cm><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>b</span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>默认值为</span></span><span
class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>1</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'> * @param {string} c=1 - </span></span><span class=cm><span
style='font-size:8.5pt;color:#999999'>参数</span></span><span class=cm><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>c</span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>有两种支持的取值</span></span><span
class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>&lt;/br&gt;1—</span></span><span class=cm><span
style='font-size:8.5pt;color:#999999'>表示</span></span><span class=cm><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>x&lt;/br&gt;2—</span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>表示</span></span><span
class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>xx</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'> * @param {object} d - </span></span><span class=cm><span
style='font-size:8.5pt;color:#999999'>参数</span></span><span class=cm><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>d</span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>为一个对象</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'> * @param {string} d.e - </span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>参数</span></span><span
class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>d</span></span><span class=cm><span style='font-size:8.5pt;
color:#999999'>的</span></span><span class=cm><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#999999'>e</span></span><span class=cm><span
style='font-size:8.5pt;color:#999999'>属性</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'> * @param {string} d.f - </span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>参数</span></span><span
class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>d</span></span><span class=cm><span style='font-size:8.5pt;
color:#999999'>的</span></span><span class=cm><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#999999'>f</span></span><span class=cm><span
style='font-size:8.5pt;color:#999999'>属性</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'> * @param {object[]} g - </span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>参数</span></span><span
class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>g</span></span><span class=cm><span style='font-size:8.5pt;
color:#999999'>为一个对象数组</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=cm><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'> * @param {string} g.h - </span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>参数</span></span><span
class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>g</span></span><span class=cm><span style='font-size:8.5pt;
color:#999999'>数组中一项的</span></span><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>h</span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>属性</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'> * @param {string} g.i - </span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>参数</span></span><span
class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>g</span></span><span class=cm><span style='font-size:8.5pt;
color:#999999'>数组中一项的</span></span><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>i</span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>属性</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=cm><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'> * @param {string} [j] - </span></span><span
class=cm><span style='font-size:8.5pt;color:#999999'>参数</span></span><span
class=cm><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>j</span></span><span class=cm><span style='font-size:8.5pt;
color:#999999'>是一个可选参数</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=cm><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'> */</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>foo</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>b</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>c</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>d</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>g</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>j</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_引号_1"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>引号</span></h3>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>最外层统一使用单引号。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=s2><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>&quot;test&quot;</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>y</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=s1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>'foo'</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>z</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=s1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>'&lt;div id=&quot;test&quot;&gt;&lt;/div&gt;'</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre>

<h3 style='vertical-align:top'><a name="_变量命名"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>变量命名</span></h3>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>标准变量采用驼峰式命名（除了对象的属性外，主要是考虑到<span
     lang=EN-US>cgi</span>返回的数据）</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>'ID'</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>在变量名中全大写</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>'URL'</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>在变量名中全大写</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>'Android'</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>在变量名中大写第一个字母</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>'iOS'</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>在变量名中小写第一个，大写后两个字母</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>常量全大写，用下划线连接</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>构造函数，大写第一个字母</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>jquery</span><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>对象必须以<span
     lang=EN-US>'$'</span>开头命名</span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>thisIsMyName</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>goodID</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>reportURL</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>AndroidVersion</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>iOSVersion</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>MAX_COUNT</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>10</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>Person</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>name</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>this</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>.</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>name</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>name</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>body</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>$</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span class=s1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#CC3300'>'body'</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>);</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>$body</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>$</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span class=s1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#CC3300'>'body'</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>);</span></span></pre>

<h3 style='vertical-align:top'><a name="_变量声明"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>变量声明</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>一个函数作用域中所有的变量声明提到函数首部，除了<span lang=EN-US>for (...)</span>里面使用的一次性变量。</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>var</span><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>的数量不做限制，但要统一，一行定义一个变量。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>doSomethingWithItems</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>items</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>b</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>var</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>value</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>10</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>result</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>value</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>+</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>10</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>for</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>var</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>len</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>items</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>.</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>length</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>&lt;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>len</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>++</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>result</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>+=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>10</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>doSomethingWithItems</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>items</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>var</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>b</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>value</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>10</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>var</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>result</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>value</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>+</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>10</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>for</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=kd><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>i</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>len</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>items</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>.</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>length</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>i</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>&lt;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>len</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>i</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>++</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>result</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>+=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>10</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=kd><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>doSomethingWithItems</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>items</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>b</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>value</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>10</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>result</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>value</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>+</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>10</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>for</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>var</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>len</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>items</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>.</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>length</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>&lt;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>len</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>++</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>result</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>+=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>10</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_函数"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>函数</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>无论是函数声明还是函数表达式，<span lang=EN-US>'('</span>前不要空格，但<span
lang=EN-US>'{'</span>前一定要有空格；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>函数调用括号前不需要空格；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>立即执行函数外必须包一层括号；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要给<span lang=EN-US>inline function</span>命名；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>参数之间用<span
lang=EN-US>', '</span>分隔，注意逗号后有一个空格。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// no space before '(', but one space before'{'</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>doSomething</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>item</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// do something</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>};</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>doSomething</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>item</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// do something</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nx><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>doSomething</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>item</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nx><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>doSomething</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>item</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// requires parentheses around immediately invoked function expressions</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>function</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>()</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>return</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>})();</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>].</span></span><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>forEach</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=kd><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>()</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>});</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>].</span></span><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>forEach</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=kd><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>()</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>});</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>[</span></span><span class=mi><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>function</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>()</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}];</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>[</span></span><span class=mi><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>function</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>()</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}];</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// use ', ' between function parameters</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>doSomething</span></span><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>b</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>c</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// do something</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>};</span></span></pre>

<h3 style='vertical-align:top'><a name="_数组、对象"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>数组、对象</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>对象属性名不需要加引号；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>对象以缩进的形式书写，不要写在一行；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>数组、对象最后不要有逗号。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=s1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#CC3300'>'b'</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>};</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>b</span></span><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>};</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>b</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>c</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>};</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>b</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>c</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>2</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>};</span></span></pre>

<h3 style='vertical-align:top'><a name="_括号"></a><span style='font-family:"微软雅黑",sans-serif;
color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>括号</span></h3>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>下列关键字后必须有大括号（即使代码块的内容只有一行）：</span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
background:#F7F7F9'>if</span></code><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>,<span
class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:#F7F7F9'>else</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>,</span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
background:#F7F7F9'>for</span></code><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>,<span
class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:#F7F7F9'>while</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>,<span
class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:#F7F7F9'>do</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>,<span
class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:#F7F7F9'>switch</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>,<span
class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:#F7F7F9'>try</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>,<span
class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:#F7F7F9'>catch</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>,<span
class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:#F7F7F9'>finally</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>,<span
class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:#F7F7F9'>with</span></code><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>condition</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>doSomething</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>();</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:
#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>condition</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>doSomething</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>();</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_null"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>null</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>适用场景：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>初始化一个将来可能被赋值为对象的变量</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>与已经初始化的变量做比较</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>作为一个参数为对象的函数的调用传参</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>作为一个返回对象的函数的返回值</span></li>
</ul>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不适用场景：</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>不要用<span
     lang=EN-US>null</span>来判断函数调用时有无传参</span></li>
 <li class=MsoNormal style='color:#5A5A5A;text-align:left;vertical-align:top'><span
     style='font-size:11.0pt;font-family:"微软雅黑",sans-serif'>不要与未初始化的变量做比较</span></li>
</ul>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>test</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>b</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>b</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>===</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kc><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>null</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=c1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>// not mean b is not supply</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>===</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kc><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>null</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=kc><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>null</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>===</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kc><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>null</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_undefined"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>undefined</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>永远不要直接使用<span lang=EN-US>undefined</span>进行变量判断；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>使用<span
lang=EN-US>typeof</span>和字符串<span lang=EN-US>'undefined'</span>对变量进行判断。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>person</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>===</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kc><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>undefined</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=p><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=k><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#006699'>typeof</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>person</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>===</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=s1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#CC3300'>'undefined'</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>...</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<h3 style='vertical-align:top'><a name="_jshint"></a><span lang=EN-US
style='font-family:"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;
font-weight:normal'>jshint</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>用<span lang=EN-US>'===', '!=='</span>代替<span lang=EN-US>'==',
'!='</span>；</span></p>

<p style='vertical-align:top'><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>for-in</span><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>里一定要有<span
lang=EN-US>hasOwnProperty</span>的判断；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要在内置对象的原型上添加方法，如<span lang=EN-US>Array, Date</span>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要在内层作用域的代码里声明了变量，之后却访问到了外层作用域的同名变量；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>变量不要先使用后声明；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要在一句代码中单单使用构造函数，记得将其赋值给某个变量；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要在同个作用域下声明同名变量；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要在一些不需要的地方加括号，例：<span lang=EN-US>delete(a.b)</span>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要使用未声明的变量（全局变量需要加到<span lang=EN-US>.jshintrc</span>文件的<span
lang=EN-US>globals</span>属性里面）；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要声明了变量却不使用；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要在应该做比较的地方做赋值；</span></p>

<p style='vertical-align:top'><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>debugger</span><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>不要出现在提交的代码里；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>数组中不要存在空元素；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要在循环内部声明函数；</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>不要像这样使用构造函数，例：</span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Courier New";color:#D44950;
background:#F7F7F9'>new function () { ... }</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>,<span
class=apple-converted-space>&nbsp;</span></span><code><span lang=EN-US
style='font-size:9.0pt;font-family:"Courier New";color:#D44950;background:#F7F7F9'>new
Object</span></code><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>；</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>==</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>++</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>===</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>++</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>for</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>key</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>in</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>obj</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>if</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>obj</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>.</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>hasOwnProperty</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>key</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>))</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=c1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>// be sure that obj[key] belongs to the object and was not inherited</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>console</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>.</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>log</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>obj</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>key</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>]);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=nb><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#336666'>Array</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>.</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>prototype</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>.</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>count</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>value</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>return</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>4</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>};</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>test</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>()</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=kc><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#006699'>true</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>var</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>0</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>+=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>test</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>()</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>console</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>.</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>log</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>x</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>var</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>x</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=c1><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>new</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>Person</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>();</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>person</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>new</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>Person</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>();</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:
#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>delete</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>obj</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>.</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>attr</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>);</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>delete</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>obj</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>.</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>attr</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>10</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>++</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>[</span></span><span class=mi><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>,</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>,</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>3</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>];</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>nums</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>[];</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:
#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#006699'>for</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=kd><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>i</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>0</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>i</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>&lt;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>10</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>i</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>++</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'> &nbsp;&nbsp;&nbsp;</span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>function</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>i</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>nums</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>[</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>i</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>]</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>j</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>return</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>i</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>+</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>j</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>};</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}(</span></span><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>i</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>));</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>singleton</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>new</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>()</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>var</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>privateVar</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>this</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>.</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>publicMethod</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>()</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>privateVar</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>};</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>this</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>.</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>publicMethod2</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>function</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>()</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>privateVar</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>};</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>};</span></span></pre>

<h3 style='vertical-align:top'><a name="_杂项_1"></a><span style='font-family:
"微软雅黑",sans-serif;color:#2A2A2A;letter-spacing:-.6pt;font-weight:normal'>杂项</span></h3>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要混用<span lang=EN-US>tab</span>和<span lang=EN-US>space</span>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不要在一处使用多个<span lang=EN-US>tab</span>或<span lang=EN-US>space</span>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>换行符统一用<span lang=EN-US>'LF'</span>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>对上下文<span lang=EN-US>this</span>的引用命名范围：<span lang=EN-US>self
&gt; that &gt; _this &gt; me</span>；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>行尾不要有空白字符；</span></p>

<p style='vertical-align:top'><span lang=EN-US style='font-size:11.0pt;
font-family:"微软雅黑",sans-serif;color:#5A5A5A'>switch</span><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>的<span
lang=EN-US>falling through</span>和<span lang=EN-US>no default</span>的情况一定要有注释特别说明；</span></p>

<p style='vertical-align:top'><span style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;
color:#5A5A5A'>不允许三元运算符嵌套。</span></p>

<p style='margin:0cm;margin-bottom:.0001pt;vertical-align:top'><span
style='font-size:11.0pt;font-family:"微软雅黑",sans-serif;color:#5A5A5A'>不允许有空的代码块。</span></p>

<pre style='background:#F7F7F9;vertical-align:top'><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp; </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=kd><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>ret</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>a</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>?</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>b</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>?</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>:</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>3</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// good</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=kd><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>ret</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>b</span></span><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>)</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>ret</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>1</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>else</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>ret</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>else</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>ret</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>3</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><span class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><span class=kd><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#006699'>function</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>Person</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>()</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>{</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=kd><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>var</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=nx><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>self</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=o><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#555555'>=</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>this</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>function</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>a</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>()</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>var</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>that</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>this</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>function</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>b</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>()</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>var</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>_this</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>this</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>function</span></span><code><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>c</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>()</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=kd><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>var</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=nx><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>me</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>=</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=k><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#006699'>this</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>;</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;</span></code></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>}</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>switch</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>condition</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>case</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>1</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>case</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=mi><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#FF6600'>2</span></span><span class=o><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#555555'>:</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>break</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>case</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>3</span></span><span
class=o><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#555555'>:</span></span></pre><pre style='background:#F7F7F9;vertical-align:
top'><code><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span class=c1><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// why fall through</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>case</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=mi><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#FF6600'>4</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;</span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>...</span></span></pre><pre style='background:#F7F7F9;
vertical-align:top'><code><span lang=EN-US style='font-size:8.5pt;font-family:
"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></code><span
class=k><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#006699'>break</span></span><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>;</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;&nbsp;&nbsp; </span></code><span
class=c1><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#999999'>// why no default</span></span></pre><pre style='background:
#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=c1><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#999999'>// not good with empty block</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=k><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#006699'>if</span></span><code><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'> </span></code><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>(</span></span><span class=nx><span lang=EN-US style='font-size:
8.5pt;font-family:"Courier New";color:#5A5A5A'>condition</span></span><span
class=p><span lang=EN-US style='font-size:8.5pt;font-family:"Courier New";
color:#5A5A5A'>)</span></span><code><span lang=EN-US style='font-size:8.5pt;
font-family:"Courier New";color:#5A5A5A'> </span></code><span class=p><span
lang=EN-US style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>{</span></span></pre><pre
style='background:#F7F7F9;vertical-align:top'><code><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>&nbsp;</span></code></pre><pre
style='background:#F7F7F9;vertical-align:top'><span class=p><span lang=EN-US
style='font-size:8.5pt;font-family:"Courier New";color:#5A5A5A'>}</span></span></pre>

<p class=MsoNormal><span lang=EN-US>&nbsp;</span></p>

</div>

</body>

</html>
