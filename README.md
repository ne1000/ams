运维自动化平台的开发
目前实现功能：
1. 主机的增删查改，免密码认证等
2. java应用发布和回退,包括tomcat重启/停止/启动等
3. nginx/apache/jdk/tomcat多实例/php-fpm/mysql/memcached/keepalived/maven/zabbix等的部署
4. 上线单的提交和显示
5. java应用的集群发布会回退

一.登陆界面
![登录界面](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%871.png)


二.Dashboard
![dashboard](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%872.png)

profile设置菜单包括退出和修改密码
![profile](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%873.png)

三.列表菜单
1.主机组的增删查改
![hostgroup](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%874.png)

机房的增删查改
![idc](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%875.png)

发布环境的增删查改
![env](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%876.png)

2.主机列表页，主机的增删查改以及主机免密码认证、初始化
![hostlist](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%877.png)

3.批量认证页，多台主机的免密码认证
![batchauth](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%878.png)

四.发布管理菜单
1.应用列表页，单应用的发布、回退、重启、启动、停止等
![apppage](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%879.png)

2.集群发布
![clusterpage](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%8710.png)

3.集群回退
![clusterrollbackpage](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%8711.png)

4.待发布, 列出等待发布的应用或sql
![waitrelease](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%8713.png)

5.已发布，列出发布的应用或sql
![released](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%8714.png)

6.上线单页，开发提交上线应用和sql语句
![onlinepage](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%8715.png)

五.部署菜单
1.部署列表，部署的应用列表都在这里，比如nginx, apache, tomcat, mysql, hadoop等，都需要写单独的ansible playbook
![installlist](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%8716.png)

2.tomcat部署详情页, 允许一台主机上部署多个tomcat实例
![tomcat](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%8717.png)

六.系统管理菜单
用户设置、用户注册
![settings](https://github.com/ne1000/ams/blob/master/%E5%9B%BE%E7%89%8718.png)
目前实现的功能暂时这些，更多功能未完待续.......
