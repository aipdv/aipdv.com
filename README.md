# Portfolio v2 - Prabhudayal Vaishnav

A high-performance, **Neobrutalistic AI Portfolio** featuring a real-time, tool-enabled voice assistant (Mira) built with Next.js 15, TypeScript, and Google Gemini.

## 🚀 Features

- **Neobrutalistic Design System**: A bold, high-contrast interface featuring heavy borders, vibrant accents (#39FF14), and a raw aesthetic optimized for visual impact.
- **Mira: Real-time Voice AI**: An integrated AI assistant powered by Google Gemini's live speech API. Mira acts as a personal guide, capable of discussing my projects, experience, and skills in real-time.
- **Voice-Driven Navigation**: Mira can automatically navigate through page routes (Projects, Resume, About) based on your natural language requests.
- **Multilingual Support**: Real-time voice interaction across multiple languages with automatic detection.
- **Multi-Device Compatibility**: A fully responsive architecture ensuring a premium experience across mobile, tablet, and desktop devices.
- **Interactive Bento Grids**: Modern asymmetric layouts with motion-enhanced cards and hover effects.
- **Battle-Tested Achievements**: Showcase of hackathon wins and research contributions with a "Validated At" spotlight carousel.

## 🛠️ Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Library**: React 19
- **Styling**: Tailwind CSS 3 (Custom Neobrutal Design Tokens)
- **Animations**: Framer Motion 12 & GSAP
- **AI Integration**: Google Gemini AI (@google/genai)
- **Icons**: Phosphor Icons (@phosphor-icons/react)
- **Package Manager**: Bun

## 📂 Project Structure

```
├── app/                    # Next.js App Router
│   ├── page.tsx           # Landing page with Bento Grid & IST Clock
│   ├── resume/            # Centered, optimized resume route
│   ├── projects/          # Selected works showcase
│   └── layout.tsx         # Root layout with Mira integration
├── components/            # React Components
│   ├── VoiceOrb.tsx       # Interactive voice visualization
│   ├── LiveChatModal.tsx  # Gemini-powered voice interface
│   ├── NeoNavbar.tsx      # Neobrutalistic navigation
│   ├── ISTClock.tsx       # Live Indian Standard Time tracker
│   └── constants.ts       # Centralized Resume Data (Source of truth)
├── services/              # Business logic & AI orchestration
├── types/                 # TypeScript type definitions
├── public/                # Static assets & images
└── tailwind.config.js     # Neobrutal design system configuration
```

## 🏁 Getting Started

### Prerequisites

- Node.js 18+ or **Bun** (Recommended)
- Google Gemini API key ([Get one here](https://aistudio.google.com/app/apikey))

### Installation

1. Clone the repository:
```bash
git clone https://github.com/aipdv/aipdv.com.git
cd aipdv.com
```

2. Install dependencies:
```bash
bun install
```

3. Set up environment variables:
```bash
cp .env.example .env.local
# Add your NEXT_PUBLIC_GEMINI_API_KEY
```

4. Run the development server:
```bash
bun dev
```

## 🧠 Mira (AI Assistant)

Mira is not just a chatbot; she is a tool-enabled voice agent.
- **Navigation**: "Show me your projects" -> Mira triggers a router event to `/projects`.
- **Resume Insight**: "Where did Prabhu work?" -> Mira fetches data from `constants.ts`.
- **Latency Optimized**: Uses a streamlined WebRTC/WebSocket-like flow for minimal interaction lag.

## 🏆 Projects Included

1. **Grand Plaza**: Voice AI Hotel Concierge System (FastAPI, LangGraph)
2. **Career Scout**: Voice AI-Powered Job Search Assistant (Next.js, Supabase)
3. **The AI Scientist**: Sakana AI Contributor (Open Source)
4. **XGen-AI**: RAG Telegram Bot (Python, Meta LLAMA 3.1)
5. **xFace**: Emotion Detection Computer Vision Bot

## 📄 License

MIT

## 🤝 Contact

- **Portfolio**: [aipdv.com](https://aipdv.com)
- **LinkedIn**: [aipdv](https://www.linkedin.com/in/aipdv)
- **Email**: hi@aipdv.com

---

Built with 💚 and Logic by Prabhudayal Vaishnav
