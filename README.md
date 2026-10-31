# QuickMeets Android
## Main repo: https://github.com/NhLinh2610-maker/Quick-Meet
## Figma design: https://www.figma.com/design/i4FnnipvVWgu2auwbkTvJ2/QuickMeetsAndroidUI?node-id=0-1&t=wpxn2akcsTikPfnW-1
Ứng dụng Android của QuickMeets, nền tảng họp nhóm nhanh không cần đăng nhập. Project sử dụng **Java và giao diện XML**. Hiện repo mới có màn hình khởi đầu; các chức năng họp chưa được triển khai.

## Bắt đầu

1. Mở thư mục này bằng Android Studio và đợi Gradle đồng bộ.
2. Cài Android SDK Platform 37 nếu Android Studio yêu cầu. Sử dụng JDK đi kèm Android Studio (phiên bản 17 trở lên).
3. Chạy cấu hình `app` trên máy ảo hoặc thiết bị Android 8.0 (API 26) trở lên.

Repo đã có Gradle Wrapper nên không cần cài Gradle riêng. Android Studio sẽ tạo `local.properties` chứa đường dẫn SDK trên máy của bạn; không đưa file này lên Git.

## Cấu trúc project

- `app/`: ứng dụng Android, hiện gồm `MainActivity.java` và giao diện `res/layout/activity_main.xml` tối giản.
- `docs/`: nơi lưu liên kết thiết kế và ghi chú tích hợp với nhóm Web/backend.


## Chức năng dự kiến

- Tạo hoặc tham gia phòng bằng mã phòng và tên hiển thị tạm thời; tối đa 10 người/phòng.
- Gọi thoại/video, điều khiển camera và chia sẻ màn hình.
- Chat thời gian thực; chỉ tải file đính kèm khi người dùng yêu cầu và lưu vào bộ nhớ đệm của ứng dụng.
- Tự đóng phòng và dọn dẹp file trên server khi tất cả thành viên rời đi.

Khi làm nhóm, hãy tạo nhánh riêng cho từng tính năng và gửi pull request trước khi gộp vào `main`. Không đưa API key, khóa ký ứng dụng hoặc thông tin đăng nhập backend lên Git.
