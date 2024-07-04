<h1><b>Network Performance Monitoring with Ansible 🔎</b></h1>
<hr>
  
<h2>Introduction</h2>
<p>This project focuses on using Ansible for network performance monitoring on Ubuntu 20.04 hosted on VirtualBox. It explores the automation capabilities of Ansible to monitor CPU load, memory usage, and network interfaces on a local Ubuntu system.</p>
<h2>Objectives</h2>
<p>
  The main objectives of this project are:
</p>
<ul>
  <li>Utilize Ansible playbooks to measure network performance on a local Ubuntu system.</li>
  <li>Monitor CPU load, memory usage, and network interfaces using automated scripts.</li>
  <li>Analyze and report system metrics to ensure optimal performance.</li>
</ul>
<h2>Setup and Configuration</h2>
<h3>System Setup</h3>
<p><b>Operating System: </b>Ubuntu 20.04 running on VirtualBox hosted on a Windows PC.</p>
<h3>Ansible Installation</h3>
<p>Ansible was installed from the official PPA repository to facilitate automated deployment and configuration tasks.</p>
<h3>Task Details</h3>
<p><b>Network Management Task</b></p>
<ul>
  <li>Playbook Name: local_monitor.yml</li>
  <li>Tasks Implemented</li>
  <ul>
    <li>Fetch and display CPU load using /proc/loadavg.</li>
    <li>Monitor and report memory usage with free -m.</li>
    <li>Retrieve network interface details using ip a command.</li>
  </ul>
</ul>
<h1>Execution of Playbooks</h1>
<p>The local_monitor.yml playbook was executed using the following command:<br><br><b><center>ansible-playbook local_monitor.yml -i hosts.ini
</center></b><br><br>The results were captured and analyzed to provide insights into the current operational status of the system.</p>
<h1>Repository Structure</h1>
<ul>
  <li>local_monitor.yml: Ansible playbook for monitoring network performance.</li>
  <li>local_monitor.yml: Ansible playbook for monitoring network performance.</li>
  <li>local_monitor.yml: Ansible playbook for monitoring network performance.</li>
</ul>
<h1>USAGE</h1>
<p>To use this project:</p>
<ol>
  <li>Ensure you have Ansible installed on your system.</li>
  <li>Clone the repository to your local machine.</li>
  <li>Modify hosts.ini to include your target hosts.</li>
  <li>Run ansible-playbook local_monitor.yml -i hosts.ini to execute the playbook.</li>
</ol>






