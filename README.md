# Dola Workspace Releases

Kho public chỉ dùng để phát hành bộ cài Dola Workspace. Source chính được giữ riêng.

## Tải bản mới nhất

[Mở trang phát hành mới nhất](https://github.com/txhieu198/dola-workspace-releases/releases/latest)

Linux Mint/Ubuntu x86_64 nên tải file `.deb`. File `.AppImage` dành cho chế độ portable.

## Cài trên Linux Mint

```bash
cd ~/Downloads
sudo apt install ./DolaWorkspace-1.0.0-linux-x64.deb
sudo apt install ffmpeg
```

Sau đó mở **Dola Workspace** từ menu ứng dụng.

## Chạy AppImage portable

```bash
chmod +x DolaWorkspace-1.0.0-linux-x64.AppImage
./DolaWorkspace-1.0.0-linux-x64.AppImage
```

Nếu máy thiếu FUSE:

```bash
./DolaWorkspace-1.0.0-linux-x64.AppImage --appimage-extract-and-run
```

Kiểm tra file tải về bằng `SHA256SUMS` được đính kèm trong từng release.
