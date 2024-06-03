<h1>Lola La Chata - Halloween 23</h1>

 <!-- ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)/> -->

<h2>Description</h2>
Renowned detective, Detective Rodriguez, known for cracking every case he encounters, found himself facing a daunting challenge: the sudden disappearance of his close friend, Lola. Determined to help, Rodriguez delves into the investigation with a fierce resolve.

In the pursuit of answers, various pieces of evidence have been gathered. Now, Detective Rodriguez stands on the precipice of a crucial step: investigating the shared desktop computer of Lola and her husband, Hector.

Here's where you come in. You are now stepping into the shoes of Detective Rodriguez. Can you unravel the mystery? Will you be able to solve the case, bringing closure to Lola's friends and relatives, or will her disappearance remain an unsolvable enigma, haunting the hearts of those who loved her? The fate of this mystery lies in your hands
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
 
<b>Look into Lab Files on Desktop</b> <br/>
* Translate Message from Lola La Chata to Mr Rodriguez
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/49faa3bf-5d8b-471a-be1d-2f4101a8ffbc)" height="80%" width="80%" alt="Planning Diagram"/>
<br />
<br />
 
<b>DC Installation (Server ISO):</b>  <br/>
<img src="https://github.com/nickstrunk/ActiveDirectoryLab/assets/165805194/8679325e-bd56-47df-b4cc-43c1231c8c47" height="80%" width="80%" alt="DC Installation"/>
<br />
<br />
 
<b>Set Up IP Addressing:</b> <br/>
<img src="https://github.com/nickstrunk/ActiveDirectoryLab/assets/165805194/0e89e34f-1e39-4e07-a98b-c96f3da20198" height="80%" width="80%" alt="Network Interface Cards"/>
<br />
<br />
* No default gateway because the domain controller serves as the default gateway
<br />
* Active directory automatically installs DNS, so there server will use itself as the DNS server. Can use either its own IP address (172.16.0.1) or loopback address (127.0.0.1)
<br />
<br />
<img src="https://github.com/nickstrunk/ActiveDirectoryLab/assets/165805194/1914bbad-8393-437e-ad44-ef71e65595b2" height="80%" width="80%" alt="Internal Addressing"/>
<br />
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
