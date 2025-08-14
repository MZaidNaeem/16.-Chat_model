# 16.Context-Aware, Memory-Boosted Chat Model

![Screenshot](gitimg.png)

I built a chatbot that doesn’t just respond — it remembers.
This model stores the entire conversation history across sessions, so every interaction feels like a true continuation rather than a reset.

By combining the workflow control of LangGraph with the intelligence of LangChain, enhancing text understanding through stemming, and preserving context in an SQL database, I’ve created a conversational AI that feels significantly more natural and reliable.

🚀 What Makes It Stand Out:
Most chatbots start fresh each time you talk to them.
This one remembers your past messages — whether from minutes ago or weeks ago — and uses that memory to give relevant, consistent replies.

📌 How It Works:

🔍 Preprocesses text with stemming for better language understanding

🗂 Manages state with LangGraph for smooth conversation flow

🧠 Uses LangChain’s LLM for intelligent and context-aware responses

💾 Stores all conversations in an SQL database for persistent memory

🔄 Delivers replies that take previous interactions into account

🛠 Tech Stack:
LangGraph | LangChain | Python | SQL Database | NLP (Stemming) | Streamlit

🌍 Why This Matters:
Perfect for virtual assistants, customer support systems, and knowledge bots — anywhere that context and memory create a more human-like and trustworthy experience.
