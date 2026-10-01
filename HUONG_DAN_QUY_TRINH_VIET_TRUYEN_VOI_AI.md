# HƯỚNG DẪN QUY TRÌNH VIẾT TRUYỆN DÀI VỚI AI
## Tác phẩm: "Tuyệt Đối Cẩn Trọng: Ta Tại Cấm Địa Âm Thầm Vô Địch"

---

## I. KIẾN TRÚC THƯ MỤC DỰ ÁN

```
📁 antigravity_writting/
│
├── 📄 DAN_Y_CHI_TIET_TRUYEN_TU_TIEN_CAU_DAO.md   ← [ĐÃ CÓ] Cốt truyện tổng thể
├── 📄 HUONG_DAN_QUY_TRINH_VIET_TRUYEN_VOI_AI.md   ← [FILE NÀY] Hướng dẫn quy trình
├── 📄 TRANG_THAI_HIEN_TAI.md                       ← [CẦN TẠO] Bộ nhớ dài hạn của AI
│
├── 📁 Quyen_1_Tiem_Long_Kho_Tu/
│   ├── 📄 quyen_1_dan_y_chi_tiet.md                ← Dàn ý từng chương cho Quyển 1
│   └── 📄 quyen_1_noi_dung.md                      ← Nội dung truyện Quyển 1
│
├── 📁 Quyen_2_Cam_Ky_Giau_Mat/
│   ├── 📄 quyen_2_dan_y_chi_tiet.md
│   └── 📄 quyen_2_noi_dung.md
│
├── 📁 Quyen_3_Than_Uy_Dao_To/
│   ├── 📄 quyen_3_dan_y_chi_tiet.md
│   └── 📄 quyen_3_noi_dung.md
│
├── 📁 Quyen_4_Bao_To_Hon_Do/
│   ├── 📄 quyen_4_dan_y_chi_tiet.md
│   └── 📄 quyen_4_noi_dung.md
│
└── 📁 Quyen_5_Chan_Ly_Khoi_Nguyen/
    ├── 📄 quyen_5_dan_y_chi_tiet.md
    └── 📄 quyen_5_noi_dung.md
```

---

## II. QUY TRÌNH 4 BƯỚC LẶP LẠI (CHO MỖI BATCH 3–5 CHƯƠNG)

```
┌─────────────────────────────────────────────────────────────────────┐
│                    VÒNG LẶP VIẾT TRUYỆN                             │
│                                                                     │
│   BƯỚC 1              BƯỚC 2              BƯỚC 3        BƯỚC 4     │
│ ┌──────────┐       ┌──────────┐       ┌──────────┐   ┌──────────┐  │
│ │ NẠP NGỮ  │ ───>  │ AI VIẾT  │ ───>  │ BẠN ĐỌC  │──>│ CẬP NHẬT │  │
│ │ CẢNH CHO │       │ 3-5      │       │ REVIEW   │   │ TRẠNG    │  │
│ │ AI       │       │ CHƯƠNG   │       │ SỬA NẾU  │   │ THÁI     │  │
│ └──────────┘       └──────────┘       │ CẦN      │   └──────────┘  │
│                                       └──────────┘        │         │
│         ▲                                                 │         │
│         └─────────────────────────────────────────────────┘         │
│                          LẶP LẠI                                    │
└─────────────────────────────────────────────────────────────────────┘
```

### Bước 1: Nạp ngữ cảnh (Context Loading)
Trước mỗi lần giao AI viết, bạn cần gửi kèm **3 tài liệu**:
1. **File "TRANG_THAI_HIEN_TAI.md"** — Tóm tắt mọi thứ đã xảy ra (bộ nhớ dài hạn)
2. **Dàn ý chi tiết** cho batch chương sắp viết (3-5 chương tiếp theo)
3. **2-3 chương cuối cùng đã viết** — Để AI nối mạch văn phong & giọng kể

### Bước 2: AI viết 3–5 chương
Dùng prompt mẫu (xem phần III bên dưới).

### Bước 3: Bạn đọc & review
- Kiểm tra tính nhất quán nhân vật
- Sửa lỗi logic / cốt truyện
- Đánh giá chất lượng văn phong

### Bước 4: Cập nhật file "TRANG_THAI_HIEN_TAI.md"
Sau mỗi batch, cập nhật:
- Chương đã viết đến đâu
- Cảnh giới hiện tại của MC và các nhân vật
- Sự kiện quan trọng vừa xảy ra
- Các phục bút / mâu thuẫn còn treo
- Nhân vật mới xuất hiện

---

## III. CÁC MẪU PROMPT CHUẨN

### Prompt A: Giao AI viết batch chương mới

