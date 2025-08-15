# Ứng dụng-IOT-điều khiển-thiết bị-trong-thời gian-thực
Ứng dụng IOT giám sát nhiệt độ,độ ẩm và điều khiển thiết bị theo thời gian thực. Dự án được tôi thực hiện khi kết thúc khóa học ngoại khóa của khoa điện tử PTIT

Trong thực tế khoa học công nghệ phát triển mạnh mẽ, nhu cầu của con người về các thiết bị thông minh hỗ trợ đời sống cũng ngày càng cao. Với mong muốn tạo nên được một sản phẩm giá thành rẻ có tính ứng dụng thực tiễn vào cuộc sống, vận dụng những kiến thức đã được học ở lớp ngoại khóa “Đồ án nhúng” tôi đã lên ý tưởng và thực hiện “ứng dụng IOT (Internet of Thing) giám sát nhiệt độ, khí gas và điều khiển thiết bị nhà ở”. Tôi hi vọng sản phẩm của ý tưởng này giúp ích được vào cuộc sống và truyền thêm động lực cho tôi trong quá trình học tập. 

Hệ thống gồm có các khối sau: khối xử lí, khối đầu vào, khối thực thi, khối sever và khối app. Quan trọng nhất là khối điều khiển trung tâm, có nhiệm vụ điều khiển toàn hệ thống.
Tôi lựa chọn mạch điều khiển là ESP32 vì các ưu điểm phù hợp với nhu cầu sau: giá rẻ, cộng đồng hỗ trợ lớn, dễ lập trình. 
Về phần mềm, tôi chọn PlatformMIO (là một plugin có khả năng lập trình Arduino) nhận thấy rằng tốc độ nạp chương trình nhanh 
và giao diện hiển thị thuận tiện hơn trong quá trình làm việc cũng như sửa lỗi cho nên đây là lựa chọn để tôi thực hiện đề tài này.

Tổng quan về sơ đồ khối hệ thống:

![image](https://github.com/user-attachments/assets/8de31ed9-d517-411c-8317-847a75b711f3)

![image](https://github.com/user-attachments/assets/451dcbfe-46cc-4930-835d-e684eb059fdc)

Hình ảnh sản phẩm thực tế:

![image](https://github.com/user-attachments/assets/c4166df1-c821-4a1e-98a7-072a41ff9d50)

Giao diện ứng dụng điều khiển:

![image](https://github.com/user-attachments/assets/07b649ea-2e7e-47ac-aa97-f363bcf7e597)
![image](https://github.com/user-attachments/assets/7280a2aa-59f6-4226-af67-5c60366dd2f6)

Tổng quan dự án có thể xem đầy đủ ở đường link sau: https://drive.google.com/drive/folders/1QL_kK87EN9d5eyBuhCm8NLX9yPFYJeKa
