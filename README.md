# 📊 StackOverflow Language Trend Analyzer

A web application that visualizes **10 years of programming language popularity trends** using StackOverflow data — with dynamic multi-language selection, real-time graph updates, and interactive Chart.js visualizations.

---

## 🌐 Live Demo
> Open `frontend/index.html` in your browser to run locally.

---

## ✨ Features

- 📈 **10-Year Trend Visualization** — See how languages like Python, JavaScript, Java, and more grew or declined
- 🔀 **Multi-language Selection** — Compare multiple languages side by side in real time
- 📊 **Interactive Charts** — Powered by Chart.js with smooth animations
- 🔌 **Backend API** — Flask API serves historical trend data from CSV dataset
- 📱 **Responsive UI** — Works across devices

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Charts | Chart.js |
| Backend | Python, Flask |
| Data | StackOverflow CSV dataset |

---

## 🗂️ Project Structure

```
Stack-Overflow-Analysis/
│
├── frontend/
│   └── index.html        # Main UI with Chart.js visualizations
├── app.py                # Flask backend API
├── data.csv              # StackOverflow language trend dataset
└── requirements.txt      # Python dependencies
```

---

## 🚀 How to Run Locally

**1. Clone the repository**
```bash
git clone https://github.com/Rakshita-0206/Stack-Overflow-Analysis.git
cd Stack-Overflow-Analysis
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Run the Flask server**
```bash
python app.py
```

**4. Open in browser**
```
http://localhost:5000
```

---

## 📊 What the Data Shows

- Languages tracked: Python, JavaScript, Java, C#, PHP, TypeScript, C++, and more
- Time range: 2013 – 2023
- Data source: StackOverflow Developer Survey / Tags dataset
- Metric: Percentage of questions asked per language per year

---

## 🙋‍♀️ Author

**Rakshita K Biradar**
B.Tech Computer Science, Sitare University, Lucknow
📧 su-24110@sitare.org | [GitHub](https://github.com/Rakshita-0206) | [LinkedIn](www.linkedin.com/in/rakshita-k-biradar-a218ab324)

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