```
Bạn là một tiểu thuyết gia chuyên nghiệp viết truyện Tiên hiệp/Huyền huyễn 
bằng tiếng Việt, chuyên thể loại Cẩu Đạo / Vô Địch Lưu. 

Phong cách viết: 
- Giọng kể ngôi thứ ba, tập trung vào nội tâm và suy nghĩ hài hước hoang tưởng 
  của nhân vật chính Ninh Uyên.
- Xen kẽ giữa các đoạn bế quan tu luyện nhảy thời gian (time skip) với những 
  cú twist drama từ bảng tin Thiên Cơ Kính.
- Khi nhân vật chính ra tay, phải cực kỳ sảng khoái, 1 chiêu miểu sát, 
  không kéo dài chiến đấu.
- Mỗi chương 2,500 – 3,500 từ.
- Cuối mỗi chương phải có cliffhanger (tin tức chấn động hoặc nguy cơ mới).

===== TRẠNG THÁI HIỆN TẠI =====
[Dán nội dung file TRANG_THAI_HIEN_TAI.md vào đây]

===== DÀN Ý CÁC CHƯƠNG CẦN VIẾT =====
[Dán dàn ý chi tiết cho 3-5 chương tiếp theo]

===== 2 CHƯƠNG CUỐI ĐÃ VIẾT (để nối văn phong) =====
[Dán 2 chương gần nhất]

===== YÊU CẦU =====
Hãy viết Chương [X] đến Chương [Y] theo dàn ý trên. 
Đảm bảo:
1. Giữ đúng tính cách nhân vật (Ninh Uyên cẩn trọng hoang tưởng, 
   Ô Quy Tử mỏ hỗn, Sở Hàn kiêu hùng nhưng sợ sư tôn…)
2. Có ít nhất 1 lần check Thiên Cơ Kính mỗi 2-3 chương.
3. Mỗi chương kết thúc bằng cliffhanger khiến người đọc muốn đọc tiếp.
4. Duy trì nhịp độ: Bế quan → Drama → Ra tay sảng khoái → Bế quan tiếp.
```

### Prompt B: Giao AI tạo dàn ý chi tiết cho 1 quyển

```
Dựa trên cốt truyện tổng thể sau đây, hãy phân tách Quyển [X] thành 
chính xác [200] chương, mỗi chương có:
- Tiêu đề chương (hấp dẫn, có hook)
- Tóm tắt 3-5 dòng nội dung chính
- Ghi chú nhân vật xuất hiện
- Ghi chú cảnh giới MC ở thời điểm đó
- Đánh dấu các chương "đỉnh điểm" (climax) và "chuyển giai đoạn"

[Dán nội dung phần Quyển X từ file DAN_Y_CHI_TIET]
```

### Prompt C: Giao AI cập nhật trạng thái sau mỗi batch

```
Dựa trên nội dung 5 chương vừa viết dưới đây, hãy cập nhật file 
TRANG_THAI_HIEN_TAI theo format chuẩn:

[Dán 5 chương vừa viết]

Cần cập nhật:
1. Số chương đã hoàn thành
2. Cảnh giới hiện tại của tất cả nhân vật đã xuất hiện
3. Tóm tắt 5 sự kiện quan trọng nhất vừa xảy ra
4. Các mâu thuẫn/phục bút đang treo chưa giải quyết
5. Nhân vật mới xuất hiện (tên, vai trò, tính cách)
6. Quan hệ nhân vật thay đổi
```

---

## IV. FILE "TRẠNG THÁI HIỆN TẠI" - BỘ NHỚ DÀI HẠN CHO AI

File này là **"bộ não" của dự án** — nó giúp AI nhớ mọi thứ đã xảy ra 
dù bạn bắt đầu một phiên chat hoàn toàn mới.

### Format chuẩn cho TRANG_THAI_HIEN_TAI.md:

```markdown
# TRẠNG THÁI TRUYỆN: Tuyệt Đối Cẩn Trọng

## Tiến độ
- Quyển hiện tại: 1
- Chương đã viết: 0 / 200
- Batch gần nhất: Chưa bắt đầu

## Cảnh giới nhân vật
| Nhân vật | Cảnh giới hiện tại | Ghi chú |
|:---|:---|:---|
| Ninh Uyên | Phàm nhân (chưa tu luyện) | Đang roll mệnh cách |
| Ô Quy Tử | Rùa đen phàm | Chưa khai trí |
| Thiền Nguyệt | Chưa xuất hiện | — |
| Sở Hàn | Chưa xuất hiện | — |

## Tóm tắt sự kiện đã xảy ra (mới nhất ở trên)
- (chưa có)

## Mâu thuẫn / Phục bút đang treo
- (chưa có)

## Nhân vật đã xuất hiện
- (chưa có)

## Ghi chú văn phong & giọng kể
- Giọng kể ngôi 3, xen kẽ nội tâm hài hước của MC.
- MC luôn có những suy nghĩ hoang tưởng kiểu: 
  "Tên này chắc chắn đang giấu bài, ta phải cẩn thận..."
```

