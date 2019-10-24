## react新建项目  
1、电脑安装最新版Node.js.  
2、npx create-react-app my-app (新建一个my-app项目)  
如报错:(npm代理为淘宝的代理的时候就会发生这样的错误，将npm代理换回来就不报错了)  
npm ERR! Unexpected end of JSON input while parsing near '...rsion: OpenPGP.js v3.'   
npm ERR! A complete log of this run can be found in:  
npm ERR!     C:\Users\qin\AppData\Roaming\npm-cache\_logs\2019-10-24T05_43_34_135Z-debug.log  
则执行指令  
npm config set registry http://registry.cnpmjs.org  
后重新执行新建项目指令  

3、npm start(浏览器运行项目)  


## todolist项目文件  
react16.4快速上手-慕课网教学视频学习