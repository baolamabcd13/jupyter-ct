# 🎓 Student Performance Data Analysis

Phân tích dữ liệu kết quả học tập của học sinh bằng Python & Jupyter Notebook.  
Đây là đề tài cá nhân trong môn học **Kho Dữ Liệu và Khai Phá Dữ Liệu** tại Đại học.

---

## 📁 Mục lục

- [Giới thiệu](#giới-thiệu)
- [Cài đặt & chạy Notebook](#cài-đặt--chạy-notebook)
- [Các bước thực hiện](#các-bước-thực-hiện)
- [Cấu trúc báo cáo](#cấu-trúc-báo-cáo)
- [Tài liệu tham khảo](#tài-liệu-tham-khảo)

---

## 📌 Giới thiệu

- **Tên đề tài**: Phân tích và khai thác dữ liệu kết quả học tập học sinh
- **Nguồn dữ liệu**: Student Performance Dataset (UCI hoặc Kaggle)
- **Mục tiêu đề tài**:
  - Tiền xử lý, thống kê, trực quan hóa dữ liệu
  - Áp dụng kỹ thuật khai phá: phân lớp, phân cụm, luật kết hợp
  - Đánh giá hiệu quả mô hình bằng các phương pháp phổ biến (ROC, Confusion Matrix,...)

---

## 🚀 Cài đặt & chạy Notebook

```bash
# Clone project
git clone https://github.com/baolamabcd13/jupyter-ct.git
cd jupyter-ct

# Tạo môi trường ảo
python -m venv venv
source venv/bin/activate

# Cài thư viện
pip install -r requirements.txt

# Mở Notebook
jupyter notebook
```

---

## 🔍 Các bước thực hiện

### 1. Giới thiệu và khảo sát dữ liệu

- Nguồn gốc, số lượng dòng & cột
- Mô tả chi tiết từng thuộc tính: kiểu dữ liệu, null, unique

### 2. Phân tích thống kê thủ công

- Tính toán các giá trị thống kê (min, max, mean, median, mode, five-number summary)
- Vẽ biểu đồ: Boxplot, Histogram, QQ Plot, Scatter Plot
- Nhóm theo thuộc tính danh nghĩa (`sex`, `internet`,...) và trực quan hóa lại

### 3. Đo lường tương đồng dữ liệu

- Ma trận tương quan (Heatmap)
- Cosine Similarity giữa 4 dòng dữ liệu chọn mẫu

### 4. Tiền xử lý, tổng hợp và trực quan hóa

- Mã hóa biến danh nghĩa (One-Hot Encoding)
- Chuẩn hóa dữ liệu (StandardScaler)
- Tổng hợp dữ liệu theo nhóm (`groupby`)
- Trực quan hóa nâng cao: pairplot, heatmap, bar chart,...

### 5. Khai phá dữ liệu

- 🧠 **Luật kết hợp**: sử dụng Apriori + phân tích lift, confidence
- 🔍 **Phân lớp**: Random Forest + ROC Curve + classification report
- 🔵 **Phân cụm**: KMeans kết hợp PCA → trực quan kết quả phân cụm

---

## 📄 Cấu trúc báo cáo

1. **Giới thiệu tập dữ liệu**
2. **Phân tích thống kê thủ công**
3. **Đo lường tương đồng & khác biệt**
4. **Tiền xử lý, tổng hợp và trực quan hóa**
5. **Khai phá dữ liệu**
6. **Kết luận & đề xuất**
7. **Tài liệu tham khảo**

---

## 📚 Tài liệu tham khảo

- [https://www.kaggle.com](https://www.kaggle.com)
- [https://scikit-learn.org](https://scikit-learn.org)
- [https://pandas.pydata.org](https://pandas.pydata.org)
- [https://seaborn.pydata.org](https://seaborn.pydata.org)
- [https://matplotlib.org](https://matplotlib.org)
