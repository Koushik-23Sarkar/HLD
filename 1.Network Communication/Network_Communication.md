#### Network Communication	
Network Communication: are rules that both client and server follow to communicate.
	In HLD, we deal with 2 layers:
				1. Application Layer
				2. Transport Layer
1. Application Layer:

   I. HTTP / HTTPS  
   II. FTP / SFTP: File Transfer Protocol  
   III. SMTP: Simple Mail Transfer Protocol  
        - POP3 / IMAP  
   IV. WebRTC: Peer-to-peer real-time communication (audio, video, data)  
   V. WebSockets: Full-duplex communication between client and server  
2. Transport Layer:

   I. TCP: Transmission Control Protocol  
      --> Reliable but slower  
      --> Connection-oriented (3-way handshake)  
      --> Guarantees delivery, order, and error checking  
      --> Receiver sends acknowledgements (ACK) back to sender  

   II. UDP: User Datagram Protocol  
       --> Unreliable but faster  
       --> Connectionless (no handshake)  
       --> No guarantee of delivery, order, or duplication  

#### Topic:
1. Request Responance model
2. Horizontal Scaling vs Vertical Scaling
3. Distributed System
4. Data Intefrity
5. DNS: Domain Name System (mapping of URL --> IPs)
