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

[!IMPORTANT]

1. Compulsory you install the **mongo db** in you system

