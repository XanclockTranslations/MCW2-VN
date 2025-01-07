# Lịch sử cập nhật bản dịch

## v0.2 (ngày 7 tháng 1 năm 2025)

Sửa một chút nội dung trong `customenGuerillas`. Hiện đã xong 7/15 file dịch được trò chơi cung cấp.

### Đã dịch

- `customenInfo` (chứa một số string về một số từ khóa, VD: `Hoa Kỳ`, `Liên Xô`, ...).
    - Ghi chú 1: Một số string có thể tối nghĩa hoặc không phù hợp ngữ cảnh. #TODO: Cần sửa đổi lại cho hợp.

### Đang dịch

- `customenactions` (tổng hợp nhiều loại string trong trò chơi). 
    - Ghi chú 1: Hiện tại dịch đến dòng `$lecongresditnon=Quốc hội nói không!`. #TODO: Cần dịch tiếp.

## v0.1 (ngày 5 tháng 1 năm 2025)

Bản dịch đầu tiên, hiện đã xong 6/15 file dịch được trò chơi cung cấp.

Đánh giá của người dịch: Có thể sẽ có thay đổi lớn trong tương lai, nhưng hiện tại, việc dịch các file dữ liệu cơ bản của trò chơi không quá khó khăn.

### Đã dịch

- [x] `customen_countries` (tên các quốc gia trên thế giới).
    - Ghi chú 1: Hiện tại quy tắc đặt tên của các quốc gia chưa thống nhất (VD: `Bắc Triều Tiên` và `Bắc Việt Nam` nhưng `CHLB Đức` và `CHDC Đức`; có thể người dịch sẽ tự sửa lại. Hiện tại vẫn dịch theo quy tắc của trò chơi).
    - Ghi chú 2: Các thành phần phụ trong tên quốc gia (VD: `Bắc` trong `Bắc Triều Tiên`, `Vương quốc` trong `Vương quốc Anh`, `CHLB` trong `CHLB Đức`, ...) viết tắt nếu có thể (trung bình là nhiều hơn 2 từ thì viết tắt).
- [x] `customentuto` (???).
    - Ghi chú 1: File này hiện tại chỉ có 2 string `Information` (thông tin).
- [x] `customenPays` (???).
    - Ghi chú 1: File này hiện tại có tên các quốc gia (giống `customen_countries` 99%) với chừng 1-2 string khác. Không rõ mục đích của file này (theo dev, đây là file dùng để thực hiện một số thử nghiệm).
- [x] `customenMois` (các tháng trong năm).
- [x] `customencitations` (???).
    - Ghi chú 1: File này hiện tại không có gì để dịch. #TODO: Cần theo dõi thêm.
- [x] `customenGuerillas` (tên một số nhóm du kích).
    - Ghi chú 1: Các nhóm du kích khác được đặt ở các file khác (sẽ dịch dần). Hi vọng sau này sẽ thống nhất lại cách tổ chức file. #TODO: Cần theo dõi thêm.