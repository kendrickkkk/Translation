Dịch Máy (Machine Translation) với mục đích tự động dịch văn bản hoặc lời nói từ ngôn ngữ
tự nhiên này sang ngôn ngữ tự nhiên khác. Dịch máy sử dụng kết hợp nhiều ý tưởng và các kỹ thuật
với nhau từ ngôn ngữ học, khoa học máy tính, xác suất thống kê và trí tuệ nhân tạo. Với mục tiêu của
dịch máy là phát triển một hệ thống cho phép tạo ra bản dịch chính xác giữa các ngôn ngữ tự nhiên
của con người.
Các hệ thống dịch máy điển hình hiện này như: Google Translate, Bing Translator,... đã đạt được
chất lượng bản dịch tốt và được tích hợp trong nhiều nền tảng ứng dụng khác nhau và có thể dịch tốt
giữa hơn 100 các ngôn ngữ tự nhiên.
Như vậy, Input/Output của bài toán là:
• Input: Văn bản đầu vào của ngôn ngữ nguồn.
VD: Câu đầu vào tiếng việt: "Tôi đang học NLP"
• Output: Văn bản được dịch sang ngôn ngữ đích.
VD: Câu được dịch sang tiếng anh: " I am learning NLP"
Mô hình hoá bài toán dịch máy, với mục tiêu là huấn luyện và tối ưu các tham số mô hình θ với đầu
vào văn bản từ ngôn ngữ nguồn w
(s) và đầu ra văn bản từ ngôn ngữ đích tuơng ứng w
(s)
:
ˆw
(t) = argmax(w(t))
θ(w
(s)
), w(t)
))
Vì vậy, để giải quyết tốt bài toán dịch máy, chúng ta cần quan tâm tối ưu:
• Phần 1: Thuật toán học tối ưu bộ tham số θ
• Phần 2: Thuật toán giải mã (decoding) để sinh ra bản dịch tốt nhất cho văn bản đầu vào
Hiện nay, có ba hướng tiếp cận chính cho bài toán này:
• Hướng 1: Dịch máy dựa vào luật (Rule-based Machine Translation - RBMT)
• Hướng 2: Dịch máy dựa vào thống kê (Statistical Machine Translation - SMT)
• Hướng 3: Dịch máy dựa vào mạng nơ-ron (Neural Machine Translation - NMT)
Trong các hướng tiếp cận này NMT đang ngày càng phát triển và cho chất lượng bản dịch tốt vượt
trội. Vì vậy, phạm vi project tập trung vào các phương pháp dựa trên mạng nơ-ron gồm 2 nội dung
chính:
• Phương pháp 1: Xây dựng mô hình dịch máy sử dụng kiến trúc Transformer
• Phương pháp 2: Xây dựng mô hình dịch máy sử dụng Pre-trained Language Model như BERT
và GPT
