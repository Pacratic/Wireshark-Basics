<h1>Wireshark Basics Lab</h1>



<h2>Objectives:</h2>
How to use general Wireshark tools.<br />
How to perform packet dissrection.<br />
How to navigate the packet files.<br />

<br />
<h2>Lab Overview</h2>
This room/lab will be used to work with the basics of Wireshark utilizing packet dissection, packet navigation, and packet filtering. 


<h2>Languages and Utilities Used</h2>

- <b>C,C++</b>
- <b>Wireshark 3.2.3</b>


<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="left">
Launch Exercise.pcapng: <br/>
  <br/>
  In this section of the of the lab, the objective is to read the capture file comments. To do this I am going to go to the statistics tab and use the capture file properties. This gives me an overview of the file while also showing the capture file comments. In this comment listed I can see the flag as TryHackMe_WiresharkDemo
<img src="https://i.imgur.com/tRCLMNI.png" height="80%" width="80%" alt=/>
<br />
<br />
  Other information such as the SHA256 value, OS, and total packets can all be found within this window as well. In this window it can be seen that there is a total of 58620 packets and other relevant info. 
<br/>
  <br/>
  Packet Dissection:
  <br/>
  <br/>
  In this section it gets more granular in terms of the info provided. In the packet 27 I can pull data to view various OSI layers.
<br/>
  Layer 1: this view gives us a look at the details specefic to the physical layer of the OSI Model
<br/>
  <img src="https://i.imgur.com/71BsmFC.png" height="80%" width="80%" alt=/>
<br/>
  <br/>
  Layer 2: this view gives us a look at the source and destination addresses from the data link layer of the OSI Model
<br/>
    <img src="https://i.imgur.com/iu3MyAp.png" height="80%" width="80%" alt=/>
    <br/>
    <br/>
  Layer 3: This layer shows the source and destination IPv4 addresses from the netwrok layer of the OSI Model
  <br/>
  <img src="https://imgur.com/6fbf784c-a09f-41ec-b2b2-44f74713fb72" height="80%" width="80%" alt=/>
  <br/>
  <br/>
  Layer 4: This layer will show the protocol used and source destination port from the transport layer of the OSI Model, it will aslo show specified sedment from the TCP that needed to be reassembled.
  <br/>
   <img src="https://i.imgur.com/m83wDjo.png" height="80%" width="80%" alt=/>
   <br/>
   <br/>
   Layer 5: This layer shows us the details specefic to the protocol used and can show the application specefic data.
<br/>
  <img src="https://i.imgur.com/3tBqcsO.png" height="80%" width="80%" alt=/>
  <br/>
  <br/>
  Using this we can dissect the packet the answer questions specefic to the individual packet, looking at another packet and using this window I can now answer markup language used, arrival date of packet, TTL value, TCP payload size, and e-tag value.
<br/>
<br/>
Packet Navigation:
<br/>
<br/>


