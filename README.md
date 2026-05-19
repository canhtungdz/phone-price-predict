---- Thông Tin Thành Viên Nhóm ----
1. Nguyễn Cảnh Tùng, K68A4, MSSV: 23001950
2. Nguyễn Ngọc Tuấn, K68A4, MSSV: 23001948
3. Nguyễn Khánh Toàn, K68A4, MSSV: 23001944

---- Phân Chia Công Việc Của Các Thành Viên ----
1. Nguyễn Cảnh Tùng: Tiền xử lí dữ liệu, Thực nghiệm với mô hình hồi quy KNN, mô hình phân loại Naive Bayes, mô hình phân cụm GMM và Kmeans. Hỗ trợ viết báo cáo.
2. Nguyễn Ngọc Tuấn: Phân tích và trực quan hóa dữ liệu, thực nghiệm với mô hình Hồi quy tuyến tính, Hồi quy SoftMax, mô hình phân cụm DBScan. Viết Slide.
3. Nguyễn Khánh Toàn: Hỗ trợ viết báo cáo và slide.

--- Lấy dữ liệu và tổ chức dữ liệu ---
Dữ liệu được lấy trên Kaggle. Link: https://www.kaggle.com/datasets/pratikgarai/mobile-phone-specifications-and-prices/data

Trong file source code đã thiết kế để chạy trên Google Colab. Data đã được tải về và chia sẻ trên Google Drive. Trong code đã có đoạn load data từ drive. Chỉ ấn bấm chạy.

Toàn bộ source code đều ở trong một file duy nhất là final.ipynb
Cần upload lên Google Colab và thực hiện chạy ở trên đó.

--- Các kịch bản thử nghiệm ---
Nhóm xây dựng các mô hình hồi quy KNN và Linear Regression trên ba bộ dữ liệu khác nhau:

1.  Dữ liệu gốc sau khi tiền xử lý
2.  Dữ liệu đã giảm còn 6 chiều bằng PCA
3.  Dữ liệu đã giảm còn 4 chiều bằng PCA

Mỗi bộ dữ liệu được đánh giá theo ba kịch bản chia train–test: 
- 4 : 1 
- 7 : 3 
- 6 : 4

Nhóm thực hiện các phương pháp phân cụm dữ liệu trên bộ dữ liệu gốc đã tiền xử lí.

Các mô hình phân loại SoftMax và Naive Bayes được thực hiện trên các bộ dữ liệu khác nhau:
	Trước hết, đầu ra được chia ra làm 3 và 4 khoảng với cỡ mẫu bằng nhau.
	Sau đó thực hiện các kịch bản sau cho từng trường hợp đầu ra trên:

		1. Dữ liệu gốc đã tiền xử lí
		2. Dữ liệu đã giảm chiều bằng PCA (15 chiều).

	Các kịch bản chia train:test giống như các mô hình Hồi quy.