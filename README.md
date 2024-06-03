<h1>Lola La Chata - Halloween 23</h1>

 <!-- ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)/> -->

<h2>Description</h2>
Renowned detective, Detective Rodriguez, known for cracking every case he encounters, found himself facing a daunting challenge: the sudden disappearance of his close friend, Lola. Determined to help, Rodriguez delves into the investigation with a fierce resolve.

In the pursuit of answers, various pieces of evidence have been gathered. Now, Detective Rodriguez stands on the precipice of a crucial step: investigating the shared desktop computer of Lola and her husband, Hector.

Here's where you come in. You are now stepping into the shoes of Detective Rodriguez. Can you unravel the mystery? Will you be able to solve the case, bringing closure to Lola's friends and relatives, or will her disappearance remain an unsolvable enigma, haunting the hearts of those who loved her? The fate of this mystery lies in your hands.
In a quiet town, the disappearance of María Dolores Estévez Zuleta, affectionately known as "Lola La
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
<h3>Q1) What is the full path of the encrypted storage? (Format: C:\path\to\name.ext)</h3>
<b>Look into Lab Files on Desktop</b> <br/>
** Translate Message from Lola La Chata to Mr Rodriguez <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/49faa3bf-5d8b-471a-be1d-2f4101a8ffbc)" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />
 
** Read More About Scenario <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/ae817c95-8d87-4d61-a4eb-636352910366" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />


<b>Browse Program Files for Clues to Installed Software</b> <br/>
** OSINT VeraCrypt - Disk Encryption Software <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/f03ce4a0-be94-45ce-9f13-86a7aa55fe59" height="80%" width="80%" alt="VeraCrypt Found"/>
<br />
<br />

<b>Investigate VeraCrypt files</b> <br/>
** OSINT .hc VeraCrypt File Extension - Encrypted files with VeraCrypt <br />
** ANSWER TO Q1) C:\Program Files\VeraCrypt\HectorFiles.hc <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/0a1406c3-7b2a-4883-a2f0-0893362a1400" height="80%" width="80%" alt="VeraCrypt Found"/>
<br />
<br />

<h3>Q2) What Encryption Algorithm and Type of the encrypted storage? (Format: algorithm, type)</h3>
<b>Decrypt storage and mount to open drives</b> <br/>
** Select HectorFiles.hc - Need Password to mount<br />
** Investigate running tools - Ditto <br />
** OSINT Ditto - Clipboard Manager (password could be copied to clipboard at some point) <br />
** Try possible passwords from Ditto <br />
** Found one that worked <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/7bb486b8-8b6d-4e93-8c93-a0b2bfc16d08" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />
** ANSWER TO Q2) AES, hidden <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/4dc817fe-ca4b-4c8d-91b0-88d04408e273" height="80%" width="80%" alt="VeraCrypt Found"/>
<br />
<br />

<h3>Q3) What is the version of the steno tool used to decode the secret message found inside MyDealLola.jpg? (Format: X.X.X)</h3>
<b>Look into silenteye or openpuff as possible steno tool used (HINT: listed as investigation tags)</b> <br/>
** Investigating Program Files again but not finding anything related to silenteye or openpuff <br />
** Enabled hidden files under View > check Hidden items - No clues in local drive <br />
** FOUND silenteye - Enabled hidden files in disk with HectorFiles (hidden folder "hate") <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/49faa3bf-5d8b-471a-be1d-2f4101a8ffbc)" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />
 
** Read More About Scenario <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/ae817c95-8d87-4d61-a4eb-636352910366" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />


<b>Browse Program Files for Clues to Installed Software</b> <br/>
** OSINT VeraCrypt - Disk Encryption Software <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/f03ce4a0-be94-45ce-9f13-86a7aa55fe59" height="80%" width="80%" alt="VeraCrypt Found"/>
<br />
<br />

<b>Investigate VeraCrypt files</b> <br/>
** OSINT .hc VeraCrypt File Extension - Encrypted files with VeraCrypt <br />
** ANSWER TO Q1) C:\Program Files\VeraCrypt\HectorFiles.hc <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/0a1406c3-7b2a-4883-a2f0-0893362a1400" height="80%" width="80%" alt="VeraCrypt Found"/>
<br />
<br />
<b>Investigate newly mounted storage</b> <br/>
** Letters_To_Lola - Image capture Spanish message > Image to text converter to get text > Translate Spanish text to English <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/48f646fb-5e50-4ed2-88e3-23ca8a822fd1" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/2977f1c7-c0dd-4be1-87ae-dcdea716f6bc" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />


<h3>Q7) Going back to Letters_To_Lola.rtf there is a highlighted word, What is the spanish word and its english counterpart? (Format: spanish, english)</h3>
** ANSWER TO Q7) traicion, betrayal <br />
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
