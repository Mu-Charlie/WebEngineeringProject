
## 准备

- 自己电脑的SSH公钥
- Github添加到合作者
- 学会Git基础使用
- 服务器IP：123.206.87.13

## 前后端代码仓库地址

- 前端：https://github.com/wxjackie/newProjbarFE
- 后端：https://github.com/wxjackie/newProjbarBE
- API文档地址：https://github.com/wxjackie/newProjbarBE/tree/master/apidoc# Web Project Info 

## 前端

> 暂定人员：曹萌、李莹莹、童彤、穆财林

主要任务：

- 前端素材搜集（图片、配色、排版）和写页面
- 数据绑定（获取数据并渲染到指定位置）

必要公有信息：

- Nginx访问路径: `/usr/share/nginx/htmls`，配置路径：`/etc/nginx/nginx.conf` 
- 主要使用jQuery + Bootstrap，和一点HTML和CSS

## 后端

> 暂定人员：王星锦、王帅、王旻琛、沙福鑫、王博、陈金宇

主要任务：

- 设计数据库
- 写接口和业务，以json形式返回数据

必要公有信息：

- 数据库：端口3306，数据库名heyweb，用户名：root，密码：root
- 主要使用`Spring Boot`

返回数据格式规定：

```json
{
    "code": 0,
    "msg": "ok",
    "data": "test"
}
```

- code：自设错误码，0正常/1错误
- msg：提示信息
- data：返回数据

## 主要功能列表

用户个人中心：

- 注册、登录、退出登录
- 修改个人资料，包括基础信息和技能信息
- 通知信息（处理一些用户间的组队请求）
- 查看自己的项目

首页：

- 项目列表
- 个人列表
- 项目详情（申请加入）和个人详情（邀请加入），触发邮件提醒
- 筛选和搜索功能
- 发布项目功能
- 推荐匹配功能（暂定）

后台：

- 管理员登录、管理
- 项目列表、个人列表、对两者的删除、禁用操作
