# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# 10962ssm衡水特产展销系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 第1章 绪论
## 1.1背景及意义
随着社会的快速发展，计算机的影响是全面且深入的。人们生活水平的不断提高，日常生活中人们对衡水特产展销系统方面的要求也在不断提高，热衷于特产展销的人数更是不断增加，使得衡水特产展销系统的开发成为必需而且紧迫的事情。衡水特产展销系统主要是借助计算机，通过对衡水特产展销系统所需的信息管理，增加用户的选择，同时也方便对广大用户信息的及时查询、修改以及对用户信息的及时了解。衡水特产展销系统对用户带来了更多的便利，该系统通过和数据库管理系统软件协作来满足用户的需求。计算机技术在现代管理中的应用，使计算机成为人们应用现代技术的重要工具。能够有效的解决获取信息便捷化、全面化的问题，提高效率。
## 1.2 国内外研究概况
随着国内经济形势的不断发展，中国互联网进入了一个难得的高峰发展时期，这使得中外资本家纷纷转向互联网市场。然而，许多管理领域的不合理结构，人员不足以及管理需求的增加使得更多的人具备了互联网管理的意识。

在当今高度发达的信息中，信息管理改革已成为一种更加广泛和全面的趋势。 “衡水特产展销系统”是基于Mysql数据库，在JSP程序设计的基础上实现的。为确保中国经济的持续发展，信息时代日益更新，蓬勃发展。同时，随着信息社会的快速发展，衡水特产展销系统面临着越来越多的信息，因此很难获得他们对高效信息的需求，如何使用方便快捷的方式使查询者在广阔的海洋信息中查询，存储，管理和共享信息方面有效，对我们的工作和生活具有重要的现实意义。因此，国内外技术界对此进行了深入而广泛的研究，一个新的研究领域——衡水特产展销系统诞生了。
## 1.3 研究的内容
目前许多人仍将传统的纸质工具作为信息管理的主要工具，而网络技术的应用只是起到辅助作用。在对网络工具的认知程度上，较为传统的office软件等仍是人们使用的主要工具，而相对全面且专业的衡水特产展销系统的信息管理软件仍没有得到大多数人的了解或认可。本选题则旨在通过标签分类管理等方式，实现管理员；个人中心、用户管理、特产商品管理、商品类型管理、我的收藏管理、系统管理、订单管理，用户；个人中心、特产商品管理、我的收藏管理、订单管理，前台首页；首页、特产商品、我的收藏管理、我的、跳转到后台、购物车、客服等信息管理功能，从而达到对衡水特产展销系统信息的高效管理。


# 第2章 相关技术
## 2.1 JSP技术介绍
JSP技术本身是一种脚本语言，但它的功能是十分强大的，因为它可以使用所有的JAVA类。当它与JavaBeans 类进行结合时，它可以使显示逻辑和内容分开，这就极大的方便了用户的需求。JavaBeans 可以对JSP技术的程序进行扩展，从而形成新的应用程序，而且JavaBeans的代码可以重复使用，所以就便于对程序进行维护。JavaBean 组件有内部的接口，可以帮助不同的人对系统进行访问。1999年，Sun微系统公司正式推出了JSP技术，这是一种动态技术，是基于整个JAVA体系和JavaServlet提出的，是具有普遍适用性的WEB技术，也是本系统设计的核心技术之一。JSP技术能够极大的提高WEB网页的运行速度。这些内容会与脚本结合，并且由JavaBean和Servlet组件封装。所有的脚本均在服务器端运行，JSP引擎会针对客户端所 提交的申请进行解释，然后生成脚本程序和JSP标识，然后通过HTML/XML页面将结果反馈给浏览器。因此，开发人员亲自设计最终页 面的格式和HTML/XML标识时，完全可以使用JSP技术。

