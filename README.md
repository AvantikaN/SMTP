# SMTP on Cisco Packet Tracer

SMTP is a set of communication guidelines that allow software to transmit an electronic mail over the internet is called Simple Mail Transfer Protocol.The main purpose of SMTP is used to set up communication rules between servers. The servers have a way of identifying themselves and announcing what kind of communication they are trying to perform. They also have a way of handling the errors such as incorrect email address. For example, if the recipient address is wrong, then receiving server reply with an error message of some kind.

Here, I have implemented the configuration of SMTP and DNS on Cisco Packet Tracer. 
I followed the below procedure :
1. Build network topology by adding 2 PC(PC0, PC1), switch, DNS Server and Email server.
    ![image](https://github.com/AvantikaN/SMTP/assets/99970466/9d5a5457-4216-4487-baf4-c245ce966f09)
3. Configure IP addresses on the PCs, DNS Server and the Mail Server.
4. Configure email client on PC0 and PC1 by adding the user, server and login information.
   ![image](https://github.com/AvantikaN/SMTP/assets/99970466/31ff376c-6cc4-4218-96e3-cf2d9e195bde)
   ![image](https://github.com/AvantikaN/SMTP/assets/99970466/701ccf27-6fbf-49d0-9b3e-c6f7565b61b5)


6. Configure EMAIL server by clicking on the email server -> Services-> EMAIL-> add the username password of the mail of both the PCs
   ![image](https://github.com/AvantikaN/SMTP/assets/99970466/3fb3f4aa-4500-4d37-a48e-61f8d82908ca)

8. Configure DNS server by clicking on that server-> Services-> DNS-> add name and ip address of the mail server
   ![image](https://github.com/AvantikaN/SMTP/assets/99970466/c84773b7-309a-4aaf-a20e-5be29a5d3a24)

10. Test the email server by composing mail on either of the PCs and recieving it on the other.
    ![image](https://github.com/AvantikaN/SMTP/assets/99970466/0dc51a80-38b3-4322-805f-aef8429696cd)

  
