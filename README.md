# Telegram Bot - Country Information

## Giới thiệu
Bot Telegram này cung cấp thông tin chi tiết về các quốc gia khi người dùng nhập lệnh. Bot sử dụng API để lấy dữ liệu và trả về thông tin về quốc gia theo yêu cầu.

## Tính năng
- Tìm kiếm thông tin về quốc gia bằng lệnh `/tênquốcgia`
- Dịch tên quốc gia sang tiếng Việt sử dụng thư viện `deep_translator`
- Gửi danh sách các lệnh có sẵn
- Giới hạn sử dụng bot trong nhóm và hướng dẫn người dùng tham gia nhóm nếu sử dụng ngoài nhóm

## Cài đặt
### Yêu cầu
- Python 3x
- Các thư viện Python:
  - `telebot`
  - `deep_translator`
  - `requests`

### Cách cài đặt
1. Cài đặt các thư viện cần thiết:
   ```sh
   pip install pyTelegramBotAPI deep-translator requests
   ```
2. Chỉnh sửa mã nguồn để thêm token bot của bạn.
3. Chạy bot:
   ```sh
   python main.py
   ```

## Cách sử dụng
- Nhập `/tênquốcgia` để nhận thông tin chi tiết về quốc gia.
- Nếu sử dụng ngoài nhóm, bot sẽ yêu cầu người dùng tham gia nhóm.
- Bot tự động dịch tên quốc gia sang tiếng Việt trước khi tìm kiếm.

## Lưu ý 
- Thay BOT_TOKEN trong mã nguồn bằng token thật của bot Telegram.
- Đảm bảo bot có quyền nhận và gửi tin nhắn.

# Screenshot

## ![image](https://github.com/user-attachments/assets/b9d30ad7-1ca5-49ab-aa0c-5194ee004b47)