所以结合衡水特产展销系统的需求及功能模块的实现，使用JSP技术是最合适的，而且JSP的拓展性比较好，对于衡水特产展销系统在后期使用过程中可以不断对系统功能进行拓展，使系统更完善，更方便的满足用户需求。
## 2.2 MyEclipse开发环境
MyEclipse支持广泛、兼容性高并且功能强大，是一个Eclipse 插件集合，普遍适应于JAVA和J2EE的系统开发，支持 JDBC，Hibernate，AJAX，Struts，Java Servlet，Spring，EJB3等市面上存在的几乎所有数据库链接工具和主流Eclipse产品 开发工具。 

MyEclipse在业内是所熟知的开发工具，该平台在开发的过程中运用的就是该工具。MyEclipse又被称之为企业级的工作平台，它是以Eclipse IDE为基础的。MyEclipse可以帮助我们进行数据库的研发和J2EE的使用，除此之外，还可以提高系统的运营能力，这突出表现在服务器的整合过程中。MyEclipse的功能相当完备，能够为J2EE的集成提供必要的环境支持，从而完成编码、测试、调试及发布等功能。它可以支持JSP，HTML，SQL，Javascript，Struts， CSS等。
## 2.3 Tomcat服务器
Tomcat属于一种轻型的服务器，所以说在中小企业中并不具有普适性。但是当程序员需要开发或调试JSP 程序时，则通常会将该服务器作为首选。对于一个仅具有计算机基础知识的人来说，计算机系统具有一个好的Apache服务器，可以很好的对HTML 页面进行访问。Tomcat 虽然是Apache的扩展，但是它们都是可以独立运行的，二者是不互相干扰的。当配置正确的时候，Apache服务器为HTML 页面的运行提供技术支持，Tomcat 的任务则是运行Servle和JSP 页面。Tomca也具有一定的HTML页面处理功能。
## 2.4 MySQL数据库
Mysql的语言是非结构化的，用户可以在数据上进行工作。因为Mysql的语言和结构比较简单，但是功能和存储信息量很强大，所以得到了普遍的应用。

Mysql数据库在编程过程中的作用是很广泛的，为用户进行数据查询带来了方便。Mysql数据库的应用因其灵活性强，功能强大，所以在实现某功能时只需要一小段代码，而不像其他程序需要编写大段代码。总体来说，Mysql数据库的语言相对要简洁很多。 
## 2.5 JAVA简介
Java主要采用CORBA技术和安全模型，可以在互联网应用的数据保护。它还提供了对EJB（Enterprise JavaBeans）的全面支持，java servlet API，Java（java server pages），和XML技术。JAVA语言是一种面向对象的语言，它通过提供最基本的方法来完成指定的任务，开发者只需要知道一些概念就能够编写出一些应用程序。Java程序相对较小，其代码能够在小机器上运行。Java是一种计算机编程语言，具有封装、继承和多态性三个主要特性，广泛应用于企业Web应用程序开发和移动应用程序开发。

Java语言和一般编译器以及直译的区别在于，Java首先将源代码转换为字节码，然后将其转换为JVM的可执行文件，JVM可以在各种不同的JVM上运行。因此，实现了它的跨平台特性。虽然这使得Java在早期非常缓慢，但是随着Java的开发，它已经得到了改进。

# 第3章 系统分析
## 3.1 需求分析
衡水特产展销系统主要是为了提高工作人员的工作效率和更方便快捷的满足用户，更好存储所有数据信息及快速方便的检索功能，对系统的各个模块是通过许多今天的发达系统做出合理的分析来确定考虑用户的可操作性，遵循开发的系统优化的原则，经过全面的调查和研究。

系统所要实现的功能分析，对于现在网络方便的管理，系统要实现用户可以直接在平台上进行查看所有数据信息，根据需求可以进行在线添加，删除或修改衡水特产展销系统信息，这样既能节省时间，不用再像传统的方式耽误时间，真的很难去满足用户的各种需求。所以衡水特产展销系统的开发不仅能满足用户的需求，还能减少原有不必要的工作量，大大提高了管理员的工作效率。
## 3.2 系统可行性分析
### 3.2.1技术可行性：技术背景     
本网站在Windows操作系统中进行开发，并且目前PC机的性能已经可以胜任普通网站的web服务器。系统开发所使用的技术也都是自身所具有的，也是当下广泛应用的技术之一。

