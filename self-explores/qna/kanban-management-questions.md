# Kanban Management - Essential Questions & Answers

## Muc Luc (Table of Contents)

1. [Khai niem co ban (Fundamental Concepts)](#1-khai-niem-co-ban)
2. [Nguyen tac & Thuc hanh (Principles & Practices)](#2-nguyen-tac--thuc-hanh)
3. [Kanban Board & Visualization](#3-kanban-board--visualization)
4. [WIP Limits (Gioi han cong viec dang lam)](#4-wip-limits)
5. [Flow Metrics (Cac chi so do luong)](#5-flow-metrics)
6. [Cumulative Flow Diagram (CFD)](#6-cumulative-flow-diagram)
7. [Service Level Expectations (SLE)](#7-service-level-expectations)
8. [Daily Operations & Management](#8-daily-operations--management)
9. [Common Mistakes & How to Avoid](#9-common-mistakes--how-to-avoid)
10. [Professional Scrum with Kanban (PSK)](#10-professional-scrum-with-kanban)

---

## 1. Khai Niem Co Ban

### Q1.1: Kanban giai quyet van de gi?
**A:** Kanban giai quyet **van de hang doi (queue problem)** - khi he thong khong du kha nang xu ly luong yeu cau, dan den viec hinh thanh hang doi, lang phi thoi gian va tai nguyen.

### Q1.2: Su khac biet giua Kanban, Kanban System va Kanban Method la gi?
**A:**
- **Kanban**: Tu tieng Nhat nghia la "the hinh anh" hoac "the tin hieu" - don gian la mot cach goi cho "card"
- **Kanban System (Pull System)**: He thong keo - cho phep lam viec voi muc lang phi toi thieu va ton kho thap
- **Kanban Method**: Phuong phap hien dai (2010, David Anderson) - bao gom Kanban + Kanban System + nguyen tac, gia tri, thuc hanh tot nhat, huong dan de cai tien lien tuc

### Q1.3: Flow (dong chay) la gi trong Kanban?
**A:** Flow la su chuyen dong cua gia tri xuyen suot he thong phat trien san pham. Kanban toi uu hoa flow bang cach cai thien hieu qua, hieu suat va tinh du doan cua quy trinh.

### Q1.4: Dinh nghia cua Kanban theo Kanban Guide la gi?
**A:** Kanban la **mot chien luoc de toi uu hoa dong chay gia tri thong qua mot quy trinh su dung he thong keo truc quan, gioi han cong viec dang lam (WIP-limited pull system)**.

### Q1.5: Push System va Pull System khac nhau nhu the nao?
**A:**
- **Push System**: Moi nguoi lam xong phan viec cua minh va "day" cong viec sang buoc tiep theo, bat ke nguoi tiep nhan da san sang chua
- **Pull System**: Nguoi o buoc tiep theo "keo" cong viec khi ho da san sang va co kha nang xu ly. Dieu nay tranh hinh thanh hang doi va lang phi.

---

## 2. Nguyen Tac & Thuc Hanh

### Q2.1: 4 nguyen tac co ban cua Kanban Method la gi?
**A:**
1. **Bat dau tu nhung gi ban lam hom nay** - Khong thay doi cau truc to chuc, chi truc quan hoa va toi uu workflow hien tai
2. **Dong y cai tien lien tuc** - Khong ngung tim kiem cach cai thien tung buoc nho
3. **Ton trong quy trinh, vai tro, trach nhiem hien tai** - Kanban phai thich ung voi to chuc, khong phai nguoc lai
4. **Khuyen khich hanh vi lanh dao tu moi nguoi** - Tu quan ly, trach nhiem ca nhan, hop tac

### Q2.2: 6 thuc hanh chinh cua Kanban la gi?
**A:**
1. **Truc quan hoa workflow** - Su dung Kanban Board
2. **Gioi han Work In Progress (WIP)** - Han che so luong item dang lam
3. **Quan ly flow** - Dam bao dong cong viec hieu qua, khong co bottleneck
4. **Lam ro chinh sach quy trinh** - Mo ta ro rang cac quy tac lam viec
5. **Thiet lap vong phan hoi** - Dinh ky danh gia va dieu chinh
6. **Cai tien tap the, tien hoa thu nghiem** - Su dung mo hinh va phuong phap khoa hoc

### Q2.3: "Stop starting and start finishing" nghia la gi?
**A:** Day la khau hieu cua Kanban - **Ngung bat dau them cong viec moi, tap trung hoan thanh cong viec dang lam**. Dieu nay giup duy tri flow on dinh va tranh lang phi.

### Q2.4: Chinh sach ro rang (Explicit Policies) la gi va tai sao quan trong?
**A:** Chinh sach ro rang la cac quy tac duoc viet ra va cong khai cho toan bo doi nhu:
- Cach xu ly item khan cap
- WIP limits cho moi column
- Tieu chi de chuyen item sang buoc tiep theo
- Definition of Done

**Quan trong vi:** Giup moi nguoi hieu va thuc hien nhat quan, tao su minh bach va ho tro tu quan ly.

---

## 3. Kanban Board & Visualization

### Q3.1: Kanban Board can bao gom nhung gi?
**A:**
- **Diem bat dau va ket thuc** - Khi nao cong viec duoc coi la "started" va "finished"
- **Dinh nghia work items** - Don vi gia tri di chuyen qua he thong (VD: Product Backlog Items)
- **Trang thai workflow** - Cac buoc cong viec tu bat dau den ket thuc (it nhat 1 trang thai active)
- **Chinh sach ro rang** - Cach cong viec di chuyen qua moi trang thai
- **Chinh sach WIP limits** - Gioi han so luong item o moi cot

### Q3.2: "Done" sub-column dung de lam gi?
**A:** "Done" sub-column giup phan biet:
- Item dang trong trang thai "In Progress" cua buoc do
- Item da hoan thanh buoc do va san sang de duoc "keo" sang buoc tiep theo

### Q3.3: Swimlane dung de lam gi?
**A:** Swimlane dung de:
- Phan loai cong viec theo loai (VD: Bug, Feature, Urgent)
- Phan loai theo thanh vien doi
- Phan loai theo do uu tien hoac class of service
- Theo doi cac du an khac nhau tren cung 1 board

### Q3.4: Buffer Column la gi va khi nao su dung?
**A:** Buffer Column la cot dem giua 2 buoc cong viec, dung de:
- Chua item da hoan thanh buoc truoc nhung chua bat dau buoc tiep
- Giup can bang luong cong viec giua cac buoc
- Phat hien bottleneck khi buffer day len

### Q3.5: Board variations pho bien la gi?
**A:**
- **Urgent swimlane** - Cho cong viec khan cap
- **Buffer columns** - Cot dem giua cac buoc
- **Swimlane theo team member** - Phan cong viec theo nguoi
- **Multiple boards** - Nhieu board cho cac muc dich khac nhau

---

## 4. WIP Limits

### Q4.1: WIP Limits la gi va tai sao quan trong?
**A:** WIP Limits la **gioi han so luong item toi da dang duoc xu ly** tai moi buoc trong workflow.

**Quan trong vi:**
- Tao ra Pull System - chi bat dau cong viec moi khi co kha nang
- Tranh hinh thanh hang doi
- Giup phat hien bottleneck
- Tang tap trung va hop tac
- Giam da nhiem (multitasking) - mat 30% nang suat

### Q4.2: Lam sao de xac dinh WIP Limit phu hop?
**A:**
- **Diem bat dau:** WIP Limit = So nguoi co the lam buoc do
- **Dieu chinh:** Thu nghiem 1-2 tuan, quan sat va thay doi theo thuc te
- **Luu y:** Neu nhanh hon o buoc sau, co the tang WIP limit (VD: review nhanh gap doi thi WIP = 2 x so reviewer)
- **Quan trong:** Phai **can bang** de giam thoi gian cho va hang doi

### Q4.3: WIP Limit qua cao hoac qua thap thi sao?
**A:**
- **Qua cao:** Item tich tu, tao hang doi, mat loi ich cua Kanban
- **Qua thap:** Team member bi nhan roi, khong tan dung het nguon luc

### Q4.4: Khi nao duoc phep vuot WIP Limit?
**A:** **Chi khi co item khan cap (urgent)** theo chinh sach da dinh truoc. Item khan cap can:
- Duoc danh dau ro rang (mau khac, swimlane rieng)
- La ngoai le, khong phai thuong xuyen
- Co chinh sach ro rang ve the nao la "khan cap"

### Q4.5: Little's Law la gi va ap dung nhu the nao?
**A:** Little's Law mo ta moi quan he:

```
Average Cycle Time = Average WIP / Average Throughput
```

**Ap dung:** Neu Cycle Time qua dai, hanh dong dau tien la **giam WIP**. Cang nhieu item dang lam cung luc, cang mat nhieu thoi gian de hoan thanh moi item.

---

## 5. Flow Metrics

### Q5.1: 4 chi so flow co ban can theo doi la gi?
**A:**
1. **Work in Progress (WIP)** - So item da bat dau nhung chua hoan thanh
2. **Cycle Time** - Thoi gian tu khi bat dau den khi hoan thanh 1 item
3. **Work Item Age** - Thoi gian tu khi bat dau den hien tai (cho item chua xong)
4. **Throughput** - So item hoan thanh trong 1 don vi thoi gian

### Q5.2: Lead Time va Cycle Time khac nhau nhu the nao?
**A:**
- **Lead Time:** Tu khi **yeu cau duoc tao** (customer order) den khi **giao hang** - goc nhin khach hang
- **Cycle Time:** Tu khi **bat dau lam** (team starts) den khi **hoan thanh** - goc nhin team

**VD mua xe:** Lead Time = tu khi dat hang den khi nhan xe. Cycle Time = tu khi bat dau san xuat den khi xong (khong tinh thoi gian cho giay to)

### Q5.3: Throughput la gi va do nhu the nao?
**A:** Throughput la **so luong item hoan thanh trong 1 khoang thoi gian** (VD: 10 items/tuan, 25 items/thang).

**Cong dung:**
- Hieu hieu suat trong qua khu
- Du doan kha nang trong tuong lai
- Phat hien xu huong (dang nhanh len, cham di, hay on dinh?)

### Q5.4: Work Item Age la gi va tai sao quan trong?
**A:** Work Item Age (Aging WIP) la **thoi gian tu khi bat dau den hien tai** cho item dang trong tien trinh.

**Quan trong vi:**
- La chi so du bao (leading indicator) - giup phat hien van de som
- Phat hien item bi "mac ket" can duoc chu y
- Ap dung nguyen tac "first in, first out" - hoan thanh item cu truoc khi bat dau cai moi
- Giong nhu do an sap het han - can an/xu ly truoc khi hong

### Q5.5: Dung metrics nao cho tung su kien Scrum?
**A:**
| Metric | Sprint Planning | Daily Scrum | Sprint Review | Retrospective |
|--------|----------------|-------------|---------------|---------------|
| Cycle Time | | | Also | Key |
| Throughput | Key | | Key | Key |
| WIP | | Key | Also | Key |
| Work Item Age | Also | Key | | Also |

---

## 6. Cumulative Flow Diagram

### Q6.1: CFD la gi va cach doc?
**A:** CFD la bieu do vung chong (stacked area chart) hien thi:
- **Truc X:** Thoi gian
- **Truc Y:** So luong item tich luy
- **Cac vung mau:** Dai dien cho cac trang thai trong workflow

**Cach doc:**
- **Chieu cao vung:** So item o trang thai do
- **Do nghieng:** Toc do item di chuyen qua trang thai
- **Khoang cach ngang giua cac duong:** Cycle Time hoac Lead Time

### Q6.2: CFD cho biet dieu gi ve van de trong workflow?
**A:**
- **Vung DO (Not Started) tang nhanh:** Tao nhieu item hon kha nang xu ly - can them nguoi hoac giam input
- **Vung XANH LA (Done) tang nhanh:** Team dang nhanh roi, co the can bo sung cong viec hoac dieu chuyen nguon luc
- **Vung XANH DUONG (In Progress) tang nhanh:** WIP vuot kiem soat, team bat dau nhieu nhung khong hoan thanh - can ap dung WIP Limits chat che hon

### Q6.3: Lam sao tinh cac metrics tu CFD?
**A:**
- **WIP:** Chieu cao cua vung "In Progress" tai 1 thoi diem
- **Lead Time:** Khoang cach ngang tu khi item vao "Not Started" den khi vao "Done"
- **Cycle Time:** Khoang cach ngang tu khi item vao "In Progress" den khi vao "Done"
- **Throughput:** Muc tang cua vung "Done" trong 1 khoang thoi gian

### Q6.4: Tai sao khong nen bo qua CFD?
**A:** CFD cung cap:
- **Du lieu lich su** - khong chi la snapshot nhu Kanban Board
- **Xu huong** - thay doi theo thoi gian
- **Nhieu metrics trong 1 bieu do** - WIP, Lead Time, Cycle Time, Throughput
- **Phat hien bottleneck** som hon

---

## 7. Service Level Expectations

### Q7.1: SLE la gi va khac voi commitment nhu the nao?
**A:** SLE (Service Level Expectation) la **du bao ve Cycle Time dua tren du lieu lich su**, bao gom:
- Mot khoang thoi gian (VD: 8 ngay)
- Mot muc xac suat (VD: 85%)

**VD:** "85% cong viec se hoan thanh trong 8 ngay hoac it hon"

**Khac voi commitment:**
- SLE la **ky vong** dua tren du lieu, khong phai **cam ket** dua tren uoc tinh
- SLE chap nhan su khong chac chan trong cong viec tri thuc
- SLE duoc cap nhat khi co du lieu moi

### Q7.2: Lam sao xac dinh SLE phu hop?
**A:**
1. Su dung **Cycle Time Scatterplot** de xem hieu suat qua khu
2. Chon percentile phu hop (50%, 70%, 85%, 95%)
3. Xac dinh muc do chac chan team muon dat duoc
4. **VD:** Neu 85% item hoan thanh trong 6 ngay -> SLE = 6 ngay voi 85% do tin cay

### Q7.3: Dung SLE de lam gi?
**A:**
- **Phat hien van de flow** - item nao dang vuot SLE?
- **Giao tiep voi stakeholder** - dat ky vong thuc te ve thoi gian giao hang
- **Kich hoat hanh dong** - khi item vuot percentile, can dieu tra va xu ly
- **Cai tien lien tuc** - theo doi va dieu chinh SLE theo thoi gian

### Q7.4: Aging WIP Chart dung de lam gi?
**A:** Aging WIP Chart hien thi:
- Cac item dang xu ly va vi tri trong workflow
- Thoi gian moi item da o trang thai hien tai
- Percentile lines (30%, 50%, 70%, 95%) tu du lieu lich su
- **Mau sac chi thi rui ro:** Xanh = tot, Vang = chu y, Do = rui ro cao

**Loi ich:** Phat hien som item co nguy co vuot SLE de hanh dong kip thoi.

---

## 8. Daily Operations & Management

### Q8.1: Daily Meeting (Daily Scrum) trong Kanban/Scrumban tap trung vao gi?
**A:** Tap trung vao **flow** va **hanh dong** de duy tri flow:
- **Item nao bi block?** Lam gi de unblock?
- **Item nao dang cham hon du kien?** Work Item Age la bao nhieu?
- **Item nao sap hoac da vuot SLE?** Lam gi de hoan thanh?
- **Co yeu to nao ngoai board anh huong den cong viec hom nay?**
- **Co thong tin moi nao thay doi ke hoach?**
- **Da vuot WIP limit chua?** Lam gi de hoan thanh item dang lam?

### Q8.2: Lam gi khi phat hien bottleneck?
**A:**
1. **Xac dinh nguyen nhan:** Thieu nguon luc? Thieu ky nang? Quy trinh khong hieu qua?
2. **Hanh dong ngay:**
   - Chuyen nguoi tu buoc khac sang ho tro
   - Pair work - nguoi co kinh nghiem ho tro nguoi it kinh nghiem
   - Giam WIP limit de giam ap luc
3. **Hanh dong dai han:**
   - Dao tao cross-functional
   - Tu dong hoa
   - Them nguon luc
   - Cai tien quy trinh

### Q8.3: Lam gi khi team member bi nhan roi?
**A:**
- **Ho tro nguoi khac** trong buoc hien tai hoac buoc khac
- **Lam viec theo cap (pair work)** de dao tao lan nhau
- **Cai tien quy trinh** - viet tai lieu, tu dong hoa
- **Giam WIP limit** o cac buoc truoc de can bang luong cong viec

### Q8.4: Retrospective trong Kanban/Scrumban tap trung vao gi?
**A:**
- **Phan tich CFD** - xu huong, bottleneck
- **Danh gia flow metrics** - WIP, Cycle Time, Throughput thay doi nhu the nao?
- **Dieu chinh Definition of Workflow:**
  - Thay doi trang thai workflow
  - Dieu chinh WIP limits
  - Sua doi SLE
  - Thay doi batch size
- **Thiet ke thi nghiem** - thu cai tien va do luong ket qua

---

## 9. Common Mistakes & How to Avoid

### Q9.1: Sai lam #1 - Khong dinh nghia WIP Limits
**A:** **Neu khong co WIP Limits, ban KHONG dang su dung Kanban!**

**Giai phap:**
- Bat dau voi WIP Limit = so nguoi lam o moi buoc
- Dieu chinh sau khi quan sat thuc te

### Q9.2: Sai lam #2 - Khong ton trong WIP Limits
**A:** Team dinh nghia WIP Limits nhung lien tuc vi pham vi "chi 1 lan" -> lan sau lap lai -> mat het loi ich.

**Giai phap:**
- Chi vi pham khi co item KHAN CAP theo chinh sach
- Item khan cap phai duoc danh dau ro rang
- Thao luan voi team khi muon vi pham

### Q9.3: Sai lam #3 - Lam viec tren "Ghost Tasks"
**A:** Ghost Task la cong viec dang lam nhung KHONG hien thi tren board -> mat kiem soat WIP, mat tracking metrics.

**Giai phap:**
- Moi cong viec deu phai co card tren board
- Thao luan voi quan ly ve anh huong cua viec "chen ngang"
- Thiet lap chinh sach ro rang

### Q9.4: Sai lam #4 - Bo qua CFD
**A:** Chi nhin Kanban Board (snapshot) ma khong phan tich CFD (xu huong lich su).

**Giai phap:**
- Cap nhat CFD thuong xuyen
- Review CFD trong Daily va Retrospective
- Su dung cong cu tu dong tao CFD

### Q9.5: Cac dau hieu cho thay flow co van de?
**A:**
- **WIP tang:** Bat dau nhieu nhung khong hoan thanh
- **Cycle Time tang:** Item mat nhieu thoi gian hon binh thuong
- **Throughput giam:** Hoan thanh it item hon
- **Work Item Age cao:** Item "mac ket" lau khong di chuyen
- **Hang doi hinh thanh:** Tich tu o 1 buoc nao do

---

## 10. Professional Scrum with Kanban (PSK)

### Q10.1: Kanban va Scrum ket hop nhu the nao?
**A:** Kanban **bo sung** cho Scrum, khong thay the:
- Sprint van la WIP Limit o cap cao (gioi han cong viec trong 1 Sprint)
- Them WIP Limits chi tiet hon cho tung buoc trong Sprint
- Su dung flow metrics de cai thien quy trinh
- Scrum events van giu nguyen, them goc nhin flow

### Q10.2: Definition of Workflow la gi?
**A:** Definition of Workflow la **su hieu biet chung cua team** ve:
- Trang thai workflow (cac cot tren board)
- Khi nao cong viec bat dau va ket thuc
- WIP Limits cho moi trang thai
- Chinh sach keo (pull policies)
- SLE

**Luu y:** Pham vi co the vuot ra ngoai Sprint, bao gom ca hoat dong truoc va sau Sprint.

### Q10.3: Sprint trong Scrum voi Kanban co gi khac?
**A:**
- Sprint van la **vong phan hoi** de inspect va adapt
- **Khong chi giao gia tri 1 lan/Sprint** - co the giao nhieu lan trong Sprint
- Su dung Sprint events de:
  - Review va adapt Definition of Workflow
  - Phan tich flow metrics
  - Cai tien quy trinh

### Q10.4: Cau hoi can tra loi trong Daily Scrum (flow-based)?
**A:**
1. Item nao bi block va lam gi de unblock?
2. Cong viec nao cham hon du kien? Work Item Age la bao nhieu? Da vi pham SLE chua?
3. Co yeu to nao ngoai board anh huong den kha nang hoan thanh hom nay?
4. Co thong tin moi nao thay doi ke hoach?
5. Da vi pham WIP limit chua? Lam gi de hoan thanh cong viec dang lam?

### Q10.5: Dau la cac thuc hanh Kanban cho Scrum Team?
**A:**
1. **Truc quan hoa Workflow** - Kanban Board
2. **Gioi han WIP** - Sprint la WIP Limit, them limits chi tiet hon
3. **Quan ly tich cuc work items** - Theo doi Work Item Age, phan hoi nhanh voi item bi block
4. **Inspect va Adapt Definition of Workflow** - Dieu chinh trong Retrospective

---

## Cau Hoi Tu Kiem Tra (Self-Assessment Questions)

### Hieu Biet Co Ban
1. Kanban giai quyet van de gi trong doanh nghiep?
2. Giai thich su khac biet giua Push System va Pull System?
3. 4 nguyen tac co ban cua Kanban la gi?
4. 6 thuc hanh chinh cua Kanban la gi?

### WIP va Flow
5. Tai sao WIP Limits quan trong trong Kanban?
6. Lam sao xac dinh WIP Limit ban dau?
7. Little's Law mo ta moi quan he gi?
8. Khi nao duoc phep vuot WIP Limit?

### Metrics
9. 4 flow metrics co ban la gi?
10. Lead Time va Cycle Time khac nhau nhu the nao?
11. Work Item Age dung de lam gi?
12. Throughput dung de du doan gi?

### CFD va SLE
13. CFD cho biet nhung thong tin gi?
14. Lam sao tinh Cycle Time tu CFD?
15. SLE khac voi commitment nhu the nao?
16. Khi nao item can duoc chu y dac biet?

### Scrum voi Kanban
17. Kanban bo sung cho Scrum nhu the nao?
18. Definition of Workflow bao gom nhung gi?
19. Dung metrics nao trong Sprint Planning? Daily Scrum? Retrospective?
20. Daily Scrum tap trung vao cau hoi nao?

---

## Tai Lieu Tham Khao

- The Kanban Guide for Scrum Teams (Scrum.org, 2021)
- A Kanban Primer for Scrum Teams (Yuval Yeret, Steve Porter)
- 4 Key Flow Metrics and How to Use Them in Scrum's Events
- Deliver on Time with Service Level Expectations (SLEs)
- Aging Work in Progress: Managing Work Flow

---

*Tài liệu được tổng hợp từ khóa học Kanban/Scrum/Scrumban và các tài liệu chuẩn bị cho chứng chỉ Professional Scrum with Kanban (PSK).*
