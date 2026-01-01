# 🌱 Ghars – Smart Agriculture Platform (Backend)

Ghars is a smart agriculture backend platform built using **Spring Boot**.  
The platform integrates real-world agriculture with AI-powered insights, virtual farming, and a full e-commerce system, and is **successfully deployed and running on AWS**.

---

## 🎯 Project Objectives

| Objective | Description |
|---------|-------------|
| Digitization | Digitize farm, field, and crop management |
| Productivity | Improve agricultural productivity using AI |
| Learning | Support learning-based agriculture |
| Virtual Farming | Enable virtual farming and simulation |
| Recommendations | Smart plant recommendations |
| E-Commerce | Integrated store with payment & delivery |
| Community | Events and farmer engagement |

---

## 🧱 System Architecture

| Layer | Responsibility |
|-----|----------------|
| Controller Layer | RESTful REST APIs |
| Service Layer | Business logic & integrations |
| Repository Layer | JPA / Hibernate database access |
| Model Layer | Entities |
| DTO Layer | Data Transfer Objects |
| External Services | AI, Payment, Email |

---

## 🛠️ Technologies Used

| Technology | Usage |
|----------|------|
| Java | Backend language |
| Spring Boot | Application framework |
| Spring Data JPA | ORM |
| Spring Security | Authentication & authorization |
| MySQL | Relational database |
| Lombok | Reduce boilerplate |
| REST APIs | Communication |
| OpenAI API | AI features |
| Moyasar | Payment gateway |
| SMTP / Gmail | Email notifications |
| AWS | Deployment & hosting |

---

## 👩‍💻 My Contributions (Backend – E-Commerce & Smart Logic)

### 🧩 Entities

| Entity | Description |
|------|-------------|
| Product | Agricultural products |
| Stock | Inventory management |
| Order | Customer orders |
| OrderItem | Order details |
| Invoice | Billing system |
| Delivery | Delivery handling |
| Payment | Payment processing |

---

### 🔗 REST Endpoints

| Category | Endpoints |
|--------|----------|
| Orders | createOrder, getMyOrders, checkOrderStatus |
| Payments | payOrder, refundOrder |
| Order Status | updateOrderStatus |
| Returns | requestReturn, confirmReturn |
| Order Items | addOrderItem |
| Delivery | createDelivery, updateDeliveryStatus, assignDriverToOrder |
| Invoices | createInvoice |
| Platform Analytics | getPlatformTotalProfit |
| Products | addProduct, changeProductPrice |
| Stock | addStockQuantity |
| Events | eventRegistration + email confirmation |

---

### 🌱 Smart Agriculture Features

| Feature | Description |
|-------|-------------|
| Seasonal Plants | Get suitable plants by season |
| Location Filtering | Filter plants by location |
| Smart Recommendation | Recommend best plant for user |
| Smart Irrigation | AI-based irrigation scheduling |

---

## 🤖 AI & Smart Features

| Feature | Description |
|-------|-------------|
| AI Learning | AI-powered agricultural learning |
| Plant Identification | Identify plants using images |
| Disease Detection | Detect plant diseases |
| Smart Suggestions | Intelligent plant recommendations |
| Seasonal Logic | Season-based recommendations |
| Location Logic | Location-based recommendations |

---

## 🌐 External Services Used

| Service | Purpose |
|-------|--------|
| PlantNet API | Plant identification |
| Moyasar Payment Gateway | Online payments |
| SMTP / Gmail | Email service |
| OpenAI API | AI intelligence |

---

## 🧪 Testing & Security

| Area | Details |
|-----|--------|
| API Testing | Postman |
| Security | Role-based access control |
| Authorization | Spring Security request matchers |

---

## 🚀 Deployment

| Platform | Status |
|--------|--------|
| AWS | Deployed & running |
