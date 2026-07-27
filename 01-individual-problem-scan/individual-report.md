## Scan rộng (Phase 1)

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại / Tốn thời gian |Sinh viên mới ra trường không biết cách viết CV như thế nào| Sinh viên năm 3-4 mới ra trường muốn tìm việc làm|Sinh viên viết CV nhưng không biết đưa cái gì vào project hay kinh nghiệm làm việc,...|
| 2 | Tốn thời gian / AI có thể làm tốt hơn |Sinh viên năm nhất mới lên Hà Nội loay hoay trong việc tìm trọ| Sinh viên năm nhất|Mỗi lần tìm trọ phải lên các group tìm rất lâu và có thể bị miss hoặc không tìm được nhà trọ phù hợp với tài chính yêu cầu của mình, và cũng không biết nhà trọ đó có còn phòng không, mất thời gian nhắn tin, hỏi phòng.|
| 3 | Tốn thời gian / AI có thể tốt hơn |Học sinh lớp 12 không biết đặt nguyện vọng, định hướng | Học sinh lớp 12 |Học sinh lớp 12 loay hoay không biết định hướng, không biết nên đặt nguyện vọng vào trường nào phù hợp với số điểm của mình, không biết mình nên theo ngành nào mà hầu hết là theo ngành hot, theo bố mẹ định hướng mà bản thân không thực sự yêu thích ngành đó|
| 4 | Pain từ người khác / AI có thể tốt hơn | Tìm chỗ đỗ xe khi vào khu vực trung tâm thành phố | Người tìm bãi đỗ xe, đặc biệt người mới tới khu vực | Khu trung tâm ít bãi đỗ, người lái phải chạy vòng nhiều lần hoặc hỏi người xung quanh mới tìm được chỗ hợp lệ |
| 5 | Pain từ người khác / AI có thể tốt hơn |Nhân viên gán nhãn dữ liệu rất mất thời gian để gán nhãn |Nhân viên gán nhãn dữ liệu|Việc gán nhãn dữ liệu thủ công là công đoạn tốn kém, mất thời gian và rất lâu và không đồng nhất giữa các annotator.|
| 6 | | | | |
| 7 | | | | |
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |

---

# Phase 2 — Top 3 Problem Cards + draft workflow

## Chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Định hướng, đề xuất trường đại học cho học sinh cấp 3 | Actor rõ (học sinh lớp 12), workflow lặp lại mỗi mùa tuyển sinh, impact lớn vì ảnh hưởng quyết định dài hạn | "Phù hợp" đo bằng tiêu chí gì cho đủ khách quan, dữ liệu điểm chuẩn có cập nhật kịp không |
| 2 | Điều chỉnh CV theo từng JD khi ứng tuyển | Workflow rõ, lặp lại mỗi lần ứng tuyển, có thể đo bằng thời gian và tỷ lệ pass vòng lọc hồ sơ | Tỷ lệ pass ATS khó verify vì không phải ứng viên nào cũng biết kết quả sàng lọc |
| 3 | Tìm bãi đỗ xe khu trung tâm | Pain thật, nhiều người gặp, có thể đo bằng thời gian tìm chỗ | Cần dữ liệu bãi đỗ real-time, có thể vượt phạm vi một buổi lab |

## Problem Card #1 — Định hướng đại học cho học sinh cấp 3

**Problem 1 câu:**
Học sinh lớp 12 mất nhiều thời gian tự tổng hợp thông tin tuyển sinh rải rác từ nhiều nguồn để chọn trường/ngành phù hợp, dễ chọn sai vì thiếu đối chiếu hệ thống giữa năng lực, tài chính và khoảng cách.

**Actor:**
Học sinh lớp 12 chuẩn bị đăng ký nguyện vọng đại học (có phụ huynh hỗ trợ).

**Thời điểm / bối cảnh:**
Giai đoạn cuối năm lớp 12, trước hạn đăng ký nguyện vọng xét tuyển.

**Current workflow:**

```text
1. Tìm thông tin trường/ngành trên nhiều website, fanpage, group tư vấn
2. Ghi chú điểm chuẩn các năm trước của từng trường/ngành
3. Đối chiếu với điểm thi/học bạ của bản thân
4. Hỏi thêm thầy cô, anh chị khóa trước, người quen
5. Cân nhắc thêm tài chính và khoảng cách địa lý
6. Tổng hợp thành danh sách nguyện vọng
7. Điền và nộp nguyện vọng
```

