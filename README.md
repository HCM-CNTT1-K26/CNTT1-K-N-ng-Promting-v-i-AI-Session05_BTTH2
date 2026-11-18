# CNTT1-K-N-ng-Promting-v-i-AI-Session05_BTTH2


### 1. Sơ đồ truyền ngữ cảnh giữa các bước
Để giải quyết bài toán viết dài (1.000 – 1.500 từ) mà không bị loãng ý hay mất mạch, dữ liệu đầu ra của bước trước được đóng gói thành một khối thông tin cố định, làm nguyên liệu bắt buộc cho bước tiếp theo:

Plaintext
[Bước 1: Chốt dữ liệu khách hàng] ──► Khối <DU_LIEU_NGHIEN_CUU>
                                            
[Bước 2: Lên khung dàn ý SEO]     ──► Khối <DAN_Y_CHUAN_SEO>
                                          
[Bước 3: Viết chi tiết & Nối mạch] ──► Bài PR hoàn chỉnh (1.000 - 1.500 từ)

### 2. Chi tiết chuỗi 3 Prompt thành phần

#### Bước 1: Prompt nghiên cứu khách hàng và nỗi đau (Pain Points)

*Mục tiêu: Khóa chặt đối tượng đọc và vấn đề thực tế để bước sau không bị viết lan man.*

 **Câu lệnh (Prompt 1):**
 Bạn đang làm việc ở vị trí Trưởng nhóm Chiến lược Nội dung B2B, chuyên tư vấn truyền thông cho các công ty phần mềm doanh nghiệp.
 Nhiệm vụ của bạn là phân tích chân dung khách hàng và tìm ra những khó khăn thực tế mà giải pháp **[Tên sản phẩm AI Chatbot]** có thể giải quyết.
 **Thông tin đầu vào của sản phẩm:**
 * **Tên giải pháp:** [Điền tên, ví dụ: VinaChat AI]
 * **Điểm mạnh cốt lõi:** [Ví dụ: Hiểu tiếng Việt tự nhiên kể cả tiếng lóng, kết nối trực tiếp phần mềm quản lý bán hàng CRM, tự động trực tin nhắn 24/7 và giảm 65% chi phí nhân sự trực page]
 * **Nhóm ngành nhắm tới:** [Ví dụ: Bán lẻ trực tuyến, Bất động sản, Thẩm mỹ viện]
 
 
 **Yêu cầu định dạng kết quả:**
 Trình bày ngắn gọn, đi thẳng vào thực tế vận hành doanh nghiệp và gói gọn toàn bộ kết quả vào trong cặp thẻ `<DU_LIEU_NGHIEN_CUU>` dưới đây:
 `<DU_LIEU_NGHIEN_CUU>`
 * **Người đọc mục tiêu:** (Ghi rõ chức danh như Chủ doanh nghiệp, Trưởng phòng CSKH, Giám đốc vận hành; quy mô công ty và áp lực công việc hằng ngày của họ).
 * **3 Nỗi đau lớn nhất trong vận hành:** (Mỗi nỗi đau trình bày theo luồng: Thực trạng đang gặp -> Hậu quả gây thất thoát doanh thu hoặc mất khách).
 * **Cách sản phẩm giải quyết:** (Đối chiếu trực tiếp từng tính năng của chatbot vào 3 nỗi đau trên, kèm con số ước tính hiệu quả).
 * **Bộ từ khóa SEO:** (1 từ khóa chính và 4 từ khóa phụ liên quan trực tiếp đến nhu cầu tìm kiếm của doanh nghiệp).
 `</DU_LIEU_NGHIEN_CUU>`
 
 
 **Lưu ý:** Chỉ xuất dữ liệu phân tích trong thẻ quy định, chưa viết thành bài báo ở bước này.



#### Bước 2: Prompt lập dàn ý chi tiết (Outline)

*Mục tiêu: Ép khung cấu trúc chuẩn SEO và chia định mức số từ cho từng phần để kiểm soát độ dài.*

 **Câu lệnh (Prompt 2):**
 Dựa trên dữ liệu thực tế vừa phân tích ở bước trước, bạn hãy đóng vai một Biên tập viên chuyên mục Công nghệ - Kinh doanh để lập dàn ý chi tiết cho một bài PR dài khoảng **1.200 từ** (nằm trong khung 1.000 – 1.500 từ).
 **Dữ liệu đầu vào bắt buộc:**
 [Dán toàn bộ nội dung trong thẻ `<DU_LIEU_NGHIEN_CUU>` từ Bước 1 vào đây]
 **Yêu cầu đầu ra:**
 Xuất toàn bộ dàn ý vào trong cặp thẻ `<DAN_Y_CHUAN_SEO>` theo cấu trúc chuẩn sau:
 `<DAN_Y_CHUAN_SEO>`
 * **Giọng điệu xuyên suốt:** Chuyên nghiệp, khách quan, điềm đạm và đáng tin cậy như các bài phân tích chuyên sâu trên báo kinh tế (không dùng từ ngữ quảng cáo sáo rỗng, khoa trương).
 * **Tiêu đề chính (H1):** Viết 2 phương án tiêu đề chứa từ khóa chính, đánh trúng vào bài toán chi phí hoặc hiệu suất của doanh nghiệp, sau đó chọn ra 1 tiêu đề tốt nhất.
 * **Đoạn mở đầu (Lead - khoảng 130 từ):** Dẫn dắt từ thực tế khách hàng rời bỏ thương hiệu vì chờ đợi phản hồi lâu, sau đó giới thiệu sự xuất hiện của giải pháp AI Chatbot.
 * **Các phần thân bài (H2 và H3 - tổng khoảng 950 từ):** Chia làm 4 mục lớn (H2), trong mỗi H2 có 2 ý nhỏ (H3). Ghi rõ số từ dự kiến và từ khóa SEO cần chèn vào từng mục:
 * *Mục H2 số 1:* Những điểm nghẽn khiến đội ngũ CSKH quá tải và làm rơi rụng đơn hàng.
 * *Mục H2 số 2:* Cơ chế vận hành của [Tên sản phẩm] giúp tự động hóa quy trình tư vấn.
 * *Mục H2 số 3:* Bài toán tối ưu chi phí và cải thiện tỷ lệ chốt đơn thực tế.
 * *Mục H2 số 4:* Khả năng tích hợp nhanh chóng vào hệ thống sẵn có của doanh nghiệp.
 
 
 * **Đoạn kết và Kêu gọi hành động (CTA - khoảng 120 từ):** Khẳng định lại xu hướng ứng dụng AI và mời doanh nghiệp đăng ký trải nghiệm thử miễn phí hoặc nhận tư vấn giải pháp.
 `</DAN_Y_CHUAN_SEO>`
 
 



