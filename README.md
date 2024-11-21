# Lost and Found System

Welcome to the **Lost and Found System** repository! This system allows users to report lost or found items using a simple Java Swing GUI. The application stores data in a **MongoDB** database and allows users to search for lost items, report lost or found items, and interact with others through a user-friendly interface.

## Features

- **Report Lost Items**: Users can log lost items, providing detailed descriptions, location, and the time the item was lost.
- **Report Found Items**: Users can report found items and provide details for others to claim them.
- **Search for Lost Items**: Users can search for lost items based on keywords, item category, or location.
- **MongoDB Integration**: The system stores all data, including item reports and user information, in MongoDB.
- **Java Swing GUI**: The frontend is built using Java Swing, making it a desktop application.

## Technologies Used

- **Java Swing**: For the graphical user interface (GUI).
- **MongoDB**: For storing the lost and found item data.
- **Java Driver for MongoDB**: To connect and interact with MongoDB from Java.
- **Maven**: For dependency management (you can also use Gradle or another build tool).

## Installation

### Prerequisites

Before getting started, ensure you have the following installed:

- **Java Development Kit (JDK)** (version 8 or above)
- **MongoDB** (you can use a local MongoDB instance or a cloud database)
- **Maven** (optional, but useful for managing dependencies)

### Steps to Set Up Locally

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/lost-and-found.git
   cd lost-and-found
