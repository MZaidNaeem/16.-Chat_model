# 16.Context-Aware Persistent Chat Model

!(Screenshot)[gitimg.png]

I built a Generative AI chatbot that not only replies to messages but also remembers the entire conversation history across sessions — thanks to SQL-based persistence and LangGraph state management.

At first, I struggled with keeping conversations consistent over time. Then I realized I could combine LangGraph workflows for state handling with LangChain's LLM integration — and persist that state in a database. Now, the bot understands context from past interactions and gives meaningful responses instead of starting fresh every time.

💡 Best Part of the Model:
Most chatbots lose memory when the session ends.
This model remembers what you said days ago — making conversations natural and continuous. Plus, it uses stemming to better understand variations of words and maintain intent recognition.

📌 How It Works:
✅ Accepts user input and preprocesses it (stemming, normalization)
✅ Manages context using LangGraph state
✅ Generates intelligent responses via LangChain LLM
✅ Saves conversation history in SQL database for persistence
✅ Reloads past chats so the bot never forgets your context

📈 Tech Stack:
LangGraph | LangChain | Python | SQL Database | NLP (Stemming) | Streamlit

🌐 Use Case Impact:
Perfect for virtual assistants, customer support bots, and knowledge management systems that require long-term context and persistent memory.
