# SRC Watch for Premiere Pro

Panel cho Premiere Pro (macOS và Windows 10/11): quét các watch folder, import media mới vào bin `SRC Media` và tự tạo/cập nhật sequence dọc cho từng folder.

Repo này chỉ chứa các bản phát hành (Releases), không có mã nguồn.

## Cài lần đầu

1. Tải file `SRC-Watch-<version>.zxp` ở [bản mới nhất](https://github.com/zelgnuj/premiere-src-watch/releases/latest).
2. Cài bằng [ZXPInstaller](https://zxpinstaller.com) (có bản cho macOS và Windows). Trên Windows, nếu hiện cảnh báo SmartScreen thì bấm **More info → Run anyway**.
3. Khởi động lại Premiere Pro 2024 trở lên → **Window → Extensions → SRC Watch** (hoặc **Extensions (Legacy)**).

Không cần cài thêm gì khác: plugin tự đọc codec video (MP4/MOV/WebM/MKV).

## Cập nhật

Không cần cài lại. Khi có bản mới, panel hiện dải **"Có bản mới vX — Cập nhật"**; bấm **Cập nhật** rồi **Mở bản mới**. Cài đặt, folder và flag được giữ nguyên.

> Máy đã cài **0.10.0** sẽ báo "Không kết nối được Premiere". Mở panel, bấm **Cập nhật** ở dải "Có bản mới" rồi **Mở bản mới** để lên bản đã sửa. Nếu không thấy dải này, tải và cài lại file `.zxp` mới nhất.

> Windows được hỗ trợ từ bản **0.12.0**. Các bản trước chỉ chạy trên macOS.
