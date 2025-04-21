# Survey Management API (Dropwizard + Elasticsearch + Kibana + Swagger)

This is a Dropwizard-based REST API that accepts survey data, logs it, and stores it in Elasticsearch. Kibana is used for real-time visualization, and Swagger UI is bundled for interactive API documentation.

---

## 🛠 Technologies Used

- Java 17
- Dropwizard 4.0.3
- Elasticsearch 7.17.17
- Kibana 7.17.17
- Swagger (OpenAPI 3) - self-hosted UI
- Maven
- Docker & Docker Compose

---

## 📦 Features

- RESTful endpoint `/surveys` that accepts `SurveyData`
- Validates and logs incoming JSON to the console
- Stores each survey entry in Elasticsearch (`surveys` index)
- Visualizes average score per gender using Kibana
- Swagger UI hosted locally for API interaction

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Docker & Docker Compose installed

---

### ▶️ Run the Application

```bash
docker-compose up --build
