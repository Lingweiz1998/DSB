# i2p: Assessment 2: Data Set Bilography

## 1. 谁收集的数据？25字；1分

### 考虑数据的来源，其与基础数据生成过程的关系

这个数据库的数据来源于Airbnb网站上的公开信息，由Murray Cox创建的一个叫做Inside Airbnb的和Airbnb公司并无关系的网站汇总而成的。

## 2. 他们为什么要收集？50字；2分

### 考虑收集数据的目的，这可能会如何形成数据的形式/内容

Murray通过收集这些数据，利用地图和可视化的方式分析Airbnb在一个时间段内某些城市的使用情况。因此数据库可能包含各种地理信息（住址），时间信息（预约时间等）以及文字信息（对房间的描述，或者住户的评论）

## 3. 如何收集的？75字；3分

### 收集数据的方法是什么，如何形成数据的形式/内容

Inside Airbnb通过收集某一时间段内Airbnb网站上展示的公开信息制作了该数据库。数据在经过了核实、清洗,分析和汇总。数据库的内容主要由Airbnb网站要求用户上传的内容决定，因此一些非必要的信息可能不完整。同时，出于隐私保护的目的，一些数据在收集时就已经进行了模糊处理。

## 4. 它包含哪些有用的信息？100字；7分

### 对学生确定的可能支持后续分析的关键字段和记录的一般描述

首先，对于任何的基于空间分布的研究，该数据库所包含的房源的经度和纬度信息都是必要的。需要注意的是，Airbnb为了保护隐私对房屋的位置做了模糊化处理，因此房源的位置会有0-450英尺的误差。不仅如此，该数据库也包含了每一个房源的租金，不同时间段内的租出天数，以及该房源的主人拥有多少出租房源，等等。

## 5. 它缺少哪些有用的信息？50字；7分

### 概括性地描述一个天真但技术熟练的用户可能认为数据包括但不包括的关键字段和记录

Inside Airbnb在介绍中提到了对于房源的出租模式的对比的研究。因此，在打开数据库前，笔者认为能够观察到年均单次租出时长或者租出时长的中位数的数据列。然而在数据中并没有发现这些信息，也没有发现可以计算出这些数据的每一次租房时长记录之类的原始数据。同时，笔者认为房东是否住在该房源的“True or false”信息也是一个重要的数据列，但是该数据库并不包含这个信息。

## 6. 数据 "完整 "到什么程度？150字; 20分

### 反思Q4和Q5，这些数据在多大程度上是它声称允许我们检查的过程的 "完整 "图景

Inside Airbnb声称它的数据可以让研究局者们探索Airbnb的真实使用情况，从这个角度来看，数据库在很大程度上是完整的，但是缺失了部分重要信息。首先，正如该网站自己所声称的那样，这个数据库能够回答绝大部分基础的问题，比如房源的位置，租金多少，房源的主人是谁，他/她拥有多少套出租房源。然而，该网站也声称这个数据库可以回答诸如出租模式是短租还是长租之类的问题，却并未包含足够的信息（每次租房的时长）来展示房源的这一特征。同时该数据库也缺失对房东是否住在他们的出租房源内的准确信息。

## 7. 这将支持什么样的分析？150字；15分

### 考虑到上述的局限性和机会，这个数据支持什么样的分析

该数据库支持对于房租价格的空间分析，比如探讨房租金额和房源所在的区域的关系。同时，也可以研究房源在空间上是否有聚集的现象，这个现象和所在地区，相同房东是否有关系之类的分析。不仅如此，数据也可以初步探讨所在城市的Airbnb房东对房屋的使用模式，例如，大部分房东是偶尔出租自己的主要住所，还是拥有大量房源并且将它们当作酒店只用来出租。

## 8. 它不支持什么样的分析？100字; 15分

### 考虑到上述的限制和机会，有哪些分析是不能进行的，而一个天真但技术熟练的用户可能认为是可能的

该数据库可能不支持研究租出模式相关的分析，因为数据库中的信息无法判断一个房源主要以短租还是长租的模式被使用。例如通过分析城市的长租房源和短租房源的地理位置是否有聚集现象，探究它们和其他因素的关系。同时，由于数据库的不足，房东是否在房源内无法被准确确认，因此房东对房屋的使用模式没法被精准分析。

## 9. 第7项所列的用途中，哪些是符合伦理的？300字; 30分

尽管人们可以在如同Airbnb这样的在线公共平台管理自己的隐私设置，在大多数情况下我们无法很好的自我管理自己的隐私。这不仅仅因为很多人对平台的数据收集范围的了解程度，也因为在大数据泛滥的现代社会，多个不同来源数据结合在一起，可能会揭露一些人们不愿意公开的隐私信息。在Airbnb上，由于房东被要求公开自己的部分信息，因此相比于租客，他们的隐私信息更容易在对数据库的分析后被泄露。
在绝大部分情况下，对于房源租金的空间分析都不会涉及房东的个人信息，但是在分析房东的房屋使用模式时，由于使用了房东拥有的出租房源数量，结合房价信息有可能会透露出一些房东的个人资产信息。不仅如此，一个房东所持有的房源分布也会揭露出他/她可能的日常活动区域，这些隐私Airbnb并没有强制要求房东们上传并公开，但是在后续的分析中很容易被泄露。

## 附加信息

请提交本次考核的Markdown（.md）文件。
请不要写上你的姓名，写上你的学号即可。
参考书目、绘图或表格等形式的辅助信息应添加在附录中，不计入总字数。请注意，由于Turnitin不太可能处理Markdown中的嵌入式图片，因此图可能需要链接到GitHub上的资源。

### 参考文献

请在提交的正文中使用IEEE风格的参考文献（这是 "数字 "和顺序的，例如[1]适用于文档中的第一个参考文献，所有随后对该文档的参考文献都使用数字1
