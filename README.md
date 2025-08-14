📦 Fetch and Display User Data from Public API
📌 Project Overview

This project demonstrates how to fetch data from a public API using the JavaScript Fetch API and display it dynamically on a webpage.
We use the free API:
🔗 https://jsonplaceholder.typicode.com/users

The webpage fetches user information (name, email, address) and displays it with a clean design.
A Reload button allows refetching the data, and proper error handling ensures smooth user experience.

🚀 Features

✅ Fetch data from a public API using Fetch API

✅ Display user Name, Email, and Address

✅ Handle network errors gracefully

✅ Reload button to refetch data without refreshing the page

✅ Responsive and clean CSS design

🛠️ Technologies Used

HTML5

CSS3

JavaScript (Fetch API)

📂 Project Structure
📁 fetch-user-data
 ┣ 📜 index.html      # HTML structure
 ┣ 📜 style.css       # Styling for the webpage
 ┣ 📜 script.js       # JavaScript fetch and display logic
 ┗ 📜 README.md       # Project documentation

📜 How It Works

HTML creates a container for the user list and a reload button.

JavaScript Fetch API requests JSON data from the API.

The data is parsed, looped, and displayed dynamically in the DOM.

CSS styles the displayed cards for better user experience.

A Reload button calls the fetch function again to get fresh data.

🔧 Installation & Setup

Follow these steps to run the project locally:

1️⃣ Clone the repository
git clone https://github.com/yourusername/fetch-user-data.git

2️⃣ Navigate into the folder
cd fetch-user-data

3️⃣ Open the project

Simply open index.html in your browser.
You can also use VS Code Live Server for better experience.



You can view the project live here:
🔗 Live Demo on GitHub Pages

📌 API Reference

We are using the JSONPlaceholder API:

https://jsonplaceholder.typicode.com/users


Sample Response:

[
  {
    "id": 1,
    "name": "Leanne Graham",
    "email": "Sincere@april.biz",
    "address": {
      "street": "Kulas Light",
      "suite": "Apt. 556",
      "city": "Gwenborough"
    }
  }
]

👨‍💻 Author

Sanjeet Kumar
💼 Software Developer | 🌐 Web Development Enthusiast
