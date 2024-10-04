# 30 days SOC Project

## Objective

This SOC Project created by <a href="https://www.youtube.com/@MyDFIR">MyDFIR</a> for Junior SOC Analyst like me that want to explore the pratical world of a Security Operation Center.

Reccomendetion: I'm at the start of my studing/carrer in cybersecurity, and probably there can be some error of spalling or something that isn't right. I will try my bast to be precise and  

<!-- ### Skills Learned
[Bullet Points - Remove this afterwards]

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.
-->
### Tools Used

- Draw.io for the presentation of the project with a diagram
<!-- 
- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.
-->
## Steps
<!--drag & drop screenshots here or use imgur and reference them using imgsrc -->
<h3>Day 1: Network Diagram</h2>
<p>We will create a diagram of the network to have all the info about it written down.</p>

<img src="https://github.com/user-attachments/assets/d113bf72-e69c-4a08-b598-ae55e36a476f" alt="Ref 1: Network Diagram">
<p>Ref 1: Network Diagram</p>

<h3>Day 2: ELK Stack Introduction</h3>

<p>For collecting telemetric there are two popular ways, that are: <b>Beats</b> and <b>Elastic Agents</b>.</p>

<div>
  <table border="1" cellpadding="10">
    <tr>
      <th><b>Types of Beats</b></th>
      <th><b>Description</b></th>
    </tr>
    <tr>
      <td>File Beat</td>
      <td>Logs</td>
    </tr>
    <tr>
      <td>Metric Beat</td>
      <td>Metrics</td>
    </tr>
    <tr>
      <td>Packet Beat</td>
      <td>Network Data</td>
    </tr>
    <tr>
      <td>Winlog Beat</td>
      <td>Windows Event</td>
    </tr>
    <tr>
      <td>Audit Beat</td>
      <td>Audit Data</td>
    </tr>
    <tr>
      <td>Heartbeat Beat</td>
      <td>Uptime</td>
    </tr>
  </table>
</div>

<h3>Day 3: Elasticsearch setup</h3>

