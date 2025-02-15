# CareerCV - Job Tracker  

**Still unemployed? Lost in job portals? Forgetting where you even applied?**  

_Say no more_  

CareerCV helps you streamline your job search by allowing you to:  
✅ **Apply** to jobs with just one click  
✅ **Schedule Interviews** seamlessly  
✅ **Track** every stage of your job applications effortlessly  

**Try it out now!** → [CareerCV](https://careercv.vercel.app)  

---

## 📜 Table of Contents

- [✨ Features](#-features)
- [🔧 Tech Stack](#-tech-stack)
- [🎯 How to Use](#-how-to-use)
- [🛠️ Installation (For Developers)](#%EF%B8%8F-installation-for-developers)
- [📁 Project Structure](#-project-structure)
- [🤝 Contributing](#-contributing)
- [⭐ Show Your Support](#-show-your-support)

---

## ✨ Features  

- **One-Click Applications** – Apply to jobs quickly without the hassle of navigating multiple portals or filling out repetitive forms  
- **Job Application Tracker** – Keep track of each and every stage of your job applications and never forget where you applied  
- **Interview Scheduling** – Easily schedule and manage your interviews in one place directly using your own Google Calendar, ensuring you never miss an important meeting  
- **Application Status** – Monitor whether your applications are active or inactive, so you know which opportunities are still open  
- **Phases of Application** – Applied, Interview Scheduled, Interviewed, Offer Letter Received  
- **City Tracking** – See the location (city) of each job you’ve applied to, helping you stay organized geographically  
- **Success Rate Estimation** – Get an estimate of your probability of getting selected based on applicant data, qualifications, and historical hiring trends  
- **Firebase Authentication** – Secure user verification to protect your data  
- **Interactive Sidebar Navigation** – Smooth sidebar for easy access to all features  
- **Simple and Lightweight** – Built with HTML, CSS, and Vanilla JavaScript for fast and efficient use  

💡 **Tip:** Don't forget to check out the interactive **sidebar** on the left!  

---

## 🔧 Tech Stack  

- **Frontend**: React.js, Material-UI, Axios  
- **Backend**: Node.js, Express.js, MongoDB, Passport.js (for authentication)  
- **Authentication**: Firebase Authentication & JWT  
- **Deployment**: [Vercel](https://careercv.vercel.app), Docker  

---

## 🎯 How to Use  

1. **Visit** → [CareerCV](https://careercv.vercel.app)  
2. **Sign up or log in** to start tracking your job applications  
3. **Apply to new job applications** and update their status easily  
4. **Explore the interactive sidebar** for smooth navigation  
5. **Schedule interviews** and manage everything in one place  
6. **Eureka!** Rock the interview, get the offer letter, and it's done!  

---

## 🛠️ Installation (For Developers)  

To run the project locally:  

### Clone the repository  
```bash
git clone https://github.com/techSaswata/careerCV-jobtracker.git
cd careerCV-jobtracker
```

### Backend Setup  
```bash
npm install
node server.js
```

### Frontend Setup  
```bash
cd client
npm install
npm start
```

Now, open `http://localhost:3000` in your browser to explore CareerCV locally.  

---

## 📁 Project Structure  

```
careerCV-jobtracker/
│
├── server.js                  --> Backend Express server (handles API routes, connects to MongoDB)
├── package.json               --> Node.js dependencies & scripts
├── public/                    -->frontend
│   ├── src/
│   │   ├── components/        --> Reusable UI pieces (forms, lists, cards)
│   │   ├── pages/             --> Main screens (Dashboard, Login, Profile)
│   │   ├── login.js             --> Main router - decides which page to show
│   │   └── index.js           --> React entry point that renders the app
│
├── config/                    --> Configuration central
│   ├── db.js                  --> MongoDB connection logic
│   └── passport.js            --> Authentication strategies using Passport.js
│
├── models/                    --> MongoDB models
│   ├── User.js                --> User schema (email, password hash, timestamps)
│   └── JobApplication.js      --> Job application schema (company, role, status, dates)
│
├── routes/                    --> All API endpoints
│   ├── auth.js                --> Handles login/registration routes
│   └── jobListings.js                --> CRUD operations for job applications
│
├── utils/                     --> Helper functions
│   └── StatusApp.js        --> Parses PDF resumes to extract skills/experience (if implemented)
│
├── .env.example               --> Template for environment variables
└── .gitignore                 --> Ignores unnecessary files in Git
```

---

## 🤝 Contributing  

Contributions are welcome! Feel free to fork the repo, make changes, and submit a pull request.  

---

## ⭐ Show Your Support  

If you like the project, don’t forget to ⭐ star the repository and leave feedback!  

---

Made with ❤️ by TechSd

