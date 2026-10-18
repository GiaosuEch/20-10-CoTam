# DỰ ÁN SOICODOC 20/10: LỜI CHÚC TỪ NHÓM NAM GỬI CÁC BẠN NỮ

Tài liệu này ghi lại toàn bộ thông tin dự án, các cập nhật về âm nhạc tiếng Anh, đồng bộ lời bài hát thời gian thực, credit tác giả, nhân vật đại diện **soicodoc** và kịch bản lời thoại mới mang phong cách **trưởng thành, lịch thiệp, tinh tế** từ tập thể nam gửi tặng các bạn nữ nhân ngày 20/10.

---

## 1. Thông Tin Bản Quyền & Credit
* **Credit hiển thị**: `cre: Khôi Nguyên` được thu nhỏ tinh xảo (8.5px trên PC, 7.5px trên Mobile) ở góc dưới cùng bên phải màn hình (`fixed bottom-right`), màu chữ mờ nhẹ nhàng (opacity 0.28), như một chữ ký watermark tinh tế, hoàn toàn không gây phân tâm hay che khuất bất kỳ nội dung nào.
* Đã định vị chính xác trước thẻ đóng `</body>` của tài liệu chính, hiển thị ổn định và mượt mà trên toàn bộ các cảnh.

---

## 2. Âm Nhạc & Hệ Thống Đồng Bộ Lời Bài Hát (Synced Lyrics)

* **Bài hát**: *Every Second* – Mina Okabe.
* **Thời lượng nhúng**: 2 phút 05 giây (MP3 Stereo 128kbps, mã hóa Base64 nhúng thẳng vào thẻ `<audio id="tiny-soundtrack">`).
* **Khắc phục lỗi "hát một đằng lời một nẻo" & Giới hạn hiển thị theo cảnh**:
  1. **Khớp mốc thời gian tuyệt đối (Zero-Latency Alignment)**: Đã trích xuất chính xác từng giây phát âm thực tế của ca sĩ từ tệp âm thanh MP3. Từng câu hát cất lên trùng khớp 100% với từng dòng chữ xuất hiện trên màn hình:
     * `0.0s`: *"Every second, every day"*
     * `3.0s`: *"I spend hoping we never change"*
     * `5.6s`: *"Love when you never wait or hesitate"*
     * `10.0s`: *"To tell me what is on your mind, really do"*
     * `14.5s`: *"Enjoy your company, I think you would agree"*
     * `18.2s`: *"Just where you'd rather be is right here with me"*
     * `21.9s`: *"Make my day in every way"*
     * `25.5s`: *"Know I'll be okay when you are around"*
     * ... và tiếp tục liên tục cho đến hết bài.
  2. **Hiển thị ĐỘC QUYỀN tại cảnh Nụ cười Waguri (Exclusive Smile-Scene Display)**:
     * Theo đúng yêu cầu, lời bài hát **CHỈ xuất hiện duy nhất ở phân cảnh nụ cười Waguri** (`activeWish === 'smile'`, nơi có đĩa than cổ điển xoay tròn và câu thoại *"và nụ cười hạnh phúc sẽ luôn đồng hành mỗi ngày."*).
     * Lyric được căn chỉnh vị trí tuyệt đẹp ở khoảng giữa đĩa than và nhân vật Waguri, chữ to rõ, phát sáng êm dịu.
     * Ở tất cả các phân cảnh khác (từ lúc chào hỏi, cỏ 4 lá, máy bay giấy đến màn kết), khung lyric được ẩn hoàn toàn (`display: none; opacity: 0;`), đảm bảo không gian màn hình luôn thoáng đãng, tập trung vào thông điệp lời chúc.

---

## 3. Bảng Kịch Bản Lời Thoại Đã Hoàn Thiện

Toàn bộ lời thoại mang phong cách **chững chạc, lịch thiệp và mang tính đại diện tập thể**:

