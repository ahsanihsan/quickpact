# 📄 QuickPact – AI Contract Assistant (Mobile App)

QuickPact is a mobile-first application that helps users understand, assess, and interact with legal contracts using AI. Users can upload, scan, or capture contracts and receive smart summaries, risk evaluations, and contextual chat support — all from their phone.

## 🚀 Features

- 📸 **Capture or Upload Contracts**  
  Take a photo, upload an image, or paste text to input a contract.

- 🧠 **AI-Powered Summarization**  
  Generate a plain-language summary of the contract using LLMs.

- ⚠️ **Risk & Clause Analysis**  
  Identify potential red flags, ambiguous terms, or high-risk clauses.

- 💬 **Chat With Your Contract**  
  Ask questions like “When does this contract end?” or “Is there an auto-renewal?” using a custom AI chatbot.

- 🔒 **Secure Contract Storage**  
  Encrypted storage of scanned contracts, summaries, and chats.

---

## 📱 Tech Stack

| Layer        | Technology                                  | Purpose                                       |
| ------------ | ------------------------------------------- | --------------------------------------------- |
| Frontend     | React Native (Expo)                         | Cross-platform mobile app                     |
| OCR          | Google ML Kit / Tesseract                   | On-device text extraction                     |
| AI Backend   | OpenAI GPT-4o / Claude / Mistral            | Summarization, risk detection, chat           |
| Vector DB    | Supabase / Weaviate / Pinecone              | Store contract embeddings for contextual chat |
| File Storage | Supabase Storage / Firebase Storage         | Store contract images & extracted text        |
| Auth         | Supabase Auth / Firebase Auth               | User authentication                           |
| Backend API  | Node.js (Express) / Supabase Edge Functions | Processing + analysis orchestration           |
| State Mgmt   | Redux Toolkit / Zustand                     | UI and app state                              |

---

## 🧠 AI Capabilities

QuickPact uses advanced natural language models to:

- Summarize contract contents into bullet points or paragraphs
- Extract key clauses (termination, payment terms, NDAs, etc.)
- Analyze legal risks and non-standard terms
- Respond conversationally using contract-specific context (via embeddings)

> ⚠️ Disclaimer: AI outputs are not legal advice. Users should consult a lawyer for formal legal matters.

---

## 📂 Folder Structure
