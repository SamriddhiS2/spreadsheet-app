# Web Spreadsheet Application  

This project is a web-based spreadsheet application that mimics Google Sheets' core functionalities, including mathematical operations, data quality checks, and UI interactions.  

## 🚀 Features  
✅ Google Sheets-like UI with toolbar and formula bar  
✅ Drag-and-drop functionality for cell content and formulas  
✅ Cell dependencies and automatic updates when changes occur  
✅ Mathematical functions: `SUM`, `AVERAGE`, `MAX`, `MIN`, `COUNT`  
✅ Data quality functions: `TRIM`, `UPPER`, `LOWER`, `REMOVE_DUPLICATES`, `FIND_AND_REPLACE`  
✅ Data validation to ensure correct data types  
✅ Ability to add, delete, and resize rows/columns  

## 🛠️ Tech Stack  
| Component  | Technology  |
|------------|------------|
| **Frontend**  | React.js, Tailwind CSS, Handsontable (optional) |
| **Backend (optional)**  | Node.js, Express.js |
| **Database (optional)**  | SQLite/PostgreSQL/MongoDB |
| **Deployment**  | Vercel/Netlify (Frontend), Render/Fly.io (Backend) |

## 📦 Installation & Setup  

1️⃣ **Clone the repository:**  
```sh
git clone https://github.com/yourusername/spreadsheet-app.git
cd spreadsheet-app
```

2️⃣ Install dependencies:
```sh
npm install
```

3️⃣ Run the application:
```sh
npm start
```

4️⃣ Open in browser:
Go to [http://localhost:3000](http://localhost:3000)

## 📂 Folder Structure
```bash
/spreadsheet-app
│── /src
│   ├── /components  # UI Components
│   ├── /utils       # Utility functions (math & data quality functions)
│   ├── App.js       # Main app file
│── README.md
│── package.json
│── .gitignore
```

## 🧪 Testing
```sh
# Run unit tests
npm test
```

## 🚀 Deployment
- Frontend: Deploy via Vercel (vercel deploy) or Netlify
- Backend: Deploy via Render or Fly.io (if needed)

## 🔒 Security & Performance Enhancements
- Input validation to prevent incorrect entries
- Optimized rendering for large datasets
- Secure API endpoints (if backend is implemented)

## 📌 GitHub Link
- 🔗 [GitHub Repository](https://github.com/SamriddhiS2/spreadsheet-app)
