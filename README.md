# **Streamlit Application for Retail Insights**

## **Overview**  
This project is a Streamlit-based web application that provides retail insights and features:  
1. **Product Recommendation System** using Market Basket Analysis.  
2. **Customer Segmentation** based on RFM (Recency, Frequency, and Monetary) analysis.  
3. **Dashboard** to visualize key sales metrics and patterns.

---

## **Features**
- **Product Recommendation**:  
  Suggests related products based on customer purchase history using Market Basket Analysis.

- **Customer Segmentation**:  
  Performs RFM analysis to group customers into clusters for targeted marketing strategies.

- **Interactive Dashboard**:  
  Visualizes sales data by countries, products, and time periods using bar charts, pie charts, and other visual elements.

---

## **Technologies Used**
- **Programming Language**: Python  
- **Libraries**:  
  - Data Manipulation: Pandas, NumPy  
  - Visualizations: Streamlit, Plotly, Seaborn, Matplotlib  
  - Machine Learning: Scikit-learn, KMeans clustering  

---

## **Project Structure**
```
StreamlitApp/
│
├── streamlitapp.py         # Main application script
├── data/
│   ├── CleanRetailData.csv # Cleaned retail dataset
│   ├── item_sets.json      # Product association rules for recommendations
│
├── README.md               # Project description
├── requirements.txt        # Python dependencies
└── LICENSE                 # License information
```

---

## **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/StreamlitApp.git
   cd StreamlitApp
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place your datasets (`CleanRetailData.csv` and `item_sets.json`) in the `data/` folder.

4. Run the application:
   ```bash
   streamlit run streamlitapp.py
   ```

---

## **Application Workflow**
### **1. Product Recommendation System**
- Select a country and product to view associated recommendations based on purchase patterns.  

### **2. Customer Segmentation**
- Segment customers using RFM metrics and visualize clusters using KMeans.  

### **3. Dashboard**
- Analyze sales trends by:
  - Top-performing products and customers.
  - Sales distribution by countries, days, and months.

---

## **Future Enhancements**
- Integrate real-time data processing.  
- Add additional clustering and recommendation techniques.  
- Deploy the app on a cloud platform for public access.

--- 

This `README.md` provides a detailed description of the project for your GitHub repository. Let me know if you need any additional changes!
