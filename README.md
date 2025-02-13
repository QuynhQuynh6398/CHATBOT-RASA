RASA là một framework để xây dựng chatbot hội thoại, có hô trợ rất nhiều công cụ người dùng để xây dựng chatbot nhanh và hiệu quả khi dữ liệu cung cấp ít

Các thành phần của chatbot RASA

nlu.yml: là 1 module đóng vai trò xử lý đầu vào câu hội thoại người dùng, xác định ý định người dùng và trích lọc thực thể
domain.yml: khai báo các đối tượng và cấu hình chatbot sẽ dùng để phục vụ cho chatbot siêu đơn giản chủ quan tâm đến 2 khai báo đó là intent và response(intent là nơi khai báo các intent mà ta đã định nghĩa ở file nlu.yml trước đó, response là nơi khai báo những câu thoại của chatbot, để dạy bot chào tạm biệt)
stories.yml: dạy cho chatbot biết cách phản ứng lại với các lời chat như thế nào