系统的开发环境和配置都是可以自行安装的，系统使用JSP开发工具，使用比较成熟的Mysql数据库进行对系统前台及后台的数据交互，根据技术语言对数据库，结合需求进行修改维护，可以使得网站运行更具有稳定性和安全性，从而完成实现网站的开发。

（1）硬件可行性分析

系统管理及信息分析的设计对于所使用的计算机没有什么硬性的要求，计算机只要可以正常的使用进行代码的编写及页面设计就可行，主要是对于服务器有些要求，对于平台搭建完成要上传的服务器是有一定的要求的，服务器必须选择安全性比较高的，然后就是在打开网站必须顺畅，不能停顿太长时间；性价比高；安全性高。

（2）软件可行性分析

开发整个系统使用的是云计算，流量的可扩展性和基于流量的智能调整云计算的优点就是流量的可扩展性和基于流量的智能调整，保障系统的安全和数据信息的及时备份。

因此，我们从两个方面进行了可行性研究，可以看出系统的开发没有问题。
### 3.2.2经济可行性
在衡水特产展销系统开发之前所做的市场调研及其他相关的管理系统，都是没有任何费用的，都是通过开发者自己的努力，所有工作都是自己亲力亲为，在碰到自己比较难以解决的问题，大多是通过同学和指导老师的帮助进行相关信息的解决，所以对于衡水特产展销系统的开发在经济上是完全可行的，没有任何费用支出的。

使用比较成熟的技术，系统是基于JSP的开发，采用Mysql数据库。所以系统在开发人力、财力要求不高，具有经济可行性。
### 3.2.3操作可行性： 
可操作性主要是对衡水特产展销系统设计完成后，用户的使用体验度，以及管理员可以通过系统随时管理相关的数据信息，并且对于管理员、用户二个权限角色，都可以简单明了的进入到自己的系统界面，通过界面导航菜单可以简单明了地操作功能模块，方便用户信息的操作需求和管理员管理数据信息，对于系统的操作，不需要专业人员都可以直接进行功能模块的操作管理，所以在系统的可操作性是完全可以的。本系统的操作过程使用的也是界面窗口进行登录，所以操作人员只要会简单的电脑操作就完全可以的。
## 3.3 项目设计目标与原则
1、关于衡水特产展销系统的基本要求

（1）功能要求：个人中心、用户管理、特产商品管理、商品类型管理、我的收藏管理、系统管理、订单管理等功能模块。

（2）性能：在不同操作系统上均能无差错实现在不同类型的用户登入相应界面后能不出差错、方便地进行预期操作。

（3）安全与保密要求：用户都必须通过注册、登录才能进入系统。

（4）环境要求：支持Windows系列、Vista系统等多种操作系统使用。

2、开发目标

衡水特产展销系统的主要开发目标如下：

（1）实现管理系统信息关系的系统化、规范化和自动化；

（2）减少维护人员的工作量以及实现用户对信息的控制和管理；

（3）方便查询信息及管理信息等；

（4）通过网络操作，提高改善处理问题和操作人员工作的效率；

（5）考虑到用户多样性特点，要求界面和操作简便易懂。

3、设计原则

本衡水特产展销系统采用JSP技术，Mysql数据库开发，充分保证了系统稳定性、完整性。 

衡水特产展销系统的设计与实现的设计思想如下： 

1. 操作简单方便、系统界面安全良好、简单明了的页面布局、方便查询相关信息。

2、即时可见：对衡水特产展销系统信息的处理将立马在对应地点可以查询到，从而实现“即时发布、即时见效”的系统功能。 
## 3.4系统流程分析
### 3.4.1操作流程
系统登录流程图，如图所示：

![](/md/blog.001.png)

图3-1登录流程图
### 3.4.2添加信息流程
添加信息流程图，如图所示：

