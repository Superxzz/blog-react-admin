![效果图](https://upload-images.jianshu.io/upload_images/12890819-f3b950acbffb944b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 前言

此 blog-react-admin 项目是基于 [蚂蚁金服开源的 ant design pro](https://pro.ant.design/index-cn) 之上，用 react 全家桶 + Ant Design  的进行再次开发的，项目已经开源，项目地址在 github 上。

效果预览 [https://preview.pro.ant.design/user/login](https://preview.pro.ant.design/user/login)

# 1. 后台管理

## 1.1 已经实现功能

- [x] 登录  
- [x] 文章管理（支持 MarkDown 语法）
- [x] 标签管理  
- [x] 留言管理
- [x] 用户管理
- [x] 友情链接管理
- [x] 时间轴管理

## 1.2 待实现功能

- [ ] 点赞、留言和评论 的通知管理
- [ ] 评论管理
- [ ] 个人中心（用来设置博主的各种信息）
- [ ] 工作台（ 接入百度统计接口，查看网站浏览量和用户访问等数据 ）

# 2. 主要项目结构

```
- pages
  - Account 博主个人中心
  - article 文章管理
  - Category 分类
  - Dashboard 工作台
  - Exection 403 404 500 等页面
  - Link 链接管理
  - Message 留言管理
  - OtherUser 用户管理
  - Tag 标签管理
  - TimeAsix 时间轴
  - User 登录注册管理
```

文章管理、用户管理、留言等 具体业务需求，都是些常用的逻辑可以实现的，也很简单，这里就不展开讲了。

# 3. 使用

使用详情请查看 [Ant Design Pro ](https://pro.ant.design/docs/getting-started-cn)，因为本项目也是在这个基础之上，按这个规范来构建的。

# 4. 缺点

开发时，程序出错后，修改正确后，webpack 有时不会及时查觉到内容已经更改，从而不能及时编译，要重新运行命令打包。

# 5. 项目地址

开源不易，如果觉得该项目不错或者对你有所帮助，欢迎到 github 上给个 star，谢谢。

**项目地址：**
> [前台展示: https://github.com/biaochenxuying/blog-react](https://github.com/biaochenxuying/blog-react)
> [管理后台：https://github.com/biaochenxuying/blog-react-admin](https://github.com/biaochenxuying/blog-react-admin)
> [后端：https://github.com/biaochenxuying/blog-node](https://github.com/biaochenxuying/blog-node)
> [blog：https://github.com/biaochenxuying/blog](https://github.com/biaochenxuying/blog)

**本博客系统的系列文章：**

- 1. [react + node + express + ant + mongodb 的简洁兼时尚的博客网站](http://biaochenxuying.cn/articleDetail?article_id=5bf57a8f85e0f13af26e579b)
- 2. [react + Ant Design + 支持 markdown 的 blog-react 项目文档说明](http://biaochenxuying.cn/articleDetail?article_id=5bf6bb5e85e0f13af26e57b7)
- 3. [基于 node + express + mongodb 的 blog-node 项目文档说明] 敬请期待...

# 6. Build Setup ( 构建安装 )

``` 
# install dependencies
npm install 

# serve with hot reload at localhost: 3000
npm start 

# build for production with minification
npm run build 
```

如果要看完整的效果，是要和后台项目  **[blog-node](https://github.com/biaochenxuying/blog-node)** 一起运行才行的，不然接口请求会失败。

# 7. 最后

对 **全栈开发** 有兴趣的朋友可以扫下方二维码关注我的公众号，我会不定期更新有价值的内容。

> 微信公众号：**BiaoChenXuYing**
> 分享 前端、后端开发等相关的技术文章，热点资源，全栈程序员的成长之路。

关注公众号并回复 **福利** 便免费送你视频资源，绝对干货。

福利详情请点击：  [免费资源分享--Python、Java、Linux、Go、node、vue、react、javaScript](https://mp.weixin.qq.com/s?__biz=MzA4MDU1MDExMg==&mid=2247483711&idx=1&sn=1ffb576159805e92fc57f5f1120fce3a&chksm=9fa3c0b0a8d449a664f36f6fdd017ac7da71b6a71c90261b06b4ea69b42359255f02d0ffe7b3&token=1560489745&lang=zh_CN#rd)

![BiaoChenXuYing](https://upload-images.jianshu.io/upload_images/12890819-091ccce387e2ea34.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)




