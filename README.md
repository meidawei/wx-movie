# 一个基于微信小程序所制作的电影小程序 #

## 前言

前段时间工作实在太忙，经常加班到12点以后。所以原先计划完成的微信小程序就搁置了，大概只完成了40%。最近闲下来了，终于可以把这个项目的1.0版本收尾了。本人之前并未接触过小程序的开发，连api都没怎么看过。趁这次粗略地看了一下官方文档，小程序的api还真是非常地庞大。由框架、组件、API三部分组成。相信要把这些api都熟悉起来，还需要段时间。由于接触小程序的时间还不长，并且这只是1.0版本，所以现在还并没有调取微信的登录接口。项目本身由阅读和电影二部分组成，阅读这部分相对简单。数据采用的是本地mock，没有什么好说的。第二部分电影调取了豆瓣免费的api接口，能够获取数据。不过在开发过程中，发现搜索接口的获取数据已经大不如前了。很多数据都搜索不到。未来计划对项目代码再做一些优化，并且以此为基础完善一些其他的功能，比如：登录，分享...

## 技术栈

微信小程序 + ES6 + less + flex + iconfont

## 目录结构介绍 ##

	|-- data                             // 本地mock数据目录
	|-- fonts                            // iconfont目录
	|-- images                           // 静态资源图片目录
	|-- page                             // 页面目录
	|   |-- guide                        // 首页目录
	|   |-- movies                       // 电影页目录
	|      |-- detail                    // 电影详情页目录
	|      |-- more-movie                // 更多电影页目录
	|   |-- posts                        // 阅读页目录
    |      |-- detail                    // 阅读详情页目录
	|-- template                         // 公用组件目录
	|   |-- movie                        // 单个电影信息组件
    |   |-- movies-grid                  // 更多电影组件
    |   |-- movies-list                  // 电影列表组件
    |   |-- posts                        // 阅读预览组件
    |   |-- stars                        // 星星评分组件
    |-- util                             // 全局方法目录
	|-- app.js                           // 项目入口脚本
	|-- app.json                         // 小程序全局配置文件
	|-- app.wxss                         // 项目全局样式文件
	|-- project.config.json              // 项目配置文件

## 结语

前端的路其实一直就不太好走，而且前端要学的技术其实很多很杂。迭代是如此之快，使得我们必须要花更多地时间去学习。特别是一些新技术的api本身就写的晦涩难懂，更是加大了学习的成本。所以我一直认为，身为前端攻城狮，如果你从骨子里，血液里没有一点对编程的兴趣或者说是热爱，只是把它当成是一种谋生的工具的话，真的很难坚持下去。所以我们既然选择了这样的一条路，我们就应该不忘初心，脚踏实地的走到最后。代码本身并不可怕，可怕的是其实我已不爱它。