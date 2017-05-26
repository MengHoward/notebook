# notebook
1. Linux  在centos中 /etc/hosts.allow 中可以设置访问ip
2. Linux 查看本机ip 可以使用 ifconfig；查看公网ip 可以使用 curl ifconfig.me
3. Java在调试程序的时候，可以增加参数 java -Xms16g -Xmx32g -XX:ParallelGCThreads=8 -jar 来控制内存使用与线程数目。
4. Linux 中 批量kill程序 ps -ef|grep LOCAL=NO|grep -v grep|cut -c 9-15|xargs kill -9 
