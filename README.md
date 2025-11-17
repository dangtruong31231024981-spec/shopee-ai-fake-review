# Hệ thống AI phát hiện đánh giá giả trên Shopee

## Tổng quan
Dự án **Shopee Fake Review Detection AI** được phát triển để **phát hiện và phân loại các đánh giá giả trên Shopee**. Các đánh giá giả do bot hoặc tài khoản gian lận tạo ra có thể làm **nhầm lẫn người mua, ảnh hưởng đến người bán chân chính và giảm uy tín nền tảng**.

Hệ thống sử dụng **học máy (ML) và xử lý ngôn ngữ tự nhiên (NLP)** để phân tích **văn bản review và metadata** nhằm đánh giá mức độ tin cậy, hầu hết **theo thời gian thực**.

## Mục tiêu
- **Tăng độ tin cậy của đánh giá:** Giúp người mua đưa ra quyết định chính xác.  
- **Bảo vệ người bán chân chính:** Ngăn chặn cạnh tranh không lành mạnh từ review giả.  
- **Nâng cao hiệu quả vận hành:** Giảm khối lượng kiểm duyệt thủ công.  
- **Hỗ trợ tăng trưởng kinh doanh:** Review xác thực giúp sản phẩm nổi bật, cải thiện tỷ lệ chuyển đổi và doanh thu.

## Nội dung kho lưu trữ
- **Tiền xử lý dữ liệu:** Làm sạch, chuẩn hóa, tokenization, trích xuất đặc trưng từ review.  
- **Mô hình AI:** SVM, Random Forest, XGBoost, TextCNN, BiLSTM, Transformer (PhoBERT).  
- **Huấn luyện & đánh giá:** Train/validation/test split, đo lường Accuracy, Precision, Recall, F1-score.  
- **Triển khai:** API, microservice, tích hợp với dashboard nội bộ hiển thị kết quả phân loại và cảnh báo.

## Công nghệ & công cụ
- **Ngôn ngữ:** Python  
- **Thư viện ML/NLP:** scikit-learn, PyTorch, TensorFlow, Hugging Face Transformers  
- **Triển khai:** Docker, FastAPI, AWS/Azure (tuỳ chọn)  

## Lợi ích
- Nâng cao **niềm tin người dùng** vào đánh giá và sản phẩm.  
- Giảm **chi phí kiểm duyệt thủ công** và rủi ro pháp lý.  
- Bảo vệ **người bán uy tín**, khuyến khích **cạnh tranh lành mạnh**.  
- Cải thiện **trải nghiệm mua sắm và uy tín thương hiệu Shopee**.

