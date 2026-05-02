# FO-04: QUY TRÌNH THANH TOÁN & CHECK-OUT (TRẢ PHÒNG)

## 1. Mục đích
Đảm bảo thu hồi đầy đủ chìa khóa, thanh toán chính xác các dịch vụ phát sinh, giải quyết tiền cọc và lưu lại ấn tượng tốt đẹp trước khi khách rời khách sạn.

## 2. Công cụ chuẩn bị
*   Hệ thống PMS.
*   Máy POS quẹt thẻ.
*   Tiền mặt (tiền lẻ để thối).
*   Hóa đơn GTGT (nếu khách yêu cầu).
*   Sổ giao nhận ca.
*   Bộ đàm để liên lạc với Buồng phòng (HK).

## 3. Các bước thực hiện

### Bước 1: Tiếp nhận yêu cầu trả phòng & Phối hợp Bellman
*   **Hành động:** Chào khách. Hỏi số phòng và thu hồi thẻ/chìa khóa phòng. Ngay lập tức gọi bộ đàm cho Bellman lên phòng hỗ trợ mang hành lý xuống sảnh hoặc ra xe cho khách.
*   **Kịch bản thoại:**
    > *"Dạ KS [Tên KS] xin chào anh/chị. Anh/chị làm thủ tục trả phòng số mấy ạ? Cho em xin lại chìa khóa phòng nhé."*
    > *(Bộ đàm): "Bellman lên phòng [Số phòng] hỗ trợ hành lý check-out giúp Lễ tân."*

### Bước 2: Báo Buồng phòng kiểm tra (Check out room)
*   **Hành động:** Dùng bộ đàm hoặc hệ thống nội bộ báo cho HK lên kiểm tra phòng (kiểm tra Minibar, đồ thất lạc, hư hỏng tài sản).
*   **Kịch bản thoại (Bộ đàm):** *"Lễ tân gọi Buồng phòng, check-out phòng [Số phòng]."*

### Bước 3: Xác nhận sự hài lòng của khách (Trong lúc chờ HK kiểm tra)
*   **Hành động:** Tranh thủ thời gian chờ đợi để hỏi thăm cảm nhận của khách về kỳ nghỉ.
*   **Kịch bản thoại:**
    > *"Dạ trong thời gian chờ các bạn kiểm tra phòng, anh/chị cho em hỏi gia đình mình nghỉ ngơi có thoải mái không ạ? Đồ ăn sáng có hợp khẩu vị anh/chị không?"*

### Bước 4: Nhận báo cáo từ Buồng phòng & Chốt bill
*   **Hành động:** Nhận thông tin từ HK. Nếu khách có dùng đồ Minibar hoặc làm mất/hỏng đồ, nhập khoản phí vào PMS. In bảng kê chi tiết (Folio) đưa khách kiểm tra.
*   **Kịch bản thoại:**
    > *"Dạ em gửi anh/chị bảng kê chi phí. Ngoài tiền phòng đã thanh toán, mình có dùng thêm [Tên đồ uống] trong Minibar giá [Số tiền]. Tổng chi phí phát sinh là [Số tiền]. Anh/chị kiểm tra lại giúp em ạ."*

### Bước 5: Thanh toán, hoàn cọc và Tiễn khách
*   **Hành động:** Thực hiện thanh toán. Nếu số tiền phát sinh nhỏ hơn tiền cọc (Deposit lúc check-in), tiến hành hoàn trả phần thừa cho khách. Trả lại CCCD/Passport (nếu khách gửi lúc check-in). Cảm ơn và chào tạm biệt.
*   **Kịch bản thoại:**
    > *"Dạ lúc nhận phòng anh/chị có cọc 500.000đ, trừ đi tiền Minibar 100.000đ, em xin hoàn lại 400.000đ tiền mặt ạ."*
    > *"Em gửi lại CCCD cho gia đình. Cảm ơn anh/chị đã chọn KS [Tên KS]. Chúc anh/chị thượng lộ bình an và hy vọng sớm được đón anh/chị quay lại ạ."*

## 4. Tiêu chuẩn hoàn thành (Checklist)
- [ ] Đã thu hồi đủ thẻ/chìa khóa phòng.
- [ ] HK báo cáo tình trạng phòng dưới 3 phút.
- [ ] Bill thanh toán chính xác, không sai sót.
- [ ] Hoàn trả đầy đủ CCCD/Passport cho khách.
- [ ] Cập nhật trạng thái phòng thành "Vacant Dirty" (Phòng trống bẩn) trên PMS.

## 5. Lưu ý an toàn & Tình huống rủi ro

*   **Tình huống 1: Khách làm hỏng/mất tài sản (vỡ cốc, mất khăn).**
    *   **Nếu** HK báo khách làm mất đồ, **thì** Lễ tân khéo léo thông báo và đưa bảng giá đền bù cho khách xem. Không dùng từ "đền bù" mà dùng từ "phí thay mới".
    *   *Script:* *"Dạ thưa anh/chị, các bạn Buồng phòng báo lại lúc dọn dẹp không thấy [Tên đồ vật] và có một ly thủy tinh bị nứt. Theo quy định của KS, em xin phép tính thêm khoản phí thay mới là [Số tiền] vào hóa đơn ạ. Mong anh/chị thông cảm."*
*   **Tình huống 2: Khách vội ra sân bay/tàu xe, không kịp chờ HK kiểm tra.**
    *   **Nếu** khách rất vội, **thì** Lễ tân linh động cho khách thanh toán dựa trên sự tin tưởng (hỏi khách có dùng gì ở Minibar không), tiến hành trả giấy tờ cho khách đi ngay.
    *   *Script:* *"Dạ nếu anh/chị đang vội ra sân bay, em xin phép chốt hóa đơn luôn ạ. Anh/chị có sử dụng thêm đồ uống nào trong tủ lạnh không ạ? ... Dạ em hoàn tất thủ tục để anh/chị di chuyển ngay cho kịp giờ nhé. Chúc anh/chị chuyến bay an toàn!"*
