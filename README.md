CI-Base
------
Codeiginter 3.x 多个入口项目共享公共配置文件数据

**Version:** 3.1.11   

## 安装使用
1. ```git clone https://github.com/skiy/ci-base.git```   
2. 配置 nginx，根据 nginx 目录的配置文件修改并移动到 `nginx/conf/vhost` 配置目录下根据环境修改)。
>> 修改 server_name(域名), $enter_file(入口文件}), root(入口目录), filter page(隔离页面)
3. 重启 nginx
4. 独立的两个项目(Demo):   
> **admin**(admin.php): http://admin.example.com   
> **website**(index.php): http://web.example.com      


## License
This project is licensed under the [MIT license](./LICENSE).
