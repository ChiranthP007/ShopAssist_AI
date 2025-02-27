# **ShopAssist AI – Laptop Recommendation Chatbot**  

## **📌 Overview**  
**ShopAssist AI** is an intelligent **laptop recommendation chatbot** that interacts with users, understands their requirements, and suggests the most suitable laptops based on their needs and preferences. It leverages **LLMs (Large Language Models) and rule-based functions** to enhance the online shopping experience by providing personalized and reliable laptop recommendations.  

---

## **🛠️ Technologies Used**  
👉 **Backend:** Flask, OpenAI API  
👉 **Database:** External dataset containing laptop specifications  
👉 **NLP & AI:** OpenAI Chat Model for conversation and recommendation  
👉 **Function Calling APIs:** For enhancing user experience and automating tasks  
👉 **Web Deployment:** Flask-based server application  

---

## **🔹 Problem Statement**  
Online shopping offers **thousands of laptop choices**, making it **overwhelming for users** to find the right one. This chatbot solves this problem by:  
- **Understanding user preferences** through interactive conversations.  
- **Matching user needs** with a structured **laptop dataset**.  
- **Providing personalized laptop recommendations** in a simple, user-friendly way.  

---

## **⚙️ System Architecture**  
ShopAssist AI follows a **three-stage process**:  

### **1️⃣ Understanding User Requirements**  
- Engages the user in a conversation to gather **detailed laptop preferences**.  
- Ensures that **all required specifications** (budget, performance, brand, etc.) are collected.  

### **2️⃣ Product Mapping & Extraction**  
- Extracts **laptop data from the database**.  
- Filters and compares **only the most relevant products** based on user input.  
- Selects the **top 3 best-matching laptops** for recommendation.  

### **3️⃣ Product Recommendation**  
- Presents the **best laptop options** with detailed descriptions.  
- Simulates a **sales representative experience** by explaining features based on the user's needs.  

---

## **🛠️ Implementation Details**  

### **👤 Key Functionalities**  
| Function | Description |  
|-----------|------------|  
| `initialize_conversation()` | Starts the chat with a system message. |  
| `get_chat_completions()` | Uses OpenAI’s API to generate chatbot responses. |  
| `moderation_check()` | Ensures that conversation remains appropriate. |  
| `intent_confirmation_layer()` | Verifies if the chatbot fully understands the user’s requirements. |  
| `dictionary_present()` | Converts user input into structured **JSON format** for processing. |  
| `compare_laptops_with_user()` | Matches user preferences with laptop specifications and selects the **top 3 recommendations**. |  
| `initialize_conv_reco()` | Begins the recommendation process based on matched results. |  

---

## **🚀 Function Calling APIs**  
This chatbot integrates **function calling APIs** to enhance user interaction and streamline backend operations.  

### **✅ Benefits of API Integration:**  
- **Faster and more accurate laptop recommendations.**  
- **Automated conversation flow** for seamless user interaction.  
- **Improved support and real-time responses.**  

---

## **📌 Installation & Setup**  

### **🔹 Clone the Repository**  
```bash
git clone https://github.com/YourUsername/ShopAssist_AI.git
cd ShopAssist_AI
```

### **🔹 Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **🔹 Run the Flask Application**  
```bash
python app.py
```

### **🔹 Access the Web Interface**  
- Open a browser and go to **http://127.0.0.1:5000/**  

---

## **📈 Future Enhancements**  
💡 Expand to **other product categories** beyond laptops.  
💡 Improve **AI-based NLP understanding** for better conversations.  
💡 Deploy on **cloud platforms** for broader accessibility.  

---

## **💌 Contact & Contribution**  
📧 Email: Chiranth0799@gmail.com  
👉 LinkedIn: https://www.linkedin.com/in/chiranthp/  
💪 Contributions are welcome! Fork the repo!  
