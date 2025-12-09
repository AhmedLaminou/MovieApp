# 🎬 MovieApp - React Native Mobile Application

A modern, cross-platform mobile application built with React Native and Expo that allows users to discover, search, and save their favorite movies. The app features a beautiful UI with trending movies, search functionality, and user profiles.

## ✨ Features

- **Trending Movies**: Discover the latest and most popular movies
- **Search Functionality**: Find movies by title, genre, or keywords
- **Movie Details**: View detailed information about each movie
- **Save Favorites**: Bookmark your favorite movies to watch later
- **Responsive Design**: Beautiful UI that works on both iOS and Android
- **Modern Stack**: Built with React Native, Expo, and Appwrite

## 🛠 Tech Stack

- **Frontend**: React Native
- **Navigation**: Expo Router
- **Styling**: NativeWind (Tailwind CSS for React Native)
- **Backend Services**: Appwrite
- **State Management**: React Query (useFetch custom hook)
- **Type Safety**: TypeScript

## 📱 Screens

1. **Home Screen**: Displays trending movies and search functionality
2. **Search Screen**: Search and filter movies
3. **Saved Movies**: View your bookmarked movies
4. **Profile**: User profile and settings
5. **Movie Details**: Detailed view of a selected movie

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or later)
- npm or yarn
- Expo CLI
- Appwrite backend (for full functionality)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/MovieApp.git
   cd MovieApp
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory and add your Appwrite configuration:
   ```env
   APPWRITE_ENDPOINT=your_appwrite_endpoint
   APPWRITE_PROJECT_ID=your_project_id
   TMDB_API_KEY=your_tmdb_api_key
   ```

4. **Start the development server**
   ```bash
   npx expo start
   ```

5. **Run on your device/emulator**
   - Press `i` for iOS simulator
   - Press `a` for Android emulator
   - Scan the QR code with Expo Go app on your physical device

## 📁 Project Structure

```
MovieApp/
├── app/                    # Main application directory
│   ├── (tabs)/            # Tab navigation screens
│   │   ├── index.tsx      # Home screen
│   │   ├── search.tsx     # Search screen
│   │   └── save.tsx       # Saved movies screen
│   ├── movie/             # Movie details screens
│   └── _layout.tsx        # Root layout configuration
├── assets/                # Static assets (images, icons, etc.)
├── components/            # Reusable UI components
│   ├── MovieCard.tsx
│   ├── SearchBar.tsx
│   └── TrendingCard.tsx
├── constants/             # App constants and configurations
├── interfaces/            # TypeScript interfaces
├── services/              # API and service layer
│   ├── api.ts            # TMDB API client
│   ├── appwrite.ts       # Appwrite service
│   └── usefetch.ts       # Custom fetch hook
└── types/                # TypeScript type definitions
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- TMDB API for movie data
- Appwrite for backend services
- Expo for the amazing development experience
- React Native community for awesome libraries and tools
