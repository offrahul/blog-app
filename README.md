# blog-app
📸 Vlog App
A full-stack Vlog App built using the MVC architecture with authentication. Users can create, edit, and manage vlogs securely.

🚀 Features
✅ User Authentication (Login, Signup, JWT)

✅ MVC Architecture Implementation

✅ Create, Read, Update, Delete (CRUD) Vlogs

✅ Secure API with JWT-based Authentication

✅ Responsive & Interactive UI

🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript (React if applicable)

Backend: Node.js, Express.js

Database: MongoDB/MySQL

Authentication: JWT (JSON Web Token)

Version Control: Git & GitHub

📂 Project Structure (MVC)
plaintext
Copy
Edit
/vlog-app  
 ├── /frontend    # Frontend files  
 ├── /backend     # Backend logic (Express, API routes)  
 │   ├── /controllers    # Business logic  
 │   ├── /models         # Database models  
 │   ├── /routes         # API Routes  
 │   ├── /middleware     # Auth & validation  
 ├── package.json  
 ├── README.md  
🛠️ Installation & Setup
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/yourusername/vlog-app.git
cd vlog-app
2️⃣ Install Dependencies
sh
Copy
Edit
npm install
3️⃣ Set Up Environment Variables (.env)
Create a .env file and add the following:

plaintext
Copy
Edit
PORT=5000  
MONGO_URI=your_mongodb_connection  
JWT_SECRET=your_jwt_secret
4️⃣ Start the App
sh
Copy
Edit
npm run dev
📌 The backend runs on http://localhost:5000/

🛡️ Authentication
Users need to sign up and log in to manage their vlogs.

JWT tokens are used for securing API routes.

📌 API Routes
Method	Route	Description	Auth Required
POST	/auth/signup	Register new user	❌ No
POST	/auth/login	User login & JWT token	❌ No
GET	/vlogs	Fetch all vlogs	✅ Yes
POST	/vlogs	Create a vlog	✅ Yes
PUT	/vlogs/:id	Update a vlog	✅ Yes
DELETE	/vlogs/:id	Delete a vlog	✅ Yes
🚀 Deployment
The app is deployed on:
🔗 Frontend: Vercel/Netlify Link
🔗 Backend: Render/Vercel Link

👨‍💻 Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

📜 License
This project is licensed under the MIT License.
https://github.com/offrahul/blog-app/issues/1#issue-2970206723
