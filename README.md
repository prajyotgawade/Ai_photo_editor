# 🎨 Pixxel — AI-Powered Professional Photo Editor

<div align="center">

**Professional image editing powered by AI. Crop, resize, adjust colors, remove backgrounds, and enhance images with cutting-edge generative AI technology.**

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-ai--photo--editor--pi.vercel.app-0070f3?style=for-the-badge)](https://ai-photo-editor-pi.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Ai__photo__editor-181717?style=for-the-badge&logo=github)](https://github.com/prajyotgawade/Ai_photo_editor)
[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js)](https://nextjs.org)
[![Replicate](https://img.shields.io/badge/AI-Replicate_API-purple?style=for-the-badge)](https://replicate.com)
[![Vercel](https://img.shields.io/badge/Deployed-Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com)

</div>

---

## 📋 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Pricing Plans](#-pricing-plans)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [AI Capabilities](#-ai-capabilities)
- [Roadmap](#-roadmap)
- [Contact](#-contact)

---

## 🚀 About the Project

**Pixxel** is a full-stack, AI-powered professional photo editing web application — built to give creators, designers, and everyday users access to powerful image editing tools directly in the browser, with no software installation required.

Powered by the **Replicate API**, Pixxel brings state-of-the-art generative AI capabilities to standard photo editing workflows — including AI background removal, content-aware image extension, object removal with natural language prompts, and 4x AI upscaling.

> Built with **Next.js + React** and deployed on Vercel — demonstrating full-stack development, AI API integration, and SaaS product architecture.

---

## ✨ Features

### 🛠 Core Editing Tools
- ✅ **Smart Crop & Resize** — Interactive cropping with aspect ratio constraints and quality-preserving resize
- ✅ **Color & Light Adjustment** — Professional brightness, contrast, saturation controls with real-time preview
- ✅ **Auto Enhance** — One-click intelligent image enhancement
- ✅ **Text Tool** — Add and customize text overlays on images

### 🤖 AI-Powered Features
- ✅ **AI Background Removal** — Instantly remove or replace backgrounds with precise edge detection
- ✅ **AI Content Editor** — Edit images using natural language prompts — remove objects, change elements, add content
- ✅ **Image Extender** — Expand canvas in any direction using AI generative fill
- ✅ **AI Upscaler** — Enhance image resolution up to **4x** while preserving fine details

### 💼 Platform Features
- ✅ **Project Management** — Organize and manage multiple image projects
- ✅ **Unlimited Exports** — Download edited images in high quality
- ✅ **Real-time Preview** — See every edit applied live before exporting
- ✅ **Responsive UI** — Works seamlessly on desktop and tablet
- ✅ **Subscription System** — Free & Pro plans with monthly billing

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| **Framework** | Next.js + React.js |
| **Language** | JavaScript / TypeScript |
| **AI Engine** | Replicate API |
| **Styling** | Tailwind CSS |
| **Deployment** | Vercel |
| **Image Processing** | Replicate AI Models |
| **Routing** | Next.js App Router |

---

## 💰 Pricing Plans

| Feature | Free | Pro ($12/mo) |
|---|---|---|
| Projects | 3 maximum | Unlimited |
| Exports per month | 20 | Unlimited |
| Basic Crop & Resize | ✅ | ✅ |
| Color Adjustments | ✅ | ✅ |
| Text Tool | ✅ | ✅ |
| AI Background Remover | ❌ | ✅ |
| AI Image Extender | ❌ | ✅ |
| AI Retouch & Upscaler | ❌ | ✅ |
| AI Content Editor | ❌ | ✅ |

---

## ⚙️ Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) v18+
- npm or yarn
- [Replicate API key](https://replicate.com) (free to get)

### Installation

**1. Clone the repository**
```bash
git clone https://github.com/prajyotgawade/Ai_photo_editor.git
cd Ai_photo_editor
```

**2. Install dependencies**
```bash
npm install
```

**3. Configure environment variables**

Create a `.env.local` file in the root directory:
```env
REPLICATE_API_TOKEN=your_replicate_api_token
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

Get your free Replicate API token at: [replicate.com/account/api-tokens](https://replicate.com/account/api-tokens)

**4. Run the development server**
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Available Scripts

```bash
npm run dev       # Start development server
npm run build     # Create production build
npm run start     # Start production server
npm run lint      # Run ESLint checks
```

---

## 📁 Project Structure

```
Ai_photo_editor/
├── app/                    # Next.js App Router
│   ├── (auth)/             # Authentication pages
│   ├── dashboard/          # Main editor dashboard
│   ├── api/                # API routes (Replicate integration)
│   └── layout.tsx          # Root layout
├── components/             # Reusable UI components
│   ├── editor/             # Image editing components
│   ├── ai/                 # AI tool components
│   └── ui/                 # Base UI components
├── lib/                    # Utility functions & API helpers
├── hooks/                  # Custom React hooks
├── public/                 # Static assets (logo, images)
├── next.config.js          # Next.js configuration
├── tailwind.config.js      # Tailwind CSS configuration
└── package.json            # Dependencies
```

---

## 🤖 AI Capabilities

Pixxel uses **Replicate API** to run powerful open-source AI models:

| AI Feature | What it does |
|---|---|
| **Background Removal** | Detects complex edges & removes backgrounds with pixel-level precision |
| **Content Editor** | Accepts natural language prompts to modify image content |
| **Image Extender** | Generative fill — extends canvas by creating new realistic content |
| **AI Upscaler** | Enhances resolution 2x–4x using super-resolution AI models |

---

## 🗺 Roadmap

- [x] Core editing tools — crop, resize, color adjustment
- [x] AI background removal
- [x] AI content editor with natural language prompts
- [x] AI image extender (generative fill)
- [x] AI upscaler (up to 4x)
- [x] Subscription system — Free & Pro plans
- [x] Production deployment on Vercel
- [ ] User authentication & saved projects
- [ ] Batch image processing
- [ ] Mobile responsive editor
- [ ] Image format conversion (PNG, WEBP, JPG)
- [ ] Team collaboration features
- [ ] API access for developers

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 📬 Contact

**Prajyot Gawade**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-prajyotgawade-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/prajyotgawade)
[![GitHub](https://img.shields.io/badge/GitHub-prajyotgawade-181717?style=flat&logo=github)](https://github.com/prajyotgawade)
[![Live App](https://img.shields.io/badge/Live_App-Pixxel-0070f3?style=flat)](https://ai-photo-editor-pi.vercel.app)

---

<div align="center">

⭐ **If you found this project useful, please give it a star!** ⭐

Built with ❤️ by Prajyot Gawade — Mumbai, India

</div>
