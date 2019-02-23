# Express - crud
这是一个小案例，操作数据的增删改查，自己封装异步的API
## 起步
- nodejs-express小框架的使用
- 初始化
- 模板处理

## 路由设计
解析
| 请求方法 |     请求路径     | get 参数 |           post 参数            |       备注       |
|----------|------------------|----------|--------------------------------|------------------|
| GET      | /studens         |          |                                | 渲染首页         |
| GET      | /students/new    |          |                                | 渲染添加学生页面 |
| POST     | /studens/new     |          | name、age、gender、hobbies     | 处理添加学生请求 |
| GET      | /students/edit   | id       |                                | 渲染编辑页面     |
| POST     | /studens/edit    |          | id、name、age、gender、hobbies | 处理编辑请求     |
| GET      | /students/delete | id       |                                | 处理删除请求     |
|          |                  |          |                                |                  |