#### Bước 3: Prompt viết chi tiết từng phần và tối ưu SEO

*Mục tiêu: Triển khai thành văn bản hoàn chỉnh, bám sát dàn ý và giữ nguyên giọng điệu từ đầu đến cuối.*

 **Câu lệnh (Prompt 3):**
 Hãy viết hoàn chỉnh bài PR chuyên sâu dài **1.000 – 1.500 từ** dựa trên hai nguồn dữ liệu bắt buộc dưới đây.
 **1. Dữ liệu khách hàng và sản phẩm:**
 [Dán nội dung thẻ `<DU_LIEU_NGHIEN_CUU>` từ Bước 1]
 **2. Khung dàn ý chuẩn SEO:**
 [Dán nội dung thẻ `<DAN_Y_CHUAN_SEO>` từ Bước 2]
 **Quy tắc viết bài bắt buộc:**
 * **Trình bày chuẩn SEO:** Dùng thẻ `#` cho tiêu đề chính, `##` cho các mục H2 và `###` cho các mục H3. Đặt từ khóa chính ở tiêu đề, đoạn mở đầu, tối thiểu 2 thẻ H2 và đoạn kết. Các từ khóa phụ rải đều tự
 * hiên trong các đoạn văn.
 * **Chiều sâu nội dung:** Phân tích rõ ràng vấn đề vận hành thay vì khen ngợi chung chung. Giải thích cụ thể cách AI xử lý tình huống của khách hàng để tạo sự tin tưởng cho người đọc là chủ doanh nghiệp.
 * **Giữ vững giọng điệu:** Duy trì sự điềm đạm, chuyên nghiệp và tin cậy xuyên suốt từ dòng đầu tiên đến câu kết thúc. Tránh tuyệt đối các từ mang tính thổi phồng như "số 1", "hoàn hảo", "thần kỳ".
 * **Lời kêu gọi hành động (CTA):** Ở cuối bài, viết một đoạn CTA rõ ràng, lịch sự, hướng dẫn cụ thể cách thức để doanh nghiệp đăng ký dùng thử bản demo.
 * **Bắt đầu trực tiếp:** Đi thẳng vào Tiêu đề bài viết, không viết lời chào hay câu dẫn nhập thừa ở đầu.

 



### 3. Quy tắc xử lý khi bài viết bị ngắt quãng giữa chừng

Với các bài viết dài trên 1.000 từ, công cụ AI thường dừng lại đột ngột khi chạm giới hạn ký tự của một lượt trả lời. Để nối tiếp mạch văn mà không bị lặp lại ý cũ hay lệch tông giọng, hãy gửi ngay câu lệnh điều khiển sau trong cùng cuộc trò chuyện:

**Câu lệnh điều khiển viết tiếp:**
 Bài viết vừa bị ngắt giữa chừng do giới hạn độ dài. Bạn hãy viết tiếp phần còn lại để hoàn thành bài PR theo đúng `<DAN_Y_CHUAN_SEO>` đã thống nhất, tuân thủ nghiêm ngặt 3 nguyên tắc sau:
 1. **Nối khớp từng chữ:** Bắt đầu viết tiếp ngay sau cụm từ cuối cùng vừa bị ngắt là: `"[Copy và dán 10 - 15 chữ cuối cùng của đoạn văn bị dừng lại vào đây]"`. Không viết lại tiêu đề hay tóm tắt lại những gì đã viết ở trên.
 2. **Giữ nguyên mạch văn và giọng điệu:** Tiếp tục duy trì văn phong chuyên nghiệp, khách quan, đồng nhất cách xưng hô và cách chia thẻ H2/H3 như nửa đầu bài viết.
> 3. **Hoàn thiện đủ cấu trúc:** Triển khai đầy đủ các mục H2, H3 còn thiếu trong dàn ý và kết thúc trọn vẹn bằng đoạn kêu gọi hành động (CTA).
> 
>
