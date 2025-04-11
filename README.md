# MoodBuddy - Student Emotion Tracking

MoodBuddy is a comprehensive web application designed to help students track their emotional well-being and connect with educators for support. The platform provides tools for mood tracking, analytics, goal setting, and secure communication between students and educators.

## Features

- 📊 Daily mood tracking with detailed analytics
- 🎯 Goal setting and progress monitoring
- 💬 Secure messaging between students and educators
- 📚 Resource library for educational and wellness content
- 📅 Check-in request system
- 📱 Real-time notifications
- 📈 Data visualization and insights

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- Supabase (Auth, Database, Storage, Edge Functions)
- Chart.js
- Lucide Icons

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/moodbuddy.git
   cd moodbuddy
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your Supabase credentials:
   ```
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## Database Setup

The application uses Supabase as its backend. The database schema includes:

- User profiles (students and educators)
- Mood entries
- Goals
- Check-in requests
- Messages
- Resources
- Notifications

All necessary migrations are included in the `supabase/migrations` directory.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.