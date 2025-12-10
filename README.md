# Casino Game – Java & JavaFX  
A modular casino application built in **Java** with a **JavaFX** frontend and a **client–server architecture**.  
The project is structured for clarity and scalability using separate packages for **database**, **networking**, **UI scenes**, and **utility classes**.  
Includes a comprehensive **Matrix test suite using JUnit** for validating core logic.

---

## Features

### Client–Server Architecture
- Dedicated **server application** that manages users, sessions, and game state.
- **Client application** built with JavaFX that communicates with the server via custom networking protocols.
- Real-time interaction between client and server for casino game operations.

### Casino Gameplay
- User balance tracking, betting logic, and game results handled through server logic.
- Clean separation of UI and game logic for maintainability.

### Modular Package Structure
/database - DB logic
/networking - Client–server communication handlers, protocols, packets
/scenes - JavaFX UI screens 
/util - Helper classes, configuration, reusable utilities
/tests - JUnit tests including Matrix testing

## 🛠️ Tech Stack

- **Java (JDK 17 or your version)**
- **JavaFX** (UI)
- **JUnit** (testing)
- **Client–Server architecture**
- **Custom networking layer** (TCP or specify protocol)
- **Modular package structure**

---

## Running the Project

### 1. Start the Server
java -jar server.jar

### 2. Start the Client
Run the JavaFX application from your IDE or packaged JAR.

Ensure the server is running before launching the client.

