[Gmeek](https://github.com/Meekdai/Gmeek) 一个博客框架，超轻量级个人博客模板，完全基于Github Pages 、 Github Issues 和 Github Actions，可以称作All in Github。不需要本地部署，从搭建到写作，只需要18秒，2步搭建好博客，第3步就是写作。

一、安装
安装及其简单，但是也要认真看下面的步骤，一步一步来。

【创建仓库】点击[通过模板创建仓库](https://github.com/new?template_name=Gmeek-template&template_owner=Meekdai)，建议仓库名称为XXX.github.io，其中XXX为你的github用户名。

【启用Pages】在仓库的设置Settings中Pages->Build and deployment->Source下面选择Github Actions。

【开始写作】打开一篇issue，开始写作，并且必须添加一个标签Label（至少添加一个），再保存issue后会自动创建博客内容，片刻后可通过https://xxx.github.io/ 访问。

【手动全局生成】这个步骤只有在修改config.json 文件或者出现奇怪问题的时候，需要执行。

通过Actions->build Gmeek->Run workflow->里面的按钮全局重新生成一次

二、配置文件
按照安装步骤成功搭建好后，就可以阅读下面的内容修改配置文件啦。
注意修改配置文件后一定要手动全局生成一次，不然会报错。
如果对json格式不熟悉，建议先简单学习一下。

config.json 文件就是配置文件，在创建的仓库内可以找到，对应修改为自己的即可。

{
    "title":"Meekdai",
    "subTitle":"童话是一种生活态度，仅此而已。",
    "avatarUrl":"https://github.githubassets.com/favicons/favicon.svg",
    "GMEEK_VERSION":"last"
}

(更多 ... ...) 
[本博客搭建参考：](https://blog.meekdai.com/post/Gmeek-kuai-su-shang-shou.html)


