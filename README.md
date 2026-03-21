# AI-Powered Applicant Tracking System (ATS)

A modern, AI-powered Applicant Tracking System built to analyze and score resumes effortlessly. Powered by React Router 7, TailwindCSS, Puter.js for zero-backend AI and storage functionalities, and PDF.js for client-side processing.

## 🚀 Features

- **Client-Side PDF Parsing:** Upload PDF resumes and securely convert them into images entirely in the browser using `pdfjs-dist`.
- **Drag & Drop Uploads:** Seamless file uploading experience powered by `react-dropzone`.
- **AI Resume Analysis:** Leverages **Puter.js** AI capabilities (`puter.ai`) to analyze resume content, provide scoring, and extract key insights.
- **Secure Storage & Authentication:** Out-of-the-box user authentication and cloud file storage via `puter.auth` and `puter.fs`.
- **Modern UI:** Built using React 19, Tailwind CSS v4, and minimal dependencies for optimal performance.

## 🛠️ Tech Stack

- **Framework:** [React Router v7](https://reactrouter.com/) (formerly Remix)
- **UI & Styling:** [Tailwind CSS v4](https://tailwindcss.com/) + `clsx` & `tailwind-merge`
- **State Management:** [Zustand](https://zustand-demo.pmnd.rs/)
- **Backend & AI:** [Puter.js](https://docs.puter.com/)
- **PDF Processing:** `pdfjs-dist`

## 📁 Project Structure

```text
ai-resume-analyzer/
├── app/
│   ├── components/       # Reusable React components (ScoreBadges, Uploader, etc.)
│   ├── constants/        # App-wide constants
│   ├── lib/              # Utility functions and Puter.js / PDF integrations 
│   ├── routes/           # React Router route definitions (Auth, Upload, Resume display)
│   ├── root.tsx          # Root layout structure
│   └── routes.ts         # Route configuration
├── public/               # Public assets and PDF workers
├── package.json
└── vite.config.ts
```

## 💻 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed globally.

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd ai-resume-analyzer
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`.

## 📜 Available Scripts

- `npm run dev` - Starts the development server.
- `npm run build` - Builds the app for production.
- `npm run start` - Starts the production server locally.
- `npm run typecheck` - Runs TypeScript type checking.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](#) if you want to contribute.

## 📝 License

This project is private and proprietary.
