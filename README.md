# graylog.contentpack
Graylog 3 Content Packs


## AWX 9.0.1.0
* AWX running on OpenShift 3.11 (Export Logs in Logstash format)
* Created with Graylog 3.1.3
### AWX Screenshots
![graylog_dashboard_awx](/screenshots/graylog_dashboard_awx.png) 
![graylog_awx_log_conf](/screenshots/graylog_awx_log_conf.png) 


## CentOS 7
* Created with Graylog 3.1.3 on CentOS7
* Graylog installed with ansible role: 
```ansible-galaxy install uniqconsulting.graylog3```
* Extractors are once in ContentPack and once separated in JSON for better handling.

### Dashboard Screenshots
![graylog_dashboard_account_mgmt](/screenshots/graylog_dashboard_account_mgmt.png)    
![graylog_dashboard_account](/screenshots/graylog_dashboard_account.png)    
![graylog_dashboard_mail](/screenshots/graylog_dashboard_mail.png)   
![graylog_dashboard_systemd](/screenshots/graylog_dashboard_systemd.png)   
![graylog_dashboard_yum](/screenshots/graylog_dashboard_yum.png)   

