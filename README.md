<h1>Raspberry Pi-Hosted Network Statistics Monitor</h1>

<h2>Description</h2>
The premise of this project was to configure my Raspberry Pi 4 (using Raspberry Pi OS) to automatically capture network statistics from my home network.
I created a Python script that leverages the Ookla Speedtest CLI tool in order to capture network data including download speed, upload speed, ping, and latency.
I used a Cronjob to automatically execute this script every 15 minutes, and the resulting data was automatically outputted and stored within a Grafana instance.
This project was incredibly fun to set up and provided me with interesting insights into the fluctuation of my network speeds during different times of day.

<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b>
- <b>Cron</b>
- <b>Grafana</b>
- <b>InfluxDB</b>

<h2>Environments Used </h2>

- <b>Raspberry Pi OS</b>

<h2>Project walk-through:</h2>

<p align="center">
<b>Install the Ookla Speedtest CLI Tool:</b> <br/>
<img src="https://i.imgur.com/NONn3o4.png" height="100%" width="100%" alt="Raspberry Pi-Hosted Network Statistics Monitor"/>
<br />
<br />
<b>Create the Python script:</b>  <br/>
<img src="https://i.imgur.com/12blql2.png" height="100%" width="100%" alt="Raspberry Pi-Hosted Network Statistics Monitor"/>
<br />
<br />
<b>Create a cron job to automate the Python script:</b>  <br/>
<img src="https://i.imgur.com/wYjAin2.png" height="100%" width="100%" alt="Raspberry Pi-Hosted Network Statistics Monitor"/>
<br />
<br />
<b>Create Dashboard in Grafana:</b> <br/>
<img src="https://i.imgur.com/40qbFbp.png" height="100%" width="100%" alt="Raspberry Pi-Hosted Network Statistics Monitor"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