---

## V. KẾ HOẠCH TIẾN ĐỘ TỔNG THỂ

### Quyển 1: 200 chương ÷ 5 chương/batch = **40 batch (40 lần giao AI)**

| Batch | Chương | Nội dung chính | Ước tính thời gian |
|:---:|:---:|:---|:---:|
| 1–6 | 1–30 | Roll mệnh cách, bắt đầu tu luyện, nhặt Ô Quy Tử | 2-3 ngày |
| 7–16 | 31–80 | Ma Môn xâm lăng, lần đầu ra tay, nhận U Minh Lục | 3-4 ngày |
| 17–28 | 81–140 | Nguyền rủa Ma Tôn, thu Sở Hàn, Cơ Mộng Ly | 4-5 ngày |
| 29–40 | 141–200 | Đại Thừa, chém nát Tiên Môn, vô địch phàm giới | 4-5 ngày |
| **Tổng Quyển 1** | **200 ch.** | | **~2-3 tuần** |

### Toàn bộ dự án: 5 Quyển × ~200 chương = **~1,000 chương**
- Tổng số batch: ~200 batch
- Thời gian ước tính: **10–15 tuần** (nếu viết đều đặn mỗi ngày)
- Tổng số từ ước tính: 2.5 – 3.5 triệu từ

---

## VI. MẸO TỐI ƯU CHẤT LƯỢNG

### 1. Chống lặp văn phong (Anti-Repetition)
Cứ mỗi 20-30 chương, thêm vào prompt:
```
LƯU Ý: Tránh lặp lại các cụm từ sau đây (đã dùng quá nhiều trong các 
chương trước): [liệt kê 5-10 cụm từ bị lặp].
Hãy đa dạng hóa cách miêu tả cảnh chiến đấu, nội tâm, và đối thoại.
```

### 2. Kiểm soát độ dài chương
- Web novel chuẩn: **2,500 – 3,500 từ / chương**
- Nếu AI viết quá ngắn, yêu cầu: *"Mở rộng chương X, thêm chi tiết 
  nội tâm, miêu tả cảnh vật, và đối thoại giữa các nhân vật"*
- Nếu AI viết quá dài: *"Cô đọng lại, giữ nhịp nhanh, cắt bớt miêu tả 
  rườm rà"*

### 3. Checkpoint review (Mỗi 50 chương)
Cứ mỗi 50 chương hoàn thành, dành 1 phiên riêng để:
```
Hãy đọc lại toàn bộ TRANG_THAI_HIEN_TAI và kiểm tra:
1. Có mâu thuẫn logic nào giữa các chương không?
2. Có nhân vật nào bị "mất tích" (xuất hiện rồi biến mất)?
3. Nhịp độ power-up của MC có quá nhanh/chậm không?
4. Các phục bút đang treo đã được giải quyết chưa?
Liệt kê tất cả vấn đề tìm thấy.
```

### 4. Xử lý giới hạn output của AI
Nếu AI bị cắt giữa chừng (output quá dài), nói:
```
Tiếp tục viết từ đoạn cuối cùng. Không lặp lại phần đã viết.
```

---

## VII. SO SÁNH CÁC MÔ HÌNH AI PHÙ HỢP

| Tiêu chí | Claude (Opus/Sonnet) | Gemini (Flash/Pro) | GPT-4o |
|:---|:---|:---|:---|
| Văn phong Tiếng Việt | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| Sáng tạo cốt truyện | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| Nhất quán nhân vật | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐ |
| Độ dài output / lần | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ |
| Tốc độ | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ |

**Khuyến nghị:** 
- Dùng model mạnh (Claude Opus, Gemini Pro) cho batch viết chính.
- Dùng model nhanh (Flash) cho việc tạo dàn ý chi tiết và cập nhật trạng thái.

---

## VIII. BẮT ĐẦU: CHECKLIST TRƯỚC KHI VIẾT CHƯƠNG ĐẦU TIÊN

- [ ] File cốt truyện tổng thể: ✅ Đã có (DAN_Y_CHI_TIET_TRUYEN_TU_TIEN_CAU_DAO.md)
- [ ] Tạo file TRANG_THAI_HIEN_TAI.md (bộ nhớ dài hạn)
- [ ] Tạo thư mục Quyen_1_Tiem_Long_Kho_Tu/
- [ ] Giao AI tạo dàn ý chi tiết 200 chương cho Quyển 1
- [ ] Viết batch đầu tiên: Chương 1–5
- [ ] Review & cập nhật trạng thái
- [ ] Lặp lại cho đến khi hoàn thành Quyển 1
