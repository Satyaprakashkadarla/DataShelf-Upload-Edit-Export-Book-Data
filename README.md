# DataShelf-Upload-Edit-Export-Book-Data
# 📚 CSV Book Editor Web App

This is a web-based CSV editor that allows users to upload, view, edit, filter, and download large CSV files (≈10,000+ rows) of book data. Built entirely using **HTML**, **CSS**, and **Vanilla JavaScript**, this app runs entirely in the browser—no backend or framework required.

---

## 🔧 Features

### ✅ Core Features
- 📤 **Upload CSV**: Upload a large CSV file containing book data (~10,000+ rows).
- 👁️ **View Data**: Display the records in a scrollable, responsive table.
- ✏️ **Edit Data**: Click and edit cells directly in the browser.
- 🔍 **Filter/Search**: Filter records by any column (e.g., Author, Genre).
- 📥 **Download CSV**: Export the edited data back to a CSV file.

### 🌟 Bonus Features
- 🔄 **Reset All Edits**: Revert the table to the original uploaded data.
- ✨ **Highlight Modified Cells**: Visually mark changed cells or rows.
- ↕️ **Column Sorting**: Sort the table by Title, Author, Year, etc.
- 📊 **Row Count & Loading Feedback**: Show how many rows are displayed, loading status.
- 📱 **Responsive Layout**: Mobile and tablet-friendly design.

---

## 📁 Sample CSV Format

The uploaded file should be in the following format:

```
Title,Author,Genre,PublishedYear,ISBN
```

You can use a real dataset or generate a fake one using tools like [Faker.js](https://github.com/faker-js/faker), Excel, or online CSV generators.

---

## 🛠️ Tech Stack

- **HTML**: Markup structure for the app.
- **CSS**: Responsive and clean layout styles.
- **JavaScript**: Core logic for CSV handling, filtering, editing, and downloading.
- **PapaParse**: For efficient CSV parsing and generation in the browser.

---

## 🚀 How to Run the App

1. **Clone or Download the Repository**

```bash
git clone https://github.com/your-username/csv-book-editor.git
cd csv-book-editor
```

2. **Open `index.html` in your browser**

You can double-click `index.html` or open it using a local server (e.g., Live Server extension in VS Code).

No build steps or installations are needed — everything runs in the browser.

---

## 📸 Screenshots

### 🖼️ Uploading a CSV File
<img width="1909" height="1051" alt="Screenshot 2025-09-24 191355" src="https://github.com/user-attachments/assets/ff6b8b41-2f2d-4d7e-88ee-0ae55e9b7758" />


### 📊 Viewing 10,000+ Rows in Table
<img width="1919" height="1061" alt="Screenshot 2025-09-24 191406" src="https://github.com/user-attachments/assets/01ef96fe-b24f-4676-8c3f-2530d70bca5b" />


### ✏️ Editing Book Data Inline
<img width="1912" height="1060" alt="Screenshot 2025-09-24 191430" src="https://github.com/user-attachments/assets/46fa016b-1648-43f2-a06d-7c54dcf6a746" />


### 🔍 Filtering Records by Author
<img width="1907" height="936" alt="Screenshot 2025-09-24 191507" src="https://github.com/user-attachments/assets/5e5964a6-7158-4dad-b3fe-2f3089bbea6e" />


### 📱 Responsive Layout on Mobile
<img width="1060" height="933" alt="Screenshot 2025-09-24 192444" src="https://github.com/user-attachments/assets/fedd21bb-eb47-4d80-be85-f5abd405ca0b" />



---

## 📂 Folder Structure

```
csv-book-editor/
│
├── index.html          # Main HTML file
├── style.css           # Styling
├── script.js           # Main JavaScript logic
├── sample.csv          # (Optional) Sample CSV file
└── README.md           # Project documentation
```

---

## 📌 Possible Improvements

- Pagination for very large files
- Undo/Redo functionality
- Column resizing
- Backend CSV storage (optional)

---

## 🤝 Contributing

Feel free to fork the project, improve it, and submit a pull request. Contributions are welcome!

---



---

## 🙋‍♂️ Author

- **SatyaPrakashkadarla**
- [LinkedIn](https://www.linkedin.com/in/satyaprakashkadarla/)
