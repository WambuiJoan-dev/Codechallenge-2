# Bots App

## Overview
The **Bots App** is a React-based application that allows users to view a collection of bots, sort and filter them, and enlist bots into their personal army. Users can also discharge bots by deleting them from the backend.

## Features
- Fetches bots from an API (`https://bots-si0g.onrender.com/bots`).
- Users can enlist bots into their personal army (one per class).
- Sort bots by **Health**, **Damage**, or **Armor**.
- Filter bots based on **Class** (Support, Medic, Assault, etc.).
- Discharge bots to remove them permanently from the database.

## Technologies Used
- **React** (useState, useEffect)
- **JavaScript (ES6+)**
- **CSS** (for styling)
- **Fetch API** (for API requests)

## Installation
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/WambuiJoan-dev/bottapp.git
   cd bottapp
   ```
2. **Install Dependencies:**
   ```sh
   npm install
   ```
3. **Start the Development Server:**
   ```sh
   npm start
   ```
4. **Access the Application:**
   Open `http://localhost:3000/` in your browser.

## Project Structure
```
📁 bottapp
├── 📁 src
│   ├── 📄 App.jsx
│   ├── 📄 BotCollection.jsx
│   ├── 📄 YourBotArmy.jsx
│   ├── 📄 SortBar.jsx
│   ├── 📄 BotCard.jsx
│   ├── 📁 assets
│   ├── 📁 styles
│   ├── 📄 index.css
│   ├── 📄 main.jsx
├── 📄 package.json
├── 📄 vite.config.js
├── 📄 README.md
```

## API Endpoints
- **GET** `/bots` - Fetch all bots.
- **DELETE** `/bots/:id` - Remove a bot permanently.

## How to Use
1. **View Bots Collection** - The homepage lists all available bots.
2. **Sort and Filter** - Use the dropdowns to sort or filter bots by class.
3. **Enlist a Bot** - Click on a bot to add it to your army (only one bot per class is allowed).
4. **Discharge a Bot** - Click the "x" button to remove a bot permanently.
5. **Release a Bot** - Removes a bot from your army but does not delete it.

## Deployment
To deploy the project to GitHub Pages:
```sh
npm run build
npm install -g gh-pages
npm run deploy
```

## Author
- **Wambui Joan**

## License
This project is open-source under the **MIT License**.

