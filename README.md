# Persona
A minimalist, full-stack AI chatbot that remembers you and builds a personality profile from your conversations.

- Lets you chat naturally with an AI (Mistral-7B via free Hugging Face Inference)
- Persists every conversation in Pinecone vector database (free tier)
- Learns from your chat history using sentence embeddings
- When you ask “Who am I?” or “Tell me about myself” (after a few messages), it generates a fun, accurate personality-style profile based on everything you’ve said

Features
- Clean, mobile-friendly UI with Tailwind CSS
- Zero-cost LLM & embeddings (Hugging Face free tier)
- Persistent memory via Pinecone serverless index
- Retrieval-augmented profile generation
- Full TypeScript codebase
- Jest tests for core logic
- Single-user demo (easy to extend with auth)

Tech stack: Next.js 14 (app router) • React • TypeScript • Tailwind • Hugging Face Inference • Pinecone • Jest
