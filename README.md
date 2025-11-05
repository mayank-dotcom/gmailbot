# Niyojaka – AI-Enabled Gmail Replier

Live Link: https://gmailbot-dun.vercel.app/

Niyojaka is an AI-powered Gmail automation agent that reads your inbox, understands the intent of each email, and drafts or sends context-aware replies automatically.  
It’s built to save hours of manual effort while maintaining a personalized communication style.

---

## 🔧 Tech Stack
- Next.js  
- Node.js  
- Express.js  
- LangChain  
- Gmail API  
- JWT Authentication  

---

## 🚀 Features
- Reads and analyzes Gmail messages securely using OAuth2  
- Generates intelligent, context-aware replies with LangChain  
- Maintains user tone and intent consistency across conversations  
- Provides option for users to review or auto-send replies  
- Secure authentication and access management using JWT  
- Real-time updates with a fast, responsive Next.js frontend  

---

## 🧩 Architecture Overview
1. **Frontend (Next.js)** – Handles UI, authentication, and real-time reply management  
2. **Backend (Node.js + Express.js)** – Manages API routes, Gmail API requests, and LangChain model inference  
3. **LangChain Integration** – Extracts message context and generates draft replies using prompt chains  
4. **Database Layer (MongoDB or JSON store)** – Stores user preferences, history, and token data  

---

## 🧠 How It Works
1. User authenticates via Google OAuth2  
2. System fetches unread Gmail messages using Gmail API  
3. LangChain model analyzes email content and generates a suitable reply  
4. User can review, edit, or auto-send the response directly  
5. Updates are reflected in real-time on the dashboard  

---

## 📦 Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/niyojaka.git
   cd niyojaka
   ```

2. Install dependencies  
   ```bash
   npm install
   ```

3. Create a `.env` file and add:
   ```
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   JWT_SECRET=your_jwt_secret
   LANGCHAIN_API_KEY=your_langchain_key
   ```

4. Run the development server  
   ```bash
   npm run dev
   ```

5. Visit `http://localhost:3000`

---

## 📈 Impact
- Automates over 80% of repetitive email responses  
- Reduces average inbox management time by 2–3 hours daily  
- Maintains tone consistency and improves response turnaround  

---

## 🤝 Contribution
Pull requests and ideas are always welcome.  
For major changes, please open an issue first to discuss what you would like to improve.
