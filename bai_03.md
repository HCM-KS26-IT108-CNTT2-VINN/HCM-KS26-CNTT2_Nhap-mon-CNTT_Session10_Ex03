## **1\. Phân tích bài toán**

* **Số ký tự ít hơn:** Markdown chỉ dùng các ký tự đơn giản (như \*\*in đậm\*\*), trong khi HTML dùng nhiều thẻ đóng/mở dài (như \<strong\>in đậm\</strong\>).  
* **Mật độ Token thấp:** Bộ tách token (Tokenizer) phải chẻ các ngoặc \< \> / của HTML thành nhiều Token phụ.  
* **Tốc độ & Chi phí:** Markdown tốn ít token hơn $\rightarrow$ AI sinh phản hồi nhanh hơn, tiết kiệm chi phí API và không bị "phình" cửa sổ ngữ cảnh.

## **2\. So sánh & Đánh giá**

### **Bảng so sánh**

| Tiêu chí | Markdown | HTML |
| :---- | :---- | :---- |
| **Ký tự định dạng** | Tối giản, chiếm rất ít dung lượng | Rườm rà, tốn nhiều ký tự mở/đóng thẻ |
| **Tiêu tốn Token** | **Rất ít** (Tối ưu chi phí & tốc độ) | **Nhiều** (Đắt hơn, phản hồi chậm hơn) |
| **Dễ đọc (Human-readable)** | **Cao**: Đọc trực tiếp dễ dàng, không bị nhiễu | **Thấp**: Bị rối bởi các đoạn mã |

### **Giải pháp tối ưu: Chọn Markdown**

* **Tốc độ & Chi phí:** Phản hồi cực nhanh tại ruộng, tiết kiệm tối đa ngân sách vận hành AI.  
* **Thân thiện với nông dân:** Dễ đọc, giao diện gọn nhẹ, tương thích hoàn hảo với các ứng dụng chat (Zalo, App di động).