**Bottleneck:**
Bước 1-3 và 5 — thông tin không tập trung, không thống nhất giữa các nguồn, học sinh phải tự đối chiếu điểm/tài chính/khoảng cách thủ công nên dễ bỏ sót hoặc hiểu sai.

**Impact:**
Có thể mất 1-2 tuần tự tìm hiểu; rủi ro chọn nguyện vọng không phù hợp năng lực hoặc tài chính, dẫn đến trượt nguyện vọng hoặc phải điều chỉnh ngành học về sau.

**Success metric:**
Giảm thời gian tổng hợp thông tin từ khoảng 1-2 tuần xuống còn vài ngày; giảm số lần học sinh phải điều chỉnh lại danh sách nguyện vọng sau khi có điểm thi.

**Non-AI alternative:**
Bảng tổng hợp điểm chuẩn công khai từ Bộ GD&ĐT/trường + buổi tư vấn hướng nghiệp trực tiếp từ thầy cô.

**AI hypothesis:**
AI tổng hợp thông tin học sinh (điểm, sở trường, tài chính, khoảng cách) rồi so khớp với dữ liệu điểm chuẩn/ngành để đề xuất danh sách trường phù hợp; học sinh vẫn tự quyết định chọn.

**Quick gut:**
Workflow.

### Draft current workflow

```text
CURRENT STATE — khoảng 1-2 tuần

[1 Tìm thông tin trường/ngành: rải rác nhiều buổi]
→ [2 Ghi chú điểm chuẩn các năm: vài giờ]
→ [3 Đối chiếu điểm bản thân: vài giờ]  <-- bottleneck
→ [4 Hỏi thầy cô/người quen: vài buổi]
→ [5 Cân nhắc tài chính/khoảng cách: vài giờ]  <-- bottleneck
→ [6 Tổng hợp danh sách nguyện vọng: 1 buổi]
→ [7 Nộp nguyện vọng: 30']
```

### Draft future workflow

```text
FUTURE STATE — còn vài ngày

[1 Học sinh nhập điểm, sở trường, tài chính, khoảng cách: 15']
→ [2 AI so khớp với dữ liệu điểm chuẩn/ngành: vài phút]
→ [3 AI đề xuất danh sách trường/ngành phù hợp: vài phút]
→ [4 Học sinh + phụ huynh review, hỏi thêm thầy cô: 1-2 buổi]  <-- human boundary
→ [5 Học sinh chốt và nộp nguyện vọng: 30']

Fallback: đề xuất AI không hợp lý (sai điểm chuẩn, bỏ sót ngành) → quay lại tư vấn trực tiếp thầy cô.
```

## Problem Card #2 —Cách viết CV cho sinh viên mới ra trường

**Problem 1 câu:**
Sinh viên mới ra trường còn mơ hồ, chưa có kinh nghiệm trong việc làm CV

**Actor:**
Người đi xin việc, đặc biệt sinh viên năm 3, năm 4.

**Thời điểm / bối cảnh:**
Mỗi lần chuẩn bị nộp hồ sơ cho một vị trí/công ty.

**Current workflow:**

```text
1. Xác định rõ điểm mạnh, điểm yếu của bản thân
2. Gạch ra keyword/kỹ năng chính mà bản thân có
3. Không nên đưa vào những kĩ năng lan man không cần thiết
4. Viết lại/sắp xếp phần kỹ năng, kinh nghiệm cho khớp keyword
5. Kiểm tra chính tả, format
6. Xuất file & nộp đơn ứng tuyển
```

**Bottleneck:**
Bước 2-4 — đối chiếu keyword và viết lại nội dung, phải tự nhớ lại kinh nghiệm bản thân để chọn từ ngữ phù hợp với từng JD.

**Impact:**
Nếu ứng tuyển mà không nêu được kĩ năng mình có, viết chung chung thì CV không match keyword có thể bị hệ thống lọc hồ sơ (ATS) loại ngay từ vòng đầu.

**Success metric:**
Giảm thời gian chỉnh 1 CV từ khoảng 30-45 phút xuống dưới 10 phút; tăng tỷ lệ CV qua được vòng lọc hồ sơ.

**Non-AI alternative:**
nêu những project, kinh nghiệm làm việc mà mình có.

**AI hypothesis:**
AI đọc giúp tạo CV dựa trên những kĩ năng, project mà mình có, bỏ đi những kĩ năng dư thừa khiến CV lan man.
**Quick gut:**
Workflow.

### Draft current workflow

