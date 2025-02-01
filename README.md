# MERN Stack Social Media App

## 📌 Project Overview
This is a full-stack social media application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to create accounts, post content, interact with other users through likes and comments, and manage their profiles.

## 🚀 Features
- User authentication (signup/login/logout)
- Create, edit, and delete posts
- Like and comment on posts
- User profile management (update avatar, bio, etc.)
- Follow and unfollow other users
- Real-time notifications
- Responsive UI with modern design

## 🏗️ Tech Stack
- **Frontend:** React.js, Redux, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose)
- **Authentication:** JWT (JSON Web Token)

## 📂 Project Structure
```
|-- social-media-app
    |-- client/               # Frontend React application
    |-- server/               # Backend Express.js application
    |-- models/               # Mongoose schemas
    |-- routes/               # API endpoints
    |-- controllers/          # Business logic for API
    |-- middleware/           # Authentication and error handling
    |-- public/               # Static files
    |-- .env                  # Environment variables
```

## 🔧 Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/social-media-app.git
   cd social-media-app
   ```
2. **Install dependencies:**
   ```sh
   cd server
   npm install
   cd ../client
   npm install
   ```
3. **Setup environment variables:**
   - Create a `.env` file in the `server` directory and add:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```
4. **Run the application:**
   ```sh
   cd server
   npm start
   ```
   In another terminal:
   ```sh
   cd client
   npm start
   ```

## 🎯 Usage
### 1️⃣ Create an Account & Login
- Sign up with an email and password
- Login to access features

### 2️⃣ Create a Post
- Upload images and write captions
- View and interact with posts in the feed

### 3️⃣ Like & Comment
- Like posts from other users
- Add and delete comments

### 4️⃣ Profile Management
- Update user bio, profile picture, and personal details

## 📊 Future Enhancements
- Direct messaging feature
- Story feature (similar to Instagram)
- Dark mode support

## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Feel free to fork the repository and submit pull requests for improvements or new features.

## 📧 Contact
For questions or collaborations, reach out at thakur.abhisheksinght97@gmail.com.

