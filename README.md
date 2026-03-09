# Lexispell

Lexispell is a spelling application designed to help users master high-frequency words, irregular "Red Words", homophones, and morphemes.

## Features

- **Spelling Practice**: Interactive spelling quizzes with definitions and example sentences.
- **Progress Tracking**: Master words across different levels and categories.
- **AI-Powered**: Uses Google Gemini to generate dynamic content and feedback.
- **Gamified Experience**: Earn scores and level up as you master more words.

## Getting Started

### Prerequisites

- Node.js (v20 or higher)
- npm

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/bwnail/Lexispell.git
   cd Lexispell
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your Gemini API key:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

### Development

Run the development server:
```bash
npm run dev
```

### Build

Build the project for production:
```bash
npm run build
```

### Deployment

The project is configured to deploy to GitHub Pages automatically via GitHub Actions when you push to the `main` branch.

Alternatively, you can deploy manually:
```bash
npm run deploy
```

## Built With

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Firebase](https://firebase.google.com/)
- [Google Gemini API](https://ai.google.dev/)
- [Motion](https://motion.dev/)
- [Lucide React](https://lucide.dev/)

## License

This project is private.
