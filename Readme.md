
# 使用的库:
- React 16
- React-Router 4
- webpack 3

# 架构设计:
- 前后端完全分离
- 单页应用
- 模块化开发
- 分层架构

# 语言和框架:
- React（框架）      
- React-Router （处理单页应用的路由）
- ES6 （语法）

# 辅助工具
- Yarn (没有使用自带的 npm, 而是使用 yarn 来安装依赖和管理包。安装比较快)
- Webpack （做代码打包）
- Git (版本维护，代码托管)

# 发布过程
- 环境配置
- 代码部署
- nginx配置
- 域名解析

# 数据接口定义
## 接口文档字段
- 接口名称
- 接口地址
- 请求信息
- 响应信息
- (altertive) 接口的描述/备注

## 响应信息示例——键值对格式
| response
```
success
{
  "status":0, //接口状态，0成功、1失败、10未登录
  "data":{    //接口数据
    "id":2,   
    "name":"oppo R8",
  }
}
fail
{
  status:1
  "msg":"该商品已下架或删除" //接口错误信息
}
```
## ES6
Babel: ES6 -> ES5 的转换器
