# MongoDB-Learning-Notes

![MongoDB Logo](https://www.mongodb.com/assets/images/global/favicon.ico)

Welcome to the MongoDB-Learning-Notes repository! This repository serves as a comprehensive collection of my notes and materials for learning MongoDB. Whether you are a beginner looking to get started with MongoDB or someone who wants to deepen their knowledge, this repository will provide you with valuable insights and resources to master this powerful NoSQL database.

## Introduction to MongoDB

MongoDB is a popular and feature-rich NoSQL database that stores data in JSON-like BSON documents. It is known for its flexibility, scalability, and ease of use, making it a top choice for modern applications. MongoDB is widely used in various domains, including web development, mobile apps, IoT, and big data analytics.

### Key Features of MongoDB

- Schemaless: MongoDB does not require a predefined schema, allowing flexibility in data structure.
- High Scalability: MongoDB can handle large amounts of data and distribute it across multiple servers.
- Powerful Query Language: MongoDB supports a rich query language for retrieving and manipulating data.
- Indexing: Efficient indexing ensures fast query performance.
- Aggregation Framework: MongoDB provides powerful aggregation capabilities for data analysis.
- Geospatial Indexing: It includes support for location-based queries and geospatial data.
- Replication and Sharding: Ensures high availability and horizontal scaling.

## Installation

Below are the installation instructions for MongoDB on Windows, macOS, and Linux. Choose the appropriate section based on your operating system.

### Windows

1. **Download Installer**: Visit the official MongoDB website (https://www.mongodb.com/try/download/community) and download the latest stable version for Windows.
2. **Run Installer**: Locate the downloaded file and run the installer.
3. **Setup Wizard**: Follow the on-screen instructions of the setup wizard. You can choose the Complete setup type to include MongoDB Compass, a visual interface for MongoDB.

### macOS

1. **Homebrew (Recommended)**: Open the terminal and run the following command to install MongoDB using Homebrew.

   ```bash
   brew tap mongodb/brew
   brew install mongodb-community
   ```
2. MacPorts: If you prefer MacPorts, use the following commands to install MongoDB.
   
   ```bash
   sudo port install mongodb
   ```
### Linux
The installation process for MongoDB on Linux may vary depending on the distribution you are using. Here, we'll cover the general steps, but for specific distributions, refer to the official MongoDB documentation.
1. Import the MongoDB GPG Key:
   ```bash
   wget -qO - https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -
   ```
2. Add MongoDB Repository:
  for Ubuntu:
   ```bash
   echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu $(lsb_release -cs)/mongodb-org/4.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.4.list
   ```
for Debian:
   ```bash
   echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu $(lsb_release -cs)/mongodb-org/4.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.4.list
   ```
3. Install MongoDB:
   ```bash
   sudo apt-get update
   sudo apt-get install -y mongodb-org
   ```
