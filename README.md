<a href="README.md">
  <img src="https://img.shields.io/badge/Language-English-blue?style=flat-square&logo=google-translate&logoColor=white" alt="English">
</a>
<a href="README-TR.md">
  <img src="https://img.shields.io/badge/Language-Türkçe-red?style=flat-square&logo=google-translate&logoColor=white" alt="Türkçe">
</a>

  <br />
  <br />

<div align="center">
  <img src="frontend/public/mascot.png" width="120" height="120" />
  <br />
  <br />

  <p>
     A web tool for querying and filtering players on FiveM servers.
  </p>

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

  <p>
    <a href="#warning">Warning</a> •
    <a href="#about">About</a> •
    <a href="#features">Features</a> •
    <a href="#tech">Tech</a> •
    <a href="#setup">Setup</a> •
    <a href="#gallery">Gallery</a> •
    <a href="#license">License</a>
  </p>

  <br />
  <br />
</div>

## <a id="warning"></a> ⚠️ Warning

This project was previously published as **Aether FiveM**. It has been renamed to **FiveM Query** to better describe what it does. As part of this change, the Aether logo was removed, the new logo is now used on the home screen and as the favicon, and the logo was removed from the navigation bar. The screenshots in the gallery still show the old name and logo.

## <a id="about"></a> 📋 About

**FiveM Query** is a web tool that lists every player connected to a FiveM server. Enter the server's `players.json` address and the tool pulls the live player list through its own backend. Each player is shown with their name, server ID and ping.

Click a player to see all of their identifiers, such as Steam, Discord, Rockstar license, Xbox Live and FiveM. You can filter the list by name, ID, Steam or Discord to quickly find the player you are looking for on crowded servers.

## <a id="features"></a> ✨ Features

- **Server query**: Enter a server's `players.json` address to fetch the live player list.
- **Player list**: See every player's name, server ID and ping. Ping is colored green, yellow or red depending on latency.
- **Player details**: Click a player to view their endpoint, ping and all identifiers, each with a color-coded label by type.
- **Combined filters**: Search by player name, ID, Steam ID and Discord ID at the same time, and clear all filters with one click.
- **Statistics**: See the total number of players, the number of players matching the filters and the average ping at a glance.
- **New query**: Clear the results and query another server without reloading the page.

## <a id="tech"></a> 🛠️ Tech

`React` · `Vite` · `Tailwind CSS` · `Node.js` · `Express`

## <a id="setup"></a> 🚀 Setup

### Requirements

- **Node.js**

### Step-by-Step Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/xkintaro/fivem-query.git
   cd fivem-query
   ```

2. **Install dependencies**

   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. **Start the backend server**

   ```bash
   cd backend
   node index.js
   ```

   The backend runs at `http://localhost:5000`.

4. **Start the development server**

   In a new terminal:

   ```bash
   cd frontend
   npm run dev
   ```

Open the app at [http://localhost:5173](http://localhost:5173) and enter a FiveM server address in the form `http://ip:port/players.json`.

## <a id="gallery"></a> 🖼️ Gallery

<img src="frontend/public/md/20260227203204299.jpg" width="100%" />

<img src="frontend/public/md/20260227203204081.jpg" width="100%" />

<img src="frontend/public/md/20260227203204191.jpg" width="100%" />

## <a id="license"></a> 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

#

<p align="center">
  <sub>❤️ Developed by "Mustafa TAŞAL" (kintaro)</sub>
</p>
