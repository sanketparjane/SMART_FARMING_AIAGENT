# 🌾 AI Agent for Smart Farming Advice

**Sanjivani University** | **School of Engineering & Technology**  
**Department of Artificial Intelligence & Machine Learning** | Semester-V, Academic Year 2025–2026  



---

## 👥 Project Team
- **Gayatri Jagtap** (2124UMLF2061)
- **Sanket Parjane** (2124UMLM2044)
- **Soham Wadale** (2124UMLM2081)
- **Sakshi Abak** (2124UMLF2019)

**Guided By:** Prof. Raz Sir

---

## ⚠️ Problem Statement
Small-scale farmers play a vital role in the agricultural sector, yet they face several challenges that affect their productivity and income.

One of the major issues is the lack of access to real-time and reliable information regarding weather conditions, soil health, crop suitability, pest control, and market prices.

Due to limited digital literacy and infrastructure, farmers often rely on outdated or inaccurate advice, leading to poor decision-making.

Additionally, most agricultural information available online is in English, creating a language barrier for farmers who primarily communicate in local languages.

The absence of personalized and data-driven guidance makes it difficult for farmers to plan effectively, resulting in reduced crop yields, financial losses, and increased risks.

Therefore, there is a strong need for an intelligent system that can provide localized, accurate, and easy-to-understand agricultural advice to empower small-scale farmers and support sustainable farming practices.

---

## 💡 Proposed Solution
The proposed system introduces an **AI Agent for Smart Farming Advice** powered by **Retrieval-Augmented Generation (RAG)**.

This intelligent agent retrieves and generates real-time, localized agricultural information to support farmers in decision-making.

It accesses trusted data sources such as meteorological departments, soil condition databases, and agricultural market platforms.

Farmers can interact with the system in their local language and ask questions such as:
- “Which crop should I grow this season?”
- “What is today’s market rate for tomatoes?”

The system combines retrieved factual data with the generative capabilities of AI to provide accurate, context-specific, and easy-to-understand responses.

By doing so, it bridges the knowledge gap and empowers small-scale farmers to improve crop yield and income.

---

## ⚙️ System Requirements

### Hardware Requirements
- Minimum 4 GB RAM and a dual-core CPU
- IBM Cloud account with provisioned cloud runtime
- Secure internet connection for real-time data streaming

### Software Requirements
- Operating System: Windows
- Python
- Cloud Platform: IBM Cloud (Watson Studio, Cloud Functions)
- Model Serving: Flask/FastAPI for REST API deployment

---

## 🧠 Algorithm & Deployment
The RAG model forms the foundation of the system and operates in two major stages: **Retrieval** and **Generation**.

### 1. Retrieval Stage
The system searches documents or database repositories to find the most relevant information related to the farmer’s query.

### 2. Generation Stage
The AI model (**IBM Granite**) synthesizes the retrieved information to generate meaningful and accurate responses.

The algorithm ensures factual accuracy and contextual understanding.

For deployment, the system utilizes **IBM Cloud Lite Services**, where the backend RAG model, API endpoints, and user interface are hosted.

This setup allows real-time data access and scalable deployment for multiple users across different regions.

---

## 📊 Results
The system provides a simple and user-friendly chat interface where farmers can type or speak their questions in their local language.

The AI agent responds with accurate and context-based answers retrieved from verified agricultural data sources.

For example:
- When a user asks, *“Which crop should I grow this season in Maharashtra?”*, the system suggests the most suitable crops based on weather conditions, soil type, and market trends.
- When asked, *“What is today’s mandi rate for tomatoes?”*, the system provides real-time market price updates.

The results demonstrate that the system effectively delivers localized and reliable agricultural guidance in an accessible format.


## 🚀 Future Scope
- IoT-based sensor integration for real-time soil and crop monitoring
- Image recognition for pest and disease detection
- Multilingual voice assistant support
- Blockchain integration for crop supply-chain transparency
- Integration with government agricultural schemes and subsidy information
- Improved RAG models using domain-specific datasets for enhanced personalization and accuracy

---

## 📌 Conclusion
The **AI Agent for Smart Farming Advice** successfully addresses the challenges faced by small-scale farmers by providing accurate, real-time, and localized agricultural insights.

By leveraging **Retrieval-Augmented Generation (RAG)** and IBM’s cloud-based AI services, the system bridges the information gap between farmers and expert agricultural knowledge.

It improves decision-making related to crop selection, pest management, and market selling, ultimately enhancing productivity and profitability.

This project demonstrates how AI can play a transformative role in sustainable and smart agriculture at the grassroots level.

---

## 📚 References
- IBM Cloud Lite Documentation – https://cloud.ibm.com/docs
- IBM Granite Models – https://www.ibm.com/granite
- Indian Meteorological Department (IMD) – https://mausam.imd.gov.in
- National Agriculture Market (eNAM) – https://www.enam.gov.in
- Food and Agriculture Organization (FAO) Reports on Smart Farming – https://www.fao.org

---

## 🙏 Thank You
