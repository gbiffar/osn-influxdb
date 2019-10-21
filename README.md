# osn-influxdb

This ansible role will install influxdb

For a list of variable that should be defined, see defaul/main.yml

Example playbook (assumed influxdb is a host group defined):

\- hosts:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\- influxdb  
&nbsp;&nbsp;&nbsp;remote_user: ansible  
&nbsp;&nbsp;&nbsp;become: yes  
&nbsp;&nbsp;&nbsp;become_method: sudo 
<br /><br />
&nbsp;&nbsp;&nbsp;roles:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- osn-influxdb
