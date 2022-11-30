# TryHackMe-Practical-Investigations

In this module we will be using a few different evtx files to perform a number of investigations of event logs while using Sysmon to removes the noise of normal network activity.<br>
<br>
<b>Investigation 1:</b><br>
<br>
What is the full registry key of the USB device calling svchost.exe in Investigation 1? <br>
<br>
<a href="https://imgur.com/61qpW1e"><img src="https://i.imgur.com/61qpW1e.png" title="source: imgur.com" /></a><br>
<a href="https://imgur.com/d6Gwrvu"><img src="https://i.imgur.com/d6Gwrvu.png" title="source: imgur.com" /></a><br>
<br>
<b>Answer:</b> HKLM\System\CurrentControlSet\Enum\WpdBusEnumRoot\UMB\2&37c186b&0&STORAGE#VOLUME#_??_USBSTOR#DISK&VEN_SANDISK&PROD_U3_CRUZER_MICRO&REV_8.01#4054910EF19005B3&0#\FriendlyName<br>
<br>
What is the device name when being called by RawAccessRead in Investigation 1?<br>
<br>
<a href="https://imgur.com/rBFTAC7"><img src="https://i.imgur.com/rBFTAC7.png" title="source: imgur.com" /></a><br>
<br>
<b>Answer:</b> \Device\HarddiskVolume3<br>
<br>
What is the first exe the process executes in Investigation 1?<br>
<br>
<a href="https://imgur.com/v0u7BfB"><img src="https://i.imgur.com/v0u7BfB.png" title="source: imgur.com" /></a><br>
<br>
<b>Answer:</b> rundll32.exe <br>
<br>
<b>Investigation 2:</b><br>
<br>
What is the full path of the payload in Investigation 2?<br>
<br>
<a href="https://imgur.com/zbkCb2Y"><img src="https://i.imgur.com/zbkCb2Y.png" title="source: imgur.com" /></a><br>
<br>
<b>Answer:</b> C:\Users\IEUser\AppData\Local\Microsoft\Windows\Temporary Internet Files\Content.IE5\S97WTYG7\update.hta<br>
<br>
What is the full path of the file the payload masked itself as in Investigation 2?<br>
<br>
<a href="https://imgur.com/YzC4Ci9"><img src="https://i.imgur.com/YzC4Ci9.png" title="source: imgur.com" /></a><br>
<br>
<b>Answer:</b> C:\Users\IEUser\Downloads\update.html<br>
<br>
What signed binary executed the payload in Investigation 2?<br>
<br>
