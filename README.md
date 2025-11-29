#  HỆ THỐNG AI PHÁT HIỆN ĐÁNH GIÁ GIẢ (FAKE REVIEW DETECTION)

##  Giới thiệu dự án
Dự án xây dựng hệ thống AI/Machine Learning giúp phát hiện đánh giá giả (spam review) trên nền tảng thương mại điện tử.  
Hệ thống gồm: tiền xử lý dữ liệu, khám phá dữ liệu (EDA), huấn luyện mô hình, đánh giá hiệu năng và thiết kế workflow chạy trên Orange.



##  Thành viên nhóm

| Họ & Tên | Vai trò |
|---------|---------|
| **Trương Kim Đăng** | Project Manager (PM) |
| **Huỳnh Hoàng Hải Yến** | Business Analyst (BA) |
| **Nguyễn Thị Thanh Thảo** | Data Engineer (DE) |
| **Nguyễn Hương Thủy** | Data Analyst (DA) |
| **Trần Thúy Hồng** | ML Engineer (MLE) |
| **Lã Nguyễn Yến Nhi** | Communication & Design Lead (CDL) |


## 📂 Cấu trúc file trong repository

```
Shopee- AI-Fake-Review/
│
├── README.md                         # File mô tả dự án
│
├── Data gop.xlsx                     # File dữ liệu đã gộp và làm sạch
├── metadata.csv                      # Metadata mô tả các trường dữ liệu
├── train.xlsx                        # Dataset training
├── test.csv                          # Dataset test
├── data (2).tgz                      # File nén toàn bộ dataset gốc
│
├── aiprojec final.ows                # File Orange: pipeline mô hình AI chạy toàn bộ
│                                     
│
├── dashboard/
│   ├── review_dashboard.pbix         # Dashboard Power BI thể hiện kết quả mô hình
│   └── dashbord.png                      # Ảnh, icons dùng cho dashboard 
│
│
│
├── ai_canvas.png                     # File AI Canvas mô tả toàn bộ dự án
│
├── report/
│   ├── bao_cao_lan_1.pdf             # Báo cáo tiến độ lần 1
│   ├── bao_cao_lan_2.pdf             # Báo cáo tiến độ lần 2
│   ├── final_report.pdf              # Báo cáo cuối kỳ hoàn chỉnh
│   ├── slides.pdf                       # Slide thuyết trình cuối kỳ
│                       
└── product/
    ├── bouncher_demo.png                # Files dùng trình bày sản phẩm demo

```


## Công nghệ sử dụng
- Orange Data Mining    
- Pandas, NumPy  
- Scikit-learn  
- TF–IDF Vectorizer  
- Logistic Regression, Random Forest  



## 🌐 Truyền thông nội bộ
https://www.notion.so/Project-AI-Nh-m-7-1ec94327b80e8044b030e4fa1ed28639?source=copy_link


## 📁 Repository dự án
https://github.com/dangtruong31231024981-spec/shopee-ai-fake-review


## 📊 Nội dung chính của đồ án
- Làm sạch dữ liệu văn bản tiếng Việt  
- Vector hóa bằng TF–IDF  
- Huấn luyện & so sánh mô hình LR và RF  
- Đánh giá mô hình bằng Precision, Recall, F1, AUC  
- Đề xuất dashboard hiển thị kết quả mô hình  
- Phân tích rủi ro dự án và đề xuất hướng phát triển


## 📝 Ghi chú
- Repo được tổ chức đầy đủ để tái lập quy trình mô hình  
- Dữ liệu được giữ nguyên từ bước thô đến bước xử lý  
- Tất cả file báo cáo, slide và mô hình được lưu theo thư mục riêng
