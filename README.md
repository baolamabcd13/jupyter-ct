# Student Performance Data Analysis 📊

Phân tích dữ liệu kết quả học tập của học sinh bằng Python & Jupyter Notebook.  
Đây là đề tài cá nhân trong môn học **Kho Dữ Liệu và Khai Phá Dữ Liệu**.

---

## 📁 Mục lục

- [Giới thiệu](#giới-thiệu)
- [Hướng dẫn cài đặt](#🚀-hướng-dẫn-cài-đặt)
- [Chi tiết các bước thực hiện](#🔍-chi-tiết-các-bước-thực-hiện)
- [Sườn báo cáo đề tài](#📄-sườn-báo-cáo-đề-tài)
- [Tài liệu tham khảo](#📚-tài-liệu-tham-khảo)

---

## 📌 Giới thiệu

- **Tên đề tài**: Phân tích dữ liệu kết quả học tập học sinh
- **Nguồn dữ liệu**: Tập dữ liệu học sinh từ UCI hoặc Kaggle (gồm điểm học kỳ và các yếu tố ảnh hưởng)
- **Mục tiêu**:
  - Tiền xử lý, tổng hợp và trực quan hóa dữ liệu
  - Áp dụng các kỹ thuật khai phá dữ liệu như phân cụm, phân lớp
  - Đánh giá và so sánh mô hình bằng các phương pháp phổ biến

---

## 🚀 Hướng dẫn cài đặt

### 1. Clone từ GitHub

```bash
git clone https://github.com/baolamabcd13/jupyter-ct.git
cd jupyter-ct
```

### 2. Tạo môi trường ảo

```bash
python -m venv venv
source venv/bin/activate
```

### 3. Cài đặt thư viện

```bash
pip install -r requirements.txt
```

### 4. Chạy Notebook

```bash
jupyter notebook
```

---

## 🔍 Chi tiết các bước thực hiện

### Bước 1: Giới thiệu CSDL

- Trình bày nguồn gốc, nội dung của tập dữ liệu
- Số lượng bản ghi, số lượng thuộc tính
- Liệt kê tên thuộc tính, ý nghĩa, kiểu dữ liệu, số lượng giá trị thiếu và duy nhất

### Bước 2: Phân tích thống kê thủ công

- Tính toán descriptive statistics: min, max, mean, median, mode, five-number summary
- Trực quan hóa:
  - Boxplot, Histogram, Scatter Plot, QQ Plot cho các thuộc tính điểm (`G1`, `G2`, `G3`)
  - Vẽ lại biểu đồ sau khi nhóm theo thuộc tính danh nghĩa (`sex`, `studytime`,...)

### Bước 3: Đo lường tương đồng dữ liệu

- Tính ma trận tương quan giữa các biến số
- Tính độ đo cosine similarity cho 4 dòng dữ liệu dựa trên 4 thuộc tính (số, nhị phân, danh nghĩa, thứ tự)

### Bước 4: Tiền xử lý, tổng hợp và trực quan hóa

- Mã hóa các thuộc tính dạng chữ (Label Encoding)
- Chuẩn hóa dữ liệu (StandardScaler)
- Tổng hợp dữ liệu theo nhóm
- Vẽ biểu đồ nâng cao: heatmap, pie chart, bar chart, pairplot

### Bước 5: Khai thác dữ liệu

- Phân cụm học sinh theo điểm (`G1`, `G2`, `G3`) bằng KMeans
- Phân lớp giới tính bằng Decision Tree
- Đánh giá mô hình bằng các chỉ số:
  - Accuracy, Confusion Matrix
  - Đồ thị ROC Curve và AUC score

---

## 📄 Sườn Báo Cáo Đề Tài

### 1. Giới thiệu CSDL

- Mô tả dữ liệu, nguồn gốc, số lượng dòng & cột.
- Mô tả từng thuộc tính (kiểu, null, unique, thống kê).

### 2. Phân tích thống kê thủ công

- Boxplot, Histogram, QQ Plot, Scatter Plot.
- Nhóm theo danh nghĩa (giới tính...), vẽ lại biểu đồ.

### 3. Đo lường tương đồng

- Ma trận tương quan.
- Cosine Similarity (4 dòng, 4 thuộc tính).

### 4. Tiền xử lý, tổng hợp, trực quan hóa

- Mã hóa, chuẩn hóa, xử lý dữ liệu.
- Tổng hợp & vẽ biểu đồ nâng cao (bar, pie, heatmap...).

### 5. Khai thác dữ liệu

- Áp dụng ít nhất 2 phương pháp: phân cụm, phân lớp, khai phá luật.
- Đánh giá mô hình: accuracy, confusion matrix, ROC, silhouette...

### 6. Tài liệu tham khảo

- Ghi nguồn dữ liệu, thư viện sử dụng.

---

## 📚 Tài liệu tham khảo

- https://www.kaggle.com
- https://scikit-learn.org
- https://pandas.pydata.org
- https://seaborn.pydata.org
- https://matplotlib.org
