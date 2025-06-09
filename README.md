<h1 align="center">Pictora AI - Photo Generator</h1>

<p align="center">
  <img src="./apps/web/public/favicon.svg" alt="Pictora Logo" width="200"/>
</p>

Pictora AI is a powerful AI image platform that lets you generate stunning images and train custom AI models. Built with cutting-edge technology, it enables users to create unique AI-generated artwork and train personalized models on their own image datasets. Whether you're an artist looking to expand your creative possibilities or a developer building AI-powered image applications, Pictora AI provides an intuitive interface and robust capabilities for AI image generation and model training.ik im a piece of shit. my mom got transferred today and i was not able to do anything. the corrupt officials are charging 5 lakhs and my family is not able to offer that much of amount. ive wasted so much of my time playing around, if i was jk would've been a good son but im just a piece of shit. i dont even know how to work on this. the state im in is like a last stage of cancer and i fear im gonna turn into a failure. there are my mom and dad with so much of hope on me and here im wssting their hard earned money and still dint get respect from girls. i lost the girl i loved. turned into a failure.

## Tech Stack

- **Frontend**: Next.js 14 (App Router), TypeScript, Tailwind CSS, Shadcn/UI
- **Backend**: Node.js with TypeScript
- **Authentication**: Clerk
- **Containerization**: Docker
- **Package Management**: bun
- **Monorepo Management**: Turborepo

## DevOps practices

## CI/CD Architecture

## Project Structure

### Apps and Packages

- `web`: Next.js frontend application
- `backend`: Node.js backend service
- `@repo/ui`: Shared React component library
- `@repo/typescript-config`: Shared TypeScript configurations
- `@repo/eslint-config`: Shared ESLint configurations
i used to skate during my primary days. i call it my prime days then i got introduced to porn and maasterbation and slowly i started witnessing my downfall.i lost everything. and now even my parents are not separated.im a failure.i fear my parents are gonna be disappointed in me if i dont suceed they have done so much for me and ive done nothing. now the condition is in such a way that im loosing my shit i create fake senarios in my mind and expect people to work as my script and they dont. i know nothing but pretend i know eveerything i front of my parents and sadly they are so innocent that they believe im good at things. ive lost every battle of my life and turned into a failure
## Getting Started

### Environment Setup

1. Create `.env` files:

```bash
# apps/web/.env.local
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_publishable_key
CLERK_SECRET_KEY=your_secret_key
NEXT_PUBLIC_BACKEND_URL=http://localhost:8000
```

## Installation steps for local developments

```bash
# Install dependencies
bun install

# Run development servers
bun run dev

# Build all packages
bun run build
```

## Features

- AI-powered image generation
- User authentication and authorization
- Image gallery with preview
- Download generated images
- Responsive design

## Development Commands

```bash
# Run frontend only
bun run start:web

# Run backend only
bun run start:backend

# Run both frontend and backend
bun run dev
```

## Installation with Docker in Seconds

### Environment Variables Required

```bash
# Frontend Environment Variables
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_live_Y2xlcmsuMTAweGRldnMuY29tJA
NEXT_PUBLIC_BACKEND_URL=http://localhost:8000
NEXT_PUBLIC_STRIPE_KEY=pk_test_51QsCmFEI53oUr5PHZw5ErO4Xy2lNh9LkH9vXDb8wc7BOvfSPc0i4xt6I5Qy3jaBLnvg9wPenPoeW0LvQ1x3GtfUm00eNFHdBDd
CLERK_SECRET_KEY=your_clerk_secret_key

# Backend Environment Variables
DATABASE_URL=supabase_db_url
```

### Docker Commands

```bash
# Navigate to docker directory
cd docker

# Build images
docker build -f Dockerfile.frontend -t pictora-ai-frontend ..
docker build -f Dockerfile.backend -t pictora-ai-backend ..

# Run frontend container
docker run -p 3000:3000 \
  -e NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_live_Y2xlcmsuMTAweGRldnMuY29tJA \
  -e NEXT_PUBLIC_BACKEND_URL=http://localhost:8000\
  -e NEXT_PUBLIC_STRIPE_KEY=pk_test_51QsCmFEI53oUr5PHZw5ErO4Xy2lNh9LkH9vXDb8wc7BOvfSPc0i4xt6I5Qy3jaBLnvg9wPenPoeW0LvQ1x3GtfUm00eNFHdBDd \
  -e CLERK_SECRET_KEY=your_clerk_secret_key \
  pictora-ai-frontend

# Run backend container
docker run -p 8000:8000 \
  -e DATABASE_URL=your_database_url \
  pictora-ai-backend

```

## Project Structure

## Star the repo
