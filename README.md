# AngularJs
Angularjs的学习

用node运行，简单的配置如下：
安装好nodejs之后，然后在安装http-server,安装nodejs的方法，请参考官方网站；

1）安装 （全局安装加-g）
npm install http-server
2) 使用在站点的根目录下添加package.json,内容格式如下：
 "scripts": {
     "start": "http-server -a 0.0.0.0 -p 8000",
 }
 在实践的项目中的配置例如：
 {
    "scripts": {
        "start": "http-server -a 127.0.0.1 -p 8080"
    }
}

参数 :
-p 端口号 (默认 8080)

-a IP 地址 (默认 0.0.0.0)

-d 显示目录列表 (默认 'True')

-i 显示 autoIndex (默认 'True')

-e or --ext 如果没有提供默认的文件扩展名(默认 'html')

-s or --silent 禁止日志信息输出

--cors 启用 CORS via the Access-Control-Allow-Origin header

-o 在开始服务后打开浏览器

-h or --help 打印列表并退出

-c 为 cache-control max-age header 设置Cache time(秒) , e.g. -c10 for 10 seconds (defaults to '3600'). 禁用 caching, 则使用 -c-1.

3）定位到当前目录，输入：http-server,即开启了一个本地服务
4）在浏览器输入http://127.0.0.1:8080则可以看到运行的程序

