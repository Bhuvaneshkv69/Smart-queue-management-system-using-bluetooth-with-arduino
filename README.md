# Smart-queue-management-system-using-bluetooth-with-arduino


🚀 Queue Management System using Arduino with Bluetooth Notification

 📌 Overview

This project presents a **low-cost, standalone Queue Management System** built using **Arduino UNO** and **Bluetooth communication (HC-05)**. It eliminates the need for physical queues by automating token handling and notifying users in real time when their turn arrives.

The system is designed for environments like **banks, hospitals, colleges, and offices**, where efficient queue handling is essential.

---

⚙️ Features

* 🔢 **Automatic Token Generation** using push buttons
* 📶 **Bluetooth Notification (HC-05)** to alert users
* 📺 **LCD Display** showing current & next token
* 🔔 **Buzzer Alerts** for real-time notification
* 🔄 **FIFO Queue Logic** for fair processing
* 🌐 **No Internet Required** (works offline)
* 💡 **LDR Sensor Integration** for smart environment monitoring
* ⚡ **Low-cost & Scalable Design**

---

 🧠 How It Works

1. User presses button → token is generated
2. Arduino processes queue using FIFO logic
3. Current token displayed on LCD
4. When a turn arrives:

   * 🔔 Buzzer alerts
   * 📶 Bluetooth sends notification
5. Queue updates in real-time

---

🧩 Components Used

* Arduino UNO
* HC-05 Bluetooth Module
* 16x2 LCD Display
* Push Buttons
* Buzzer
* LDR Sensor
* Resistors, Breadboard, Power Supply

---

🏗️ System Architecture

```
Push Buttons → Arduino UNO → LCD Display
                         ↓
                    Bluetooth (HC-05)
                         ↓
                    User Mobile
                         ↓
                       Buzzer
```

---
 📊 Advantages

* 💰 Cost-effective solution
* 📡 No dependency on internet/cloud
* ⚡ Real-time queue updates
* 👥 Reduces overcrowding
* 🔧 Easy to implement and extend

---

📈 Future Improvements

* 📱 Mobile App Integration (Android/iOS)
* 📊 AI-based wait time prediction
* ☁️ Optional cloud/database integration
* 🔔 Multi-user notification system
* 📍 Smart queue optimization (like virtual queues)

---

📂 Project Structure

```
/Queue-Management-System
│── Arduino_Code/
│── Circuit_Diagram/
│── Documentation/
│── README.md
```

---

🛠️ Installation & Setup

1. Clone the repository

```
git clone https://github.com/your-username/queue-management-system.git
```

2. Open Arduino IDE
3. Upload code to Arduino UNO
4. Connect components as per circuit diagram
5. Pair HC-05 with mobile device
6. Run the system

---

📖 Use Cases

* 🏥 Hospitals
* 🏦 Banks
* 🏫 Colleges
* 🏢 Offices
* 🎟️ Ticket Counters

---

👨‍💻 Author

Bhuvanesh K V

---

📜 License

This project is open-source and available under the **MIT License**.

---

