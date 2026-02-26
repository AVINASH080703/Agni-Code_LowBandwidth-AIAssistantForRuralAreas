# TEAM=Agni-Code_LowBandwidth-AIAssistantForRuralAreas
Bharat-Lite is an offline-first, low-bandwidth AI assistant designed specifically for rural communities with limited internet connectivity.


# 🌾 Bharat-Lite – Low Bandwidth AI Assistant for Rural Areas

## 🚀 InnVedX Code Hackathon Submission  
**Track:** AI, Data & Smart Systems  
**Team Lead:** Avinash Kumar Sharma  
**Team Members:** Subodh Yadav, Abhishek Pratap Singh, Gaurav Singh  

---

# 📌 Problem Statement

Rural areas in India face significant digital accessibility challenges:

1. Poor and unstable internet connectivity.
2. High data consumption of modern AI assistants.
3. Limited access to critical information such as:
   - Government schemes
   - Healthcare services
   - Financial assistance
   - Employment programs
4. Existing AI systems do not support offline functionality.

There is a need for a lightweight, intelligent assistant specifically designed for low-bandwidth rural environments.

---

# 💡 Proposed Solution – Bharat Lite

**Bharat Lite** is a hybrid AI assistant designed for rural India that:

- Works in both **Offline and Online modes**
- Uses a **local searchable database** when internet is unavailable
- Allows users to manually toggle between Offline and Online AI mode
- Minimizes data usage through optimized responses
- Maintains chat history like ChatGPT
- Supports voice input for accessibility
- Uses a clean, farmer-friendly green UI for trust and usability

---

# 🏗️ System Architecture

### 1️⃣ Offline Mode
- Uses SQLite-based KnowledgeBase table
- Performs keyword-based local search
- No internet required
- Fully functional in low connectivity areas

### 2️⃣ Online Mode
- Ready for OpenAI API integration
- User-controlled toggle switch
- Intelligent AI responses
- Designed for future multilingual enhancement

### 3️⃣ Database Structure

- **Conversation Table**
  - Stores individual chat sessions

- **Message Table**
  - Stores questions and answers per conversation

- **KnowledgeBase Table**
  - Stores locally searchable rural information

---

# 🔑 Key Features

✔ Multi-conversation support (ChatGPT-style)  
✔ Sidebar conversation switching  
✔ Voice input (Hindi + English ready)  
✔ Online/Offline toggle button  
✔ Local searchable knowledge database  
✔ Persistent chat storage using SQLite  
✔ Responsive design (mobile friendly)  
✔ Lightweight and low bandwidth optimized  



