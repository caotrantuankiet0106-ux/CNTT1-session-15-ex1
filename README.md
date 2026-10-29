# Phần 1: 
### 3 hậu quả của "Thảm họa lưu trữ cục bộ"
Mất dữ liệu vĩnh viễn: Nhấn Ctrl+S ghi đè file hỏng trên ổ cứng cục bộ không thể hoàn tác (Undo) khi thiếu cơ chế quản lý lịch sử.

Rủi ro mất máy (Single Point of Failure): Dữ liệu chỉ nằm duy nhất trên máy cá nhân, dễ mất trắng nếu hỏng ổ cứng hoặc máy gặp sự cố.

Hỗn loạn phiên bản: Gửi file thủ công (v1, v2, final) qua Zalo gây rối loạn, đồng đội không biết đâu là bản code chuẩn.

# Phần 2: 
### Quy trình Hybrid Workflow (1-Click Khôi phục)
Thiết lập: Đồng bộ thư mục code lên GitHub (hoặc Google Drive/OneDrive). Không tạo file rác đánh số thủ công.

# Vận hành:

Viết code trên máy, lưu trữ và đồng bộ liên tục lên Cloud/GitHub sau mỗi cột mốc hoàn thành.

Khôi phục 1-click:

GitHub/VS Code: Chọn Revert/Discard Changes về commit trước đó.

Cloud Drive: Nhấp chuột phải file -> Version History -> Chọn mốc thời gian trước khi lỗi -> Nhấn Restore.
