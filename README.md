# HuiJiZhang-font-end-server
## 前端部署

建议在2.9+以上版本的HBuilderXHbuilderx中创建uniapp项目使用。
### 环境配置
npm i vuex-persistedstate

### App模块配置
app包含的扩展模块（影响包体积）。云打包后生效。本地打包需另行在原生工程中配置
#### 打包模块配置
勾选 Camera&Gallery(相机和相册)\n
勾选 OAuth(登录鉴权)

### App组件引入
在Dcloud市场导入秋云 ucharts echarts 高性能跨全端图表组件

https://www.npmjs.com/~qiun

在Dcloud市场导入uView2.0

https://www.npmjs.com/package/uview-ui

在Dcloud市场导入less编译

在Dcloud市场导入scss/sass编译

### 打包注意
如果采用ios打包需要苹果开发者证书
