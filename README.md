# 🎮 SteamHub

**SteamHub** is a full-featured platform that simulates a digital game storefront similar to Steam. Users can browse, purchase, and manage games, trade in-game items, and interact with a points-based system. The project includes both a **WinUI 3 desktop application** and a **web version**. 🚀  

---

## ✨ Features

### User Features
- **🏠 Homepage**: Browse featured and trending games with interactive UI animations.  
- **🎮 Game Page**: View game details, add to cart or wishlist, and access developer info.  
- **🛒 Cart & Wishlist**: Manage purchases and saved games efficiently.  
- **💎 Point Shop**: Purchase in-game items using points.  
- **📦 Inventory & Marketplace**: View owned items, list items for sale, and trade with other players.  
- **🤝 Trading System**: Secure and user-friendly item trading with other users.  

### Developer Features
- **🛠 Developer Mode**: Approve or reject games submitted by developers.  
- **📝 Game Management**: Add, edit, or remove games and associated assets.  

### Technical Features
- **🏗 Architecture**: MVVM pattern for desktop, and MVC/MVVM-like structure for web version.  
- **🗄 Database**: Entity Framework Core with Code First migrations.  
- **⚙️ Backend**: Single **ASP.NET Core Web API** serving both desktop and web clients.  
- **💻 Frontend**:  
  - **Desktop**: WinUI 3 with responsive and interactive UI  
  - **Web**: HTML, CSS, JavaScript, with dynamic game pages and interactive features  
- **🖼 Assets**: Supports game images, in-game items, and other multimedia assets.  

---

## 🛠 Tech Stack
- **Frontend**: WinUI 3 (desktop), HTML/CSS/JavaScript (web)  
- **Backend**: ASP.NET Core Web API  
- **Database**: SQL Server, Entity Framework Core  
- **Architecture**: MVVM, Code First, Clean Architecture principles  

---

## ⚡ Installation

### Backend
1. Clone the repository:  
   ```bash
   git clone <repo-url>
   ```
2. Open the solution in **Visual Studio 2022** (or later) with **.NET 8 SDK** installed.  
3. Run the **Backend API project**.

### Desktop Version
1. Open and run the **WinUI 3 frontend project**.

### Web Version
1. Open the **web project** in a browser (or run via a local server).  
2. Connect it to the backend API for full functionality.

---

## 📡 API Endpoints (Examples)
- **GET /api/games**: Retrieve all games.  
- **GET /api/games/{id}**: Retrieve a specific game by ID.  
- **POST /api/cart**: Add a game to the user’s cart.  
- **GET /api/cart/{userId}**: Get the current user’s cart.  
- **POST /api/purchase**: Complete a purchase for items in the cart.  
- **POST /api/trade**: Initiate an item trade between users.  
- **GET /api/inventory/{userId}**: Retrieve all items owned by a user.  
- **POST /api/developer/games**: Submit a new game for approval (Developer mode).  

> **Note:** Endpoints are protected and require authentication where applicable.

---

## 🚀 Usage
- Browse and search for games.  
- Add games to cart or wishlist and make purchases.  
- Manage inventory and list items on the marketplace.  
- Enable developer mode for managing game submissions.  
- Trade items securely with other users.

---

## 🤗 Enjoy SteamHub!
SteamHub is a project built for fun, learning, and experimenting with modern full-stack development. Feel free to explore, test features, and maybe even contribute ideas!