![](/md/blog.002.png) 

图3-2添加信息流程图

### 3.4.3删除信息流程
删除信息流程图，如图所示：

![](/md/blog.003.png)

图3-3删除信息流程图



# 第4章 系统设计
## 4.1 系统体系结构
衡水特产展销系统的结构图4-1所示：

网

络

管理员

服务器和程序

用户

![](/md/blog.004.png)

图4-1 系统结构

登录系统结构图，如图4-2所示：

衡水特产展销系统登录界面

用户登录

密码正确

管理员界面

用户界面

![](/md/blog.005.png)

图4-2 登录结构图

衡水特产展销系统结构图，如图4-3所示。

![](/md/blog.006.png)

图4-3 衡水特产展销系统结构图
## 4.2开发流程设计
系统流程的分析是通过调查系统所涉及问题的识别、可行性、可操作性、系统分析处理能力等具体环节来调节、整理系统的设计方案以确保系统能达到理想的状态。这些操作都要从注册、登录处着眼进行一系列的流程测试保证数据库的完整，从而把控系统所涉及信息管理的安全、保证信息输入、输出正常转换。然后，通过实际操作完成流程图的绘制工作。

衡水特产展销系统的开发对管理模块和系统使用的数据库进行分析，编写代码，系统测试，如图4-4所示。

![](/md/blog.007.png)

图4-4开发系统流程图
## 4.3 数据库设计原则
学习编程，我们都知道数据库设计是基于需要设计的系统功能，我们需要建立一个数据库关系模型，用于存储数据信息，这样当我们在程序中时，就没有必要为程序页面添加数据，从而提高系统的效率。数据库存储了很多信息，可以说是信息管理系统的核心和基础，数据库还为系统提供了添加、删除、修改和检查等操作模块，使系统能够快速找到自己想要的信息，而不是在程序代码中找到。数据库中信息表的每个部分根据一定的关系精确地组合，排列和组合成数据表。 

通过衡水特产展销系统的功能进行规划分成几个实体信息，实体信息将通过ER图进行说明，本系统的主要实体图如下：

管理员信息属性图如图4-5所示。

![](/md/blog.008.png)

图4-5 管理员信息实体属性图


特产商品信息属性图如图4-6所示

![](/md/blog.009.png)

图4-6特产商品信息属性图

用户信息属性图如图4-7所示。

![](/md/blog.010.png)

图4-7用户信息实体属性图

订单信息实体属性图如图4-8所示。

![](/md/blog.011.png)

图4-8订单信息实体属性图
## 4.4 数据表
将数据库概念设计的E-R图转换为关系数据库。在关系数据库中，数据关系由数据表组成，但是表的结构表现在表的字段上。

表名：shangpinleixing

功能：商品类型

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinleixing|varchar|200|商品类型|||




表名：techanshangpin

功能：特产商品

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinbianhao|varchar|200|商品编号|||
|shangpinmingcheng|varchar|200|商品名称|||
|leixing|varchar|200|类型|||
|tupian|varchar|200|图片|||
|shangpinxiangqing|varchar|200|商品详情|||




表名：token

功能：token表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|userid|bigint||用户id|||
|username|varchar|100|用户名|||
|tablename|varchar|100|表名|||
|role|varchar|100|角色|||
|token|varchar|200|密码|||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|expiratedtime|timestamp||过期时间||CURRENT\_TIMESTAMP|




表名：yonghu

功能：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zhanghao|varchar|200|账号|||
|mima|varchar|200|密码|||
|xingming|varchar|200|姓名|||
|xingbie|varchar|200|性别|||
|shouji|varchar|200|手机|||
|youxiang|varchar|200|邮箱|||
|shenfenzheng|longtext|4294967295|身份证|||
|touxiang|date||头像|||




表名：storeup

功能：收藏表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||用户id|||
|refid|bigint||收藏id|||
|tablename|varchar|200|表名|||
|name|varchar|200|收藏名称|||
|picture|varchar|200|收藏图片|||




