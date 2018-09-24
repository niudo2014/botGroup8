# Demo: A Simple Voice AI Bot with Web Speech API and Node.js


Cách chatbot hoạt động:
1. Sử dụng `SpeechRecognition` của Web Speech API để nghe giọng nói từ micro.
2. Gửi tin nhắn của bạn tới [API.ai](https://api.ai) (nền tảng sử lý ngôn ngữ tự nhiên) như 1 chuỗi văn bản.
3. Một AI từ API.ai gửi lại một văn bản trả lời, sử dụng `SpeechSynthesis`để gửi một giọng nói tổng hợp.




### Cách sử dụng code app >>

Đổi tên `.env.local` thành `.env` và thêm 2 mã trong tài khoản lấy từ https://api.ai của bạn vào 2 dòng trong file:

```
APIAI_TOKEN=
APIAI_SESSION_ID=some_unique_session_id
```
Hoặc deploy lên Heroku server và sử dụng.
Đơn giản hơn sử dụng nút Deploy dưới đây để deploy app tới Heroku server. Bạn chỉ cần điền API key và session ID khi deploy mà ko cần tạo file `.env`.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/niudo2014/botGroup8)

