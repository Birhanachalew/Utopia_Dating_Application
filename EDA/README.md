# EDA - Utopia Dating Application

## 💼 Made by Birhan Aschalew

### EDA is a culturally-focused dating site designed to help Ethiopians find meaningful connections leading to real marriage.

## 🎯 Project Goals

The main goal of EDA is to create a dating platform that prioritizes Ethiopian cultural values and traditions in the matching process. Unlike generic dating apps, EDA uses cultural compatibility and event-based matching to help users find partners who share similar backgrounds, beliefs, and life goals.

- **Cultural Value-Based Matching:**  
  Users provide information about their cultural background, values, and preferences. The matching algorithm prioritizes compatibility based on Ethiopian traditions, languages, and family values, ensuring that matches are more likely to lead to lasting relationships and marriage.

- **Event-Based Matching:**  
  EDA features community and cultural events (such as holidays, festivals, and gatherings) as part of the matching process. Users can connect based on shared interests in specific events, making it easier to meet like-minded individuals in real-life settings.

- **Real-Time Experience:**  
  The site works in real time, so updates and interactions happen instantly without needing to refresh the page.

- **Scalable & Modern:**  
  Built using Node.js, Express, React, Redux, and PostgreSQL, with Docker for easy setup, EDA is designed to support a large user base and provide a seamless experience.

## 📚 Technologies Used

| Node.js | HTML | React | Redux | PostgreSQL |
|---------|------|-------|-------|------------|
| Express | CSS  | JavaScript | Axios | Material UI |

## 📝 Features

- User registration and login with email verification
- Profile editing and photo uploads
- Search and filter for other users
- Like, visit, and match functionality
- Real-time chat and notifications (Socket.IO)
- Online status indicators
- Fame rating system
- Advanced search with filtering and sorting
- Block and report users

## ⚙️ Installation

**Prerequisites:**  
- [Docker](https://www.docker.com/) installed on your machine

**Steps:**
1. Clone the repository:
   ```bash
   git clone https://github.com/Birhanachalew/Utopia_Dating_Application.git
   ```
2. Create a `.env` file in the root directory:
   ```
   EMAIL_ADDRESS = <your email address>
   EMAIL_PASSWORD = <your email password>
   ```
3. Build and run the project:
   ```bash
   docker-compose up --build
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🖥️ How It Works

- **Redux Store** manages user state and notifications.
- **Socket.IO** enables real-time chat and instant notifications.
- **React Router** handles navigation.
- **Material UI** provides a modern interface.

### Registration & Sign-In

- Users register with email verification.
- Backend validates all input and stores encrypted passwords.
- Verification links are sent via email.

### User Profile

- Users complete their profile, including geolocation and tags.
- Upload up to 5 photos.
- Fame rating is calculated based on profile completeness, likes, matches, and tags.

### Browsing & Search

- Browse recommended profiles filtered by preferences and distance.
- Advanced search with pagination, sorting, and filtering.
- Block users to hide their profiles.

### Profile Viewing

- View other users’ profiles (excluding sensitive info).
- Online status is updated in real time.
- Report suspicious accounts.

### Chat

- Matched users can chat in real time.
- Messages are stored and retrieved per connection.
- Notifications for new messages and events.

### Notifications

- Receive notifications for likes, visits, messages, matches, and unlikes.
- Notifications are real-time and stored in the database.

## 🌍 How Cultural and Event-Based Matching Works

### Cultural Value-Based Matching

EDA places Ethiopian culture at the heart of its matching process. When users register, they provide details about their ethnicity, language, religion, family values, and other cultural preferences. The matching algorithm uses this information to prioritize connections between users who share similar backgrounds and beliefs, increasing the likelihood of meaningful, lasting relationships that can lead to real marriage.

### Event-Based Matching

Beyond profiles, EDA integrates Ethiopian community and cultural events—such as holidays, festivals, and gatherings—into the matching process. Users can express interest in specific events, and the platform helps connect people who plan to attend the same events or share enthusiasm for Ethiopian traditions. This makes it easier to meet like-minded individuals both online and in real-life settings.

