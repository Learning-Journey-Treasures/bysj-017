![gh_17810254f3db_258](https://github.com/user-attachments/assets/a028a5cc-fc7e-4784-a4c9-e42f53caf7fe)


**郑重声明：项目经过本地测试，确保可以运行。由于精力有限，不提供调试服务。项目仅供学习和毕业设计参考~**

1.项目介绍

技术栈+工具：SpringBoot + JSP +MySQL + Maven +IDEA2022

系统角色：管理员、宿管、学生

系统功能：管理员（学生管理、宿管管理等）、宿管（宿舍楼管理、宿舍设备管理、设备类别管理、宿舍卫生管理、报修管理、来访人员管理、离校登记管理等）、学生（我的咨询、我的来访记录、查房记录、评分记录、报修记录、设备报修等）

2.项目部署

- 创建数据库，导入项目中的sql

- 打开IDEA，导入项目apartment

- 根据本地数据库环境，修改数据库的连接信息 src/main/resources/application.properties 13-16行

- 启动项目，运行 http://localhost:8080/apartment 管理员账号/密码：admin/admin 

- 学生账号/密码：S011/123456   宿管账号/密码：test02/123456
