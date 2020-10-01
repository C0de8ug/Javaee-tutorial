# 简介 code update
这是个简单的教务系统网站,并且结合了图书订购功能,希望这个小DEMO能对大家学习有帮助

# 使用技术 

IoC容器:spring

web框架:springmvc

orm框架:mybatis

安全框架:shiro

数据源:dbcp2

日志: sl4j

Json: Gson

前端框架:Bootstrap

# 起步:

1.初始化项目

1)下载Mysql,创建一个数据库名字为giit,导入create.sql与populate.sql,直接运行其中sql即可

2)下载Tomcat

3)使用Intellij Idea导入项目,之后配置项目启动方式,使用刚才下载好的Tomcat
  
4)运行

![image](https://pic4.zhimg.com/v2-87231f2eb533cdab3d3e04c7a89457af_b.png)

# 使用简介:

1.权限介绍:

根据导入的populate.sql,运行网站初始时会存在四个权限角色:

1).管理员,账号为admin

2).学生,账号为student

3).教师,账号为teache

4).供应商,账号为supplier

*密码均为123456*

# 功能介绍:
##  1.基本信息功能:
其中可以设置一些基本的学校信息,也就是数据库中的实体-关系,之后就可以基于这些基本的关系信息进行更加复杂的功能,例如选课后可以记录多少学生选择了这门课程,只会教师提交图书后计算图书总数可以通过其中的关系得到

1)系部信息

2)专业信息

3)班级信息

4)课程信息

5)学生管理

![image](https://pic1.zhimg.com/v2-44688d7a989ae25d9db6767a50a208f8_b.png)


## 2.图书管理功能:
1)教师上传图书

2)秘书审批图书

3)查看已审核图书

![image](https://pic3.zhimg.com/v2-3ff2f0da17e8609f85da3b61671cf0de_b.png)

# 数据库表结构:
![image](http://7xi78h.com1.z0.glb.clouddn.com/db.png)

