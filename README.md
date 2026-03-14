# 🍽️ Zomato Data Analysis Project

A comprehensive exploratory data analysis (EDA) of Zomato restaurant data using Python. This project uncovers key insights about restaurant types, customer preferences, ratings, and ordering patterns.

---

## 📁 Project Structure

```
zomato-data-analysis/
│
├── Zomato_Data_Analysis_Project.ipynb   # Main Jupyter/Colab notebook
├── Zomato_data.csv                      # Dataset
├── requirements.txt                     # Python dependencies
└── README.md                            # Project documentation
```

---

## 📊 Dataset Overview

The dataset contains **148 restaurant records** with the following columns:

| Column | Description |
|---|---|
| `name` | Name of the restaurant |
| `online_order` | Whether online ordering is available (Yes/No) |
| `book_table` | Whether table booking is available (Yes/No) |
| `rate` | Customer rating (out of 5) |
| `votes` | Number of votes received |
| `approx_cost(for two people)` | Approximate cost for two people (₹) |
| `listed_in(type)` | Type/category of restaurant |

---

## 🔍 Key Analyses Performed

1. **Type of Restaurants** — Distribution of restaurant categories (Buffet, Cafes, Dining, Other)
2. **Votes by Restaurant Type** — Which category receives the most customer engagement
3. **Rating Distribution** — Frequency of ratings across all restaurants
4. **Avg Spending by Couples** — Most preferred price range for two people
5. **Online vs Offline Order Ratings** — Box plot comparison of ratings by order mode
6. **Heatmap Analysis** — Relationship between restaurant type and online ordering availability

---

## 📌 Key Findings

- 🍽️ **Majority of restaurants** fall under the **Dining** category
- 👍 **Dining restaurants** receive the **maximum votes**
- ⭐ **Most restaurants** are rated between **3.5 and 4.0**
- 💑 **Couples prefer** restaurants with an approximate cost of **₹300**
- 📱 **Online orders** receive **higher ratings** compared to offline orders
- 📊 **Dining restaurants** overwhelmingly prefer accepting **online orders** (77 vs 33)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- pip

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/zomato-data-analysis.git
   cd zomato-data-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook Zomato_Data_Analysis_Project.ipynb
   ```

   Or open directly in **Google Colab** by uploading the `.ipynb` file.

---

## 🛠️ Technologies Used

- **Python 3** — Core programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical data visualization
- **Jupyter Notebook / Google Colab** — Interactive development environment

---

## 📷 Visualizations

The project includes the following plots:

- Count plot of restaurant types
- Line plot of total votes by restaurant type
- Histogram of restaurant ratings
- Count plot of approximate cost for two people
- Box plot of ratings by online vs offline order mode
- Heatmap of restaurant type vs online order availability

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
