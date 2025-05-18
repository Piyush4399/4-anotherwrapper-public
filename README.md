# AnotherWrapper

### 🧠 Overview  
AnotherWrapper is a backend service built to automate video content creation using AI tools.  
It acts as the engine behind various frontends, handling processes like:

- AI-based script generation
- Voice synthesis
- Image generation
- Video rendering
- Upload automation

This project integrates GPT for text, image-to-video tools, and cloud storage (Supabase).

---

### ⚙️ Tech Stack  
- Node.js / TypeScript  
- Supabase (for database and storage)  
- GPT-4 (for generating video scripts and captions)  
- n8n (for automation workflows)  
- JSON2Video / Runway / Kling (for media generation)

---

### 🔁 Workflow Summary  

1. A user uploads a file or provides input
2. GPT generates the content (scripts, summaries, titles)
3. Image and audio are generated
4. These are combined into a video
5. Output is uploaded and logged in Supabase

---

### 📂 Folder Structure

```bash
anotherwrapper/
├── api/                  # API routes and handlers
├── services/             # GPT, TTS, and video generation logic
├── supabase/             # Supabase client and service
├── workflows/            # n8n exported flows (json)
├── utils/                # Helper functions
└── README.md             # Project overview
