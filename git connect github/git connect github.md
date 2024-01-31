- 下载git
- 创建一个github账号
- 创建本地SSH并粘贴到github
- 自报家门——git config --global user.name "(github用户名)"

​					  		 git config --global user.email "注册github的邮箱"

- 查看自己HTTP代理并建立自己打代理

1.控制面板→网络和internect→internect选项→连接→局域网设置→![image-20240201003230480](C:\Users\22467\AppData\Roaming\Typora\typora-user-images\image-20240201003230480.png)

1. ——git config http.proxy http://127.0.0.1:15732
2. ——git config https.proxy http://127.0.0.1:15732
3. 将 `sslVerify` 设置为 `false` ——git config --global http.sslVerify false

拓展：删去代理——git config --global --unset http.proxy