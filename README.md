启动发布代码

```
//初始化

npm install

//开发

npm run dev

//发布

npm run build

```

说明一下：由于要解决移动端iOS操作系统click事件延迟300ms问题，特意使用了tap事件来替代click事件。所以运行时最好是在浏览器中的手机模拟器中操作。mui有plus对象，只能在手机端环境运行，有可能pc端会报错
