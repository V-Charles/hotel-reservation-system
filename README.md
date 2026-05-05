<img width="1200" height="419" alt="Image" src="https://github.com/user-attachments/assets/2f743b46-8904-41a0-b2ce-1853bb8da97d" />

---

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

### 💡 The "Why"
Hospitality management requires a seamless transition between viewing availability and finalizing bookings. This project was designed to practice building a professional, responsive UI using Bootstrap while integrating a local data persistence layer to simulate reservation workflows and data handling.

---

### 🌐 Live Demo
The frontend of this application is live and can be accessed here:  
🔗 **[Live Project Link](https://v-charles.github.io/hotel-reservation-system/)**

⚠️ **Important Note:** GitHub Pages is a static hosting service. While you can browse the interface online, the **reservation and data listing features** require a running backend. To experience the functional flow (submitting and viewing reservations), please follow the **How to Run** instructions below to start the local JSON Server.

---

### 📷 Visual Proof
<img width="1262" height="893" alt="Image" src="https://github.com/user-attachments/assets/a6924600-6360-477e-9166-837eb3082ec8" />

---

### 🛠 Key Features
* **Responsive Booking Interface:** A mobile-friendly dashboard for managing hotel stays, built with the Bootstrap framework.
* **API Interaction Simulation:** Implementation of Create and Read (CR) operations, allowing users to submit new reservations and list them.
* **Navigation Flow:** Multi-page experience including a landing page and a dedicated reservation list area.
* **Local Data Persistence:** Uses `db.json` and JSON Server to store and retrieve guest reservation data locally.

---

### 📂 Project Structure
<pre>
hotel-reservation-system/
├── bootstrap/
│   ├── css/           # Framework styles
│   └── js/            # Framework components
├── icones/            # UI icons
├── imagens/           # Project assets and gallery
├── db.json            # Simulated database for JSON Server
├── index.html         # Landing page
└── reservas.html      # Reservation management page
</pre>

---

### 🚀 How to Run
**Prerequisites:**
* A web browser.
* Node.js installed on your machine.
* **JSON Server** installed globally (run `npm install -g json-server`).

**Steps:**
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/v-charles/hotel-reservation-system.git](https://github.com/v-charles/hotel-reservation-system.git)
2. **Start the simulated API:**
   Navigate to the project folder and run:
   ```bash
   json-server --watch db.json
3. **Launch the application:**
   Open `index.html` in your browser. The frontend will now be able to communicate with your local `db.json` server.
   * **Note:** To view the simulated list of reservations, manually navigate to the `/reservas` path in your browser.

---

Developed by [Vinicius Charles Macedo Dias](https://www.linkedin.com/in/vinicius-charles/)
