# 🔒 Privacy-Aware AI Agent (LangGraph Workflow)

This project implements a **Privacy Filter + Moderation Filter + LLM Processor** pipeline following a **LangGraph-style workflow**.  
The system ensures that all user inputs are sanitized before being processed by an AI model.

---

## 🚀 Features

### ✅ **1. Privacy Filter**
Automatically detects and redacts:
- Email addresses → `[EMAIL]`
- Phone numbers → `[PHONE]`
- Credit card numbers → `[CARD]`
- Physical addresses → `[ADDRESS]`

### ✅ **2. Moderation Filter**
Removes and sanitizes:
- Profanity
- Slang
- Harmful content
- Toxic/abusive language

### ✅ **3. LLM Processing Node**
- Receives safe, filtered text  
- Performs intelligent response generation  
- Ensures final output is safe and compliant  



## 🛠️ Technologies Used
- Python 3.x  
- Regular Expressions (re)  
- Custom filtering logic  
- LangGraph-style design

##🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to change.
