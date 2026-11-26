# Cài đặt HandsOn Beta 3

- **Windows 10/11 x64.** Đối chiếu SHA-256 bằng `Get-FileHash -Algorithm SHA256 .\HandsOn-Windows-v1.0.0-beta.3.zip`. Giải nén toàn bộ ZIP, rồi mở HandsOn.exe. Windows thật vẫn chờ nghiệm thu.
- **macOS 13+ Apple Silicon.** Đối chiếu bằng `shasum -a 256 HandsOn-macOS-v1.0.0-beta.3.zip`. Giải nén bằng Archive Utility. Bản QA ký ad hoc. Gatekeeper có thể từ chối ứng dụng, vì bản này chưa có Developer ID và chưa notarize. [Hướng dẫn phân phối của Apple](https://developer.apple.com/documentation/security/notarizing-macos-software-before-distribution)
- **Android 7.0+ với WebView tương thích.** So khớp SHA-256 của APK, rồi mở bằng trình cài của Android. Đây là APK ký Debug dành cho QA. Chưa xác minh cài trên Android thật.
- **iPhone và iPad.** Trải nghiệm trên [Safari](https://handsonapp.pages.dev/). Phiên bản này cung cấp gói cho ba hệ điều hành ở trên.
- **Offline AI Desktop.** Cài riêng GGUF tương thích vào thư mục models mà chatbot hướng nghiệp hiển thị ở chế độ Offline. Lần hỏi đầu có thể chậm hơn vì phải nạp model. Microphone dùng dịch vụ nhận diện của thiết bị khi khả dụng, hoặc có thể nhập bằng bàn phím.

Thông báo giấy phép của tài nguyên 3D, phim và font có trong mục nguồn của ứng dụng và các tệp CREDITS đi cùng gói.
