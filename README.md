### React多页面环境搭建
```
npm run dev //开发命令
npm run devNew //多页面文件自动创建 开发复制html文件
npm run p //生产文件打包
npm run ptp  //打包成生产环境包,并用gulp 创建 构建时间buildTime.txt,然后把这个包压缩成zip文件,并传到 测试环境及预生成环境
//"ptp": "npm run p && gulp buildTime zip test pre", //test、pre是自动上传到服务器 这个可以去掉 "ptp": "npm run p && gulp buildTime zip",
```