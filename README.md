## 前后端代码仓库地址

- 前端：https://github.com/wxjackie/newProjbarFE
- 后端：https://github.com/wxjackie/newProjbarBE
- API文档地址：https://github.com/wxjackie/newProjbarBE/tree/master/apidoc

## 项慕吧开发指南



https://github.com/wxjackie/newProjbarFE/blob/master/README.md



## 如何访问我们的网站？



[项目吧链接点击这里..](http://123.206.87.13/projbar)



## 关于Task

- task2：wiki页面中[项目建议书.md](https://github.com/Mu-Charlie/WebEngineeringProject/wiki/%E9%A1%B9%E7%9B%AE%E5%BB%BA%E8%AE%AE%E4%B9%A6)
- task3：[Web项目需求文档.docx](https://github.com/Mu-Charlie/WebEngineeringProject/wiki/%E9%A1%B9%E7%9B%AE%E5%BB%BA%E8%AE%AE%E4%B9%A6)
- task4：[Web应用建模.md](https://github.com/Mu-Charlie/WebEngineeringProject/blob/master/Web%E5%BA%94%E7%94%A8%E5%BB%BA%E6%A8%A1.md)
- task5：[Web应用架构报告.md](https://github.com/Mu-Charlie/WebEngineeringProject/blob/master/Web%E5%BA%94%E7%94%A8%E6%9E%B6%E6%9E%84%E6%8A%A5%E5%91%8A.md) [Web应用项目架构报告.docx](https://github.com/Mu-Charlie/WebEngineeringProject/blob/master/Web%E5%BA%94%E7%94%A8%E9%A1%B9%E7%9B%AE%E6%9E%B6%E6%9E%84%E6%8A%A5%E5%91%8A.docx)
- task6：[Web应用设计-内容设计.md](https://github.com/Mu-Charlie/WebEngineeringProject/blob/master/Web%E5%BA%94%E7%94%A8%E8%AE%BE%E8%AE%A1-%E5%86%85%E5%AE%B9%E8%AE%BE%E8%AE%A1.md) [交互设计+展示设计.docx](https://github.com/Mu-Charlie/WebEngineeringProject/blob/master/%E4%BA%A4%E4%BA%92%E8%AE%BE%E8%AE%A1%2B%E5%B1%95%E7%A4%BA%E8%AE%BE%E8%AE%A1.docx)
- task8：[Web应用测试.md](https://github.com/Mu-Charlie/WebEngineeringProject/blob/master/Web%E5%BA%94%E7%94%A8%E6%B5%8B%E8%AF%95.md)

## 前端

> 暂定人员：李莹莹、童彤、穆财林、王星锦

主要任务：

- 前端素材搜集（图片、配色、排版）和写页面
- 数据绑定（获取数据并渲染到指定位置）

必要公有信息：

- Nginx访问路径: `/usr/share/nginx/htmls`，配置路径：`/etc/nginx/nginx.conf` 
- 主要使用jQuery + Bootstrap，和一点HTML和CSS

## 后端

> 暂定人员：王星锦、曹萌、王帅、王旻琛、沙福鑫、王博、陈金宇

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

