<h1>Raspberry Pi-Hosted Network Statistics Monitor</h1>

<h2>Description</h2>
The premise of this project was to configure my Raspberry Pi 4 (using Raspberry Pi OS) to automatically capture network statistics from my home network.
I created a Python script that leverages the Ookla Speedtest CLI tool in order to capture network data including download speed, upload speed, ping, and latency.
I used a Cronjob to automatically execute this script every 15 minutes, and the resulting data is automatically output and stored within a docker-hosted Grafana instance.

<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b>
- <b>Bash</b>
- <b>Cron</b>
- <b>Grafana</b>
- <b>Docker</b>

<h2>Environments Used </h2>

- <b>Raspberry Pi OS</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
