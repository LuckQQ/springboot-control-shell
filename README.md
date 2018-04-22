# springboot-control-shell
springboot jar包控制脚本


## 如何使用

1. 上传打好的jar包到服务器  
2. 拷贝脚本到jar包同级目录  
3. 修改脚本中DEFAULT_APP_NAME的值为jar包名称  

4. 执行./boot.sh start stop restart status  
   分别为 启动 停止 重启 状态查看  

5. 不修改脚本中DEFAULT_APP_NAME的值则每次执行需加上jar包名称  
   默认值为jenkins-test.jar  
