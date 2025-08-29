# Data Transmission in LAN

We can transmit data in two ways: **WiFi** or **wired connection**.  
Here, we will discuss **how data moves through a wired network**.

---

## 1. From Network Layer to Data Link Layer

- When data comes from the **top network layer** into the **Data Link layer**, it is called a **frame**.  
- Each frame has a **header** and **footer** added.  
- The **header** includes the **MAC address** of the source and destination.

---

## 2. Physical Layer

- Now the frame is ready to go to the **Physical layer**.  
- In this layer, the frame is converted into **bits (0 and 1)** to move through the cable.  
- This layer uses some **protocols** to send data through the cable, such as **CSMA/CD**.  

### CSMA/CD (Carrier Sense Multiple Access / Collision Detection)

- Provides a **collision domain** in the network.  
- When two or more hosts try to send data at the same time, their data may **collide**.  
- The protocol first **checks the cable** for any signal.  
- If no signal is detected, data is sent.  
- It also **notifies all hosts** that someone is sending data, so they wait.

> ⚠️ **Note:** This behavior is mainly for **older hubs**.

---

This is a simplified view of how **data moves in a LAN** from higher layers down to the physical medium.
