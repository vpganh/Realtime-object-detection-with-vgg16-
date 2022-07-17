# Realtime-object-detection-with-vgg16
## Sử dụng model VGG16 để xây dựng một bộ nhận diện vật thể thời gian thật bằng Python.

## Thu thập dữ liệu
- Ảnh của vật thể được chụp từ camera bằng `cv2`.
- Gán nhãn cho dữ liệu bằng `labelme`
- Chia bộ dữ liệu thành 3 phần Train-Valid-Test theo tỉ lệ 70%/15%/15%

## Tiền xử lý dữ liệu
- Làm giàu dữ liệu bằng `albumentations`
- Đưa ảnh về kích thước 450x450
## Train
- Sử dụng mô hình VGG16 từ `tensorflow.keras.applications`
- Sử dụng hàm tối ưu Adam từ `tf.keras.optimizers.Adam(learning_rate=0.0001, decay=lr_decay)`

## Kết quả
Video Realtime: https://drive.google.com/file/d/1ntGFqshQu0J4_uQXoKQV1LDrCf-8xni5/view?usp=sharing
![image](https://user-images.githubusercontent.com/108390918/179392870-12eee233-b8a5-4ce6-aaf2-c3829842c138.png)