表名：config

功能：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||





表名：users

功能：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|




# 第5章 系统详细设计
##
## 5.1前台首页功能模块
衡水特产展销系统，在衡水特产展销系统可以查看首页、特产商品、我的收藏管理、我的、跳转到后台、购物车、客服等内容，如图5-1所示。

![](/md/blog.012.png)

图5-1系统首页界面图

用户登录、用户注册，通过注册填写账号、密码、姓名、手机、邮箱、身份证等信息进行登录、注册操作，如图5-2所示。

![](/md/blog.013.png)

![](/md/blog.014.png)

图5-2用户登录、用户注册界面图

特产商品，在特产商品页面可以查看商品编号、商品名称、类型、图片、商品详情、价格等信息进行添加到购物车、立即购买，如图5-3所示。 

![](/md/blog.015.png)

图5-3特产商品界面图

个人中心，在个人中心页面可以查看账号、密码、姓名、性别、手机、邮箱、身份证、头像、余额等信息进行更新信息、退出登录如图5-4所示。

![](/md/blog.016.png)

图5-4个人中心界面图

##
##
## 5.2管理员功能模块 
管理员登录，通过填写用户名、密码等信息，输入完成后选择登录即可进入衡水特产展销系统，如图5-5所示。

![](/md/blog.017.png)

图5-5管理员登录界面图


衡水特产展销系统，在衡水特产展销系统可以查看个人中心、用户管理、特产商品管理、商品类型管理、我的收藏管理、系统管理、订单管理等内容，如图5-6所示。

![](/md/blog.018.png)

图5-6管理员功能界面图

特产商品管理，通过填写商品编号、商品名称、类型、图片、商品详情、价格等信息进行查看、修改、删除操作，如图5-7所示。

![](/md/blog.019.png)

图5-7特产商品管理界面图

商品类型管理，在商品类型管理页面可以查看商品类型等信息进行修改、删除、查看，如图5-8所示。 

![](/md/blog.020.png)

图5-8商品类型管理界面图

我的收藏管理，在我的收藏管理页面可以查看用户ID、收藏ID、表名、收藏名称、收藏图片等信息进行查看、修改、删除，如图5-9所示。

![](/md/blog.021.png)

图5-9我的收藏管理界面图

客服聊天表，在客服聊天表页面可以查看提问、是否回复等信息进行查看、修改、删除，如图5-10所示。

![](/md/blog.022.png)

图5-10客服聊天表界面图


已支付订单，在已支付订单页面可以查看订单ID；用户ID、商品ID、商品名称、商品图片、购买数量、价格/积分、折扣价格、总价格/总积分、折扣总价格、

支付类型、状态、地址等信息进行查看、修改、删除，如图5-11所示。

![](/md/blog.023.png)

图5-11已支付订单界面图

已退款订单，在已退款订单页面可以查看订单ID；用户ID、商品ID、商品名称、商品图片、购买数量、价格/积分、折扣价格、总价格/总积分、折扣总价格、支付类型、状态、地址等信息进行查看、修改、删除，如图5-12所示。

![](/md/blog.024.png)

图5-12已退款订单界面图

## 5.3用户功能模块 
特产商品管理，在特产商品管理页面通过填写商品编号、商品名称、类型、图片、商品详情、价格等信息进行查看如图5-13所示。

![](/md/blog.025.png)

图5-13特产商品管理界面图

我的收藏管理，在我的收藏管理页面可以查看用户ID、收藏ID、表名、收藏名称、收藏图片等信息查看、修改、删除，如图5-14所示。

![](/md/blog.026.png)

图5-14我的收藏管理界面图

已退款订单，在已退款订单页面可以查看订单ID；用户ID、商品ID、商品名称、商品图片、购买数量、价格/积分、折扣价格、总价格/总积分、折扣总价格、支付类型、状态、地址等信息删除操作，如图5-15所示。

![](/md/blog.027.png)

图5-15已退款订单界面图

# 










