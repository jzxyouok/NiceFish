# NiceFish（美人鱼）

NiceFish（美人鱼）是一个微型Blog系统，前端基于Angular 2，后端是基于Node的http服务端，数据存储用的MangoDB。 

可以用来搭建团队Blog，微信SNS站点，个人站点，或者用于学习Angular2（其实我并不在乎你用来干嘛，那关我什么事呢对吧？）。 

【注意】上面两句话都是吹牛的，因为我现在连前端功能都没写完呢，后端一点儿都没写呢，不过我会尽快的，请给我加个星儿，谢谢。

## 用法

用git克隆本项目，进入项目目录后依次执行以下命令：

	npm install
	npm install -g angular-cli
	ng serve

打开你的浏览器，访问http://localhost:4200/

## 注意（请仔细看）

 - 如果在npm install的过程中有报错，可能是某些包被墙掉(f**k GFW)了，请自己设置翻墙代理之后再运行npm install，设置方式示例：npm config set proxy=http://127.0.0.1:1080  。

 - 如果有node-gyp的报错，可以在npm install的后面加上参数 --no-optional  。

 - 如果有node-sass的报错，尝试一下翻墙，再次f**k GFW 。

 - 如果你是在Windows下安装，启动cmd的时候要用管理员身份启动。

 - 如果你是在MAC或者Linx下安装，请尝试用sudo执行安装命令，否则某些目录可能权限不够。

 - 如果你想要生成模块之间的依赖关系图，请使用angular2-dependencies-graph，这是一个第三方的node模块，路径在这里https://github.com/manekinekko/angular2-dependencies-graph 。当前的模块依赖关系图我已经生成在src/documentation目录下。

 - 这个项目暂时不接受issue或者PR，演进修改什么的完全看我自己的心情。

## 开源许可证
 MIT

 你可以随意使用此项目，无需通知我，因为我可能很忙没空搭理你。

  

## 关于我
我是大漠穷秋，目前是Google Angular项目组在中国的PM，负责Angular的推广工作，我会经常发布一些与Angular相关的技术文章，希望能给大家带来一点点帮助，请点这里：https://my.oschina.net/mumu/blog  。