## 📊 Student Courses Network Visualization

This Jupyter Notebook presents a data visualization project focused on analyzing student course enrollments.  
It reads data from an Excel file containing multiple sheets, merges them into a single DataFrame, and constructs a **graph-based network** to visualize relationships between students and courses.

### 🔧 Key Features

- 📁 Loads and combines data from multiple Excel sheets.
- 🔎 Cleans and preprocesses the dataset by dropping irrelevant columns.
- 🌐 Uses **NetworkX** to build and render visual networks of course connections.
- 🇸🇦 Supports **Arabic text reshaping** and **right-to-left display** using `arabic_reshaper` and `bidi.algorithm` for clear labels and node names.
- 📈 Leverages **Matplotlib** for customized graph visualizations.

### 📦 Libraries Used

- `pandas` – for data manipulation  
- `networkx` – for creating and drawing network graphs  
- `matplotlib` – for visual representation  
- `arabic_reshaper` & `bidi` – for accurate Arabic text display in plots  

### 🖼 Example Use Case

Visualizing which students are enrolled in which courses or how certain courses are interconnected through student selections.  
This kind of network helps institutions identify course popularity, overlap, or student behavior patterns.

---

Feel free to explore the code, tweak the visualizations, or adapt it to your dataset!
