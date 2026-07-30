# 🚀 QuickGPT – AI Text & Image Generator

QuickGPT is a full-stack AI-powered web application that allows users to generate **AI text responses** and **AI images** through an intuitive chat interface. The application provides secure authentication, chat history management, image publishing, and a credit-based usage system.

🌐 **Live Demo:** https://quick-gpt-six-xi.vercel.app/

---

# 📸 Preview

Visit the live application:

👉 https://quick-gpt-six-xi.vercel.app/

---

# ✨ Features

### 🤖 AI Text Generation
- Generate AI-powered text responses.
- Fast conversational interface.
- Chat history is saved automatically.

### 🎨 AI Image Generation
- Generate AI images from text prompts.
- High-quality AI-generated images.
- Option to publish generated images.

### 💬 Chat Management
- Create unlimited chats.
- View previous conversations.
- Delete chats anytime.
- Chat history stored in MongoDB.

### 👤 Authentication
- User Registration
- Secure Login
- JWT Authentication
- Protected Routes

### 💳 Credit System
- Credit-based AI usage.
- Separate credit cost for text and image generation.
- Stripe payment integration for purchasing credits.

### 🖼️ Public Gallery
- Publish generated AI images.
- Explore images shared by other users.

### 📱 Responsive UI
- Clean modern interface.
- Mobile Friendly
- Desktop Optimized

---

# 🛠️ Tech Stack

## Frontend
- React.js
- Vite
- Tailwind CSS
- React Router
- Axios
- React Markdown
- PrismJS
- React Hot Toast

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt.js

## AI & Cloud Services
- Google Gemini API
- ImageKit AI
- Stripe Payments

---

# 📂 Project Structure

```
QuickGPT
│
├── client
│   ├── React
│   ├── Tailwind CSS
│   └── Vite
│
├── server
│   ├── Express
│   ├── MongoDB
│   ├── JWT Authentication
│   ├── Gemini AI
│   ├── ImageKit
│   └── Stripe
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/your-username/QuickGPT.git
```

---

## Install Frontend

```bash
cd client
npm install
npm run dev
```

---

## Install Backend

```bash
cd server
npm install
npm run dev
```

---

# 🔑 Environment Variables

Create a `.env` file inside the **server** folder.

```env
PORT=3000

MONGODB_URI=your_mongodb_url

JWT_SECRET=your_secret

GEMINI_API_KEY=your_gemini_api_key

IMAGEKIT_PUBLIC_KEY=your_public_key
IMAGEKIT_PRIVATE_KEY=your_private_key
IMAGEKIT_URL_ENDPOINT=your_url_endpoint

STRIPE_SECRET_KEY=your_stripe_secret
STRIPE_WEBHOOK_SECRET=your_webhook_secret
```

---

# 🧪 Test Account

Use the following credentials to test the application.

**Email**

```
hello@gmail.com
```

**Password**

```
1234
```

---

# 📦 Main API Modules

### User
- Register
- Login
- Get User Profile
- Published Images

### Chat
- Create Chat
- Get Chats
- Delete Chat

### Messages
- AI Text Generation
- AI Image Generation

### Credits
- Purchase Credits
- Credit Management

---

# 💳 Payment Integration

- Stripe Checkout
- Credit Purchase
- Secure Webhook Verification

---

# 🎯 Future Improvements

- Conversation Search
- Dark Mode
- Chat Export
- AI Voice Chat
- Multiple AI Models
- Prompt Templates
- Image Download History

---

# 👨‍💻 Author

**Shailendra Kumar**

If you like this project, don't forget to ⭐ the repository.

---
## 📄 License

This project is developed for learning and portfolio purposes.
