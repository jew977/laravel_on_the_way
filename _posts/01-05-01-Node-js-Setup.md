---
isChild: true
title: Node.js 安裝
anchor:  Node_js_setup
---

## Node.js 安装 {#Node_js_setup_title}

系统默认安装环境Ubuntu 。

第一步：安装最新的nodejs和npm

{% highlight console %}

> sudo add-apt-repository ppa:chris-lea/node.js

{% endhighlight %}

{% highlight console %}

> sudo apt-get update

{% endhighlight %}

{% highlight console %}

> sudo apt-get install nodejs 

{% endhighlight %}

第二步：检测版本

{% highlight console %}

> node  --version

{% endhighlight %}


{% highlight console %}

> npm -v

{% endhighlight %}

第三步：升级npm

{% highlight console %}

> sudo npm install -g npm

{% endhighlight %}


