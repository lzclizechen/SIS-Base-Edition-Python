# SIS
Student Information System



一个基础班的SIS（Student Information System）。

可以用来学习类似信息管理系统的设计思想和结构。但是不能用于应用。同时该软件中存在大量bug。

后续我会逐渐上传各种版本的SIS。比如：

- ”学生信息管理系统 升级版“：这个版本我会清除此版本中的一些bug，并添加更多功能。同时支持txt，xls，sqlite3数据库。增加配置文件，用来控制，增加配置模式命令行等。同时也会借鉴一下其他信息管理系统的功能，并不断丰富。
- “学生信息管理系统 （GUI）版”：这个版本，我会给SIS增加GUI，以及MySQL或SQL Server数据库支持。同时支持从txt，xls中导入信息。
- “Django 的学生信息管理系统（Web）版”：这个版本，我会使用Django来开发，做成Web版。是不是有点期待。

补充说明，本代码来自《Python程序案例课堂》，如有兴趣，欢迎阅读此书。并声明，本代码不可用于商业用途。





## Date：2019-03-30

1. 优化了代码结构，封装了获取txt文件里所有内容的函数为getAllStudent()。

2. 解决了changStudent()里面，索引的问题。
3. 给Student类增加了\_\_getitem\_\_()构造函数，可以用索引获取其内信息。