## Tải xuống

> Bỏ qua mục Source code tự sinh của GitHub. Hãy tải đúng bộ cài cho hệ điều hành.

| File | Mục đích |
| --- | --- |
| `DolaWorkspace-1.0.0-linux-x64.deb` | Bộ cài cho Linux Mint/Ubuntu |
| `DolaWorkspace-1.0.0-linux-x64.AppImage` | Bản portable, không cần cài |
| `DolaWorkspace-Setup-1.0.0-win-x64.exe` | Bộ cài Windows có shortcut và trình gỡ cài đặt |
| `DolaWorkspace-1.0.0-x64.exe` | Bản Windows portable, chạy ngay không cần cài |
| `SHA256SUMS` | Mã kiểm tra tính toàn vẹn |

## Điểm chính

- Chromium multi-profile với cookie/storage tách riêng.
- Multi-tab, khởi động/dừng nhiều profile và nhập cookie Dola.
- Nhập cookie theo chế độ thay toàn bộ phiên Dola cũ và xác minh sau khi ghi.
- Video Cleaner 9:16: Cut đáy hoặc Zoom, 1080x1920, 60 FPS, tối đa 3 luồng.

## Cài trên Linux Mint

```bash
cd ~/Downloads
sudo apt install ./DolaWorkspace-1.0.0-linux-x64.deb
sudo apt install ffmpeg
```

Mở **Dola Workspace** từ menu ứng dụng.

## Windows

- Muốn cài đặt bình thường: chạy `DolaWorkspace-Setup-1.0.0-win-x64.exe`.
- Muốn dùng portable: chạy `DolaWorkspace-1.0.0-x64.exe`.

AppImage portable:

```bash
chmod +x DolaWorkspace-1.0.0-linux-x64.AppImage
./DolaWorkspace-1.0.0-linux-x64.AppImage
```

Build từ source tag `v1.0.0`, commit `11bf2f0`.
