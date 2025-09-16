# 🧮 The NumPy Journey

Welcome to **The NumPy Journey**!  
This repository is my hands-on exploration of **NumPy** — Python’s powerful numerical computing library, widely used in **data science** and **machine learning**.

---

## 📚 What's Covered

### ✅ Phase 1: NumPy Basics
- Introduction to NumPy arrays  
- Array creation techniques  
- Indexing and slicing  
- Array attributes and data types  
- Basic array operations  

---

### ✅ Phase 2: Intermediate NumPy
- Array operations and broadcasting  
- Sorting arrays  
- Filtering with boolean masks  
- `np.where()` vs Fancy Indexing  
- Adding and removing elements  
- Array compatibility and reshaping  

---

### ✅ Phase 3: Advanced NumPy with Business Examples
- Vectorized string operations using `np.vectorize()`  
- Monthly average sales calculation  
- Zomato restaurant sales analysis using multi-dimensional arrays  
- Total sales per year using aggregation (`np.sum`)  
- Minimum sales per restaurant  
- Maximum sales per year  
- Average sales per restaurant  
- Cumulative sales using `np.cumsum`  
- Data visualization with Matplotlib (cumulative sales over years)  
- Vector arithmetic (addition, multiplication, dot product)  
- Calculating angle between two vectors using linear algebra  

---

### ✅ Phase 4: Images with NumPy
- Saving and loading `.npy` files (`np.save`, `np.load`)  
- Working with random arrays and zero arrays  
- Converting an image into a NumPy array (`matplotlib.image.imread`)  
- Saving images as `.npy` files for faster loading  
- Displaying images with Matplotlib  
- Creating **dark image effects** using NumPy operations (`1 - image_array`)  

---

### ✅ Phase 5: Background Removal Project 🖼️
In this mini-project, NumPy is combined with **image processing** techniques to remove the background of an image.  

- Load and process image as a NumPy array  
- Identify and separate foreground vs background pixels  
- Apply thresholding / masking with NumPy  
- Save the background-removed image  
- Visualize original vs processed image  

This showcases how **NumPy** can be leveraged for **real-world computer vision tasks**.  

---

## 📓 Tools Used
- 🐍 Python 3.x  
- 📓 Jupyter Notebook  
- 💡 NumPy  
- 📊 Matplotlib  

---

## 🚀 Getting Started

To run the notebooks locally:

```bash
# Clone the repository
git clone https://github.com/your-username/numpy-journey.git
cd numpy-journey

# Create and activate virtual environment (Windows)
python -m venv venv
venv\Scripts\activate

# Or (macOS/Linux)
# python3 -m venv venv
# source venv/bin/activate

# Install dependencies
pip install numpy matplotlib jupyter

# Launch Jupyter Notebook
jupyter notebook