```text
CURRENT STATE — 30-45 phút/lần

[1 Đọc JD: 5']
→ [2 Gạch keyword: 5']  <-- bottleneck
→ [3 Rà CV gốc: 10']  <-- bottleneck
→ [4 Viết lại/sắp xếp CV: 15']  <-- bottleneck
→ [5 Kiểm tra chính tả/format: 5']
→ [6 Xuất file & nộp: 5']
```

### Draft future workflow

```text
FUTURE STATE — dưới 10 phút/lần

[1 Nêu những điểm mạnh, điểm yếu, kinh nghiệm làm việc và project mình làm cho AI: 1']
→ [2 AI trích keyword và chọn lọc những thông tin phù hợp: 1']
→ [3 AI gợi ý phần cần nhấn mạnh/sắp xếp lại: 1']
→ [4 AI tạo ra CV: 5']  <-- human boundary
→ [5 Xuất file & nộp: 2']

Fallback: 
```

## Problem Card #3 — Tìm trọ cho sinh viên 

**Problem 1 câu:**
Sinh viên tốn rất nhiều thời gian tìm trọ phù hợp với yêu cầu về tài chính, tiện ích,... của mình

**Actor:**
Sinh viên đại học

**Thời điểm / bối cảnh:**
Đến mùa nhập học, sinh viên năm nhất mới ra trường vội vàng tìm trọ sao cho tiện lợi trong việc di chuyển đến trường

**Current workflow:**

```text
1. Lên group tìm trọ quanh khu vực mình định sinh sống
2. Tìm kiếm những phòng trọ phù hợp với nhu cầu tài chính, tiện ích mà mình cần
3. Nhắn hỏi chủ trọ để xin thông tin phòng
4. Nếu trọ hết thì lại phải tiếp tục tìm tiếp

```

**Bottleneck:**
Bước 2: Mất thời gian lướt tìm trọ và không biết trọ đó còn không

**Impact:**
Mỗi lần lên group tìm trọ có thể mất 10-20 phút, thậm chí là hàng tiếng nhưng vẫn không tìm được trọ ưng ý

**Success metric:**
Giảm thời gian tìm trọ chỉ với 1 click chuột.

**Non-AI alternative:**


**AI hypothesis:**
Ứng dụng tổng hợp dữ liệu nhà trọ, gợi ý nhà trọ phù hợp với yêu cầu của mình.

**Quick gut:**


### Draft current workflow

```
Người dùng có nhu cầu tìm phòng trọ
            │
            ▼
Tham gia các group Facebook/Zalo hoặc nền tảng đăng tin
            │
            ▼
Lướt qua nhiều bài đăng để tìm phòng phù hợp
(Giá, vị trí, diện tích, tiện ích,...)
            │
            ▼
Nhắn tin hoặc gọi điện cho chủ trọ để hỏi:
- Phòng còn không?
- Giá hiện tại?
- Có thể xem phòng không?
            │
            ▼
        Phòng còn?
      ┌───────────────┐
      │               │
     Có             Không
      │               │
      ▼               ▼
Đặt lịch xem      Quay lại bước tìm kiếm
phòng hoặc thuê   và tiếp tục lướt tin
```

### Draft future workflow

```text
FUTURE STATE — dưới 5 phút/lần

[1 Mở app, nhập khu vực muốn tìm trọ: vài giây]
→ [2 Nhập nhu cầu về tài chính, diện tích, dịch vụ,... mong muốn: vài giây]
→ [3 App gợi ý phòng trọ còn trống và phù hợp với yêu cầu: 1-2 phút]
→ [4 Người dùng chọn phòng trọ ưng ý và liên hệ với chủ trọ: 1']  <-- humanundary

Fallback: Phòng trọ đã hết chỗ và mất thời gian tìm.
```

## Chọn card muốn pitch nhất

Card tôi muốn pitch nhất:

```text
Problem Card #1 — Định hướng đại học cho học sinh cấp 3
```

Vì sao:

```text
Bài này có actor rõ nhất, ảnh hưởng đến quyết định dài hạn của học sinh (chọn ngành/trường), workflow lặp lại mỗi mùa tuyển sinh và có thể đo được bằng thời gian tổng hợp thông tin cũng như số lần phải điều chỉnh nguyện vọng.
```

Câu hỏi tôi muốn nhóm challenge:

```text
Nếu AI đề xuất trường/ngành dựa trên dữ liệu điểm chuẩn cũ hoặc thiếu cập nhật, làm sao học sinh biết để không tin nhầm? Boundary và cơ chế kiểm tra lại nên đặt ở đâu trong workflow?
```