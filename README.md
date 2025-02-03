🎵 Spotify Web Clone

📌 About the Project

This project is a simplified recreation of the Spotify Web Interface, developed during the Alura Front-end Dev Immersion. It features a clean UI with a functional search filter connected to a mock API (JSON-Server).

🚀 Features

✅ Functional Search Bar – Filters artists and playlists based on user input.
✅ Responsive Design – Works across different screen sizes with CSS Grid & Media Queries.
✅ Playlist & Artist Display – Dynamic content rendering using JavaScript & DOM Manipulation.

📂 Project Structure

📦 spotify-from-0
 ┣ 📂 assets/            # Stores images, icons, and other media files
 ┣ 📂 styles/            # Contains all CSS files for styling
 ┣ 📂 api-artists/       # JSON file simulating a backend API
 ┣ 📜 index.html         # Main structure of the web app
 ┣ 📜 script.js          # JavaScript logic for search & UI interactions
 ┗ 📜 README.md          # Project documentation

🛠️ Technologies Used

HTML5 – Structure of the web page
CSS3 – Styling with CSS Grid & Media Queries
JavaScript (ES6+) – Dynamic interactions & API fetching
JSON-Server – Simulated backend for artist data

🔧 Setup Instructions
1️⃣ Clone the repository


git clone https://github.com/LaisZagati/spotify-from-0.git

cd spotify-web-clone

2️⃣ Install JSON-Server

npm install -g json-server

3️⃣ Run the Mock API

json-server --watch api-artists/artists.json --port 5000

4️⃣ Open index.html in a browser and explore the app!

🎯 Future Improvements

Convert project to React for better componentization.

Implement Spotify API for real-time music data.


Let me know if you need any changes! 😊