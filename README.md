# erpsoftwarearchitecture

# 🍦 Heladería de la Biodiversidad - ERP System

## Software Architecture Project
**Universidad Manuela Beltrán - Facultad de Ingeniería**

### Team Members
- Daniel Felipe Rojas González
- Isaac Núñez Melo
- Nicolás Rodríguez Betancourt
- Cristian David Cotrino

**Instructor:** Carlos Eduardo Mujíca Reyes  
**Date:** February 2026

---

## 📋 Table of Contents
1. [Project Definition](#project-definition)
2. [Problem Statement](#problem-statement)
3. [Proposed Solution](#proposed-solution)
4. [Justification](#justification)
5. [End Users](#end-users)
6. [Comparative Analysis](#comparative-analysis)
7. [Functional Requirements](#functional-requirements)
8. [Non-Functional Requirements](#non-functional-requirements)
9. [Project Scope](#project-scope)
10. [Selected Technologies](#selected-technologies)
11. [Architecture Diagrams](#architecture-diagrams)

---

## 🎯 Project Definition

### Problem Statement
The ice cream shop faces issues related to long queues and high waiting times during customer service, which negatively affects the service experience. Additionally, manual management of orders, inventory, and suppliers hinders operational and administrative control of the business, generating possible errors and low efficiency in internal processes.

### Proposed Solution
The proposed solution consists of developing a web-based system integrated with a POS-type ERP that automates the ordering process and administrative management of the ice cream shop.

**Key Features:**
- Customers can consult the menu and register their orders online
- Automatic turn assignment and estimated waiting time
- Real-time order reception for staff preparation
- Centralized business operations including sales, inventory, suppliers, and financial reports

**Expected Product:**  
A digital platform designed to optimize customer service and centralize business operations, including sales, inventory, suppliers, and financial reports.

### Justification
This project is valuable because it:
- ✅ Improves customer experience by reducing wait times and physical queues
- ✅ Optimizes internal processes of the establishment
- ✅ Strengthens traceability and control of raw materials from biodiversity-rich communities in Colombia
- ✅ Promotes fair trade and sustainability
- ✅ Contributes to business efficiency and positive social and environmental impact

**Biodiversity Focus:**  
The ice cream shop works with raw materials from indigenous and peasant communities from biodiverse regions of Colombia:
- 🌳 Amazon
- 🌊 Chocó
- 🏖️ Caribbean
- 🌾 Eastern Plains (Llanos Orientales)
- ⛰️ Sierra Nevada de Santa Marta

---

## 👥 End Users

The system is designed for:

1. **Ice Cream Shop Customers**
   - Use the web platform to place orders
   - Consult waiting times
   - View menu with descriptions and prices

2. **Operational Staff**
   - Receive and prepare orders in real-time
   - Manage POS operations

3. **Administrator/Business Owner**
   - Control sales, inventory, suppliers
   - Access financial reports
   - Make data-driven decisions

---

## 📊 Comparative Analysis

| Aspect | Without ERP | With Integrated POS ERP | Analysis |
|--------|-------------|------------------------|----------|
| **Order Management** | Manual orders at counter, human errors, long physical queues | Orders placed from web, automatic turn assignment | Reduces errors, improves customer experience |
| **Wait Time** | Disorganization during peak hours | Automatic time calculation based on order load | Solves the central problem: long queues |
| **Inventory Control** | Manual control, risk of stockouts | Automatic inventory updates, low stock alerts | Improves efficiency, prevents economic losses |
| **Supplier Management** | Dispersed information | Structured registry by region and products | Essential for biodiversity-focused business |
| **Decision Making** | Based on estimates | Automatic reports on sales and profitability | Enables strategic data-driven decisions |
| **Customer Experience** | Physical queue waiting | Digital turn, menu consultation, estimated times | Increases satisfaction and loyalty |
| **Scalability** | Difficult expansion | Replicable system for new locations | Allows business growth |

### Existing ERP Comparison

| Application | Cost | Suppliers Module | HR Module | Inventory | Billing/Sales | CRM/Customers |
|-------------|------|------------------|-----------|-----------|---------------|---------------|
| **Odoo** | Free (15 days) + $20/$30/$50 | ✅ Yes | ✅ Yes | ✅ Real-time stock | ✅ Yes | ✅ Yes |
| **Siigo** | Free (limited) + $10-$92 | ✅ Yes | ❌ No | ✅ Yes | ✅ Electronic invoice | ✅ Yes |
| **Alegra** | Free trial (15 days) + $5-$50 | ✅ Yes | ❌ No | ✅ Basic | ✅ Electronic invoice | ✅ Yes |

---

## ⚙️ Functional Requirements

### Order Management Module
- Online menu consultation
- Product selection and customization
- Turn assignment system
- Estimated waiting time calculation
- Order status tracking

### Inventory Module
- Real-time stock control
- Automatic updates on each sale
- Low stock alerts
- Product categorization

### Supplier Module
- Registry of supplier communities by region
- Product sourcing traceability
- Purchase order management

### Sales and Billing Module
- Automatic invoice generation
- Sales record by product
- Payment processing

### Reports and Analytics
- Best-selling products
- Sales by period
- Profitability analysis
- Inventory status

---

## 🔒 Non-Functional Requirements

### HIGH PRIORITY

#### 1. Performance
- Response time: **< 2 seconds** for common operations
- Concurrent users: Minimum **50 users** without service degradation
- Turn assignment: **< 1 second**
- Real-time estimated time updates

#### 2. Availability
- Uptime: **99%** during business hours
- Maximum recovery time: **30 minutes**
- Offline mode for basic POS operations
- Automatic backup every 24 hours

#### 3. Usability
- Intuitive interface
- Maximum **3 clicks** to place an order
- Responsive design (mobile, tablet, desktop)
- Employee training: Maximum **2 hours**
- WCAG 2.1 Level AA accessibility compliance

#### 4. Visual Identity
- **Name:** "Heladería de la Biodiversidad"
- Design reflects connection with indigenous communities
- Evokes nature, freshness, and sustainability
- Conveys artisanal quality and fair trade

### MEDIUM PRIORITY

#### 5. Security
- Secure password policies
- Role-based access control (RBAC)
- Encryption of sensitive data
- Audit logging of all critical operations
- Compliance with Law 1581 of 2012 (Colombia personal data protection)

#### 6. Scalability
- Horizontal growth capability
- Modular architecture
- Multi-location support
- Scalable database design

#### 7. Maintainability
- Clean code following best practices
- Complete technical documentation
- Modular architecture
- Version control with Git

### LOW PRIORITY

#### 8. Compatibility
- Browser support: Chrome, Firefox, Safari, Edge
- OS compatibility: Windows, macOS, Linux, Android, iOS
- Standard web technologies: HTML5, CSS3, JavaScript

#### 9. Resource Efficiency
- Optimized database queries with proper indexes
- Caching for repeated queries
- Image compression
- Cost-effective hosting capability

---

## 🎯 Project Scope

### Included in Prototype
✅ Online ordering system with turn management  
✅ Inventory management  
✅ Supplier management  
✅ Sales tracking  
✅ Basic administrative reports

### Not Included in Initial Version
❌ Electronic invoicing (future phase)  
❌ Mobile application (future phase)  
❌ Advanced analytics dashboard (future phase)

### Triple Constraint Consideration

**Scope:** Prototype with core functionalities (orders, inventory, suppliers, sales)

**Time:** Development aligned with course timeline, focusing on high-priority features first

**Cost:** 
- Open-source tools and frameworks
- No ERP licenses required (prototype/simulation)
- No physical infrastructure needed

---

## 💻 Selected Technologies

### Development Environment
- **Code Editor:** Visual Studio Code
- **Version Control:** GitHub (repository and documentation)

### Frontend
- **Languages:** C#, JavaScript
- **Responsive Design:** HTML5, CSS3

### Backend
- **Framework:** .NET (C#)
- **API:** RESTful services

### Database
- **Platform:** Azure
- **Purpose:** Store inventory, sales, suppliers, and customer data

### Hosting & Deployment
- Cloud-based deployment
- Scalable infrastructure

---

## 📐 Architecture Diagrams

### Class Diagram
[Include your class diagram image here]

### Object Diagram
[Include your object diagram image here]

### Component Diagram
[Include your component diagram image here]

### Deployment Diagram
[Include your deployment diagram image here]

### Package Diagram
[Include your package diagram image here]

### Composite Structure Diagram
[Include your composite structure diagram image here]

---

## 💰 Return on Investment (ROI)

The investment can be recovered through:

1. **Increased Sales:** Optimized service time allows serving more customers
2. **Reduced Losses:** Inventory automation reduces errors and waste
3. **Cost Reduction:** Automated administrative processes lower operational costs
4. **Better Decision Making:** Data-driven insights improve resource efficiency
5. **Customer Loyalty:** Improved experience increases repeat business

---

## 🤔 Guiding Questions

### What is the role of a Software Architect?

A software architect designs the structure of a software system and defines how it is organized. Their key responsibilities include:

- Making critical decisions about tools and technologies
- Ensuring good software performance
- Creating development plans for easier and clearer system development
- Producing documentation
- Guiding the development team

---

## 📚 Software Architecture Models

This project follows the **4+1 Architectural View Model** by Philippe Kruchten:

1. **Logical View:** Shows components (objects) and their interactions
2. **Process View:** Shows processes/workflow and how they communicate
3. **Development View:** Building block views and static organization
4. **Physical View:** Installation, configuration, and deployment
5. **Scenarios (+1):** Use case view validating the complete design

---

## 🌱 Sustainability & Social Impact

This project promotes:
- 🌍 **Fair Trade:** Direct relationships with indigenous and peasant communities
- 🌿 **Biodiversity:** Highlighting Colombia's biodiverse regions
- ♻️ **Traceability:** Complete supply chain transparency
- 💚 **Sustainability:** Supporting local economies and traditional practices

---

## 📄 License

This project is developed for academic purposes as part of the Software Architecture course at Universidad Manuela Beltrán.

---

## 📞 Contact

For more information about this project, please contact the development team through the university.

---

**Last Updated:** February 2026
