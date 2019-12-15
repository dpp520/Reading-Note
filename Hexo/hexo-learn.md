# Hexo学习资源
[Hexo中文网](https://hexo.io/zh-cn/docs/index.html) 
[npmjs指导](https://docs.npmjs.com/resolving-eacces-permissions-errors-when-installing-packages-globally)

# 技术工具
```
△git
△nodejs
△hexo
```

# Hexo学习笔记
```
1.markdown标记语言，常见Readme.md中的语法：#H1 ##H2
2.GC垃圾回流，控制内存释放
3.go静态强类型、编译型语言
4.mac安装Hexo出现EACESS权限错误，尊村npmjs发布的指导，强烈建议不要使用root、sudo等方法覆盖权限
```

# 文件夹目录
```
.
├── _config.yml（配置）
├── package.json （依赖）
├── scaffolds （模板文件夹）
├── source （资源文件夹）
|   ├── _drafts
|   └── _posts
└── themes （主题文件夹）
```

# Hexo命令
```
Hexo指定文件夹中新建所需要的文件：hexo init <folder>
Hexo指定文件夹中新建所需要的文件：hexo init <folder>
新建一篇文章：hexo new [layout] <title>
生成静态文件：hexo generate
发表草稿：hexo publish [layout] <filename>
启动服务器：hexo server
部署网站：hexo deploy
清除缓存文件 (db.json) 和已生成的静态文件 (public)：hexo clean
列出网站资料：hexo list <type>
显示 Hexo 版本：hexo version
```

