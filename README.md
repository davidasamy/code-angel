# Code Angel

AI-assisted coding tool that helps students learn while giving instructors full visibility into how AI is being used — creating an auditable paper trail for AI assistance in coding assignments.

## Tech Stack

- **Frontend:** Next.js
- **Auth & Database:** Supabase
- **AI Backend:** AWS Bedrock (Titan)

## Getting Started

### Demo

Visit [codeangel.study](https://codeangel.study) 

### Local Setup

1. Clone the repo and install dependencies
```bash
git clone https://github.com/your-repo/code-angel.git
cd code-angel
npm install
```

2. Create a `.env.local` file
```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
AWS_REGION=your_aws_region
AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key
```

3. Start the dev server
```bash
npm run dev
```

## How It Works

Students interact with the AI to get coding help, hints, debugging, code generation. Every interaction is logged and reviewable by instructors through a dashboard, maintaining academic integrity without blocking access to AI tools.

## Built By

Rikhil R, David Samy, and Akshaj Bharadwaj — DubHacks '25
