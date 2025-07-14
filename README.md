# 🛒 Grocery List React App

A simple and interactive grocery list application built with **React**. Users can add, search, check off, and delete grocery items. The list is stored in the browser's `localStorage`, so it persists across sessions.

## 🔗 Live Demo

➡️ [View Live on Netlify](https://admirable-beijinho-4e4a46.netlify.app)

---

## ✨ Features

- ✅ Add new items to the list
- 🔍 Real-time search filter
- 🗑️ Delete items from the list
- ✔️ Mark items as checked/unchecked
- 💾 Persists data using `localStorage`
- 📦 Built with React (using hooks like `useState`)

---

## 📂 Folder Structure

    Grocery-List/
    ├── public/ # Static assets
    ├── src/ # React components
    │ ├── App.js # Main app component
    │ ├── Header.js
    │ ├── Footer.js
    │ ├── Content.js
    │ ├── AddItem.js
    │ ├── SearchItem.js
    │ ├── LineItem.js
    │ └── ItemList.js
    ├── .gitignore
    ├── package.json
    └── README.md


---

## 🚀 How to Run Locally

1. **Clone the repository**
   
       git clone https://github.com/rnccsstudent/Grocery-List.git
       cd Grocery-List
   
2. Install dependencies

       npm install
   
3. Start development server

       npm run start
   If you're using WSL or have file watching issues, use:

       CHOKIDAR_USEPOLLING=true && npm start
   
4. Open *http://localhost:3000* in your browser.

---

### 🏗️ Build for Production

   installed the CLI first:

    npm install -g netlify-cli
    
  Then create an optimized build/ folder ready for deployment (e.g., Netlify, GitHub Pages, etc.).
  
    npm run build

  🌐 Deploy to Netlify

    netlify deploy --dir=build --prod
---

### 📜 License

    This project is open source and available under the MIT License.

---

### 🙋‍♂️ Author

- Pranab Mahata
- [GitHub](https://github.com/rnccsstudent)

---

### (Optional) 🛠️ Project Setup (Using create-react-app)

To create a similar app from scratch, you can use:

    npx create-react-app grocery-list
    cd grocery-list

Then start adding your components in the src folder.

### 💬 Feedback

      If you find a bug or want to suggest a feature, feel free to open an issue or a pull request.

---
