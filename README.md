# AI Buddy

A multi-component project with a Next.js frontend and a Node.js Express backend.

## Project Structure

- `frontend/ai-buddy`: Next.js 16 project with Tailwind CSS v4 and shadcn UI.
- `backend`: Node.js Express server with TypeScript.

## Getting Started

### Prerequisites

- Node.js (Latest LTS version)
- npm or yarn

### Installation

1.  **Frontend Setup:**
    ```bash
    cd frontend/ai-buddy
    npm install
    ```

2.  **Backend Setup:**
    ```bash
    cd backend
    npm install
    ```

### Development

You can run both the frontend and backend simultaneously using the root scripts:

```bash
# In the root directory
npm run dev
```

Or run them individually:

- **Frontend:** `cd frontend/ai-buddy && npm run dev` (Runs on http://localhost:3000)
- **Backend:** `cd backend && npm run dev` (Runs on http://localhost:5000)
