# watermelonluo.github.io
<font color=e5004f size=5>****个人主页****</font>

利用hexo跟GitHub搭建博客

安装hexo
$ npm install -g hexo

初始化
$ cd /Workspaces/hexo/
$ hexo init

$ hexo g # 生成
$ hexo s # 启动服务

上传到github
deploy:
  type: git
  repository: git@github.com:liuxianan/liuxianan.github.io.git
  branch: master
  
npm install hexo-deployer-git --save

常用hexo命令
hexo new "postName" #新建文章
hexo new page "pageName" #新建页面
hexo generate #生成静态页面至public目录
hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
hexo deploy #部署到GitHub
hexo help  # 查看帮助
hexo version  #查看Hexo的版本

hexo s -g #生成并本地预览
hexo d -g #生成并上传
写博客
hexo new 'my-first-blog'
