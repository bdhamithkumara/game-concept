This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.


# 67 Never Die Pronunciation Practice Web App

**Fun, viral-inspired pronunciation trainer** for Sinhala, Tamil, and English  
Inspired by the MEOVV Narin & Ella "67 never die" TikTok challenge

## Project Summary

This project aims to create an interactive web application (with potential mobile expansion later) that combines the playful, viral aesthetic of the "67 never die" meme with real pronunciation practice. Users record themselves saying words/phrases (starting with "six seven" equivalents), compare to a native model, and improve step-by-step — all wrapped in a dynamic road + flying flags visual style.

**Current date of summary**: February 2026  
**Developer location vibe**: Sri Lanka 🇱🇰

## Core Concept

- **Inspiration**: Viral TikTok videos where people say "67" / "six seven" in many languages with cute hand gestures 👋🖐️
- **Educational twist**: Turn it into a pronunciation learning tool focused on accuracy, especially for underrepresented languages like Sinhala and Tamil
- **Visual style**: Looping highway/road background + country flags flying past (like in many trend videos)
- **Target users**: People who want to practice pronunciation (heritage learners, tourists to Sri Lanka, locals improving English, etc.)

## Languages & Progression Plan

1. **Priority languages** (MVP focus)
   - Sinhala (හය හත – haya hata)
   - Tamil (ஆறு ஏழு – aaru eḻu)
   - English (six seven)

2. **Content progression** (agreed best practice)
   - **Level 1**: Single words / numbers (build confidence on individual sounds)
   - **Level 2**: Short phrases & basic sentences (introduce linking & rhythm)
   - **Level 3**: Paragraphs / connected speech (real-world flow, intonation, reductions)

## Technical Approach Discussed

- **Phase 1 – Web-first** (recommended)
  - HTML/CSS/JS (vanilla or React/Next.js)
  - Hosting: Vercel or Netlify (free & instant)
  - Easy sharing via link → low barrier for testing

- **Phase 2 – Mobile** (only if web gains traction)
  - React Native or Flutter (code reuse possible)

- **Key features**
  - Animated road background (CSS scroll or video loop)
  - Flying flags per language (FlagCDN)
  - Hand gesture animation (CSS or emoji)
  - Audio: User recordings (MediaRecorder) + model audio (your voice)
  - Feedback methods:
    - Web Speech API (good for English/Tamil, limited Sinhala)
    - Side-by-side waveform comparison
    - Self-assessment fallback
    - Future: Cloud STT or pronunciation APIs (Azure, Google)

- **Gamification**
  - Scores, streaks, level unlocks
  - Shareable results ("I nailed Sinhala හය හත!")

## Competition & Niche Advantage

- Very low direct competition
- No existing app combines:
  - "67 never die" viral meme style
  - Road + moving flags visuals
  - Focused Sinhala/Tamil pronunciation practice
- Closest: TikTok filters, ELSA Speak, Duolingo numbers modules, but none match the fun + Sri Lanka-centric angle

## Monetization Ideas (long-term)

- Platform ad revenue (TikTok/YouTube if videos promote it)
- Affiliates (language apps)
- Premium features (more languages, advanced feedback)
- Digital downloads (phrase packs)

## Current Status

- In **planning & early prototyping** stage
- Multiple code snippets shared (HTML/JS prototypes with animation, speech, recording)
- Next recommended steps:
  1. Build minimal web MVP (road + flags + word challenges + record/compare)
  2. Test Sinhala browser recognition
  3. Promote small via TikTok/X → gather real user feedback
  4. Iterate based on usage

## Final Vibe

**67 never die…**  
…and neither does this pronunciation journey! 🇱🇰🛣️🖐️🗣️

Built with lots of back-and-forth help from Grok 🚀


expensive tracker app for friends 
