# Skillcraft - DSA Learning Tracker

A comprehensive Data Structures and Algorithms learning platform built with modern web technologies.

## 🚀 Features

- **Interactive Learning Path**: Structured DSA chapters with progress tracking
- **Progress Analytics**: Visual progress indicators and difficulty-based tracking
- **User Authentication**: Secure login system with admin controls
- **Responsive Design**: Beautiful UI that works on all devices
- **Dark/Light Theme**: Toggle between themes for comfortable learning
- **Real-time Updates**: Instant progress synchronization

## 🛠️ Technologies Used

- **Frontend**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS + shadcn/ui components
- **Backend**: Supabase (Database & Authentication)
- **State Management**: TanStack Query
- **Routing**: React Router DOM
- **Charts**: Recharts for analytics
- **Icons**: Lucide React

## 📦 Installation

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/aditya-dev-projects/Project-Dsa-Roadmap.git
   cd Project-Dsa-Roadmap
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:8080`

## 🏗️ Project Structure

```
src/
├── components/     # Reusable UI components
├── pages/         # Page components
├── hooks/         # Custom React hooks
├── lib/           # Utility functions and configurations
├── data/          # Static data and constants
└── integrations/  # External service integrations
```

## 🚀 Deployment

### Vercel (Recommended)

1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect the Vite configuration
3. Deploy with one click

### Netlify

1. Build the project: `npm run build`
2. Upload the `dist` folder to Netlify
3. Configure redirects for client-side routing

### Manual Deployment

```bash
npm run build
# Upload the dist/ folder to your hosting provider
```

## 📊 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Links

- **Repository**: https://github.com/aditya-dev-projects/Project-Dsa-Roadmap
- **Live Demo**: [Coming Soon]

---

Built with ❤️ for the DSA learning community
