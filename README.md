# consul
#执行效果

#模拟node1 user order sever_down

运行脚本
```
bash /root/script/consul_status.sh 

service-order-10.10.10.1 已删除
service-user-10.10.10.1 已删除
10.10.10.1:service-order was restart by 2020-05-07-15-15
10.10.10.1:service-user was restart by 2020-05-07-15-15
```
把脚本追加定时crontab，就可以实现自动化consul服务监控
