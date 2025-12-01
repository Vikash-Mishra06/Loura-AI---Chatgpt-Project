# Loura-AI 💬  
**A Full Stack ChatGPT-style AI Chat Application**  

## 🚀 What is Loura-AI  
Loura-AI is a full-stack web application enabling real-time chat powered by AI, with support for RAG (Retrieval-Augmented Generation), embeddings + vector search, and persistent chat history. Built with a modern MERN + AI stack, it’s designed to provide a smooth, scalable, and intelligent conversational experience.

---

## ✨ Key Features  
- Real-time chat interface using WebSockets (or equivalent real-time mechanism)  
- AI-powered responses leveraging embeddings + vector database + RAG pipelines  
- Persistent chat history (so users can revisit old conversations)  
- Clean and responsive UI (works on desktop and mobile)  
- Modular backend + frontend architecture for easy extensibility  

---

## 🛠 Technology Stack  

**Frontend:**  
- React / Next.js  
- Tailwind CSS (or your chosen styling)  
- WebSocket / real-time frontend logic  

**Backend:**  
- Node.js + Express.js  
- MongoDB (or your chosen DB) + Mongoose / ORM  
- AI & Vector Search / Embeddings integration (e.g. OpenAI / similar + vector store)  
- REST API / WebSocket endpoints  

**DevOps / Tools:**  
- Docker (optional)  
- Environment variables for API keys / secrets  
- Git / GitHub for version control  

---

## 🧑‍💻 Getting Started  

### Prerequisites  
- Node.js (14.x or above)  
- npm or yarn  
- MongoDB (local or remote)  
- AI / LLM API key (if needed)  
- (Optional) Docker — if using Docker setup

---

## 💡 Usage

- Open the frontend in browser.
- Start a new chat or continue previous conversation.
- Send messages — backend processes with AI + vector search / embeddings, returns response.
- Chat history persists — you can reload or revisit previous chats.

---

## 🔭 Future Improvements / Roadmap

- User authentication / login system (optional)
- Multi-user support / chat rooms / group chats
- File / media sharing support
- Dark / light theme toggle
- Better prompt handling / rate limiting / caching responses
- Deployment-ready Docker / CI-CD setup

---

## 🤝 Contributing

- Contributions are welcome!
If you’d like to contribute:
- Fork this repository
- Create a new branch — feature/your-feature-name
- Implement your addition / fix
- Submit a Pull Request
- Please ensure code quality, add tests (if applicable), and keep same coding style.

---

### Installation / Setup  

```bash
# Clone the repo
git clone https://github.com/Vikash-Mishra06/Loura-AI---Chatgpt-Project.git

# Go into project folder
cd Loura-AI---Chatgpt-Project

# Install dependencies (frontend + backend)
npm install
# or
yarn install

MONGODB_URI=your_mongo_connection_string
AI_API_KEY=your_ai_api_key
JWT_SECRET=your_secret   # if using authentication
PORT=5000                 # or your preferred port


# Start backend server
npm run server
# or (if combined)
npm run dev

# Start frontend (if separate)
npm run client
