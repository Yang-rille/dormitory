## DormitorySystem 
![IDE](https://img.shields.io/badge/IDE-IntelliJ%20IDEA-brightgreen.svg) ![Java](https://img.shields.io/badge/Java-1.8-blue.svg) ![Database](https://img.shields.io/badge/Database-MySQL-lightgrey.svg) 
- 毕业设计💼
- MD5加密🔒
- SSM框架🎨
- Layui框架🎄

#### 实现功能
- [x] 管理员的登录与登出  
- [x] 管理员,班级,学生,宿舍，卫生，访客各模块增删改查  
- [x] 个别模块关联查询  
- [x] 各个模块数据导出Excel

#### 一些截图
![dorm1](http://image.zxkidea.top/dorm1.png)

![dorm1](http://image.zxkidea.top/dorm2.png)

![dorm1](http://image.zxkidea.top/dorm3.png)

![dorm1](http://image.zxkidea.top/dorm4.png)

### 部署过程
1、本地安装数据库mysql8.0版本以上，安装教程：https://www.cnblogs.com/winton-nfs/p/11524007.html；
2、修改src目录下的db.properties文件重的用户名秘密为自己的数据库的用户名和密码；
3、进入mysql的bin目录下;
4、执行 mysql -u root -p *****; create database dormitory; use dormitory（*****代表数据库密码）; 
5、插入表和数据，执行source **/dormitory/dormitory.sql（**代表项目的路径）;
6、d_admin表中所有的密码明文为：111111
7、配置好tomacat,点击运行，查看效果。

