# User-Authentication-System

## Step 1: Initialize & Install Packages

### In VS Code terminal:
```
npm init -y

npm install express mongoose bcryptjs jsonwebtoken dotenv cors
```

## Project Structure

```
UserAuthSystem/
│
├── server.js
├── .env
├── package.json
├── /models
│   └── User.js
├── /routes
│   └── authRoutes.js
├── /public
│   ├── index.html
│   ├── login.html
│   ├── profile.html
│   └── style.css
└── /config
    └── db.js
```
## Run Project
```
node server.js
```

## Output:
```
✅ MongoDB Connected...
🚀 Server running on port 5000
```

## IMPORTANT

1. Compulsory you install the **mongo db** in you system
2. After to connect the database after to paste the chrome page --> ``` http://localhost:5000/ ```
        

