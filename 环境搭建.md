
iTerm2（https://www.iterm2.com/）

—————————————

oh my zsh

sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

—————————————

安装gulp（https://www.gulpjs.com.cn/docs/getting-started/）
1.	$ npm install --global gulp （全局）
 	$ npm install --save-dev gulp（项目依赖）
2.	在项目根目录下创建一个gulpfile.js的文件：

	var gulp = require('gulp');

	gulp.task('default', function() {
 	 // 将你的默认的任务代码放在这
	});
3.	运行gulp

—————————————

homebrew
https://brew.sh/

—————————————

ningx安装+配置

brew search nginx
brew install nginx

nginx -V							版本

sudo nginx -t  						查看nginx配置文件(是nginx自带的管理命令，可以管理nginx务                                     keeplive自动重启（不用每天重启）)

sudo brew services restart nginx    重启nginx

sudo nginx 							重启nginx（在nginx目录下执行）

sudo brew services stop nginx		关闭nginx

sudo nginx -s stop					关闭nginx

ps -ef  | grep nginx 				查看进程是否在后台运行

```
server {
    server_name  域名;

        root  项目根目录;

        location / {
        index  index.html index.htm;
    }
}
```

—————————————


switchhost！配置

127.0.0.1 域名  （指向本机）

—————————————


Sourcetree（Git GUI）

pwd 当前路径







