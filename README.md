# AI Learning Coach

An AI-powered web application that transforms any topic into a structured learning plan, explains concepts step-by-step, and helps users track progress.

Built with Next.js and OpenAI API.

---

## 🚀 Features

* Generate structured learning roadmaps from any topic
* Step-by-step concept explanations
* Practice questions and quizzes
* Personalized study suggestions
* Clean and minimal interface
* Secure server-side AI requests

---

## 🧱 Tech Stack

Frontend: Next.js
Backend: Next.js API routes (serverless)
AI Provider: OpenAI API
Hosting: Vercel
Styling: Tailwind CSS
Database (optional): Supabase

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ai-learning-coach.git
cd ai-learning-coach
```

### 2. Install dependencies

```bash
npm install
```

### 3. Create environment variables

Create a file named `.env.local` in the root directory:

```
OPENAI_API_KEY=your_api_key_here
NEXT_PUBLIC_APP_NAME=AI Learning Coach
```

---

## ▶️ Run Locally

```bash
npm run dev
```

Open:
http://localhost:3000

---

## 🔌 API Endpoint

### POST `/api/chat`

Request body:

```json
{
  "prompt": "Explain neural networks simply"
}
```

Response:

```json
{
  "result": "AI generated response..."
}
```

---

## 🧠 System Prompt Design

The application uses a structured system prompt to ensure consistent and educational responses.

Example behavior:

* Explain clearly
* Break concepts into steps
* Provide examples
* Suggest next learning actions

---

## ☁️ Deployment

### Deploy with Vercel

1. Push repository to GitHub
2. Import project in Vercel
3. Add environment variable:

   * OPENAI_API_KEY
4. Deploy

Your app will be live with automatic updates on every push.

---

## 🔐 Security Notes

* API keys are stored server-side only
* No secrets exposed to the client
* Rate limiting recommended for public deployments

---

## 🧩 Future Improvements

* User accounts
* Study history tracking
* Progress dashboard
* PDF upload and analysis
* Quiz generator
* Export notes feature
* Streaming AI responses

---

## 📄 License

MIT License

---

## 👤 Author

Built by [Your Name]

---

## ⭐ Support

If you like this project:

* Star the repository
* Share with others
* Contribute improvements
