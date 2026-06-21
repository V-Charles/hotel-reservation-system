# Hotel Reservation System

## Description

**Objective:** Provide a seamless interface for viewing hotel availability and finalizing bookings.

**Problem Solved:** Simulates a complete reservation workflow, bridging the gap between a responsive frontend and a functional data persistence layer for hospitality management.

**Project Context:** Front-end project focused on building a professional, responsive UI using Bootstrap, integrated with a local JSON Server to simulate backend data handling and API interactions.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

## Preview

<img width="1262" height="893" alt="Image" src="https://github.com/user-attachments/assets/a6924600-6360-477e-9166-837eb3082ec8" />

---

## About the Project

The Hotel Reservation System is a multi-page web application designed to practice responsive UI development and data management. It features a landing page for viewing hotel information and a dedicated reservation management area.

To simulate a real-world scenario without a complex backend architecture, the project utilizes JSON Server. This allows the application to perform Create and Read (CR) operations locally, storing guest reservation data in a `db.json` file. The interface is built entirely with Bootstrap, ensuring a mobile-friendly and professional layout across all devices.

---

## Features

- Responsive mobile-friendly booking interface built with Bootstrap
- Multi-page navigation flow (landing page and reservation list)
- API interaction simulation for Create and Read (CR) operations
- Submitting new guest reservations
- Local data persistence using `db.json` and JSON Server

---

## Deploy

The frontend of this project is hosted on GitHub Pages as a static site.

**Access the application:** [Live Project Link](https://v-charles.github.io/hotel-reservation-system/)

> **Important Note:** While you can browse the interface online, the **reservation and data listing features** require a running backend. To experience the functional flow (submitting and viewing reservations), please follow the **How to Run** instructions below to start the local JSON Server.

---

## How to Run

### Prerequisites

- A modern web browser
- Node.js installed on your machine
- JSON Server installed globally

---

### Clone the Repository

```bash
git clone github.com/v-charles/hotel-reservation-system.git
cd hotel-reservation-system

```

---

### Installation

```bash
# Install JSON Server globally to run the simulated database
npm install -g json-server

```

---

### Configuration and Execution

1. Start the simulated API by navigating to the root folder of the project.
2. Run the following command to watch the `db.json` file:

```bash
json-server --watch db.json

```

3. Launch the application by opening the `index.html` file directly in your browser.
4. **Note:** To view the simulated list of reservations, manually navigate to the `/reservas.html` page in your browser or use the application's navigation flow.

The simulated API will typically be available at:

```bash
http://localhost:3000

```

---

## Environment Variables

This project does not require environment variables. Database simulation is handled locally via the `db.json` file.

---

## API Endpoints

The application communicates with a local JSON Server to simulate a REST API based on the `db.json` file.

| HTTP Method | Route (Endpoint) | Description |
| --- | --- | --- |
| GET | `/reservas` | Returns the list of all stored hotel reservations |
| POST | `/reservas` | Submits and saves a new reservation to the local database |

---

## Author

Developed by [Vinicius Charles Macedo Dias](https://www.linkedin.com/in/vinicius-charles/)
