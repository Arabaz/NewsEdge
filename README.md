# NewsEdge
# 📰 Reader App – iOS News App with Offline Support & Bookmarks
 
An iOS news application built using **Swift** with **MVVM architecture**, **Core Data** for offline caching, and **bookmarking support**. The app fetches news from a public API and allows users to search articles, view details, and save favorites locally.
 
---
 
## 🚀 Features
 
- 🔍 **Search News Articles**
- 💾 **Offline Caching with Core Data**
- 📌 **Bookmark/Unbookmark News Articles**
- 🌗 **Dark/Light Mode Support**
- 📡 **Public API Integration**
- 🎯 **MVVM Architecture**
 
---
 
## 📱 Screenshots
 
| Home Screen | Search | Bookmarks |
|-------------|--------|-----------|
| __ | _HomeScreen.png_ | SearchScreen.png   | _BookmarksScreen.png_ | _NoBookmarks.png_
 
---
 
## 📦 Tech Stack
 
- **Language**: Swift
- **Architecture**: MVVM
- **Local Storage**: Core Data
- **Networking**: Alamofire
- **UI**: UIKit (or SwiftUI if applicable)
 
---
 
## 🧠 How It Works
 
1. On launch, the app fetches news articles from a public API.
2. All non-bookmarked articles are deleted from Core Data, and new ones are inserted.
3. Bookmarked articles are **preserved** even after data refresh.
4. Users can:
   - Search articles
   - Bookmark/unbookmark them
   - View bookmarks in a dedicated tab
 
---
 
## 🛠 Setup Instructions
 
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/reader-app-ios.git
   cd reader-app-ios


