# Bộ tài liệu Claude bằng tiếng Việt

Tài liệu hướng dẫn dùng Claude Code, viết bằng tiếng Việt, dành cho người mới bắt đầu và chưa quen dòng lệnh.

## Đang có

### Cài Claude Code trên Windows

Tệp: [`2026-09-21-huong-dan-cai-claude-code-windows.md`](2026-09-21-huong-dan-cai-claude-code-windows.md)

Hướng dẫn tuần tự từ lúc mở PowerShell tới lúc đăng nhập xong và gõ được câu lệnh đầu tiên:

- Điều kiện trước khi bắt đầu: Windows 10 1809+, RAM 4 GB, x64 hoặc ARM64, tài khoản Pro/Max/Team/Enterprise.
- Bước 1–6: mở PowerShell đúng loại → kiểm tra 64-bit → chạy bộ cài chính thức → chuẩn bị PATH → xác minh → đăng nhập lần đầu.
- Xử lý lỗi `claude is not recognized` và bảng bốn lỗi hay gặp.
- Phụ lục cho macOS, Linux và WSL.

Tài liệu này **đã được kiểm chứng bằng một lần cài đặt thật** trên Windows, không viết theo lý thuyết. Hai chỗ người mới hay vấp — màn hình "Quick safety check" có con trỏ mặc định ở *No, exit*, và việc chạy `claude` ngay tại `C:\WINDOWS\system32` — đều được ghi lại từ thực tế.

### Script cài đặt một lần

Tệp: [`2026-09-21-script-cai-claude-code-windows.ps1`](2026-09-21-script-cai-claude-code-windows.ps1)

Khối PowerShell thay cho Bước 2–5: kiểm tra 64-bit, chạy bộ cài chính thức, thêm PATH khi chưa có, chạy kiểm tra. Có nhánh dự phòng khi bộ cài lỗi. Script chỉ thêm, không xoá và không ghi đè.

Cách dùng: mở PowerShell 64-bit, sao chép toàn bộ nội dung tệp, dán vào rồi nhấn Enter.

## Nguồn đối chiếu

Mọi lệnh trong tài liệu đều đối chiếu tài liệu chính thức của Anthropic:

- [Claude Code Setup](https://code.claude.com/docs/en/setup)
- [Troubleshoot installation](https://code.claude.com/docs/en/troubleshoot-install)

## Quy tắc đặt tên tệp

- Chữ thường, không dấu, phân cách bằng dấu gạch ngang.
- Cấu trúc: `yyyy-mm-dd-loai-chu-de.md`
- Phiên bản dùng v1, v2, v3. Không dùng final, new hoặc latest.
