<h1>MariaDB</h1>

 
<h2>Description</h2>
MariaDB is a community-developed, commercially supported fork of the MySQL relational database management system
<br />


<h2>Languages and Utilities Used</h2>

- <b>MariaDB</b> 


<h2>Environments Used </h2>

- <b>Centos 7  </b>

<h2>Tooling Walkthrough:</h2>

<p align="center">
Steps to install and configure an apache server
<br />
<br />
   <p align="left">
1. dnf install -y httpd<br />
  <br />
2. add ports to the firewall<br />
 -	a. firewall-cmd --zone public --add-port {80,443}/tcp --permanent
  <br />
  - b. firewall-cmd --reload
<br/>
<br/>
3. add service http or https to the firewall<br />
 -	a. firewall-cmd --zone public --add-service http --permanent
  <br />
  - b. firewall-cmd --reload
<br />
<br />
4. systemctl restart httpd
<br />
<br />
5. apache config files are under can be located under /etc/http/ and /var/www/html/







<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
