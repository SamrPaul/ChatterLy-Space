---

# 💬 ChatterLy Space

A Java-based client–server chat application enabling real-time communication between two users.

---

## 🚀 Project Overview

**Chatterly Spacet** is a simple yet powerful desktop chat application built entirely in Java. It demonstrates core concepts of **socket programming** , and **peer-peer architecture**.
The application allows two clients to connect to a central server and exchange text messages instantly in real time. The interface is built using **Java Swing** and **AWT**, designed to be intuitive and responsive.

---

## ⚙️ Features

* 🖥️ **Client–Server Communication** using Java Sockets
* 💬 **Real-Time Messaging** between connected clients
* 🧑‍💻 **User Interface** built using Java Swing
* 🧵 **Multithreading: Each client connection runs on a separate thread for concurrent communication.**
* 🚫 **Basic Validation & Connection Handling**
* ⚡ **Lightweight and Platform Independent**

---

## 🧰 Technologies Used

* **Language:** Java
* **Concepts:** Socket Programming, Streams and Javax , basic UI development
* **UI Toolkit:** Java Swing / AWT.

---

## 📂 Project Structure

```
/Chatting Application
│── Client.java        # Client-side logic and UI
│── Server.java        # Server handling multiple clients
│── README.md          # Project documentation
```

---

## 🛠 How to Run the Project

1. **Clone this repository**

   ```bash
   git clone https://github.com/SamrPaul/chatterLy-Space.git
   cd "Chatting Application"
   ```
2. **Compile the Java files**

   ```bash
   javac Server.java Client.java
   ```
3. **Start the Server**

   ```bash
   java Server
   ```
4. **Run one or more Clients** (in separate terminals or systems)

   ```bash
   java Client
   ```


---

## 🧩 Key Concepts Demonstrated

* **Socket Programming:** Establishes TCP connections between clients and the server.
* **I/O Streams:** Uses InputStream and OutputStream for message transmission.
* **Event Handling:** Java Swing components handle user input and message display.
* **Multithreading:** Each client connection runs on a separate thread for concurrent communication.

---

## 💡 Future Enhancements

* Add database integration for chat history and user accounts
* Implement file/image sharing
* Enhance UI with JavaFX or a modern framework
* Add encryption for message security
* Deploy server on cloud for remote communication

---

## 🧑‍💻 Author

Developed by **Samriddhi Paul**
*For educational and demonstration purposes.*

---
