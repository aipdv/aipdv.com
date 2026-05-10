# Portfolio v2: Prabhudayal Vaishnav

A Neobrutalistic AI Portfolio featuring a tool-enabled voice assistant named Mira. This project is built with Next.js 15, TypeScript, and Google Gemini.

## Screenshots

![Home Page](/assets/screenshots/home-page.png)
![Selected Projects](/assets/screenshots/selected-projects.png)
![Resume Page](/assets/screenshots/resume-page.png)
![Call Active](/assets/screenshots/call-active.png)

## Features

- **Neobrutalistic Design System**: A high-contrast interface using heavy borders and vibrant accents. The aesthetic is optimized for visual impact and technical clarity.
- **Mira: Real-time Voice AI**: An AI assistant powered by the Google Gemini live speech API. Mira discusses projects, experience, and skills in real-time.
- **Voice-Driven Navigation**: Mira executes page routing to sections like Projects, Resume, or About based on natural language requests.
- **Multilingual Support**: Real-time voice interaction with automatic language detection.
- **Multi-Device Compatibility**: A responsive architecture for mobile, tablet, and desktop environments.
- **Interactive Bento Grids**: Asymmetric layouts utilizing motion-enhanced cards and hover effects.
- **Validated Achievements**: Documentation of hackathon wins and research contributions presented via a spotlight carousel.

## Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Library**: React 19
- **Styling**: Tailwind CSS 3 with custom design tokens
- **Animations**: Framer Motion 12 and GSAP
- **AI Integration**: Google Gemini AI
- **Icons**: Phosphor Icons
- **Package Manager**: Bun

## Project Structure

```
├── app/                    # Next.js App Router
│   ├── page.tsx           # Landing page with Bento Grid
│   ├── resume/            # Optimized resume route
│   ├── projects/          # Selected works showcase
│   └── layout.tsx         # Root layout with Mira integration
├── components/            # React Components
│   ├── VoiceOrb.tsx       # Voice visualization
│   ├── LiveChatModal.tsx  # Gemini voice interface
│   ├── NeoNavbar.tsx      # Neobrutalistic navigation
│   ├── ISTClock.tsx       # Indian Standard Time tracker
│   └── constants.ts       # Centralized resume data
├── services/              # Business logic
├── types/                 # TypeScript definitions
├── public/                # Static assets
└── tailwind.config.js     # Design system configuration
```

## Getting Started

### Prerequisites

- Node.js 18 or Bun
- Google Gemini API key

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
# Add NEXT_PUBLIC_GEMINI_API_KEY
```

4. Start the development server:
```bash
bun dev
```

## Mira (AI Assistant)

Mira is a tool-enabled voice agent.
- **Navigation**: "Show me your projects" triggers a router event to /projects.
- **Resume Data**: "Where did Prabhu work?" fetches data from constants.ts.
- **Latency Optimization**: Minimal interaction lag through optimized WebRTC flow.

## Projects

1. **Grand Plaza**: Voice AI Hotel Concierge System
2. **Career Scout**: Voice AI Job Search Assistant
3. **The AI Scientist**: Sakana AI Contributor
4. **XGen-AI**: RAG Telegram Bot
5. **xFace**: Emotion Detection Computer Vision Bot

## License

MIT

## Contact

- **Portfolio**: [aipdv.com](https://aipdv.com)
- **LinkedIn**: [aipdv](https://www.linkedin.com/in/aipdv)
- **Email**: hi@aipdv.com

Built with Next.js, TypeScript, and Logic by Prabhudayal Vaishnav
