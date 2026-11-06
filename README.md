# AI Interview Simulator

A role-aware interview practice workspace that helps learners rehearse technical interviews, answer questions, and review AI-generated feedback.

## Features

- Configure target role and experience level
- Practice an interview one question at a time
- Receive feedback on answer strengths and improvement areas
- Review guidance for constructing stronger answers
- Save interview sessions through the MongoDB persistence layer
- Responsive interview-focused interface

## Technology

- React 18 and Vite 5
- Node.js 24 runtime
- Express and Mongoose
- MongoDB
- OpenAI-compatible model API
- Vercel deployment configuration

## Requirements

- Node.js 24.x and npm
- AI provider API key
- MongoDB URI for session persistence

## Local setup

```bash
git clone https://github.com/Siddharthsingh123456/ai-interview-simulator.git
cd ai-interview-simulator
npm install
```

Create a local `.env` file based on `.env.example`:

```env
OPENAI_API_KEY=your_api_key
OPENAI_MODEL=gpt-4o-mini
MONGODB_URI=your_mongodb_connection_string
```

Never commit real keys or database credentials.

## Run locally

```bash
npm run dev
```

Build and preview:

```bash
npm run build
npm run preview
```

## Deployment

Import the repository into Vercel, configure the environment variables, and deploy from the repository root. Check the deployment logs and test a complete interview flow after deployment.

## Practice guidance

Use feedback as a learning aid, not as an authoritative hiring assessment. Avoid entering personal, confidential, or employer-sensitive information.

## License

No license file is currently specified. Contact the repository owner before reuse.
