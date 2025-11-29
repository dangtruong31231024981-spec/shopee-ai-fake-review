#  Hệ thống AI đánh giá độ tin cậy của đánh giá người dùng của Shoppe

## 📌 Tổng quan
Dự án **Shopee Fake Review Detection AI** được phát triển nhằm **phát hiện và phân loại các đánh giá giả trên Shopee**.  
Các đánh giá giả do bot hoặc tài khoản gian lận tạo ra có thể:
- Làm **nhầm lẫn người mua**
- Ảnh hưởng đến **người bán chân chính**
- Giảm **uy tín nền tảng thương mại điện tử**

Hệ thống sử dụng **Machine Learning (ML)** và **Xử lý ngôn ngữ tự nhiên (NLP)** để phân tích **văn bản review và metadata**, đánh giá mức độ tin cậy **gần như theo thời gian thực**.


## 👥 Thành viên nhóm
- **Trương Kim Đăng** – Project Manager (PM)
- **Huỳnh Hoàng Hải Yến** – Business Analyst (BA)
- **Nguyễn Thị Thanh Thảo** – Data Engineer (DE)
- **Nguyễn Hương Thủy** – Data Analyst (DA) 
- **Trần Thúy Hồng** – ML Engineer (MLE)
- **Lã Nguyễn Yến Nhi** – Communication & Design Lead (CDL)

## 🎯 Mục tiêu
- **Tăng độ tin cậy của đánh giá** → giúp người mua đưa ra quyết định chính xác.  
- **Bảo vệ người bán chân chính** → ngăn chặn cạnh tranh không lành mạnh từ review giả.  
- **Nâng cao hiệu quả vận hành** → giảm khối lượng kiểm duyệt thủ công.  
- **Hỗ trợ tăng trưởng kinh doanh** → cải thiện tỷ lệ chuyển đổi và doanh thu.


## 📂 Nội dung kho lưu trữ
- **Tiền xử lý dữ liệu:** Làm sạch, chuẩn hóa, tokenization, trích xuất đặc trưng (VnCoreNLP, TF-IDF, BoW).  
- **Mô hình AI:** Random Forest (chính), Logistic Regression
- **Huấn luyện & đánh giá:** Train/validation/test split, đo lường Accuracy, Precision, Recall, F1-score, AUC  
- **Triển khai:** API (FastAPI/Flask), Docker, tích hợp dashboard hiển thị kết quả phân loại và cảnh báo


## 🛠️ Công nghệ & công cụ
- **Công cụ:** Orange, Power BI
- **Ngôn ngữ:** Python
- **Thư viện ML/NLP:** scikit-learn, PyTorch, TensorFlow, Hugging Face Transformers  
- **Tiền xử lý:** VnCoreNLP, TF-IDF, Bag of Words  
- **Triển khai:** Docker, FastAPI, AWS/Azure (tuỳ chọn)  



## 📦 Nguồn dữ liệu

Dự án sử dụng bộ dữ liệu **ViSpamReviews** cho nhiệm vụ phát hiện đánh giá spam trên các sàn thương mại điện tử Việt Nam.  
Dataset được xây dựng và công bố cho mục đích nghiên cứu, với quy trình gán nhãn nghiêm ngặt để phân loại:

- **Nhiệm vụ nhị phân:** Phân loại review thành **spam** hoặc **không spam**.  
- **Nhiệm vụ đa lớp:** Xác định loại spam (spam nhẹ, spam quảng cáo mạnh, v.v.).

### 📂 Các baseline đi kèm dataset
- **Deep Neural Models (DNN):** TextCNN, BiLSTM, GRU  
- **Transformers:** PhoBERT, BERT4News  
- **Sentence-BERT:** embedding cho mô tả sản phẩm  

### 🔗 Nguồn tham khảo
- Kaggle Inference: [ViSpamReviews Inference](https://www.kaggle.com/cinhvn/pt-vispamreviews-inference)  
- Publication (Version 1): [https://arxiv.org/abs/2207.14636](https://arxiv.org/abs/2207.14636)  
- Publication (Version 2 – Metadata Integration): [https://arxiv.org/abs/2405.13292](https://arxiv.org/abs/2405.13292)  

### 📖 Trích dẫn
```python
@InProceedings{10.1007/978-3-031-21743-2_48,
  author    = {Van Dinh, Co and Luu, Son T. and Nguyen, Anh Gia-Tuan},
  editor    = {Nguyen, Ngoc Thanh and Tran, Tien Khoa and Tukayev, Ualsher and Hong, Tzung-Pei and Trawi{\'{n}}ski, Bogdan and Szczerbicki, Edward},
  title     = {Detecting Spam Reviews on Vietnamese E-Commerce Websites},
  booktitle = {Intelligent Information and Database Systems},
  year      = {2022},
  publisher = {Springer International Publishing},
  address   = {Cham},
  pages     = {595--607},
  isbn      = {978-3-031-21743-2}
}
```
