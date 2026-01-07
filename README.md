<p align="center">
    <img src="https://gitee.com/lcm742320521/ruoyi-app/raw/master/static/images/logo/logo.png" alt="" />
</p>

<h1 align="center">RuoYi-App</h1>
<h3 align="center">v2026.01</h3>

<h4 align="center">基于 Uniapp X 的移动端快速开发框架</h4>

<p align="center">
    <a href="https://gitee.com/lcm742320521/ruoyi-app/stargazers">
        <img src="https://gitee.com/lcm742320521/ruoyi-app/badge/star.svg?theme=dark" alt="" />
    </a>
	<a href="https://gitee.com/lcm742320521/ruoyi-app/blob/master/LICENSE">
	    <img src="https://img.shields.io/badge/License-Apache 2.0-green" alt="" />
	</a>
</p>

## 平台简介
RuoYi App 移动解决方案，采用 Uniapp X 框架，一份代码多终端适配。

* 同时支持鸿蒙、Android、iOS、微信小程序。
* 技术栈：Uniapp X、Vue、UTS、Uni UI等。
* 配套后端代码仓库地址 [RuoYi-Solon](https://gitee.com/opensolon/ruoyi-solon) 或 [RuoYi-Cloud-Solon](https://gitee.com/opensolon/ruoyi-cloud-solon)。
* 请使用使用 HBuilderX（v4.87+）打开项目。

## 项目结构
~~~
ruoyi-app
├── api                                   // 所有请求（后台接口）
├── components                            // 全局公用组件
├── config                                // 配置文件
├── harmony-configs                       // 鸿蒙配置文件
├── pages                                 // 页面文件
├── plugins                               // 插件（功能增强：比如全局方法挂载、全局组件挂载等）
├── static                                // 静态资源
│   ├── images                            // 图片
│   ├── styles                            // 样式
├── store                                 // 仿Pinia
├── uni_modules                           // 依赖
├── utils                                 // 全局公用方法
├── .gitignore                            // git 忽略项
├── App.uvue                              // 入口页面
├── index.html                            // html模板
├── LICENSE                               // 许可证
├── main.uts                              // 入口文件
├── manifest.json                         // 配置文件
├── pages.json                            // 页面配置
├── README.md                             // README说明
├── theme.json                            // 主题适配
├── uni.scss                              // 样式变量
~~~

## 内置功能
1.  个人信息：修改登录用户个人信息。
2.  生物认证：指纹登录等。
3.  主题切换：明亮 / 暗黑模式切换。

## 版本要求
请使用使用 HBuilderX（v4.87+）打开项目。
