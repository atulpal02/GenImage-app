GenImage - text to image generator
React Vite TailwindCSS Express.js

GitHub stars GitHub forks GitHub issues

✨ Features
🚀 Fast Processing: Optimized for performance
📱 Responsive Design: Works on all devices
🔒 Secure Processing: Your images stay private
💡 AI: AI-powered Images
🚀 Quick Start
Prerequisites
Node.js (v18 or higher)
npm (v9 or higher)
Git
1. Clone the Repository
git clone https://github.com/singh04ayush/imagify.git
cd imagify
2. Backend Setup
# Navigate to server directory
cd server

# Install dependencies
npm install

# Create .env file in the server directory
touch .env

# Add the following environment variables to .env:
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLIPDROP_API=your_clipdrop_api_key

# Start the server
npm run server
Backend Environment Variables Explanation
Variable	Description	Example
PORT	Server port number	5000
MONGODB_URI	MongoDB connection string	mongodb+srv://username:password@cluster.mongodb.net/imagify
JWT_SECRET	Secret key for JWT authentication	your-secret-key-here
CLIPDROP_API	API key for ClipDrop image generation	your-clipdrop-api-key
3. Frontend Setup
# Open a new terminal
# Navigate to client directory
cd client

# Install dependencies
npm install

# If vite not installed
npm install vite@latest

# Create .env file in the client directory
touch .env

# Add the following environment variable to .env:
VITE_BACKEND_URL=http://localhost:5000

# Start the development server
npm run dev
Frontend Environment Variables Explanation
Variable	Description	Example
VITE_BACKEND_URL	Backend API URL	http://localhost:5000
4. Access the Application
Frontend: http://localhost:5173
Backend API: http://localhost:5000
Important Notes:

Never commit your .env files to version control
Make sure to replace the example values with your actual configuration
The CLIPDROP_API key can be obtained from ClipDrop API
Keep your JWT_SECRET secure and use a strong random string
Development Scripts
Command	Description
npm run server	Starts backend
npm run dev	Starts frontend
Environment Variables
Variable	Description	Default
PORT	Server port	5000
MONGODB_URI	MongoDB connection string	-
JWT_SECRET	JWT secret key	-
🛠️ Tech Stack
Frontend
React Vite TailwindCSS

Backend
Node.js Express MongoDB

🤝 Contributing
We welcome contributions! Here's how you can help:

PRs Welcome Open Source Love

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
📝 License
License: MIT

This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgment
Resource	Description
Heroicons	Beautiful icons
TailwindCSS	Utility-first CSS framework
React Community	Amazing React ecosystem
