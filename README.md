# LeetCode Profile Tracker 🔎

This is a clean and responsive web app that lets you track LeetCode problem-solving stats for any user. Just enter a username and fetch their Easy, Medium, Hard, and Total solved problems — all with the help of LeetCode's GraphQL API and a proxy server.


## 🚀 Features

- ✅ Fetch LeetCode stats using GraphQL
- ✅ Displays problems solved by difficulty
- ✅ Clean and modern UI
- ✅ No frameworks — pure HTML, CSS, JS
- ✅ Easy to deploy and customize



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


