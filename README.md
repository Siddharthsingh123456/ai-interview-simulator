# AI Interview Simulator

A role-aware interview practice workspace for rehearsing technical interviews and reviewing AI-generated feedback.

## Features
- Configure a target role and experience level
- Practice interviews one question at a time
- Receive feedback on strengths and improvement areas
- Review guidance for stronger answers
- MongoDB-backed session persistence
- Responsive interview-focused interface

## Stack
React 18 · Vite 5 · Node.js 24 · Express · Mongoose · MongoDB · OpenAI-compatible API · Vercel

## Requirements
Node.js 24.x, npm, an AI provider API key, and MongoDB URI for session persistence.

## Setup
```bash
git clone https://github.com/Siddharthsingh123456/ai-interview-simulator.git
cd ai-interview-simulator
npm install
```
Create `.env` from `.env.example`:
```env
OPENAI_API_KEY=your_api_key
OPENAI_MODEL=gpt-4o-mini
MONGODB_URI=your_mongodb_connection_string
```
Keep credentials out of Git.

## Run and build
```bash
npm run dev
npm run build
npm run preview
```

## Deploy
Deploy the repository root to Vercel and configure environment variables in Project Settings. Test a complete interview flow after deployment.

## Note
AI feedback is a learning aid, not a hiring assessment or guarantee of interview performance. Avoid entering confidential personal or employer information.

## License
No license file is currently specified. Contact the repository owner before reuse.
