<h1 align="center">🎵 Emotion Music Recommendation</h1>

<p align="center">
  Nhận diện cảm xúc khuôn mặt và gợi ý nhạc phù hợp 🎧
</p>

---

## 🚀 Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
</p>

---

## 📌 Giới thiệu

Emotion Music Recommendation là project Python sử dụng camera để nhận diện cảm xúc khuôn mặt và gợi ý danh sách nhạc phù hợp với trạng thái hiện tại của người dùng.

Project tập trung vào việc kết hợp:
- Xử lý ảnh (Computer Vision)
- Nhận diện cảm xúc (AI)
- Ứng dụng web với Flask


##  Chức năng chính

- 📷 Mở camera trực tiếp trên trình duyệt  
- 🙂 Nhận diện khuôn mặt người dùng  
- 🧠 Phân tích cảm xúc khuôn mặt  
- 🎧 Gợi ý danh sách nhạc theo cảm xúc  
- 🌐 Giao diện web đơn giản, dễ sử dụng  


## Cách hoạt động

1. Người dùng mở website local
2. Hệ thống bật camera để nhận diện khuôn mặt
3. Model AI phân tích cảm xúc từ khuôn mặt
4. Ứng dụng trả về danh sách nhạc phù hợp với cảm xúc đó

Ví dụ:

| Cảm xúc | Gợi ý nhạc |
|---|---|
| Happy | Nhạc vui, năng lượng |
| Sad | Nhạc nhẹ, thư giãn |
| Angry | Nhạc giảm căng thẳng |
| Neutral | Nhạc nhẹ nhàng |

---

## Cài đặt và chạy project

### 1. Clone project

git clone https://github.com/NguyenQuynh1607/emotion-music-recommendation.git
cd emotion-music-recommendation
### 2. Tạo môi trường ảo
python3 -m venv venv
### 3.Kích hoạt môi trường ảo
Trên macOS / Linux:
source venv/bin/activate
Trên Windows:
venv\Scripts\activate
### 4. Cài thư viện
pip install -r requirements.txt
### 5. Chạy ứng dụng
python app.py
Sau đó mở trình duyệt và truy cập:
http://localhost:5000/
## Lưu ý khi chạy
	•	Cần cho phép trình duyệt truy cập camera
	•	Project chạy trên môi trường local
	•	Không tắt Terminal khi đang chạy app
	•	Muốn dừng chương trình, nhấn: CTRL + C
