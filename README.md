Shortify 🚀
A Smart URL Shortener with Advanced Analytics

📌 Overview
Shortify is a powerful URL shortening service that allows users to create short links and track analytics in real time. It provides detailed insights into link usage, including the number of clicks and individual user interactions. The platform also features user authentication with login and signup functionality for a personalized experience.

🔥 Features
✅ Shorten Links – Instantly generate short URLs.
✅ Analytics Dashboard – Track how many times a link is clicked.
✅ User Tracking – Monitor link clicks per user.
✅ User Authentication – Secure login/signup functionality.
✅ Modern UI – Built with React for a smooth experience.
✅ Fast & Scalable – Backend powered by Spring Boot.

🛠️ Tech Stack
Technology	Purpose
Spring Boot	Backend API
ReactJS	Frontend UI
MySQL/PostgreSQL	Database for storing links & analytics
JWT Authentication	Secure user authentication
Spring Security	Authorization & authentication
React Router	Frontend navigation
Axios	API communication
📂 Project Structure
Shortify/ │── backend/ # Spring Boot backend │ ├── src/main/java/ # Java source code │ ├── src/main/resources/ # Config files │ ├── pom.xml # Maven dependencies │── frontend/ # ReactJS frontend │ ├── src/ # React source code │ ├── package.json # React dependencies │── README.md # Project documentation

🚀 API Endpoints Method Endpoint Description Auth Required POST /api/auth/signup User registration ❌ POST /api/auth/login User login ❌ POST /api/shorten Shorten a link ✅ GET /api/links/{id} Get analytics for a link ✅ GET /api/links/click/{shortUrl} Redirect & track clicks ❌

📊 Analytics & Tracking Shortify records every link click along with:

Total clicks Unique users IP Address & User Agent Referrer (source website) 🎯 Future Enhancements 🔹 QR code generation for each short link. 🔹 Advanced analytics (country, device type). 🔹 Admin panel to manage links. 🔹 Dark mode UI.

🤝 Contributing Contributions are welcome! Follow these steps:

Fork the repository. Create a new branch (feature-branch). Commit your changes (git commit -m "Add new feature"). Push to your fork (git push origin feature-branch). Submit a Pull Request! 📜 License This project is licensed under the MIT License.

