---
layout: post
title:  应该定期更新自己的简历
categories: [Job,markdown]
---


已经工作了7年，最近悟出了一个道理---应该定期更新简历。不应该在需要换工作时，才开始意识到需要写简历，这样是被动的更新简历。主动定期的更新简历，可以让工作来找你。因为如果每隔一段时间，你的简历有内容可更新，比如学习了一些新的技术，做了一个新的项目，说明你一直在进步。一个在职业素养上不断进步的人，当然是工作来找你呀！技术更新太快，做我们这一行就像逆水行舟，不进则退！

好了，鸡汤不要说太多，我是一个比较务实的人，下面给点干货。最近发现了一个[基于Markdown生成简历的工具](https://github.com/there4/markdown-resume)，你只需要专注填写简历本身，效率非常高。它可以导出pdf和html。从样式上，两者基本没有差异。pdf格式适用于简历投递，而html格式适用于挂到[自己的博客中装B](/resume_public.html)。



根据上面的github地址，将工程clone下来，然后安装好php。我是Window 7系统，安装对应版本php，然后设置php的环境变量，并且打开php.ini配置，设置**mbstring**库和**extension_dir**选项。如果需要导出pdf格式，还需要根据项目readme中的指引，安装wkhtmltopdf库，并且设置环境变量。

生成简历命令


{% highlight raw %}
md2resume pdf --template swissen resume_public.md .
md2resume html --template swissen resume_public.md .
{% endhighlight %}

最后，该工具内置5个模板，个人觉得**swissen**模板最好，效果可以参考[我的个人简历](/resume_public.html)。
