# 亮点：快速搭建MySQL集群监控
* 集合zabbix，导入自动化脚本以及grafana模板

# 步骤
# 1. 部署zabbix agent
* 导入agent配置文件(zabbix_agentd.conf)，以及脚本scripts.tar.gz。并启动agent
# 2. 增加自动化发现模板
* 登陆web端，添加模板(zbx_export_templates.xml)
# 3. 配置grafana变量
* 选择zabbix数据源，Query填写：DB-MySQL.*  
# 4. 添加MySQL dashboard
* 导入grafana dashborad文件(grafana_mysql.json)


# demo图片
* grafana变量设置
![Image text](https://raw.githubusercontent.com/ocpeng/MySQL-monitor/master/MySQL-monitor/demo/02.png)
* 最终效果展示
![Image text](https://raw.githubusercontent.com/ocpeng/MySQL-monitor/master/MySQL-monitor/demo/01.png)
* 如能帮助到您，欢迎给与支持，谢谢
![Image text](https://raw.githubusercontent.com/ocpeng/MySQL-monitor/master/MySQL-monitor/demo/03.png)
