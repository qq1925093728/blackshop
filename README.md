# blackshop
##地大黑店

#### ·简介：  
 地大黑店是一个基于SSM（Spring+SpringMVC+MyBatis）的校园二手交易平台项目。是对已有开源项目进行了二次开发，新增的部分功能。具体效果怎么样，嗯。。在我这里是完全调通可以运行的，代码数据库都有，花点时间配一点环境捣鼓一下应该就可以跑了。

#### ·项目来源：  
 在 https://github.com/hlk-1135 看到了他的项目，刚好自己要做一个关于校园二手交易平台，就自己pull下来进行了修改和二次开发，有兴趣的同学可以自己跑跑看看，其实还蛮有意思的。

#### ·系统架构  
 开发环境：IntelliJ IDEA、Atom、Navicat for MySQL

#### ·功能  
 基本实现了一个校园二手交易平台的登录注册、发布商品、浏览商品、修改个人信息、搜索、用户管理、商品管理，系统分为用户和后台管理员两部分。

#### ·目前的问题/仍存在的bug  
 1.代码方面仍在存在冗余？因为是对别人开源项目的二次开发和学习，里面有些包和js具体的使用方法还在学习，有些部分的代码可以进行删改，这个在学习相应部分的知识后进行调整。  
 2.首次页面加载缓慢？！嗯。。这个是历史遗留问题，我在运行的时候确实也发现了这个问题，尤其是在清除浏览器缓存后第一次加载主页的时候，图片刷的很慢，在这里限制了上传图片的大小，希望能够加载的快一点，但是目前来讲。。好像不太奏效。前后端代码交互的优化，个人能力有限，目前只能先这样了。  
 3.管理员后台怎么进？其实这个后台页面在我刚二次开发这个项目的时候，我也很迷，他竟然没有一个登陆通道，需要将浏览器地址最后一个斜杠后面的内容改为/admin，而且登陆后的地址，直接复制进浏览器地址栏，竟然可以直接进后台？我怀疑他只做了个假的后台登陆页面。。。应该要加一个验证的吧，至于怎么做，我现在不会。。。后续应该会修改。  
 4.现在实现了什么？嗯，因为我是地大（北京）的，所以结合自己学习特色，做了部分内容的修改和开发，更符合为我们学校定制的校园二手交易平台的感jio，如果你有兴趣，你可把改为具有你们学校特色校园二手交易平台。	
