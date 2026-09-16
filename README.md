# Mini Hackathon AI — Batch 04 · Lớp 3A

**SPEC → Prototype → Demo.** Đây không phải cuộc thi code — đây là cuộc thi **tư duy sản phẩm AI**.

## 👥 Thành viên nhóm & Phân công vai trò

**Lớp:** 3A · **Phòng:** E403 · **Cụm:** Bàn 1 · **Track:** [Chờ chốt: Track A / Track B]

| Họ và Tên | Mã Học Viên | Vai trò chính | Phần việc đảm nhiệm trong dự án |
|---|---|---|---|
| **Nguyễn Đức Phát** | **2A202602753** | Product Lead & Coordinator | Quản lý dự án, định hình AI Spec, điều phối các mốc Checkpoint, phụ trách video & pitch |
| **Chử Trần Phương Nam** | **2A202602675** | Tech Lead & AI Architect | Kiến trúc AI/LLM pipeline, thiết kế prompt engineering & tool calling, tích hợp backend |
| **Đỗ Thành Đạt** | **2A202602874** | AI & Evaluation Engineer | Xây dựng bộ test Golden Set, thiết lập luồng đánh giá tự động (eval), kiểm thử an toàn |
| **Nguỵ Khắc Phi Long** | **2A202602532** | UX & Evaluation Specialist | Khảo sát người dùng (User Research), thiết kế luồng trải nghiệm (UI/UX Mock), thu thập bằng chứng |

> Nhóm copy nguyên file README này về repo của mình, rồi điền bảng trên. Cột **Phần việc đảm nhiệm** ghi càng cụ thể càng tốt.

- Thời lượng: **47,5 giờ** từ phát đề đến thuyết trình (ca 3A) — LAB 5 (phát đề + build) · LEC 6 (tiếp tục build theo ca) · LAB 6 (vòng thi)
- Nhóm: **3-4 người** · thi theo phòng (E403 / E402), chia cụm rồi chung kết phòng — xem *Thể thức thi*
- **Chia cụm theo bàn**, không cần chung đề tài. Chủ đề tự chọn trong khuôn khổ đề bài
- Nhóm nhỏ thì **chọn lát cắt nhỏ**, và phải có **khảo sát nỗi đau thật** — đây là chỗ ăn điểm nặng nhất

## Bắt đầu từ đâu?

1. Đọc **`01-challenge-brief.md`** để hiểu khung chung và 5 tiêu chí, rồi **`tracks/README.md`** để chọn track và đề.
2. Mở **`02-guide.md`** — hướng dẫn từng giai đoạn, đứng ở đâu đọc mục đó.
3. Viết spec theo **`03-ai-spec-template.md`** — deliverable trung tâm của cả sự kiện.
4. Đọc **`04-rubric.md`** ngay từ đầu — biết trước bài được chấm theo tiêu chí nào.

| File / thư mục | Nội dung |
|---|---|
| `01-challenge-brief.md` | Đề bài: bảng 5 track · lát cắt · ràng buộc chung · 5 tiêu chí nghiệm thu |
| `02-guide.md` | Hướng dẫn 5 giai đoạn: khám phá → spec → build → đo & validate → demo |
| `03-ai-spec-template.md` | Template AI Spec (nộp tại **hạn chốt spec** — xem Lịch) |
| `04-rubric.md` | Rubric 100 điểm (25 nộp checkpoint + 67 chấm bài + 8 điểm R6) + checklist xác minh 6 mốc |
| `tracks/` | **5 track**, mỗi đề cùng một khung mục: A VLearn Tutor · B Trợ lý Discord · C Lesson Studio · D Học tập thích ứng & tương tác · E Làn mở (trong phạm vi AI20k) — bắt đầu từ `tracks/README.md` |
| `data/` | Dữ liệu thật đã ẩn danh: `vlearn-pack/` (chatlog VLearn tutor + 6 transcript bài giảng + 2 bộ slide bản hackathon) và **`discord-pack/` (tin nhắn Discord khoá 4 + bản tin bot)** — dùng để tìm bằng chứng và xây golden set. **Đọc `data/README.md` trước** |
| `further-reading/` | Tài liệu tham khảo có tóm lược tiếng Việt: **Mom Test** (phỏng vấn), **PAIR Guidebook** (Google, 6 chương), **HAX Toolkit** (Microsoft, 18 nguyên tắc), **JTBD Playbook** + worksheet — bắt đầu từ `further-reading/README.md` |

## Lịch — 6 checkpoint (ca 3A · 47,5 giờ)

| Mốc | Cần hoàn thành | Hạn (ca 3A) |
|---|---|---|
| — | Khai mạc 17:30 · phát đề 18:00 | 16/9 |
| **CP1** | Canvas 4 ô + đội trưởng + **link repo GitHub công khai** | **19:30** · 16/9 |
| **CP2** | Cho thấy **luồng hoạt động** — bấm thử được, hoặc sơ đồ luồng | **21:00** · 16/9 |
| **CP3** | **Video thao tác** 30 giây + **số đo** (thử bao nhiêu, đúng bao nhiêu) | **16:00** · 17/9 |
| **CP4** | Chốt `spec.md` — **khoá chuẩn "đạt"** · tự khai phần chưa xong | **21:00** · 17/9 |
| **CP5** | Slide PDF + **video demo dự phòng cho buổi pitch** — nộp cuối | **13:00** · 18/9 |
| **CP6** | Thuyết trình · không nộp thêm | **17:30** · 18/9 |

