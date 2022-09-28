# presonal-blog

jjjanice.github.io中的内容由该代码库生成，该代码库内容修改完成后，将public内容push到jjjanice.github.io代码库中即可

### 运行
```bash

第一步：启动
hexo server

第二步：打开页面
http://localhost:4000/
```

### 创建文章
hexo new post 文章名称

### 推送至远程
hexo clean && hexo g && hexo d

### hexo命令解读
```
hexo clean 清楚缓存文件（db.json和public静态文件）
hexo generate 生成静态文件
hexo deploy 推送至_config_yml中配置的远程分支
```

### 参考文档
https://blog.csdn.net/yaorongke/article/details/119089190