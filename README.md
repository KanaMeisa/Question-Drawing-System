# 抽题系统

抽题系统。以HTML、CSS以及部分由C++通过WebAssembly编译而成的部分JavaScript代码作为前端，Node.js作为后端服务器。

通过Node.js部署后端服务器，实现题库图片的前后端交互。

整个抽题系统有三大功能：学号抽题、随机抽题和管理员功能。

- 学号抽题：输入学号完成抽题操作，抽题后服务器会记录下用户的学号、IP地址、平台等信息。
- 随机抽题：无需输入学号，即可随机从题库中抽取六道题。
- 管理员功能：进入管理员界面需要输入正确的用户名和密码。在管理员界面中，可以查看题库中的所有题目，可以上传题目图片来添加到题库中。其次可以查看抽题记录，记录包含多种信息。

原题
![题目](https://github.com/KanaMeisa/Dazuoye/blob/main/public/%E9%A2%98%E7%9B%AE.jpg)
