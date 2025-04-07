<h1>Security Incident and Event Management (SIEM) with ELK Stack</h1>


<h2>Description</h2>
I deployed an AWS OpenSearch domain and configured Logstash to ingest CloudTrail logs from S3. In Kibana I created index patterns and custom dashboards to visualize security events. I enabled prebuilt detection rules to catch suspicious activity and set up real‑time alerts to notify the team of potential threats. This scalable SIEM solution boosted visibility and sped up incident response.
<br />


<h2>Utilities Used</h2>

- AWS OpenSearch Service
- Amazon S3
- AWS CloudTrail
- AWS EC2
- AWS IAM roles and security groups
- Logstash 
- Kibana 


<h2>Project Walk-through</h2>

<p align="center">
Set up CloudTrail to S3 <br />
<img src="https://i.imgur.com/yY1Pggt.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create OpenSearch domain <br/>
<img src="https://i.imgur.com/4VXDR8D.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch EC2 and install Logstash <br/>
<img src="https://i.imgur.com/2Grcol8.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Define index patterns in Kibana <br/>
<img src="https://i.imgur.com/2Qs6lPW.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
Enable detection rules <br/>
<img src="https://i.imgur.com/pg0ib8P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure real‑time alerts <br/>
<img src="https://i.imgur.com/7wFIZ4m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
