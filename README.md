# 🤖 Shopee Fake Review Detection AI

## 📌 Tổng quan
Dự án **Shopee Fake Review Detection AI** được phát triển nhằm **phát hiện và phân loại các đánh giá giả trên Shopee**.  
Các đánh giá giả do bot hoặc tài khoản gian lận tạo ra có thể:
- Làm **nhầm lẫn người mua**
- Ảnh hưởng đến **người bán chân chính**
- Giảm **uy tín nền tảng thương mại điện tử**

Hệ thống sử dụng **Machine Learning (ML)** và **Xử lý ngôn ngữ tự nhiên (NLP)** để phân tích **văn bản review và metadata**, đánh giá mức độ tin cậy **gần như theo thời gian thực**.


## 👥 Thành viên nhóm
- **Trương Văn A** – Trưởng nhóm, quản lý dự án  
- **Nguyễn Thị B** – Backend & MLOps  
- **Lê Văn C** – Frontend & UI/UX  
- **Phạm Thị D** – Data Engineer & Tester  


## 🎯 Mục tiêu
- **Tăng độ tin cậy của đánh giá** → giúp người mua đưa ra quyết định chính xác.  
- **Bảo vệ người bán chân chính** → ngăn chặn cạnh tranh không lành mạnh từ review giả.  
- **Nâng cao hiệu quả vận hành** → giảm khối lượng kiểm duyệt thủ công.  
- **Hỗ trợ tăng trưởng kinh doanh** → cải thiện tỷ lệ chuyển đổi và doanh thu.


## 📂 Nội dung kho lưu trữ
- **Tiền xử lý dữ liệu:** Làm sạch, chuẩn hóa, tokenization, trích xuất đặc trưng (VnCoreNLP, TF-IDF, BoW).  
- **Mô hình AI:** Random Forest (chính), Logistic Regression, Naive Bayes.  
- **Huấn luyện & đánh giá:** Train/validation/test split, đo lường Accuracy, Precision, Recall, F1-score, AUC.  
- **Triển khai:** API (FastAPI/Flask), Docker, tích hợp dashboard hiển thị kết quả phân loại và cảnh báo.


## 🛠️ Công nghệ & công cụ
- **Ngôn ngữ:** Python  
- **Thư viện ML/NLP:** scikit-learn, PyTorch, TensorFlow, Hugging Face Transformers  
- **Tiền xử lý:** VnCoreNLP, TF-IDF, Bag of Words  
- **Triển khai:** Docker, FastAPI, AWS/Azure (tuỳ chọn)  



## 📊 Kết quả chính
- **Random Forest** đạt:  
  - Accuracy: **97.6%**  
  - Precision: **97.7%**  
  - Recall: **97.6%**  
  - AUC: **0.999**  
- **Kết quả kinh doanh:**  
  - ROI: **175% trong 3 năm**  
  - NPV: **+7.12 tỷ VND**  
  - IRR: **~82%**  
- **Tác động:**  
  - Giảm phản hồi tiêu cực ~35%  
  - Tăng tỷ lệ chuyển đổi ~12%  
  - Giảm chi phí kiểm duyệt 30–50%

