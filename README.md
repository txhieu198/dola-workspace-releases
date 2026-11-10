# Dola Workspace Releases

Kho public chỉ dùng để phát hành bộ cài Dola Workspace. Source chính được giữ riêng.

## Tải bản mới nhất

[Mở trang phát hành mới nhất](https://github.com/txhieu198/dola-workspace-releases/releases/latest)

Bản hiện tại: **2.5.6**. FFmpeg đã được đóng gói sẵn, không cần cài thêm.

- [Tải Dola Workspace cho Windows (portable `.exe`)](https://github.com/txhieu198/dola-workspace-releases/releases/download/v2.5.6/DolaWorkspace-2.5.6-x64.exe)
- [Tải Dola Workspace cho Linux Mint/Ubuntu x86_64 (`.AppImage`)](https://github.com/txhieu198/dola-workspace-releases/releases/download/v2.5.6/DolaWorkspace-2.5.6-linux-x64.AppImage)
- [Tải SHA256SUMS](https://github.com/txhieu198/dola-workspace-releases/releases/download/v2.5.6/SHA256SUMS)

## Chạy trên Windows

Tải file `.exe` rồi mở trực tiếp; bản portable không cần cài đặt.

## Chạy trên Linux Mint

```bash
cd ~/Downloads
chmod +x DolaWorkspace-2.5.6-linux-x64.AppImage
./DolaWorkspace-2.5.6-linux-x64.AppImage
```

Nếu máy thiếu FUSE:

```bash
./DolaWorkspace-2.5.6-linux-x64.AppImage --appimage-extract-and-run
```

## Máy vẽ

Bật **Máy vẽ** trên thiết bị mới cần quản trị viên cho phép thiết bị đó nhận việc vẽ.
Nếu ứng dụng báo "Thiết bị chưa được cấp quyền vẽ", gửi mã thiết bị hiển thị trong
thông báo cho quản trị viên.

Kiểm tra file tải về bằng `SHA256SUMS` được đính kèm trong từng release.