| Phân Cảnh (Click) | Lời thoại (Tập thể nam gửi tặng) | Ý nghĩa & Biểu cảm của soicodoc |
| :---: | :--- | :--- |
| **0** | **Chào các bạn,** | Robot mở mắt thức dậy, lời chào lịch thiệp. |
| **1** | **tớ là soicodoc** | Tự giới thiệu nhân vật đại diện. |
| **2** | **Hôm nay tớ nhận nhiệm vụ đặc biệt từ tập thể nam...** | Chuyển đổi người gửi từ *Dr D* thành **Tập thể nam**. |
| **3** | **để gửi gắm những điều tốt đẹp nhất đến phái nữ hôm nay.** | Nhạc cất lời ca, không gian bừng sáng sắc hồng. |
| **4** | **Nhân ngày Phụ nữ Việt Nam 20/10** | Bầu trời sao, ánh vàng lung linh và lá thu rơi. |
| **5** | **chúng tớ muốn gửi lời chúc chân thành nhất:** | Bước đệm trang trọng dẫn vào các lời chúc. |
| **6** | **chúc các bạn luôn dồi dào sức khỏe và bình an,** | Hiệu ứng nhịp tim yêu thương và sóng ECG neon. |
| **7** | **luôn tự tin, rạng rỡ và tỏa sáng theo cách riêng của mình,** | Cánh hoa đào và bụi pha lê lấp lánh rơi. |
| **8** | **và nụ cười hạnh phúc sẽ luôn đồng hành mỗi ngày.** | **Cảnh đặc biệt**: **Waguri 20/10 Ôm Hoa** (Nét vẽ Anime 2D truyền thống) rạng ngời, đĩa than xoay tròn & **hiển thị lời bài hát Mina Okabe**. |
| **9** | **Có một món quà may mắn từ chúng tớ, ngọn cỏ 4 lá này** | Chuyển sang tông xanh thiên nhiên tươi mát (ẩn lyric). |
| **10** | **các bạn hãy đón nhận nhé!** | Robot nghiêng mắt trao tặng cỏ bốn lá may mắn. |
| **11** | **chúc các bạn luôn gặp được thật nhiều điều may mắn và thành công** | Lời chúc công việc, học tập và tương lai. |
| **12** | **Cảm ơn các bạn vì đã luôn thật tuyệt vời!** | Lời triên sâu sắc, ấm áp từ phái nam. |
| **Máy bay** | **Các bạn hãy cùng chúng tớ chắp cánh<br>cho những điều ước hôm nay bay thật xa nhé! ✨** | Mời chạm giữ bình "Nạp yêu thương" để phóng máy bay. |
| **Cất cánh** | **Mong nụ cười của các bạn sẽ luôn rạng rỡ và bay cao! 💕** | Dòng chữ crossfade ngọt ngào khi máy bay cất cánh. |
| **Màn kết** | 🌸 **Chúc Các Bạn Một Ngày 20/10 Thật Ý Nghĩa, Rạng Rỡ & Trọn Vẹn Niềm Vui!** 🌸<br>*Cảm ơn các bạn đã luôn là những mảnh ghép tuyệt vời đồng hành cùng chúng tớ. Mong nụ cười và sự tự tin sẽ luôn rạng ngời trên môi các bạn mỗi ngày! 💕* | Bảng chúc mừng hoàn chỉnh, có nút xem lại và sao chép link. |

---

## 4. Tinh Chỉnh Kỹ Thuật & Tối Ưu Hóa Hiệu Năng
* **Nâng Cấp Nhân Vật Cảnh Nụ Cười (Waguri Ôm Hoa 20/10 - Nét Vẽ Anime 2D Nguyên Bản)**:
  - **Nét vẽ chuẩn 2D Japanese Anime**: Giữ nguyên vẹn phong cách anime cel-shading mực đen thủ công của nhân vật gốc Waguri (*Kaoru Hana wa Rin to Saku*), đôi mắt trăng khuyết cười tít mắt, má hồng anime đáng yêu; không bị bóng bẩy hay mang cảm giác "tranh AI".
  - **Trang phục & phụ kiện 20/10**: Thay bộ đồng phục học sinh cũ bằng áo cardigan hồng pastel dịu dàng, hai tay ôm bó hoa tươi thắm chúc mừng ngày Phụ nữ Việt Nam.
  - **Chuyển động êm ái, thư thái (Gentle Live2D Loop 4.0s)**:
    * Chuyển động nhẹ nhàng, thư giãn theo đúng điệu nhạc acoustic êm đềm: hơi thở nhấp nhô khẽ, làn tóc bay nhẹ theo gió, đầu nghiêng êm ái và bó hoa đong đưa tự nhiên.
  - **Tối ưu dung lượng cực đỉnh**: Video WebM trong suốt chỉ nặng **319 KB** (so với 1.7 MB của video cũ - nhẹ hơn hơn 5 lần!), tổng tệp `index.html` chỉ còn **4.7 MB**.
* **Sửa lỗi cú pháp Javascript vườn hoa Kado (Script #4)**: Chuyển đổi chuỗi đa dòng `flowerDoc` sang template literal (backticks `` `...` ``), khắc phục hoàn toàn lỗi cú pháp làm gián đoạn hiệu ứng hoa.
* **Tệp Sao Lưu An Toàn**: Tệp gốc ban đầu được lưu giữ tại [index.html.bak](file:///d:/Nguyen/2010%20c%C3%B4%20T%C3%A2m/index.html.bak).

