# Assignment 1
###### tags: `Wireless Communications`



##  1: Make a Wireshark and KS Wireshark installation guide
### 

- **1.1 Install Wireshark**
    - Visit Wireshark Official Website
        - [Link to Official Website](https://www.wireshark.org/)
        - ![image](https://hackmd.io/_uploads/SyCS3du2le.png)

     - Download Install Package
         -  [Link to Download Install Package](https://www.wireshark.org/#download)
         -  ![image](https://hackmd.io/_uploads/ryn8Y8u2gl.png)
    - Click on Windows x64 Installer to acquire pakage
        - [Link to Package](https://2.na.dl.wireshark.org/win64/Wireshark-4.4.9-x64.exe) 
    - Wait for the download process to complete
        - ![image](https://hackmd.io/_uploads/HyM8qUd2lg.png)

    - Click on the downloaded file to start installation process
    -  Click "Yes" on UAC window
        -  ![image](https://hackmd.io/_uploads/H1wjqLuhxg.png)
    - Click "Next" on Setup window
        - ![image](https://hackmd.io/_uploads/Hkc09UOhgx.png)
    - Click "Noted"
        - ![image](https://hackmd.io/_uploads/S1xGjLuhge.png)
    - Click "Next"
        - ![image](https://hackmd.io/_uploads/ryNNiLungg.png)
    - Pick the packages you would like to install, then click "Next"  
        - ![image](https://hackmd.io/_uploads/SkLdsLOnex.png)
    - Click "Next"
        - ![image](https://hackmd.io/_uploads/BytciIdnxe.png)
    - Click "Next"
        - ![image](https://hackmd.io/_uploads/ry_AsI_hxe.png)
    - Click "Next"
        - ![image](https://hackmd.io/_uploads/BkMehLu3xg.png)
    - Click "Install"
        - ![image](https://hackmd.io/_uploads/BJRz3I_nlg.png)
    - Click "I agree" on Ncap setup window
        - ![image](https://hackmd.io/_uploads/SJGI2LOhge.png)
    - Click "Install"
        - ![image](https://hackmd.io/_uploads/rJE_3I_neg.png)
    - Click "Next" after Ncap successfully installed 
        - ![image](https://hackmd.io/_uploads/SyGj28uhll.png)
    - Click "Finish"
        - ![image](https://hackmd.io/_uploads/HJR2hUdhgl.png)
    - Back to Wireshark setup window, then click "Next"
        - ![image](https://hackmd.io/_uploads/B13ZpIO3le.png)
    - Click "Finish"
        - ![image](https://hackmd.io/_uploads/H1YVa8dhxg.png)
    - Click on Wireshark icon on your Desktop
        - ![image](https://hackmd.io/_uploads/H1kdpIu2gl.png)
    - Complete!
        - ![image](https://hackmd.io/_uploads/BJ7cpIO3ee.png)

- **1.2 Install KS Wireshark**
    - Acquire Install Package on Provided Link
        - [Link](https://drive.google.com/drive/folders/1FiEmKeXc4M7qfkHbAzDjbaQ0Yn-SRcCO)
    - Download .exe file to your desktop
        -  ![image](https://hackmd.io/_uploads/HJEdA8Ongl.png)
    - Click on KS Wireshark install package
        - ![image](https://hackmd.io/_uploads/By2aRLOnll.png)
    - Click "Yes" on UAC window
        - ![image](https://hackmd.io/_uploads/rJveyDu3xg.png)
    - Click "Yes" on setup window
        - ![image](https://hackmd.io/_uploads/rkJXJwd3lg.png)
    - Click "I agree"
        - ![image](https://hackmd.io/_uploads/B1KEyvuhgx.png)
    - Click "Next"
        - ![image](https://hackmd.io/_uploads/r1sI1wOnlg.png)
    - Click "Next"
        - ![image](https://hackmd.io/_uploads/BJI_kPOnex.png)
    - Click "Next"
        - ![image](https://hackmd.io/_uploads/ry3FyDd3eg.png)
    - Click "Next"
        - ![image](https://hackmd.io/_uploads/B1Eoyvd2le.png)
    - Click "Install"
        - ![image](https://hackmd.io/_uploads/Hkt2JPdnxl.png)
    - Click "Next" after installation process completed
        - ![image](https://hackmd.io/_uploads/HJeegPdnxl.png)
    - Click "Finish"
        - ![image](https://hackmd.io/_uploads/ByWflD_2ll.png)


   



         
    
    
    - **Reference:**
        - [鳥哥 vbird](https://linux.vbird.org/)
        




## 2. Capture packets: access the NTUST homepage (https://www.ntust.edu.tw/home.php) and answer the following questions
### 
- **2.1 What is the IP address and port of the NTUST homepage (https://www.ntust.edu.tw/home.php)?**
    - IP Address: 140.118.242.124
    - Port: 443
        - ![image](https://hackmd.io/_uploads/HkaH6vu2el.png)

        - ![image](https://hackmd.io/_uploads/rJn-6wOnlx.png)


- **2.2 What is the IP address and port of your PC when initially accessing the page?**
    - IP address: 192.168.31.158 (DHCP)
    - Port: 3100
        - ![image](https://hackmd.io/_uploads/ryo86vdhlx.png)

        - ![image](https://hackmd.io/_uploads/rJfMpP_2lx.png)


- **2.3 What is the process of the TCP three-way handshake?**
    1. Client → Server：SYN=1, ACK=0（request to establish connection）
        - ![image](https://hackmd.io/_uploads/SJ7Y6vO3gg.png)


    2. Server → Client：SYN=1, ACK=1（accept and reply ACK)
        - ![image](https://hackmd.io/_uploads/HJO9pw_hee.png)

 
   
     3.  Client → Server：ACK=1（confirm the reply）
            - ![image](https://hackmd.io/_uploads/rkE2pDu3gg.png)

    **Diagram of TCP hanshake (from Wireshark official website)**
    - ![image](https://hackmd.io/_uploads/Hy7_0POnxe.png)


 


## 3. Use the filter dns to find a DNS packet and answer the following questions
### 

![image](https://hackmd.io/_uploads/H1zmy_Oheg.png)

- **3.1 What is the IP address and port of the DNS server?**
    - IP address: 1.1.1.1
    - Port: 53 (UDP)
    - ![image](https://hackmd.io/_uploads/SkcUJOOngx.png)

- **3.2 What is the domain name in this query?**
    - Domain: www.ntust.edu.tw
    - ![image](https://hackmd.io/_uploads/B1u6Ju_2xe.png)

- **3.3 Which protocol(s) does this DNS packet use? (List the protocols from Layer 2 — Link Layer — up to Layer 5 — Application Layer in the TCP/IP five-layer model.)**
    - Layer 2: Ethernet Ⅱ
    - Layer 3: IPv4
    - Layer 4: UDP
    - Layer 5: DNS
     ![image](https://hackmd.io/_uploads/SkXvWO_hll.png)



## 4. Access an HTTP page (e.g., http://www.gzxyzn.com/Article/bjrk2/1644.html) and answer the following questions
### 
- **4.1 Which HTTP page did you access?**
    - Address: http://abehiroshi.la.coocan.jp/
    - ![image](https://hackmd.io/_uploads/HkUqMOOnll.png)
    - ![image](https://hackmd.io/_uploads/HJHtQddnxx.png)


- **4.2 What is the IP address and port of the server hosting this page?**
    - IP address: 222.158.205.72
    - Port: 80
    - ![image](https://hackmd.io/_uploads/SJMT7ud3eg.png)

- **4.3 What is the request method?**
    - Request Method: GET
    - ![image](https://hackmd.io/_uploads/BkW4VdO3le.png)

- **4.4 What is the response status code, and what does it mean?**
    - Status Code: 304 Not Modified
    - "304 Not Modified" means that the content on the page has not been changed since last access, does not reuqire retransmission of data.
    - ![image](https://hackmd.io/_uploads/HJOXH_Ohll.png)



## 5. Link of the PCAP

 - 1. [Pcap file for www.NTUST.edu.tw] (https://github.com/chuchenting/ET6207701-Wireless-Communications/blob/main/Assignment%201/www-ntust-edu-tw.pcap)
 - 2. [Pcap file for abehiroshi.la.coocan.jp] (https://github.com/chuchenting/ET6207701-Wireless-Communications/blob/main/Assignment%201/http.pcap)