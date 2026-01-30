# Kanban Vocabulary - Tham Khảo Nhanh

> Tài liệu trích xuất từ khóa học Kanban/Scrum/Scrumban với citations để học nhanh.

---

## Mục Lục

1. [Khái Niệm Cơ Bản](#khái-niệm-cơ-bản)
2. [Bốn Nguyên Tắc Kanban](#bốn-nguyên-tắc-kanban)
3. [Sáu Thực Hành Kanban](#sáu-thực-hành-kanban)
4. [Pull System & Flow](#pull-system--flow)
5. [WIP - Work In Progress](#wip---work-in-progress)
6. [Metrics & Đo Lường](#metrics--đo-lường)
7. [Cumulative Flow Diagram (CFD)](#cumulative-flow-diagram-cfd)
8. [Board Variations](#board-variations)
9. [Quy Trình Triển Khai](#quy-trình-triển-khai)
10. [Lỗi Thường Gặp](#lỗi-thường-gặp)

---

## Khái Niệm Cơ Bản

### Kanban (看板)
**Định nghĩa:** Từ tiếng Nhật nghĩa là "tín hiệu trực quan" hoặc "thẻ trực quan"

> **Citation:** Lecture 10 - *Kanban x Kanban System x Kanban Method*

**Bối cảnh lịch sử:**
- Toyota phát triển năm 1953
- David Anderson formalize thành Kanban Method năm 2010

---

### Kanban System (Pull System)
**Định nghĩa:** Hệ thống kéo (Pull) cho phép làm việc với lượng tồn kho tối thiểu và giảm lãng phí

> **Citation:** Lecture 10 - *"Kanban System = Pull System"*

**Nguyên tắc cốt lõi:** Chỉ duy trì lượng công việc cần thiết cho quy trình sản xuất

---

### Kanban Method
**Định nghĩa:** Phương pháp quản lý công việc bao gồm nguyên tắc, giá trị, thực hành tốt và chiến lược tập trung vào cải tiến liên tục

> **Citation:** Lecture 10-12

**Phạm vi áp dụng:**
- Phát triển phần mềm
- Sản xuất
- Dịch vụ
- Knowledge work

---

### Kanban Board
**Định nghĩa:** Công cụ trực quan thể hiện workflow với các cột hiển thị từng bước của quy trình

> **Citation:** Lectures 4, 10, 12, 14-25

**Cấu trúc:**
```
NOT STARTED → WRITE → REVIEW → PUBLISH → DONE
```

**Ví dụ đơn giản:**
```
TO DO → DOING → DONE
```

---

### Kanban Card
**Định nghĩa:** Đại diện cho một task/work item trên Kanban board

> **Citation:** Lecture 25

**Thông tin thường có:**
| Vị trí | Nội dung |
|--------|----------|
| Giữa | Tiêu đề task |
| Trên | Initials người phụ trách |
| Góc | Reference number |
| Dưới | Ngày bắt đầu/kết thúc |

---

### Queue Problem (Vấn Đề Hàng Đợi)
**Định nghĩa:** Tình trạng tích tụ công việc chờ xử lý tại các bước trong workflow

> **Citation:** Lectures 3-4

**Dấu hiệu:** Giống như xếp hàng ở siêu thị hoặc kẹt xe

**Hậu quả:**
- Kém hiệu quả
- Giao hàng chậm
- Khách hàng không hài lòng

**Ý nghĩa:** Queue = "hệ thống bị bệnh" - không thể xử lý real-time demand

---

### Bottleneck (Điểm Nghẽn)
**Định nghĩa:** Bước trong workflow tạo ra queue do thiếu năng lực hoặc tốc độ

> **Citation:** Lectures 4, 12, 18, 27

**Cách nhận biết:**
- Quan sát trực quan: quá nhiều card ở một cột
- Phân tích metrics

**Ví dụ:**
```
WRITE: 2 cards | REVIEW: 6 cards | DONE: 2 cards
                    ↑
              BOTTLENECK!
```

---

## Bốn Nguyên Tắc Kanban

> **Citation:** Lecture 11 - *Four Fundamental Principles*

### 1. Start with What You Do Today
**Ý nghĩa:** Map và visualize workflow hiện tại mà KHÔNG thay đổi gì ngay

**Triết lý:** Kanban thích ứng với workflow của bạn, không phải ngược lại

---

### 2. Agree to Continuously Improve
**Ý nghĩa:** Cam kết cải tiến từng bước để giảm lãng phí

**Phương pháp:** Cải tiến nhỏ, thường xuyên → khách hàng hài lòng có thể dự đoán được

---

### 3. Respect Current Organization
**Ý nghĩa:** Làm việc trong cấu trúc hiện có mà không ép thay đổi tổ chức

**Lợi ích:**
- Giảm kháng cự
- Không sợ mất việc
- Không cần training mới

---

### 4. Encourage Leadership from Everybody
**Ý nghĩa:** Khuyến khích tự quản và trách nhiệm chung trong team

**Yếu tố:**
- Trách nhiệm cá nhân với công việc và kết quả
- Hiểu toàn bộ chuỗi giá trị
- Góc nhìn team thay vì task riêng lẻ

---

## Sáu Thực Hành Kanban

> **Citation:** Lecture 12 - *Six Key Practices*

### 1. Visualize the Workflow
**Công cụ:** Kanban Board

**Mục đích:** Làm công việc hiển thị rõ ràng - ai làm gì, trạng thái ra sao

---

### 2. Limit Work In Progress (WIP)
**Định nghĩa:** Đặt giới hạn tối đa items trong mỗi cột

**Motto:** *"Stop starting and start finishing"*

> **Citation:** Lecture 26-27

---

### 3. Manage the Workflow
**Focus:** Đạt được continuous delivery với queues tối thiểu

**Phương pháp:** Xác định bottlenecks → Hành động khắc phục

---

### 4. Make Process Policies Explicit
**Định nghĩa:** Định nghĩa và công khai các quy tắc quản lý workflow

**Ví dụ:**
- Xử lý urgent items (thẻ đỏ)
- Chính sách buffer column
- Ngưỡng work item age

---

### 5. Implement Feedback Loops
**Định nghĩa:** Chu kỳ inspection và adaptation định kỳ

**Tần suất:** Daily, weekly, hoặc bi-weekly

---

### 6. Improve Collaboratively, Evolve Experimentally
**Quy trình:**
1. Chia sẻ hiểu biết về vấn đề
2. Tạo giải pháp cùng nhau
3. Thử nghiệm thay đổi
4. Quan sát và thảo luận kết quả
5. Xác định bước tiếp theo

---

## Pull System & Flow

### Pull System
**Định nghĩa:** Workflow nơi downstream stages kéo công việc từ upstream

> **Citation:** Lectures 4, 7, 10

**Cơ chế:** Người bên phải kéo công việc từ bên trái

```
WRITE ← REVIEW ← PUBLISH
  ↑        ↑        ↑
Writer   Reviewer  Publisher
         (pulls)   (pulls)
```

**Lợi ích:**
- Tránh tích tụ queue
- Visualize bottlenecks
- Tối ưu hóa resources
- Loại bỏ lãng phí

---

### Push System (Đối lập)
**Định nghĩa:** Upstream đẩy công việc xuống downstream

**Hậu quả:** Queue hình thành tại bottlenecks

```
WRITE → REVIEW → PUBLISH
  ↓        ↓
(pushes) (pushes)
```

---

### Flow (Continuous Flow)
**Định nghĩa:** Tiến trình mượt mà, không gián đoạn của work items qua workflow

**Mục tiêu:** Giảm thiểu thời gian chờ, tối đa hóa nhịp độ giao giá trị

---

## WIP - Work In Progress

### Work In Progress (WIP)
**Định nghĩa:** Số lượng work items đang được làm (items giữa start và done)

> **Citation:** Lectures 26-27, 33

---

### WIP Limits
**Định nghĩa:** Số lượng tối đa work items cho phép trong mỗi cột

> **Citation:** Lectures 7, 12, 19, 26-27, 45-46

**Format hiển thị:** `Current/Limit` (ví dụ: `1/2` = 1 item đang làm, limit là 2)

**Quy tắc khởi đầu:** Bắt đầu với số người available cho mỗi cột

```
WRITE [2/3] → REVIEW [1/2] → DONE
```

---

### Work Item Age (Aging WIP)
**Định nghĩa:** Thời gian đã trôi qua kể từ khi work item bắt đầu

> **Citation:** Lecture 33

**Đo lường:** Đếm ngày bằng dots trên cards (1 dot = 1 ngày)

**Mục đích:**
- Xác định tasks đang gặp khó khăn
- Indicator dự đoán cycle time
- Nguyên tắc "First In, First Out"

---

### Đặt WIP Limits Tối Ưu

| Dấu hiệu | Ý nghĩa |
|----------|---------|
| Quá cao | Cards tích tụ, queues hình thành |
| Quá thấp | Team members idle, chờ upstream |

**Keyword:** BALANCE

---

## Metrics & Đo Lường

### Lead Time
**Định nghĩa:** Thời gian từ khi work item được tạo đến khi hoàn thành (góc nhìn khách hàng)

> **Citation:** Lectures 29-30, 38

**Đo lường:** Từ cột đầu tiên → cột cuối cùng

**Công thức:**
```
Average Lead Time = Tổng lead times / Số items hoàn thành
```

**Target:** Trung bình thấp hơn = tốt hơn

---

### Cycle Time
**Định nghĩa:** Thời gian từ khi team bắt đầu làm đến khi hoàn thành (góc nhìn production)

> **Citation:** Lectures 31, 38

**Quan hệ:** `Cycle Time ≤ Lead Time`

**Công thức:**
```
Lead Time = Cycle Time + Wait Time
```

---

### Throughput
**Định nghĩa:** Số work items hoàn thành trong khoảng thời gian nhất định

> **Citation:** Lectures 32, 38

**Mục đích:**
1. Hiểu performance quá khứ
2. Dự đoán performance tương lai
3. Chẩn đoán workflow

---

### So Sánh 3 Metrics Chính

| Metric | Góc nhìn | Đo gì |
|--------|----------|-------|
| Lead Time | Khách hàng | Từ request → delivery |
| Cycle Time | Team | Từ start work → finish |
| Throughput | Capacity | Items/period |

---

## Cumulative Flow Diagram (CFD)

**Định nghĩa:** Biểu đồ area xếp chồng hiển thị tích lũy work items qua các giai đoạn theo thời gian

> **Citation:** Lectures 36-38

### Cấu trúc CFD
- **Trục Y:** Số work items
- **Trục X:** Timeline (ngày, tuần)
- **Bands:** Mỗi band màu = một workflow column

### Đọc Metrics từ CFD

| Metric | Cách đọc |
|--------|----------|
| WIP | Chiều cao của band màu cụ thể |
| Lead Time | Khoảng cách ngang giữa đỉnh cột đầu và cột cuối |
| Cycle Time | Khoảng cách ngang giữa đỉnh cột working đầu và cột cuối |
| Throughput | Độ tăng chiều cao band "Done" theo thời gian |

---

### Phân Tích CFD - Patterns

> **Citation:** Lecture 37

#### Pattern 1: Backlog Tăng Nhanh Nhất (Đỏ)
**Ý nghĩa:** Work đến nhiều hơn team xử lý được

**Giải pháp:**
- Thêm team members
- Cải thiện hiệu quả
- Giảm incoming work

---

#### Pattern 2: Done Tăng Nhanh Nhất (Xanh lá)
**Ý nghĩa:** Team hoàn thành nhanh hơn incoming rate

**Nguyên nhân:** Có thể idle capacity

---

#### Pattern 3: In-Progress Tăng Nhanh Nhất (Xanh dương)
**Ý nghĩa:** Team bắt đầu nhiều nhưng không hoàn thành (queues hình thành)

**Giải pháp:** Enforce WIP limits!

---

## Board Variations

### Buffer Column (Done Subcolumn)
**Định nghĩa:** Subcolumn trong main column đánh dấu work item "Done" nhưng chưa được kéo downstream

> **Citation:** Lectures 7, 21, 25

**Cấu trúc:**
```
WRITE           |    REVIEW        |  DONE
In Progress|Done|In Progress|Done  |
```

**Mục đích:**
- Hỗ trợ Pull System
- Phơi bày flow problems
- Ngăn queues bằng cách hiển thị wait time

---

### Swimlane
**Định nghĩa:** Lanes ngang chia board để phân tách concerns hoặc owner groups

> **Citation:** Lectures 20-23

#### Urgent Swimlane
```
┌─────────────────────────────────────┐
│ URGENT LANE    [Max: 2/week]        │
│ ⬛⬛ (Red cards)                     │
├─────────────────────────────────────┤
│ NORMAL LANE                         │
│ ⬜⬜⬜⬜                              │
└─────────────────────────────────────┘
```

**Policy cần thiết:** Định nghĩa rõ ràng thế nào là "urgent"

---

#### Team Member Swimlane
```
┌─────────────────────────────────────┐
│ Alice:  ⬜ → ⬜ → ⬜                  │
├─────────────────────────────────────┤
│ Bob:    ⬜ → ⬜                      │
├─────────────────────────────────────┤
│ Charlie: ⬜ → ⬜ → ⬜                │
└─────────────────────────────────────┘
```

---

## Quy Trình Triển Khai

### Five-Step Adoption Roadmap

> **Citation:** Lectures 39-44 (file 39-51.txt)

#### Step 1: Identify the Work
Liệt kê tất cả work items cần hoàn thành → Tạo backlog

---

#### Step 2: Prioritize the Work
**Phương pháp MoSCoW:**
- **M**ust Have
- **S**hould Have
- **C**ould Have
- **W**on't Have

---

#### Step 3: Map the Workflow
Định nghĩa board columns đại diện cho quy trình HIỆN TẠI

**Câu hỏi chính:** Work bắt đầu ở đâu? Các bước tiếp theo là gì?

---

#### Step 4: Define WIP Limits
**Điểm khởi đầu:** Số người available cho mỗi cột

**Sau đó:** Thử nghiệm và điều chỉnh

---

#### Step 5: Enter Kaizen Cycle
**Kaizen (改善):** Tiếng Nhật nghĩa là "cải tiến"

**Vòng lặp Build-Measure-Learn:**
```
    ┌─────────┐
    │  BUILD  │
    │ (Define)│
    └────┬────┘
         ↓
    ┌─────────┐
    │ MEASURE │
    │(Monitor)│
    └────┬────┘
         ↓
    ┌─────────┐
    │  LEARN  │
    │(Analyze)│
    └────┬────┘
         ↓
      REPEAT
```

---

## Lỗi Thường Gặp

> **Citation:** Lectures 45-49 (file 39-51.txt)

### Mistake 1: Không Định Nghĩa WIP Limits
**Vấn đề:** Board không có limits chỉ là visual tool, KHÔNG phải Kanban

**Hậu quả:** Không giải quyết queue problem, không có pull system

---

### Mistake 2: Không Tôn Trọng WIP Limits
**Pattern:** "Chỉ làm một lần" → trở thành hành vi lặp lại

**Hậu quả:** Phá hủy văn hóa continuous flow

---

### Mistake 3: Ghost Tasks
**Định nghĩa:** Team members làm việc trên items KHÔNG hiển thị trên board

**Nguồn gốc:** Boss yêu cầu việc ngoài board; nhân viên sợ nói "không"

**Hậu quả:**
- Không thể verify WIP limits
- Metrics không đáng tin cậy
- Flow visibility bị compromised

---

### Mistake 4: Bỏ Qua CFD
**Vấn đề:** Không phân tích CFD để tìm trends và metrics

**Hậu quả:** Bỏ lỡ cơ hội xác định và sửa vấn đề

---

## Quick Reference Table

| Khái niệm | Lectures chính | Lectures bổ sung |
|-----------|---------------|------------------|
| Queue Problem | 3-4 | 7, 26 |
| Pull System | 7 | 4, 10, 21 |
| Four Principles | 11 | Throughout |
| Six Practices | 12 | Throughout |
| WIP Limits | 26-27 | 7, 12, 19, 45-46 |
| Lead Time | 29-30 | 38 |
| Cycle Time | 31 | 38 |
| Throughput | 32 | 38 |
| CFD | 36-38 | 25 |
| Kaizen Cycle | 44 | 11 |
| Board Variations | 20-24 | 39-51.txt |
| Common Mistakes | 45-49 | 39-51.txt |
| Five-Step Adoption | 39-44 | 39-51.txt |

---

## Tài Liệu Tham Khảo Bổ Sung

Xem thư mục `others/` để có thêm:
- Kanban Guide (PDF)
- Scrum Guide (PDF)
- CFD guides
- Templates cho Lead Time, Throughput, CFD (spreadsheets)

---

*Tài liệu được trích xuất từ khóa học Kanban/Scrum/Scrumban - Tháng 1/2026*
