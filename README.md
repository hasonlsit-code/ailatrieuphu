# 💎 Ai Là Triệu Phú — Kinh tế chính trị Mác-Lênin (MLN122)

Trò chơi **Ai Là Triệu Phú** phiên bản đặc biệt về **Kinh tế chính trị Mác - Lênin**, xây dựng bằng HTML/CSS/JavaScript thuần — không cần cài đặt gì, mở là chơi được ngay.

## 🎮 Chơi ngay

👉 **https://hasonlsit-code.github.io/ailatrieuphu/**

## ✨ Tính năng

- 📖 **Sổ tay kiến thức** dạng notebook trước khi chơi — 2 chương, 10 thời kỳ, điều hướng bằng tab chương và nút "Tiếp theo":
  - **Chương I:** 5 thời kỳ hình thành & phát triển Triết học Mác - Lênin (1841-1844 → 1845-1848 → 1848-1895 → cuối TK XIX-1924 → 1924-nay)
  - **Chương II:** 5 thời kỳ kinh tế Việt Nam (cổ đại → sau Điện Biên Phủ → bao cấp sau 1975 → thời thuộc địa → Đổi mới-nay)
  - Trang cuối là luật chơi, rồi vào thẳng game
- 🪜 **15 câu hỏi** độ khó tăng dần, thang tiền thưởng từ 200.000đ đến 150.000.000đ
- 📚 **Ngân hàng 60 câu hỏi** MLN122 (20 dễ / 20 trung bình / 20 khó) trong [questions.js](questions.js), bám sát đúng nội dung Sổ tay kiến thức, mỗi ván xáo trộn ngẫu nhiên cả câu hỏi lẫn thứ tự đáp án — xem toàn bộ câu hỏi + đáp án tại [CAUHOI.md](CAUHOI.md) hoặc file Word [CAUHOI_MLN122.docx](CAUHOI_MLN122.docx)
- 🛟 **3 quyền trợ giúp**: 50:50 · 📞 Gọi điện cho người thân · 👥 Hỏi ý kiến khán giả
- ⏱️ Đồng hồ **30 giây** mỗi câu, hiệu ứng âm thanh, mốc an toàn tại câu 5 và câu 10
- 💡 **Giải thích đáp án sau mỗi câu** — vừa chơi vừa ôn thi
- 📱 Giao diện responsive, chơi tốt trên cả điện thoại

## 🚀 Chạy trên máy

Chỉ cần mở file `index.html` bằng trình duyệt, hoặc:

```bash
python -m http.server 8000
# rồi mở http://localhost:8000
```

## 📖 Nội dung kiến thức

Câu hỏi bám sát đúng nội dung Sổ tay kiến thức trong game: 5 thời kỳ hình thành & phát triển Triết học Mác - Lênin (từ bước quá độ tư tưởng 1841-1844 đến giai đoạn vận dụng sáng tạo ở Việt Nam 1924-nay) và 5 thời kỳ kinh tế Việt Nam (từ kinh tế hàng hóa giản đơn thời cổ đại, kinh tế thuộc địa, kế hoạch hóa tập trung, bao cấp, đến kinh tế thị trường định hướng XHCN hiện nay).

## ✏️ Thêm / sửa câu hỏi

Mở [questions.js](questions.js), thêm phần tử vào nhóm `easy` / `medium` / `hard` theo mẫu:

```js
{ "q": "Câu hỏi?", "a": ["Đáp án A", "Đáp án B", "Đáp án C", "Đáp án D"], "c": 0, "e": "Giải thích" }
// "c" = vị trí đáp án đúng (0-3)
```

---

*Sản phẩm học tập, lấy cảm hứng từ chương trình truyền hình "Ai Là Triệu Phú".*