**CP1 đến CP5 mỗi mốc 5 điểm.** Nộp đúng hạn được đủ, nộp muộn là **0 điểm mốc đó** — không bù được bằng mốc khác.

## Làm bài lúc nào

| | |
|---|---|
| **Thời gian tự làm** | Ngoài giờ học, và trong buổi **LEC ngày 17/9** |
| **Coach hỗ trợ** | Trên lớp và trên Discord |
| **Buổi LAB 18/9 · 17:30–21:00** | Đây là **vòng thi**, không phải giờ làm bài |

Hai phòng cùng ca dùng chung lịch mốc. Năm link form phát đủ từ đầu — xong mốc nào nộp mốc đó, không phải chờ.

## Giải thích từng mốc

### CP1 · Chốt Canvas + repo

**Để làm gì:** chốt rõ **làm cho ai và giải vấn đề gì** trước khi bắt tay vào code. Bỏ qua bước này thì hay gặp cảnh làm xong mới nhận ra không ai cần đến.

**Nộp:**
- Canvas điền đủ 4 ô theo mẫu trong `01-challenge-brief.md`
- Họ tên và **mã học viên của đội trưởng**
- **Link repo GitHub** đã để công khai
- **Khai báo willing user** — người sẵn sàng cho nhóm thử sản phẩm ở CP5. Cần ít nhất 2 người, khai từ đây

> **Khai willing user ngay từ CP1, đừng để đến CP5.** Khối R6 ở CP5 yêu cầu có ít nhất 2 willing user đã khai ở mốc này. Đến lúc cần mới đi tìm người thì không kịp.

---

### CP2 · Cho thấy luồng hoạt động

**Để làm gì:** nhìn được cả luồng từ đầu đến cuối — người dùng bấm gì trước, thấy gì sau, kết thúc ở đâu. Vẽ ra giấy thì phát hiện chỗ hổng trong mười phút; code xong mới thấy thì mất cả buổi sửa.

**Nộp một trong ba thứ, thứ nào cũng được:**
- **Bản mock bấm được** — Figma, trang tĩnh, Canva, bất cứ thứ gì click qua lại được
- **Sơ đồ luồng** vẽ tay hay vẽ máy, miễn thấy rõ các bước
- **Video quay màn hình** đi hết một lượt

**Chưa cần AI chạy thật** — cái đó để CP3. Mốc này để nhẹ, chỉ cần cho thấy nhóm đang đi hướng nào.

---

### CP3 · Video thao tác + số đo

**Để làm gì:** biết sản phẩm của mình **đang đúng đến đâu**. Có con số thì mới biết nên sửa chỗ nào tiếp, và lúc pitch cũng có cái để nói thay vì nói suông.

**Nộp hai thứ:**

**1 · Video thao tác — 30 giây, quay màn hình.** Bấm thật trên sản phẩm, thấy AI trả kết quả thật. Không cần dựng, không cần lồng tiếng.

**2 · Số đo — thử bao nhiêu lần, đúng được bao nhiêu.**

Đây là con số cho biết sản phẩm tốt đến đâu. Cách làm:

```
1. Chuẩn bị một bộ câu thử  — ví dụ 20 câu hỏi người dùng hay hỏi
2. Cho sản phẩm chạy hết 20 câu đó
3. Đếm bao nhiêu câu ra kết quả đạt chuẩn nhóm tự đặt
```

| Chưa đạt | Đạt |
|---|---|
| *"Sản phẩm chạy tốt"* | *"Thử 21 câu, 13 câu trả đúng có dẫn nguồn, 8 câu sai hoặc bịa"* |
| *"Độ chính xác cao"* | *"Thử 30 file, 24 file tóm tắt đúng ý chính, 6 file bỏ sót"* |

**Số xấu vẫn được đủ điểm** — miễn là số thật. 13 trên 21 mà phân tích được vì sao 8 câu kia sai thì ăn điểm cao hơn "chạy tốt" không có gì chứng minh.

---

### CP4 · Chốt `spec.md`

**Để làm gì:** chốt **"thế nào là đạt"** trước khi biết kết quả. Đặt chuẩn sau khi đã thấy kết quả thì con số không nói lên điều gì — và người nghe cũng biết vậy.

**Nộp:**
- Link `spec.md` đã chốt — trong đó nhóm **tự chốt "thế nào là đạt"** cho sản phẩm mình
- **Tự khai phần nào chưa làm xong**

Sau 21:00 hôm đó **không sửa chuẩn "đạt" được nữa**.

**Khai thiếu không bị trừ điểm.** Giấu mới bị.

---

### CP5 · Slide + video dự phòng

**Để làm gì:** đảm bảo buổi pitch chạy được **dù mạng hỏng hay máy chết**. Đây cũng là hạn nộp cuối — sau mốc này không nộp thêm gì.

**Nộp:**
- **Slide 6 trang, xuất ra PDF** theo `02-guide.md` §5.1. Nộp PDF chứ không nộp link — link hay hỏng quyền đúng lúc cần
- **Video demo dự phòng** — quay sẵn phần demo. Nếu hôm pitch mạng chết thì BTC chiếu video này và **không trừ điểm**.
