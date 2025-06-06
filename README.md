# LeetCode Profile Tracker 🔎

This is a clean and responsive web app that lets you track LeetCode problem-solving stats for any user. Just enter a username and fetch their Easy, Medium, Hard, and Total solved problems — all with the help of LeetCode's GraphQL API and a proxy server.

## 🌐 Live Demo

Coming soon... (You can deploy it easily using GitHub Pages or Netlify!)

## 🚀 Features

- ✅ Fetch LeetCode stats using GraphQL
- ✅ Displays problems solved by difficulty
- ✅ Clean and modern UI
- ✅ No frameworks — pure HTML, CSS, JS
- ✅ Easy to deploy and customize

## 📸 Screenshot

![screenshot](assets/screenshot.png) *(add your own screenshot if needed)*

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- GraphQL (via LeetCode API)
- CORS handled via [cors-anywhere](https://cors-anywhere.herokuapp.com/)

## 🧩 How It Works

1. Input your LeetCode username.
2. The app sends a GraphQL POST request to `https://leetcode.com/graphql/`.
3. Uses `https://cors-anywhere.herokuapp.com/` as a proxy to bypass CORS.
4. Displays your total solved problems by difficulty level.

## ⚙️ Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/leetcode-profile-tracker.git
   cd leetcode-profile-tracker

