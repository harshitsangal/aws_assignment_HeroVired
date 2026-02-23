# AWS_Assignment_HeroVired
# Travel Memory

A scalable and highly available full-stack Travel Diary application designed to support horizontal expansion across both frontend and backend layers. This project leverages RESTful APIs with MongoDB for data storage and a React frontend for user interaction.

## 🧠 Overview

This application allows users to record and share travel experiences, including trip details, costs, places visited, and photos. The backend API is built with Node.js and Express, connected to a MongoDB Atlas cluster, and the frontend is developed using React. The architecture supports **horizontal scalability** and **high availability** through health checks and automatic traffic rerouting.

## ⚙️ Key Features

- **Horizontal Scalability** – Designed to scale both frontend and backend independently as load increases.
- **High Availability** – Uses health checks and automated traffic rerouting for uninterrupted service.
- **MongoDB Atlas Integration** – Centralized cloud database with secure connection.  
- **RESTful API** – CRUD operations for trip records.  
- **React Frontend** – Dynamic and responsive user interface.

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React.js |
| Backend | Node.js + Express |
| Database | MongoDB Atlas |
| Hosting | TBD (Supports Kubernetes/Docker for scalability) |
| Environment | `.env` configuration |

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/harshitsangal/aws_assignment_HeroVired.git
```
### Data Format

{
    "tripName": "Sunset Beaches of Goa",
    "startDateOfJourney": "10-02-2026",
    "endDateOfJourney": "16-02-2026",
    "nameOfHotels": "Sea Breeze Resort",
    "placesVisited": "Calangute, Baga, Anjuna, Palolem",
    "totalCost": 45000,
    "tripType": "leisure",
    "experience": "relaxing and fun beach holiday with amazing seafood",
    "image": "https://www.bing.com/images/search?q=goa+beaches",
    "shortDescription": "A perfect getaway to enjoy sun, sand, and sea at the beautiful beaches of Goa.",
    "featured": false
}

### Screenshots

<img width="940" height="563" alt="image" src="https://github.com/user-attachments/assets/7b66fd35-07a6-4a13-87f4-c46c222fe722" />

<img width="940" height="561" alt="image" src="https://github.com/user-attachments/assets/0475a4e6-3cc8-4555-bcaf-2a91594e3a64" />

<img width="940" height="556" alt="image" src="https://github.com/user-attachments/assets/e19fce84-46a9-4f93-b0fa-4d05e0ff4219" />

<img width="940" height="560" alt="image" src="https://github.com/user-attachments/assets/3044e103-b97c-4436-841f-8485debe3da8" />

<img width="940" height="557" alt="image" src="https://github.com/user-attachments/assets/bc8de031-0ad5-4880-8546-5d541f2a5778" />

<img width="940" height="560" alt="image" src="https://github.com/user-attachments/assets/7cb2b331-f2f7-47f0-8647-d912a572fb66" />

<img width="940" height="560" alt="image" src="https://github.com/user-attachments/assets/188e2b3e-1c05-4d1f-b6da-f0b594abda43" />

<img width="940" height="560" alt="image" src="https://github.com/user-attachments/assets/cee0dc12-79f5-4a0a-b283-e4c903c99a83" />

<img width="940" height="561" alt="image" src="https://github.com/user-attachments/assets/98c4dd9e-1b29-400f-a7e1-2a44fd4cf127" />








