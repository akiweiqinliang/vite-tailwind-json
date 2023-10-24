# vite-tailwind-json

vscode内打开vite-tailwind-json
控制台中运行bash server.sh
运行成功后默认在3000端口打开，使用vscode控制台中PORTS的“forward a Port”
成功forward后把visibility权限改为public

最后把项目中axios发送请求的baseURl（代理地址）改为forwarded address就OK了

具体修改启动端口或其他功能请移步到https://github.com/typicode/json-server
