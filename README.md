大规模集成网页 (LSIP)
====================
大萌　2022-2024	<base target="_blank">

　　集成网页是**集**某个主题方向网址之**大成**的网页。集成网页利用超文本或数据库技术，把主题内容和大量的链接融合，建立结构化目录，集中在一个静态网页上，是一种数据化网页，也是web3.0众多竞争形式之一。　按照集成规模，当链接数量超过一百，称之为‘中型集成网页(MSIP)’；当链接数量超过一千，称之为‘**大规模集成网页**’(LSIP，Large Scale Integrated web Page)；当链接数量超过一万，称之为‘超大规模集成网页(VLSIP)’。

+	MSIP示例：[国际组织四大类](https://LaoSheng.top/ydyl/untied) 🌐
+	LSIP示例：[高等院校三千所](https://LaoSheng.top/fuwu/yuanxiao) 👨‍🎓

　　过去，这种数据全集一般以数据库形式保存于服务器，由服务器脚本向用户输出查询子集，实现该查询过程的网页被称为‘动态网页’。这种把数据隐藏在服务器之后的网页被称作[DeepWeb](https://www.oalib.com/search?type=0&oldType=0&kw=deepweb&searchField=All)；　而随着网络速度的提高和浏览器能力的增强，服务器也可以直接发送数据全集给浏览器，把数据查询、筛选、排序等工作交给**浏览器**完成。集成网页就是一种包含某方面数据全集的‘静态网页’，用户对数据的查询通过浏览器在本地实现，不需要再次经过服务器，既节省了网络交互次数、时间，又提高了对数据检索、利用的自由度。

　　大规模集成网页(LSIP)利用更快更强的网络，把DeepWeb的数据上升到前端，是 [web 3.0](https://cn.bing.com/search?q=web+3.0) 的一种可能形式。‘LSIP’概念由大萌于2022年7月通过[在Github建立项目](https://github.com/DiamonWoo/LSIP)首次发表，该项目以LSIP为主体，讨论‘集成网页’的理论与实践。


LSIP的技术优势
-------------
Advantages

　　大规模集成网页(LSIP)把数据交给用户，在技术上主动提供了网站数据被复制的可能。　这与传统动态网页在安全策略上相反。动态网页把数据全集藏在服务器后面的数据库，用户无法直接获取，如果有黑客绕过了服务器脚本，直接下载网站的数据库，叫做‘被拖库’，属于严重的网络安全事故。

　　LSIP在技术上属于‘静态网页’，静态网页的优势它都有。

*	服务器负担小，更安全。	
*	搜索引擎容易收录。
*	用户容易保存。

　　LSIP的数据不仅向用户开放，而且向互联网开放 —— 这是App不愿意做的事情。包括搜索引擎在内的其他网站均可以对数据进行检索、复制和再利用，这使得数据的复用率增加。　数据复用率增加将帮助数据获得进一步利用：统计、识别、机器学习，LSIP由此产生衍生信息。这个过程常被称为‘[数据挖掘(Data Mining)](https://www.zhihu.com/topic/19553534/hot)’。

　　缺点是，LSIP在制作和更新上难度更大。不过这些困难都是留给网页作者的，读者不用管。


LSIP的主题方向
-------------
Themes or Future

　　大规模集成网页 适合原本公开的数据，比如法律条款、政策文件、政府公开数据……等等。这些数据本来就允许用户复制，而LSIP能让用户复制得更快。

　　如果说，“语料是各种AI的关键”[<sup>[1]</sup>](#can)，那么LSIP就是AI大模型的金矿。LSIP可以成为人工智能(AI)的语料入口。

　　公开数据中有一些并不适合LSIP。那些随时随地会变化的数据，比如互联网的域名注册信息。用户即使下载了某一时刻的数据全集，下一秒的变化仍然需要到服务器查询，起不到节省网络交互次数的作用。　那些没有明确数量的数据，也不适合LSIP，网页的制作永远无法完成，只能‘集’，无法‘成’。

　　综上所述，大规模集成网页(LSIP)适用于公开类数据、有限集数据。


LSIP的技术指标 📐
----------------
Technical Indicators

　　光有一个链接数，还不能评价一个网页是否成为LSIP，否则把一个网页做的又丑又长就能轻易达标。当我们拆开一台手机或电脑，可以看到里面的集成电路块很小，大部分芯片的尺寸不会超过一块橡皮擦；而里面的晶体管又特别多，这才体现了既要‘大规模’又能‘集成一小块’的技术特点。 集成网页需要指标来衡量类似的技术特点。

　　大萌为**集成网页**设定以下技术指标：

+ [链接计数（LC）](LC){:target="_top"}，Link Count

　　页面单一主题下，链接的统计个数。　不是简单的页面链接总数，而是主题之内的链接计数；要排除主题之外的链接，比如页眉页脚的导航链接、页面内部的跳转链接、嵌入的广告链接，都要排除。

+ [存档大小](mht-size){:target="_top"}，mht-size of web archive file

　　网页存档为.mht文件的大小，以KB计数。　网页用浏览器保存为[单一文件网页（.mht）](mhtml)，并且在用户本地打开后能呈现该网页主题的全部链接。也就是说，网页被用户复制到本地后不损失‘链接计数（LC）’。mht是‘MHTML’的简写，也称‘Web档案/网页归档’。

+ [链接密度（LD）](LD){:target="_top"}，Link Density

　　‘链接计数’与网页存档大小的比值，称为‘链接密度’。计算公式：
```
		LD = LC / mht-size (KB)
```
　　如果一个网页的链接计数超过1000，并且链接密度大于1，则可称之为‘大规模集成网页’，条件如下：
```
	LSIP:		LC ≥ 1000
		&	LD > 1
```
　　以一个收录1000个链接的网页为例，要把存档大小控制在1000KB（1MB）之内，才能称为LSIP。换个角度计算，也就是说，LSIP每个链接所占用的存档大小不能超过1KB。　在物理学中，水(H2O)的密度为1，如果一个物体密度小与1，那么它会浮在水面；如果一个网页的链接密度(LD)小于1，那么这个网页就‘太水了’，算不上集成网页。🙄


大萌的LSIP项目 📊
----------------
LSIP Projects by Diamon

　　大萌是在制作网页的实践过程中提出的LSIP的概念，又在提出LSIP概念后明确了实践的方向。其中有四个网页称得上是典型的LSIP：

+	🗺[外交国别速查表](https://Laosheng.top/ydyl/nations)，简称：国别表。
	　249个国家或地区概况、政府网址、ISO代码、双方使馆……
+	🧧[央企股票全家福](https://Laosheng.top/fuwu/yangqi)，简称：央企股。
	　400多家央企上市公司的：股票代码、行情页面、公司官网
+	🏢[法治政府部门集](https://Laosheng.top/fuwu/fazhi)，简称：法门集。
	　333个地级市的立法/普法/执法/司法/监察部门网址
+	📑[中国千县地名网](https://Laosheng.top/fuwu/qianxian)，简称：千县网。
	　3212个县级以上政府网址，按身份证号排序

这些LSIP项目的技术指标如下：

|项目简称 与版本|链接计数(LC)|存档大小|链接密度(LD)|
|-------------|------------|-------|-----------|
|国别表 v0.7.7|	1431	|	662 KB|	2.168|
|央企股 v0.4.1|	1109	|	358 KB|	3.098|
|法门集 v0.9.4|	3045	|	542 KB|	5.618|
|千县网 v0.6.7|	3205	|	559 KB|	5.733|

<br>
　　还有一些页面尚在设计与制作过程中，部分页面将达到超大规模集成网页（VLSIP）：

+	<del>〖中国新闻云媒体 plus版〗，设计LC > 2100。</del>  
	　筹备中，在前文MISP‘云媒体’的基础上，增加媒体官网、微博，达到LSIP规模。
+	👨‍🎓 [高等院校三千所](https://Laosheng.top/fuwu/yuanxiao)，设计LC ≈ 3000，LSIP规模。  
	　收录中国军校、普通高校、港澳台高校等官方网址。（已完成）
+	🛂[中国千县公检法](https://Laosheng.top/fuwu/qianxian-gjf)，设计LC ≥ 12800，VLSIP规模。  
	　收录中，中国3212个县级以上政府网址、公安微博、两院网址，是‘法门集’的配套页面。
+	〖中国政法区划集〗，设计LC ≥ 13200，VLSIP规模。  
	　筹备中，以法门集和公检法两个页面为基础，增补非行政区的政府机构网址及公检法网址。

　　相关文档：

+	《从国际网站的语言支持看中国在世界的影响力》—— 集成网页的宏观分析示范。
+	🏆《[从世界杯看国别表](https://laosheng.top/broad/2022/worldcup)》—— LSIP的应用示范文档
+	LoL 版权声明，License of LSIP 大规模集成网页许可证 —— 促进LSIP发展，避免LSIP滥用
+	《用大规模集成网页对抗互联网垃圾农场》 —— 垃圾农场污染万维网，LSIP提纯万维网。


LSIP 缘起与命名
--------------
Named

　　‘集成网页’的实践，最早在2019年大萌制作《老生常谈云媒体》网页时出现，大萌在新冠疫情初期搜索各地官方媒体网站时遇到困难，便萌发出，要把所有官媒网站收录在一个网页的想法 ……

　　[LSIP 缘起与命名](named){:target="_top"}

　　新概念诞生了！《[中国千县政府网](https://LaoSheng.top/fuwu/qianxian)》可以称作：‘大规模集成网页’！英文：Large Scale Integrated web Page，缩写为：LSIP。

　　大规模集成电路，LSIC，指的是，集成超过1000个晶体管的电路。  
　　大规模集成网页，LSIP，指的是，集成超过1000个超链接的网页。


LSIP的产业成本
-------------
Cost

　　LSIC之所以能流行，是因为它为广泛需求提供了低成本解决方案，LSIP同样需要这个优势。

　　LSIC的初级原料非常便宜，是二氧化硅（沙），原料成本可以忽略。所以，LSIC的成本主要在设计环节和生产(复制)环节，而且往往由不同的企业分工。比如，华为设计海思芯片，交给台积电生产。

　　LSIP的初级原料是网址数据(超链接)，通常也容易获得；而网页的生产(复制)环节几乎是零成本，所以，LSIP成本的重点在于设计环节。　集成电路的设计有相当的难度，需要计算机辅助，集成网页也将朝这个方向发展，集成规模越大，设计难度越大。

　　但是LSIP还有一个硬件没有的成本——更新。传统硬件在出售之后，除了故障维修基本上不再有产品更新，我们的手机内存用满了能找厂家换个大内存吗？不能。华为除外！[<sup>[2]</sup>](#can)　但是集成网页可以升级到更大、更新。LSIP的本质是一个集文档、软件、互联网项目于一体的综合性产品，文档有审校任务，软件有升级任务，互联网有更新任务，不同的领域对产品后续维护的说法不一样。读者当然会期待在LSIP上能够看到最新最全的内容，这是LSIP的更新目标。

　　综上所述，二者的初级原料成本都很低，集成电路的成本在设计、制造，集成网页的成本在设计、更新。如果您想加入LSIP创作者队伍，您需要准备设计和更新的能力。


LSIP的设计软件 💾
----------------
Design Software

　　LSIP设计可分三个阶段：第一阶段：**信息**；经过提取、纯化后进入第二阶段：**数据**；经过关联、组织形成数据库；最后通过数据库输出HTML代码到第三阶段：**网页**。

　　LSIP概念还是刚刚提出，目前IT界没有专门的设计软件，但是三个设计阶段都有现成的软件可用。通过软件功能的组合，以及一些低代码的编程工作，可以使得LSIP的设计半自动化，大大提高设计效率。　大萌根据自身的设计经验，列举如下：

*	<b>信息采集</b> Information Collection  
	* 文本提取与提纯（各种[文本编辑器](https://github.com/topics/editor)、电子表格）
	* 网页爬虫（py或js脚本）

*	<b>信息数据化</b> Digitization of information  
	* 关系型数据库（如[SQLite](https://github.com/topics/sqlite)）
	* AI文本分析（如ChatGPT）

*	<b>数据网页化</b> Data conversion web pages  
	* 高效能H5与CSS
	* js主从表查询/js表格排序/js站内搜索

　　大萌希望LSIP能够既适宜人类阅读，又方便机器检索，以符合W3C提出的‘[语义网](https://www.chinaw3c.org/search/语义网/)’([Semantic Web](https://www.w3.org/2001/sw/))愿景。这对设计水平是个挑战。<img align="right" src="https://www.w3.org/Icons/SW/sw-horz-w3c.png" onerror="this.src='sw-web-to-w3c-bw.png'" />

　　LSIP在设计完成进入维护环节后，主要进行 网址检测 工作，以保证链接的有效性。

*	<b>网址检测</b> URL detection  


　　大萌希望**有识之士**加入LSIP创作者队伍，欢迎大家在自己感兴趣的领域设计、制作‘大规模集成网页’，为祖国高质量发展出力！

　　I hope users of other languages to make LSIP projects for their fellow citizens, which can help people understand the world as whole more easily, which is not something that Twitter and Facebook can do.

　　欢迎读者[留言讨论](https://laosheng.top/c/author)，github用户可提交issue。


in English
----------
✴️✳️❇️🕎⚛️❄️💮🏵️

　　The 'integrated web page' is a new web form based on the World Wide Web (WWW):
Integrate all hyperlinks under the same topic on a single web page, to implement the full set of URLs for that topic.

　　When the number of hyperlinks exceeds one thousand, it is called a 'Large Scale Integrated  web Page' (LSIP), named by DiamonWoo on [github.com](https://diamonwoo.github.io/LSIP/) , 202207.

　　If you have a strong will and a pure heart, join in!


<h2 id='can'>参考文献</h2>

*	[1]：科技爱好者周刊（第 299 期）：[AI 的关键是语料](https://www.ruanyifeng.com/blog/2024/05/weekly-issue-299.html)
*	[2]：华为消费者业务网站：[华为内存升级服务](https://consumer.huawei.com/cn/support/storage-upgrade/)


```
	CC 3.0 BY-NC-ND　可转载-需署名-非演绎
	大规模集成网页(LSIP)© 2022-2023 大萌
	https://diamonwoo.github.io/LSIP
	Version	0.5.2 	202406
```

LSIP是[老生常谈](https://Laosheng.top/yan/ )网站的衍生项目
