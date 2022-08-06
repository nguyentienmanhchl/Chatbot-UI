# Chatbot-UI


Có 3 cách chạy:

C1: Mở trực tiếp bằng cách nháy đúp chuột vào index.html

C2: Ở thư mục chứa file index.html chạy lệnh

python3 -m http.server 3000

Khi đó vào http://localhost:3000 là thấy giao diện chatbot

C3: Sử dụng docker (dùng khi deploy)

docker run -d -p 3000:80 -v ${pwd}:/usr/share/nginx/html nginx

docker cp index.html <ID của container nginx tạo ở lệnh trên>:/usr/share/nginx/html



******

Link server thử nghiệm: http://157.245.58.167:3000/

Mở hộp thoại bằng cách ấn nút ở góc phải dưới cùng.

Ở trang index.html, nếu muốn chuyển sang chế độ hiển thị cả câu truy vấn SPARQL thì ấn nút ở góc phải trên cùng của màn hình giao diện chatbot.
