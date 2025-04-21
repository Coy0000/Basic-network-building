# 🌐Basic-network-building


## 1.🔌 Components
<img src="https://github.com/Coy0000/Basic-network-building/blob/main/1.PNG" height="80%" width="80%" alt="Start"/>
Using 🖥️ 2PCs for each switch, 🖧 2 switches , the *2960 24TT*, and⚙️ 1 router, the *1941*.



## 2. 📶 Connection

<img src="https://github.com/Coy0000/Basic-network-building/blob/main/2.PNG" height="80%" width="80%" alt="Start"/>
Connecting all the PCs with switches using 📡 *fast ethernet*,  with *copper straight through* 🔗
<img src="https://github.com/Coy0000/Basic-network-building/blob/main/3.PNG" height="80%" width="80%" alt="Start"/>
Connecting all the switches with the router, using *gigabit ethernet.* 📡
<img src="https://github.com/Coy0000/Basic-network-building/blob/main/4.PNG" height="80%" width="80%" alt="Start"/>


## 3.Command Line Interface (CLI) part📋 
<img src="https://github.com/Coy0000/Basic-network-building/blob/main/5.PNG" height="80%" width="80%" alt="Start"/>
Opening the router CLI. 📋


Typing in the the following commands to configure the router and switches
```bash
enable
```
```bash
configure terminal
```
```bash
interface g0/0
```
```bash
ip address 192.168.1.1 255.255.255.0
```
```bash
no shutdown
```
```bash
exit
```


<img src="https://github.com/Coy0000/Basic-network-building/blob/main/6.PNG" height="80%" width="80%" alt="Start"/>

<img src="https://github.com/Coy0000/Basic-network-building/blob/main/7.PNG" height="80%" width="80%" alt="Start"/>
Arrows have turned green✔️. (between first switch and router)


And now doing the same for the other interface g0/1, except using a different ip address, 
```bash
192.168.2.1
 ```


## 4. Ip Addresses
Assigning Ip addresses according to the interface's set default gateway. 📶


🌐*Default gateway: used to send traffic outside the local network (like to another network or the internet). Basically the ip we assigned to the interfaces earlier*



<img src="https://github.com/Coy0000/Basic-network-building/blob/main/8.PNG" height="80%" width="80%" alt="Start"/>

<img src="https://github.com/Coy0000/Basic-network-building/blob/main/9.PNG" height="80%" width="80%" alt="Start"/>

<img src="https://github.com/Coy0000/Basic-network-building/blob/main/10.PNG" height="80%" width="80%" alt="Start"/>

<img src="https://github.com/Coy0000/Basic-network-building/blob/main/11.PNG" height="80%" width="80%" alt="Start"/>

## 5. 🖧Testing

Sending Simple PDU across PCs.💻
<img src="https://github.com/Coy0000/Basic-network-building/blob/main/12.PNG" height="80%" width="80%" alt="Start"/>

