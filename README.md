<h1>Lola La Chata - Halloween 23</h1>

 <!-- ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)/> -->

<h2>Description</h2>
Renowned detective, Detective Rodriguez, known for cracking every case he encounters, found himself facing a daunting challenge: the sudden disappearance of his close friend, Lola. Determined to help, Rodriguez delves into the investigation with a fierce resolve.

In the pursuit of answers, various pieces of evidence have been gathered. Now, Detective Rodriguez stands on the precipice of a crucial step: investigating the shared desktop computer of Lola and her husband, Hector.

Here's where you come in. You are now stepping into the shoes of Detective Rodriguez. Can you unravel the mystery? Will you be able to solve the case, bringing closure to Lola's friends and relatives, or will her disappearance remain an unsolvable enigma, haunting the hearts of those who loved her? The fate of this mystery lies in your hands.
In a quiet town, the disappearance of María Dolores Estévez Zuleta, affectionately known as "Lola La
<br />


<h2>Languages and Utilities Used</h2>

- <b>SilentEye</b> 
- <b>OpenPuff</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

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
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/83a0a1e2-31af-40aa-a0c3-6b4b66429e8b" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />
<b>Investigate silenteye</b> <br />
** Run silenteye.exe as Admin > Check for update - displays version <br />
** ANSWER TO Q3) 0.4.1 <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/18a5dd13-a3ce-45cd-ac17-2ec77e5a7601" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />

<h3>Q4) What is the verion of the steno tool used to unhide this secret letter form an audio file? (Format: X.XX)</h3>
<b>Investigate decoding MyDealLola.jpg</b> <br/>
** Open in silenteye > Decode > Passphrase: (potential passphrases from Ditto) <br />
** FOUND Passphrase that worked: juarez (message contains potential future password)<br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/b1058681-9603-4393-9a93-b8bf2eeb4001" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />
<b>Investigate using new potential password to mount HectorFiles again</b> <br />
** Dismount HecktorFiles > Remount HectorFies using password: romanceisdead > Successfully mounts <br />
** Mounted drive now shows more and new folders and files > "hate" now contains OpenPuff (OSINT: Steganography tool) <br /)
** Run OpenPuff as Admin > Version displayed in top left of application <br />
** ANSWER TO Q4) 4.01 <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/a85f9569-d7ca-4abb-85f5-740dd1309062" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />

<h3>Q5) What is the full file name of the carrier audio file where Letter1_from_Gustavo.rtf can be found? (Format: filename.ext)</h3>
<b>Try using silenteye to decode MyDearLola.jpg </b> <br/>
**  Decode using Passphrase: juarez > decoded file From_Juarez.txt > Saved to Desktop <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/c03c3204-e84e-4775-b263-7ba90ab098f7" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />
<b>Investigate From_Juarez.txt</b> <br />
** Translate beginning line of Spanish to English <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/260a57ff-7e97-4567-8dd8-06d4a8da3baf" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />
<b>Using OpenPuff to unhide data with steps in From_Juarez.txt</b> <br />
** Add Carriers > BTLO REPLAY presents PRETIUM Retired Blue Team Lab Walkthrough.mp3 > Enter passwords A,B, uncheck C like instructed > Unhide! to Desktop <br />
** Complete same process for rest of files in Hector_Files according to instructions in From_Juarez.txt > Creates files Letter1_from_Gustavo, Letter2_from_Gustavo, info.txt, betrayal.txt<br />
** ANSWER TO Q5) BTLO REPLAY presents PRETIUM Retired Blue Team Lab Walkthrough.mp3 (found Letter1_from_Gustavor when unhidden)<br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/7009ea17-5883-4026-957e-0eddbed74bdd" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />

<h3>Q6) What is the full file name of the carrier audio file where Letter2_from_Gustavo.rtf can be found? (Format: filename.ext)</h3>
** ANSWER TO Q6) Michael Jackson - Smooth Criminal (Official Video).mp3 (found Letter2_from_Gustavo when unhidden) <br />
<br />
<br />

<h3>Q7) Going back to Letters_To_Lola.rtf there is a highlighted word, What is the spanish word and its english counterpart? (Format: spanish, english)</h3>
** ANSWER TO Q7) traicion, betrayal <br />
<br />
<br />

<h3>Q8) What is the exact address where Detective Rodriguez can find Lola's body? (Format: Address)</h3>
** Letter1 decoded using spammimic.com with password: mydearlola  <br />
** ANSWER TO Q8) La Lomita, 45640 Tlajomulco de Zúñiga, Jalisco, Mexico <br /> <br />
<br />
<br />

<h3>Q9) What is the name of the other lover of Lola? (Format: Full Name)</h3>
** Investigate betrayal.txt <br />
** ANSWER TO Q9) Javier Antonio Rodríguez Morales <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/2c6cabaa-ad76-47c0-8bdc-d1d38da544f0" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />

<h3>Q10) Who killed Lola? (Format: Full Name)</h3>
** Translate info.txt from Spanish to English<br />
** ANSWER TO Q10) Gustavo de Jesús Gaviria Rivero <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/03e1b4a3-18db-4f84-a923-3989a41244cd" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />


<h3>Q11) Who plotted the kill of Lola and Javier? (Format: Name)</h3>
** In HectorFiles > To_Detective_Rodriguez.txt > Tells who ordered the killings <br />
** ANSWER TO Q11) Hector <br /> <br />
<img src="https://github.com/nickstrunk/LolaLaChata-Halloween23/assets/165805194/1f6dbaee-9706-4360-80bd-79e3ec30296a" height="80%" width="80%" alt="Translated Message"/>
<br />
<br />

<h3>Q12) What cartel does Hector Salamanca belong? Perform OSINT (Format: Cartel Name)</h3>
** ANSWER TO Q12) Juarez <br />
<br />
<br />

<h3>Q13) Finally, What is the exact GPS location of Lola’s body? - WRITE DOWN YOUR ANSWER, YOU'LL NEED IT FOR THE FINAL HALLOWEEN LAB! (Format: longitude, latitude)</h3>
** Letter2 decoded using spammimic.com with password: mydearlola  <br />
** ANSWER TO Q13) 20.480135, -103.44236 <br /> <br />
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
