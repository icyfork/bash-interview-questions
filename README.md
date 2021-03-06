BASH SHELL INTERVIEW QUESTIONS
=============================

####[[⬆]] Shell script

- Viết một script in ra đường dẫn tuyệt đối của chính nó
- Viết một kịch bản in ra nội dung của chính nó
- Viết một kịch bản có thể `reload` nội dung của chính nó
- Viết kịch bản tương đương với lệnh `watch`

####[[⬆]] Shell command

- Phân biệt `rsync -avz local remote` với `rsync -avz local/ remote`
- Làm thế nào để xóa tất cả các thư mục rỗng trong một thư mục?
- Tổ hợp phím `^ Z` dùng để làm gì?
- So sánh `^ C` và `^ Z`
- Làm thế nào để chờ (`sleep`) mà không phải dùng lệnh `sleep`?

####[[⬆]] Troubleshooting

- Một container của OpenVZ báo lỗi `Disk quota exceeded`, tuy nhiên check
bằng lệnh `df -h` thì thấy đĩa vẫn còn trống đến vài chục GB. Tình huống
gì có thể xảy ra (hint: df -i`)
- Khi đĩa đầy thì làm gì cho nó ... hết đầy?

####[[⬆]] Questions that can kill you

- Bạn biết `Phusion Passenger` là gì không? Có nhân vật nổi tiếng nào
  đang làm cho họ?
- Bạn đã từng đọc bài nào do `Phusion Passenger` viết chưa? Bài đó như thế nào
  và bạn đã học được gì từ bài đó?
- Làm thế nào để biết hệ thống đã chạy được bao lâu rồi? (aka `uptime`)
