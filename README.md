#遇到的问题
*使用npm run dev 运行PC端项目时，报错： “‘webpack-dev-server’ 不是内部或外部命令，也不是可运行的程序 或批处理文件。”
    >'webpack-dev-server' 不是内部或外部命令，也不是可运行的程序
或批处理文件。
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! vue@1.0.0 dev: `webpack-dev-server --inline --progress --config build/webpack.dev.conf.js`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the vue@1.0.0 dev script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.
npm WARN Local package.json exists, but node_modules missing, did you mean to install?

npm ERR! A complete log of this run can be found in:
npm ERR! C:\Users\lara\AppData\Roaming\npm-cache\_logs\2018-06-12T09_40_42_892Z-debug.log
————————————————
版权声明：本文为CSDN博主「杨子颍_Rosie」的原创文章，遵循 CC 4.0 BY-SA 版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/Xumuyang_/article/details/96140396
#解决办法
解决办法
*1、安装依赖包
    >npm install
*2、运行npm run bulid  
    >npm run build
*3、运行
    >npm run dev
*几秒钟后，就可以打开localhost:8080 了。
#git基本命令
*git add .        （注：别忘记后面的.，此操作是把Test文件夹下面的文件都添加进来）
*git commit  -m  "提交信息"  （注：“提交信息”里面换成你需要，如“first commit”）
*git push -u origin master   （注：此操作目的是把本地仓库push到github上面，此步骤需要你输入帐号和密码）

