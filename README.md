# 👨‍🍳 Chef.AI – Smart Restaurant Management Web App

Chef.AI is a smart, AI-powered restaurant management system designed to promote sustainability, reduce food waste, gamify healthy habits, and personalize user experiences using generative AI. Built using HTML, CSS, and Firebase, the app includes multiple interactive pages and connects to a real-time database.

---

## 🌟 Features

### 1. 🏠 Home Screen
- **Dashboard View** with quick links to all major features:
  - AI Recipe Generator
  - Leftover Management
  - Leaderboard
  - Points & Badges
  - Promotions
  - Events
  - Inage Search

### 2. 🔐 Authentication
- **Login / Signup Pages**
- Users are authenticated using Firebase Authentication.
- Existing users can log in; new users can sign up and are stored in Firebase.

### 3. 🍲 AI Recipe Generator
- Allows users to input food items.
- AI suggests creative recipes using Gemini API (currently mocked/dummy text in frontend).
- Awards **10 points** for each recipe generated.
- Removes used leftovers from the database.

### 4. 🍛 Leftover Management
- Users can add leftover items to the database.
- Displays a table of current leftovers.
- Includes a “Generate Recipe” button for each item.
- Recipes are generated and leftover is removed upon use.

### 5. 🏆 Leaderboard
- Displays a ranked table of sample users with:
  - **Username**
  - **Points**
  - **Badges**
  - **Average Score** (average of points and badges)
- Visualizes user engagement and gamification progress.

### 6. 🎖️ Points & Badges (User Profile)
- Shows **dummy data** of user's own points and badges.
- Can be extended to dynamically show real-time values per user via Firebase.
🖼️ Image Search & Visual Menu Personalization
Feature Description:

The Image Search feature lets users upload or search for food images and receive personalized recipe suggestions based on visual recognition. This brings AI-driven personalization to a whole new level using visual input instead of text.


### APK Link- https://drive.google.com/file/d/10gynMeFIetfBYzFSdeuLrnZ1-VoKnC6v/view?usp=sharing
