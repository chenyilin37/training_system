## 平台简介
### 后台管理系统
##### 课程管理
1. 课程分类管理：课程分类搜索查看、添加、修改/编辑、删除等
2. 课程管理：培训课程查看，添加，修改/编辑，删除等
3. 课程章节/内容管理：添加课程内容（目前支持视频，音频）
##### 考试管理
1. 题库维护：包含试题分类管理，试题管理
2. 试卷维护：包含试卷分类管理和试卷管理
3. 练习管理：包含练习题相关操作及相关试题管理
4. 考试管理：考试相关操作，包含模拟/正式考试配置
### 用户学习/考试系统
1. 课程学习
2. 练习
3. 考试
4. 个人信息配置

## 内置功能

1.  用户管理：用户是系统操作者，该功能主要完成系统用户配置。
2.  部门管理：配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。
3.  岗位管理：配置系统用户所属担任职务。
4.  菜单管理：配置系统菜单，操作权限，按钮权限标识等。
5.  角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
6.  字典管理：对系统中经常使用的一些较为固定的数据进行维护。
7.  参数管理：对系统动态配置常用参数。
8.  通知公告：系统通知公告信息发布维护。
9.  操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
10. 登录日志：系统登录日志记录查询包含登录异常。
11. 在线用户：当前系统中活跃用户状态监控。
12. 定时任务：在线（添加、修改、删除)任务调度包含执行结果日志。
13. 代码生成：前后端代码的生成（java、html、xml、sql)支持CRUD下载 。
14. 系统接口：根据业务代码自动生成相关的api接口文档。
15. 在线构建器：拖动表单元素生成相应的HTML代码。
16. 连接池监视：监视当期系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。


## 数据库说明
#####  exam_:    考试/试卷相关数据表
#####  train_:   练习相关数据表
#####  vip_:     用户相关数据表
#####  gen_:    代码生成器相关数据表
#####  qrtz_:   定时任务相关数据表
#####  sys_:    系统配置相关数据表


## 系统包结构说明（training_system）
#####  weiye-admin:    考试/试卷相关数据表
#####  weiye-cms:   练习相关数据表
#####  weiye-common:     用户相关数据表
#####  weiye-framework:     用户相关数据表
#####  weiye-generator:     用户相关数据表
#####  weiye-quartz:     用户相关数据表
#####  weiye-exam:    代码生成器相关数据表
#####  weiye-train:    代码生成器相关数据表
#####  weiye-vip:    代码生成器相关数据表
#####  weiye-weixin:    代码生成器相关数据表
