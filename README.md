# Software Engineering Nhóm 32
Thành viên
1. Đỗ Quang Dũng
2. Đỗ Ngọc Anh
3. Lê Trung Hiếu
4. Nguyễn Lâm Tùng Bách



# Tóm tắt Văn bản bằng Python

## Giới thiệu
Dự án này tập trung vào việc tóm tắt văn bản tự động bằng Python. Chúng ta sử dụng các thư viện xử lý ngôn ngữ tự nhiên (NLP) để trích xuất thông tin quan trọng từ văn bản. Có thể tóm tắt văn bản từ các định dạng khác nhau như html, pdf, word,... với số lượng từ nhất định.

## Cài đặt
Để xây dựng dự án, chúng tôi sử dụng những công cụ sau:
- Thư viện xử lý ngôn ngữ tự nhiên (NLP):
    + NLTK (Natural Language Toolkit): Thư viện mạnh mẽ cho xử lý ngôn ngữ tự nhiên, bao gồm việc tách từ, tách câu, và xử lý văn bản.
    + spaCy: Thư viện NLP hiệu suất cao với khả năng tách từ và phân tích ngữ nghĩa.
    + Gensim: Dùng để xây dựng mô hình tóm tắt dựa trên phương pháp trừu tượng.

- Thư viện xử lý văn bản và tóm tắt:
    + Sumy: Thư viện Python cho tóm tắt văn bản sử dụng các phương pháp trích xuất.
    + Transformers (Hugging Face): Dùng để tạo mô hình tóm tắt dựa trên học sâu (BERT, GPT-2, T5, v.v.
