# CDN
#看板娘的CDN,
```

1、去除了窗口大小加载判断（不知道源up为啥要加这个，导致手机端无法加载）
2、json和其他静态资源路径分离，因为貌似静态文件和json是分离的，每次加载时页面js都会去请求json，导致跨域问题