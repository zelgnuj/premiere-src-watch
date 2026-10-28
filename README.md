# SRC Watch for Premiere Pro

Panel cho Premiere Pro (macOS): quét các watch folder, import media mới vào bin `SRC Media` và tự tạo/cập nhật sequence dọc cho từng folder.

Repo này chỉ chứa các bản phát hành (Releases), không có mã nguồn.

## Cài lần đầu

1. Tải file `SRC-Watch-<version>.zxp` ở [bản mới nhất](https://github.com/zelgnuj/premiere-src-watch/releases/latest).
2. Cài bằng [ZXPInstaller](https://zxpinstaller.com).
3. Mở Premiere Pro 2024 trở lên → **Window → Extensions → SRC Watch**.

Cần `ffprobe` (ví dụ `brew install ffmpeg`) để kiểm tra codec video.

## Cập nhật

Không cần cài lại. Khi có bản mới, panel hiện dải **"Có bản mới vX — Cập nhật"**; bấm **Cập nhật** rồi **Mở bản mới**. Cài đặt, folder và flag được giữ nguyên.
