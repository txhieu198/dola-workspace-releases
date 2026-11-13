# HLA Worker Releases

Kho public chỉ dùng để phát hành bộ cài HLA Worker (trước bản 2.6.0 tên là Dola Workspace). Source chính được giữ riêng.

## Tải bản mới nhất

[Mở trang phát hành mới nhất](https://github.com/txhieu198/dola-workspace-releases/releases/latest)

Bản hiện tại: **2.6.1**. FFmpeg đã được đóng gói sẵn, không cần cài thêm.

- [Tải HLA Worker cho Windows (portable `.exe`)](https://github.com/txhieu198/dola-workspace-releases/releases/download/v2.6.1/HLAWorker-2.6.1-x64.exe)
- [Tải HLA Worker cho Linux Mint/Ubuntu x86_64 (`.AppImage`)](https://github.com/txhieu198/dola-workspace-releases/releases/download/v2.6.1/HLAWorker-2.6.1-linux-x64.AppImage)
- [Tải SHA256SUMS](https://github.com/txhieu198/dola-workspace-releases/releases/download/v2.6.1/SHA256SUMS)

## Chuyển từ Dola Workspace

HLA Worker dùng tiếp thư mục dữ liệu của Dola Workspace (`%APPDATA%\DolaWorkspace` trên Windows,
`~/.config/DolaWorkspace` trên Linux): đăng nhập, profile, extension và máy vẽ giữ nguyên.
Thoát hẳn Dola Workspace (menu khay "Thoát hoàn toàn") rồi mới mở HLA Worker; hai bản không chạy cùng lúc trên một máy.

## Chạy trên Windows

Tải file `.exe` rồi mở trực tiếp; bản portable không cần cài đặt.

## Chạy trên Linux Mint

```bash
cd ~/Downloads
chmod +x HLAWorker-2.6.1-linux-x64.AppImage
./HLAWorker-2.6.1-linux-x64.AppImage
```

Nếu máy thiếu FUSE:

```bash
./HLAWorker-2.6.1-linux-x64.AppImage --appimage-extract-and-run
```

## Máy vẽ

Bật **Máy vẽ** trên thiết bị mới cần quản trị viên cho phép thiết bị đó nhận việc vẽ.
Nếu ứng dụng báo "Thiết bị chưa được cấp quyền vẽ", gửi mã thiết bị hiển thị trong
thông báo cho quản trị viên.

Kiểm tra file tải về bằng `SHA256SUMS` được đính kèm trong từng release.
