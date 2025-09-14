# EcoRoute Optimiser 🌱 (In Development)

A Java/Spring Boot API that calculates the **most fuel-efficient route** between two locations by factoring in
distance, live weather, and traffic conditions.

This project is being built to demonstrate skills in backend development, algorithm design, and cloud deployment.

---

## 🚀 Project Goals
- **Smart Routing**: Implement Dijkstra’s algorithm (or A*) to find the lowest-cost path across a network of roads.
- **Dynamic Weights**: Adjust route cost based on:
  - Real-time weather data (OpenWeatherMap API)
  - Traffic density (mock data or free traffic API)
- **Cloud Ready**: Deploy to AWS Elastic Beanstalk for public access.

---

## 🛠️ Tech Stack
| Layer | Technology |
|------|------------|
| Language | Java 17 |
| Framework | Spring Boot 3, Spring Data JPA |
| Database | PostgreSQL (or H2 for development) |
| External APIs | OpenWeatherMap (weather), optional traffic API |
| Deployment | AWS Elastic Beanstalk / Docker |
| Testing | JUnit 5, Mockito |

---

## 📂 Planned Structure
