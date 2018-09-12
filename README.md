# sankes.github.io
## 平常博客写作和管理流程
1， 都在hexo分支上工作，用hexo new title建立新的md文件，然后书写，然后"git add . "，"git commit -m '' " ，"git push"提交。好了之后执行hexo generate -d 发布博客

2， 假如换了电脑后，先clone下你github上的博客仓库，然后 npm install -g hexo，npm install 和npm install hexo-deployer-git --save(和安装命令差不多，但是不要使用hexo init命令，因为仓库中已存在)，然后走正常博客书写发布流程即可。

感谢[rootrl](https://segmentfault.com/a/1190000011535121),[ppoffice](https://github.com/ppoffice/hexo-theme-icarus)
