# Deribit-management-system
# Deribit Order Execution and Management System (C++) – GoQuant Assignment

## 📌 Overview

This project implements a high-performance order execution and management system for the Deribit Testnet. The system is designed to interact with the Deribit exchange using both REST and WebSocket APIs, allowing real-time trading and data processing capabilities.

This solution is built in C++ with performance, modularity, and scalability in mind. The project includes:

- REST API integration for order management
- WebSocket server for market data streaming
- Multithreading for asynchronous handling
- Structured logging and error handling
- (Optional) Performance benchmarking and optimization documentation

---

## 🚀 Features

### ✅ Core Functionalities
- **Order Management**
  - Place Order
  - Cancel Order
  - Modify Order
  - Fetch Live Orderbook
  - View Current Positions

- **Market Coverage**
  - Supports **Spot**, **Futures**, and **Options**
  - Operates across **all symbols supported by Deribit Testnet**

- **WebSocket Server**
  - Handles client subscriptions per symbol
  - Streams real-time orderbook data
  - Efficient broadcasting and connection management

---

## 🛠️ Technologies Used

- **nlohmann/json** – JSON parsing and serialization

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/svscodes/deribit-management-system.git
cd deribit-management-system
