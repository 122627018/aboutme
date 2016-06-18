

###随车行
+ 通过扫码绑定一辆电动车,实现地图功能和社交功能的一个app
+ 集成百度地图api,实现地点搜索导航
+ 集成环信IM,实现了聊天模块和好友模块,结合地图实现附近的人勾搭功能
+ 采用自封装的MVP结构,通过RxAndroid结合网络访问框架让整个项目代码简洁,业务逻辑清晰.
+ 增强版的Retrofit+RxJava网络访问框架，优雅地完成了整个框架的异常处理机制
+ github:https://github.com/122627018/ASElectricBicycle

###嘉大助手
+ 第一个个人项目,实现了失物找回,校园活动,宿舍报修,新闻获取,用户模块等
+ 移动端采用MVC的架构,完成了对JavaWeb服务器端的Json数据的获取并解析
+ 通过大量的自定义view(包括dialog,button),还有自定义动画等实现酷炫的界面效果
+ github:https://github.com/122627018/jyu

###校园通
+ 通过对校园网的抓包实现学号与app账号的绑定,集成了上一个项目-嘉大助手的各个模块，从而实现一个可以实时获取教务信息的社交软件
+ 通过服务器对网页抓包实现学生个人信息,成绩,课表,选课情况,图书馆借阅情况,馆藏搜索的功能
+ 采用Materia Design的设计风格,和v7包最新控件的使用
+ github:https://github.com/122627018/MySchool


###TeachingOffice
+ 对校园网进行抓包并数据解析的一个demo
+ 无需服务器,直接在手机客户端对网页进行抓包
+ 使用jsoup对html代码进行解析
+ github:https://github.com/122627018/TeachingOffice

###TeachingOffice2
+ 对上个版本的进行代码重构，从mvc重构为MVP结构
+ 讲访问网页的驱动器迁移到JavaWeb服务器，有服务器进行抓包解析数据
+ 应用RxAndroid+Retrofit进行网络数据的请求
+ github:https://github.com/122627018/TeachingOffice2


###Retorfit_RxJava_Exception
+ 优雅地处理服务器返回的错误和客户端访问网络过程中产生的错误
+ blog：http://blog.csdn.net/qq122627018/article/details/51689891
+ github：https://github.com/122627018/Retorfit_RxJava_Exception

###RetrofitException
+ 通过对Retrofit+RxJava的工作原理，实现自定义Retrofit的gson解析工厂
+ blog：http://blog.csdn.net/qq122627018/article/details/51540812
+ github：http://blog.csdn.net/qq122627018/article/details/51689891


###BaseMVP
+ 一个最基础的mvp代码结构，优雅地处理了各层之间的绑定和初始化。解决了presenter和activity的生命周期方法
+ 详情见blog：http://blog.csdn.net/qq122627018/article/details/51684882

###BlogDemo
+ 抓包的一个demo，展示了HTtpUrlConnection的使用
+ 详情见blog：http://blog.csdn.net/qq122627018/article/details/51473150

###ChatActWidget
+ 这是一个聊天界面的控件
+ 从环信EM的客户端抽取出来，再加上自己重构实现自定义控件和表情组的功能
