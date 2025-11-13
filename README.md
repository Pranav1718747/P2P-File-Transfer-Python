# P2P File Transfer System

**Authors:**  
- SHINDE PRANAV - 24BAI1590  
- R HARISH - 24BYB1159  

**Course:** BCSE303L – Operating Systems  
**B.Tech, Computer Science & Engineering**  

---

## **Project Overview**
This project implements a **Peer-to-Peer (P2P) File Transfer System** using Python, Tkinter, and Socket Programming.  
It allows systems in a local network to share files directly without a centralized server. Features include:

- Multi-threaded file sending and receiving  
- Automatic peer discovery (UDP broadcast)  
- Secure file transfer using AES encryption  
- Progress visualization and pause/resume control  
- GUI interface built with Tkinter  

---

## **System Design**
- **Sender:** Selects file, encrypts, and sends to peers  
- **Receiver:** Accepts incoming files, displays progress  
- **Peer Discovery:** Finds peers on LAN automatically  
- **Logger:** Logs all runtime events  
- **Security Verification:** RSA-based software license verification  

---

## **Screenshots**
![Select File](screenshots/select_file.png)  
![Peer Discovery](screenshots/peer_discovery.png)  
![Send Window](screenshots/send_window.png)  
![Receive Prompt](screenshots/receive_prompt.png)  

---

## **Installation**
1. Clone the repository:  
   ```bash
   git clone https://github.com/Pranav1718747/P2P-File-Transfer-Python.git


