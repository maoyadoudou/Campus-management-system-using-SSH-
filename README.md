# Campus-management-system-using-SSH<br/>

# 1 编写校园管理系统的目的<br/>
  自学了3个框架后希望能够对框架的知识点，以及Java基础知识点进行回顾，于是决定编写一个项目，当然编写过程中也可以学习练习一下前端知识，包括HTML、CSS、JavaScript（JQuery）、AJAX等。<br/>
# 2 编写过程中的感想<br/>
  整体上说，在编写过程中，后端的问题较容易解决，反倒是前端老出问题，整个编写进度中大半时间花在处理前端问题上了。不过问题出的越多，对各个知识点的印象也就越深刻。<br/>
  编写完这个项目后，我对网页前端以及其后端还有数据库之间的运作方式有了直观的认识，也感受到了借助项目学习编程的好处。过去学习Java基础知识点时，一遍一遍的按着书本的例子敲代码，当下可以理解，过后就忘，因为根本不知道有啥用，对于初学者就算记住了，也和死记硬背没啥区别。而带着项目练习虽然无法覆盖全部知识点，但只要是用到的知识点都形成了逻辑脉络（我瞎造的词），印象和理解变得更为深刻。<br/>
# 3 项目简介<br/>
  这个项目名称为校园管理系统，分两种角色——老师和学生，共同的功能包括注册、登陆、添加和修改个人信息、上传照片、查看课表。此外针对角色特点也设置了不同的功能：<br/>
  对于老师，可以提交、修改和删除新一学期的授课信息，包括授课名称、地点、时间和授课最大人数，提交这些信息前会校验，如该时间段该教师是否已被其他老师占有，学生选择了老师的课程后，老师的课表上才会出现对应的课程信息，老师还能在打分功能中对不同的学生打分。<br/>
  对于学生，可以选择或弃选课程，选择课程后会先校验课程信息，如在该时间段是否存在已选课程。学生选课成功后，课程会出现在课表中，学生还可以在查分功能处查看课程分数。<br/>
# 4 项目遗留问题<br/>
  原本还要在项目中添加通讯录以及聊天功能，就是类似网页版微信的功能，来回顾servlet，I/O和文件下载等知识点。但后面还要继续学习SpringMVC和Mybatis两个框架以及Maven和Redis，因此决定在下一个SSM项目中再专门编写这个功能。<br/>
  另外本项目中其实还有很多可以简化和优化的地方，如有些查询功能可以将功能抽离到父类中，但我只抽离了部分功能，作为练手；有些地方故意用不合常规的命名方式，主要是为了试错，看看这些命名变了对ModelDriven工作是否产生印象。<br/>
  
  这是我的第一个Java后端项目，您若同为初学者，有问题随时可以问，若是大佬，欢迎批评指正。<br/>
