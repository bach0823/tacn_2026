# UNIT 05 — Spreadsheets and Databases

## 1. TỪ VỰNG CHÍNH (Vocabulary)

| Từ/Cụm từ (EN) | Phiên âm | Nghĩa (VI) | Gợi nhớ |
|---|---|---|---|
| **spreadsheet** | /ˈspred.ʃiːt/ | bảng tính (chương trình) | spread = trải rộng, sheet = tờ giấy |
| **worksheet** | /ˈwɜːk.ʃiːt/ | trang tính (trong một file) | work = làm việc, sheet = trang |
| **cell** | /sel/ | ô tính | ô chứa giao giữa hàng và cột |
| **column** | /ˈkɒl.əm/ | cột | hàng dọc (A, B, C...) |
| **row** | /rəʊ/ | hàng | hàng ngang (1, 2, 3...) |
| **formula (formulae)** | /ˈfɔː.mjə.lə/ | công thức | |
| **recalculate** | /ˌriːˈkæl.kjə.leɪt/ | tính toán lại | re- = lại, calculate = tính toán |
| **database management system (DBMS)** | | hệ quản trị cơ sở dữ liệu | DBMS |
| **relational database** | | cơ sở dữ liệu quan hệ | relational = thuộc về quan hệ |
| **record** | /ˈrek.ɔːd/ | bản ghi | một tập hợp các trường dữ liệu |
| **field** | /fiːld/ | trường dữ liệu | một cột thông tin đơn lẻ |
| **query** | /ˈkwɪə.rì/ | truy vấn, câu hỏi truy vấn | trích xuất dữ liệu theo điều kiện |
| **key field** | | trường khóa | trường chung để liên kết các bảng |
| **invoice** | /ˈɪn.vɔɪs/ | hóa đơn thanh toán | |
| **quantity** | /ˈkwɒn.tə.ti/ | số lượng | quant = số lượng |
| **description** | /dɪˈskrɪp.ʃən/ | mô tả, chi tiết | describe = mô tả |
| **VAT (Value Added Tax)** | | thuế giá trị gia tăng (GTGT) | VAT |
| **grand total** | /ɡrænd ˈtəʊ.təl/ | tổng số tiền cuối cùng | grand = lớn, total = tổng |
| **password** | /ˈpɑːs.wɜːd/ | mật khẩu | pass = đi qua, word = từ |
| **index** | /ˈɪn.deks/ | chỉ mục, danh mục | danh sách sắp xếp tăng tốc tìm kiếm |
| **sort** | /sɔːt/ | sắp xếp | phân loại thứ tự A-Z hoặc 1-9 |

---

### BẢNG TỔNG HỢP — BẢNG TÍNH VS CƠ SỞ DỮ LIỆU

⚠️ Bảng này là nguồn ôn chính cho dạng bài "so sánh tính năng bảng tính và cơ sở dữ liệu".

| Tính năng / Đặc điểm | Bảng tính (Spreadsheets) | Cơ sở dữ liệu (Databases / DBMS) |
|---|---|---|
| **Cấu trúc lưu trữ** | Các ô (cells) phân bố theo hàng (rows) và cột (columns). | Các bản ghi (records) chứa nhiều trường (fields) tạo thành tệp tin (files). |
| **Mục đích chính** | Lập kế hoạch tài chính, tính toán ngân sách, vẽ biểu đồ. | Lưu trữ lượng dữ liệu khổng lồ, quản lý mối quan hệ thông tin. |
| **Khả năng tự động** | Tự động tính toán lại toàn bộ khi giá trị ô thay đổi. | Thực hiện truy vấn phức tạp (queries) trên nhiều bảng liên quan. |
| **Tính bảo mật** | Bảo mật cơ bản cho sheet/file. | Bảo mật chi tiết theo từng trường (field-level password protection). |
| **Sự liên kết** | Liên kết cơ bản giữa các ô/sheet. | Liên kết nhiều tệp tin thông qua **trường khóa (key field)**. |

---

## 2. BÀI ĐỌC SONG NGỮ (Reading — EN | VI)

### Spreadsheets & Worksheets

**English (Original)**
This **worksheet** shows the income and expenses of a company. Amounts are given in $ millions. The terms worksheet and **spreadsheet** are often used interchangeably. However, technically, a worksheet is a collection of **cells** grouped on a single layer of the file. A spreadsheet refers to both the computer program that displays data in **rows** and **columns**, and to the table which displays numbers in rows and columns.

> **[VI]** Trang tính (**worksheet**) này hiển thị doanh thu và chi phí của một công ty. Các số liệu được tính theo đơn vị triệu USD. Thuật ngữ worksheet và **spreadsheet** (bảng tính) thường được sử dụng thay thế cho nhau. Tuy nhiên, về mặt kỹ thuật, một worksheet là một tập hợp các **ô** (cells) được nhóm lại trên một lớp duy nhất của tệp. Một spreadsheet đề cập đến cả chương trình máy tính hiển thị dữ liệu dưới dạng các **hàng** (rows) và **cột** (columns), và bảng hiển thị các con số dưới dạng hàng và cột.
>
> 📌 *Tóm tắt:* Trang tính (worksheet) là tập hợp các ô trên một lớp tệp tin. Bảng tính (spreadsheet) chỉ chương trình hoặc bảng hiển thị số liệu hàng/cột.

Spreadsheets are used in business for financial planning - to **keep a record** of accounts, to **analyze budgets** or to **make specific calculations**. In a spreadsheet, you can enter text, numbers and **formulae**. If you change the value of a cell, the values of the spreadsheet are **automatically recalculated**. Spreadsheet programs can also generate a variety of charts and graphs.

> **[VI]** Bảng tính được sử dụng trong kinh doanh để lập kế hoạch tài chính - nhằm **ghi chép** các tài khoản, **phân tích ngân sách** hoặc **thực hiện các phép tính cụ thể**. Trong một bảng tính, bạn có thể nhập văn bản, số và **công thức**. Nếu bạn thay đổi giá trị của một ô, các giá trị của bảng tính sẽ **tự động được tính toán lại**. Các chương trình bảng tính cũng có thể tạo ra nhiều loại biểu đồ và đồ thị khác nhau.
>
> 📌 *Tóm tắt:* Thay đổi giá trị ở một ô sẽ khiến toàn bộ bảng tính tự động tính toán lại.

### Letter Accompanying the Invoice

**English (Original)**
**Dear Ms Atkinson**,

> **[VI]** **Kính gửi cô Atkinson**,
>
> 📌 *Tóm tắt:* Thư gửi khách hàng xác nhận đã gửi đơn hàng gồm 4 PC để bàn kèm màn hình, 2 laptop, máy in laser, cơ sở dữ liệu D5 và phần mềm diệt virus.

I am writing to confirm that we have sent you four desktop PCs plus screens, two laptops and a laser printer, along with a D5 database, and an anti-virus program for each of the computers. Please allow two weeks for delivery.

> **[VI]** Tôi viết thư này để xác nhận rằng chúng tôi đã gửi cho cô bốn máy tính để bàn kèm màn hình, hai máy tính xách tay và một máy in laser, cùng với một cơ sở dữ liệu D5 và một chương trình chống virus cho mỗi máy tính. Vui lòng đợi hai tuần để giao hàng.
>
> 📌 *Tóm tắt:* Người gửi đính kèm hóa đơn và yêu cầu thanh toán qua Internet hoặc séc.

I am enclosing two copies of your **invoice**.

> **[VI]** Tôi xin đính kèm hai bản sao **hóa đơn** của cô.
>
> 📌 *Tóm tắt:* 

We would be grateful if you could make your payment by cheque or directly to our bank account through the Internet.

> **[VI]** Chúng tôi sẽ rất biết ơn nếu cô có thể thanh toán bằng séc hoặc chuyển khoản trực tiếp vào tài khoản ngân hàng của chúng tôi qua Internet.
>
> 📌 *Tóm tắt:* 

We are also delighted to inform you that we are offering our clients an online course called *A paperless office*, free of charge. Please contact us if you require any further information.

> **[VI]** Chúng tôi cũng rất vui mừng được thông tin đến cô rằng chúng tôi đang cung cấp cho khách hàng một khóa học trực tuyến miễn phí có tên là *Văn phòng không giấy tờ*. Vui lòng liên hệ với chúng tôi nếu cô cần thêm bất kỳ thông tin nào.
>
> 📌 *Tóm tắt:* 

**Yours sincerely**,

> **[VI]** **Trân trọng**,
>
> 📌 *Tóm tắt:* 

*Ian Pegg*

> **[VI]** *Ian Pegg*
>
> 📌 *Tóm tắt:*

### Databases & Relational DBMS

**English (Original)**
A **database** is a collection of related data, and the software used in databases to store, organize and retrieve the data is called the **database management system**, or `DBMS`. However, we often use the word database to cover both meanings. A database can manage any type of data, including text, numbers, images, sound, video and hyperlinks.

> **[VI]** **Cơ sở dữ liệu** là một tập hợp dữ liệu liên quan, và phần mềm được sử dụng trong các cơ sở dữ liệu để lưu trữ, tổ chức và truy xuất dữ liệu được gọi là **hệ quản trị cơ sở dữ liệu**, hay `DBMS`. Tuy nhiên, chúng ta thường sử dụng từ cơ sở dữ liệu để bao hàm cả hai nghĩa. Một cơ sở dữ liệu có thể quản lý bất kỳ loại dữ liệu nào, bao gồm văn bản, số, hình ảnh, âm thanh, video và các siêu liên kết.
>
> 📌 *Tóm tắt:* Hệ quản trị cơ sở dữ liệu (DBMS) lưu trữ, tổ chức dữ liệu.

Information is entered into the database via **fields**. Each field holds a separate piece of information, and the fields are grouped together in **records**. Therefore, a record about an employee might consist of several fields which give their name, address, phone number, date of birth, salary and length of employment with the company. Records are grouped together into **files** which hold large amounts of information. Files can easily be updated - you can always change fields, add new records or delete old ones.

> **[VI]** Thông tin được nhập vào cơ sở dữ liệu thông qua các **trường** (fields). Mỗi trường chứa một phần thông tin riêng biệt, và các trường được nhóm lại với nhau thành các **bản ghi** (records). Do đó, một bản ghi về một nhân viên có thể gồm nhiều trường hiển thị tên, địa chỉ, số điện thoại, ngày sinh, mức lương và thời gian làm việc tại công ty của họ. Các bản ghi được nhóm lại với nhau thành các **tệp tin** (files) chứa lượng thông tin lớn. Các tệp tin có thể dễ dàng được cập nhật - bạn luôn có thể thay đổi các trường, thêm bản ghi mới hoặc xóa những bản ghi cũ.
>
> 📌 *Tóm tắt:* Thông tin đi qua các trường (fields), nhóm thành bản ghi (records), tạo nên tệp (files).

A database program lets you create an **index** - a list of records ordered according to the content of certain fields. This helps you to **search** the database and **sort** records into numerical or alphabetical order very quickly. Modern databases are **relational** - that is, they are made up of related files: customers and orders, vendors and purchases, etc. Two database files can be related as long as they have a common **key field**. Databases like *Oracle*, *DB2* and *MySQL* can manage these relationships.

> **[VI]** Chương trình cơ sở dữ liệu cho phép bạn tạo một **chỉ mục** (index) - danh sách các bản ghi được sắp xếp theo nội dung của các trường nhất định. Điều này giúp bạn **tìm kiếm** cơ sở dữ liệu và **sắp xếp** (sort) các bản ghi theo thứ tự số hoặc chữ cái rất nhanh chóng. Các cơ sở dữ liệu hiện đại có tính **quan hệ** (relational) - nghĩa là chúng được tạo thành từ các tệp liên quan: khách hàng và đơn hàng, nhà cung cấp và giao dịch mua hàng, v.v. Hai tệp cơ sở dữ liệu có thể được liên kết miễn là chúng có một **trường khóa** (key field) chung. Các cơ sở dữ liệu như *Oracle*, *DB2* và *MySQL* có thể quản lý các mối quan hệ này.
>
> 📌 *Tóm tắt:* Các tệp tin được liên kết dạng quan hệ (relational) qua trường khóa (key field).

A database **query** function allows you to extract information according to certain conditions or criteria. Most aspects of the program can be protected by user-defined **passwords** and other security devices. For example, if you wanted to share an employee's personal details but not their commission, you could protect the commission field.

> **[VI]** Hàm **truy vấn** (query) cơ sở dữ liệu cho phép bạn trích xuất thông tin theo các điều kiện hoặc tiêu chí nhất định. Hầu hết các khía cạnh của chương trình có thể được bảo vệ bằng **mật khẩu** do người dùng thiết lập và các thiết bị bảo mật khác. Ví dụ: nếu muốn chia sẻ chi tiết cá nhân của nhân viên chứ không muốn chia sẻ tiền hoa hồng của họ, bạn có thể bảo vệ trường hoa hồng đó.
>
> 📌 *Tóm tắt:*

## 3. NGỮ PHÁP (Grammar)

### 3.1 Quy tắc danh từ số nhiều (Plural Nouns)

Trong tiếng Anh, việc chuyển danh từ từ số ít sang số nhiều tuân theo các quy tắc sau:

| Quy tắc | Dạng biến đổi | Ví dụ số ít | Ví dụ số nhiều |
|---|---|---|---|
| **Thông thường** | Thêm `-s` | record, client, key | records, clients, keys |
| **Kết thúc bằng: -s, -sh, -x, -ch** | Thêm `-es` | address, index, fax, virus | addresses, indexes, faxes, viruses |
| **Phụ âm + y** | Đổi `y` -> `i` + `-es` | company, query, salary | companies, queries, salaries |
| **Nguyên âm + y** | Chỉ thêm `-s` | birthday, day | birthdays, days |
| **Bất quy tắc (Irregular)** | Biến đổi nguyên âm hoặc giữ nguyên | man, woman, mouse, analysis, criterion, formula | men, women, mice, analyses, criteria, formulae (formulas) |

### 3.2 Phát âm đuôi số nhiều "-s" hoặc "-es"
Cách phát âm đuôi `-s/-es` phụ thuộc vào âm cuối cùng của danh từ số ít:

1. **Phát âm là `/s/`:** Sau các phụ âm vô thanh: `/p/`, `/t/`, `/k/`, `/f/`, `/θ/`.
   - *Ví dụ:* laptops, graphs, networks, spreadsheets.
2. **Phát âm là `/ɪz/`:** Sau các âm rít: `/s/`, `/z/`, `/ʃ/`, `/tʃ/`, `/dʒ/`.
   - *Ví dụ:* databases, switches, taxes, packages, viruses.
3. **Phát âm là `/z/`:** Sau các âm còn lại (các phụ âm hữu thanh và nguyên âm).
   - *Ví dụ:* passwords, orders, tables, systems, queries.

---

## 4. BÀI TẬP & ĐÁP ÁN (Exercises & Answer Key)

### Exercise A — Spreadsheets: True or False?

State whether these statements are True (T) or False (F). Correct the false ones:
1. A spreadsheet displays information in the form of a table with a lot of columns and rows.
2. In a spreadsheet, you can only enter numbers and formulae.
3. You cannot change the width of columns in a spreadsheet.
4. Spreadsheet programs can generate a variety of charts and graphs.
5. Spreadsheets cannot be used as databases.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **True** — Bảng tính hiển thị thông tin dưới dạng bảng gồm nhiều cột và hàng.
2. **False** — You can enter text, numbers, and formulae (bảng tính có thể nhập cả chữ, số và công thức).
3. **False** — You can easily adjust the width of columns (hoàn toàn có thể thay đổi độ rộng cột).
4. **True** — Đúng, phần mềm bảng tính có thể tạo nhiều loại biểu đồ.
5. **False** — Spreadsheets can be used as simple databases (bảng tính có thể dùng làm cơ sở dữ liệu đơn giản).

</details>

### Exercise B — Invoice Completion

Complete the invoice using words from the box:
*Company, Product, Description, Quantity, Price, VAT (21%), Grand total*

Name: Ruth Atkinson
Address: 38 High Street, Galway
Date: 16 May 2008

- (1) ________________: Media Market, Fax: 1 662 2367
- (2) ________________: PC hardware and software items
- (3) ________________: Ulysses Classic, 2GB of RAM, 1TB HD
- (4) ________________: 4 units
- (5) ________________: 850€ each
- Sub-total: 6,865€
- (6) ________________ (21%): 1,441€
- (7) ________________: 8,306€

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **Company** — Tên công ty cung cấp: Media Market.
2. **Product** — Loại mặt hàng máy tính.
3. **Description** — Mô tả thông số kỹ thuật (RAM, ổ cứng).
4. **Quantity** — Số lượng mặt hàng mua.
5. **Price** — Đơn giá mặt hàng.
6. **VAT (21%)** — Thuế GTGT 21%.
7. **Grand total** — Tổng số tiền thanh toán cuối cùng.

</details>

### Exercise C — Business Letter Completion

Complete the letter using phrases from the box:
*Yours sincerely, I am writing to, Dear Ms Atkinson, We would be grateful if you could, I am enclosing, Please contact us*

16 May 2008
Ruth Atkinson
(1) ________________,
(2) ________________ confirm that we have sent you four desktop PCs plus screens, two laptops and a laser printer, along with a D5 database. Please allow two weeks for delivery.
(3) ________________ two copies of your invoice.
(4) ________________ make your payment by cheque or directly to our bank account through the Internet.
We are also offering our clients an online course called *A paperless office*, free of charge. (5) ________________ if you require any further information.
(6) ________________,
*Ian Pegg*

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **Dear Ms Atkinson** — Lời chào đầu thư trang trọng.
2. **I am writing to** — Mục đích viết thư (xác nhận đơn hàng).
3. **I am enclosing** — Đính kèm tài liệu (hóa đơn).
4. **We would be grateful if you could** — Đề nghị lịch sự khách hàng thanh toán.
5. **Please contact us** — Hỗ trợ liên lạc khi khách hàng cần thêm thông tin.
6. **Yours sincerely** — Lời kết thư trang trọng đi kèm tên người ký.

</details>

### Exercise D — Database Statements Completion

Complete these statements about databases using information from the reading text:
1. A database management system (DBMS) is used to __________, __________ and __________ data from a database.
2. Information is entered into a database via __________.
3. Each field holds a __________ piece of information.
4. Updating a file means changing fields, __________ new records or __________ old ones.
5. Some advantages of a database program over a manual filing system are: it is much __________ to consult and update, and it occupies much __________ space.
6. Access to a common database over a network can be protected by using user-defined __________ and other security devices.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **store, organize, retrieve** — Các chức năng cơ bản của DBMS.
2. **fields** — Dữ liệu được nạp thông qua các trường.
3. **separate** — Mỗi trường chứa một phần thông tin riêng biệt.
4. **adding, deleting** — Hoạt động cập nhật tệp tin cơ sở dữ liệu.
5. **faster, less** — Lợi ích của DB điện tử so với hệ thống thủ công giấy tờ.
6. **passwords** — Bảo mật quyền truy cập chung bằng mật khẩu người dùng.

</details>

### Exercise E — Database Crossword Clues

Solve the clues based on database vocabulary:
1. A collection of data stored in a PC in a systematic way: D _ _ _ _ _ _ E
2. A unit of a database file made up of related fields: R _ _ _ _ D
3. A single piece of information in a record: F _ _ _ D
4. A type of database that maintains separate but related files linked by a common field: R _ _ _ _ _ _ _ _ L
5. A system of connected computers sharing a database: N _ _ _ _ _ K
6. To look for specific information, for example the name of an employee: S _ _ _ C H
7. To classify records into numerical or alphabetical order: S _ _ T
8. A tool/function that allows you to extract information that meets certain criteria: Q _ _ _ Y

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **DATABASE** — Cơ sở dữ liệu.
2. **RECORD** — Bản ghi.
3. **FIELD** — Trường dữ liệu.
4. **RELATIONAL** — Cơ sở dữ liệu quan hệ.
5. **NETWORK** — Hệ thống mạng máy tính.
6. **SEARCH** — Tìm kiếm thông tin.
7. **SORT** — Sắp xếp thứ tự A-Z hoặc số học.
8. **QUERY** — Câu lệnh truy vấn trích xuất dữ liệu.

</details>

### Exercise F — Plurals Formation and Pronunciation

1. **Write the plural form of the following words:**
   - client: ______________
   - key: ______________
   - query: ______________
   - businessman: ______________
   - fax: ______________
   - salary: ______________
   - mouse: ______________
   - virus: ______________

2. **Put the plural words into the correct pronunciation column (/s/, /ɪz/, or `/z/`):**
   *laptops, graphs, networks, spreadsheets, databases, switches, taxes, packages, passwords, orders, tables, systems*
   - **/s/:** ____________________________________________
   - **/ɪz/:** ___________________________________________
   - **/z/:** ____________________________________________

---

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **Plural forms:**
   - client → **clients** (thêm -s thông thường).
   - key → **keys** (nguyên âm e + y, chỉ thêm -s).
   - query → **queries** (phụ âm r + y, đổi y thành i + -es).
   - businessman → **businessmen** (số nhiều bất quy tắc).
   - fax → **faxes** (kết thúc bằng -x, thêm -es).
   - salary → **salaries** (phụ âm r + y, đổi y thành i + -es).
   - mouse → **mice** (số nhiều bất quy tắc).
   - virus → **viruses** (kết thúc bằng -s, thêm -es).

2. **Pronunciation Sorting:**
   - **/s/:** laptops, graphs, networks, spreadsheets — kết thúc bằng âm vô thanh `/p/`, `/f/` (phát âm của ph), `/k/`, `/t/`.
   - **/ɪz/:** databases, switches, taxes, packages — kết thúc bằng âm rít `/z/`, `/tʃ/` (ch), `/ks/` (x), `/dʒ/` (ge).
   - **/z/:** passwords, orders, tables, systems — kết thúc bằng âm hữu thanh `/d/`, `/r/`, `/l/`, `/m/`.

</details>

### 🧪 Mini Quiz

**Câu 1 (Trắc nghiệm):** What is the plural form of the word "criterion"?
- a. criterions
- b. criteria
- c. criterias

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 1 (Trắc nghiệm):**
*   **b. criteria ✓** — Số nhiều bất quy tắc của danh từ "criterion" (tiêu chí).
*   - a. criterions ✗ — Dạng từ sai.
*   - c. criterias ✗ — Dạng từ sai (thừa chữ s).

</details>

**Câu 2 (Trắc nghiệm):** Which field is used to connect two separate files in a relational database?
- a. query field
- b. index field
- c. key field

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 2 (Trắc nghiệm):**
*   **c. key field ✓** — Trường khóa chung dùng để liên kết mối quan hệ giữa các bảng.
*   - a. query field ✗ — Không có khái niệm này để liên kết.
*   - b. index field ✗ — Chỉ mục dùng để tăng tốc tìm kiếm, không phải trường khóa liên kết.

</details>

**Câu 3 (Điền từ):** The plural suffix "-es" in the word "viruses" is pronounced as /_____/.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 3 (Điền từ):**
*   **iz** (hoặc **/ɪz/**) — Đuôi -es trong "viruses" phát âm là /ɪz/.

</details>

**Câu 4 (Điền từ):** A database management system is abbreviated as _____________.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 4 (Điền từ):**
*   **DBMS** — Viết tắt của Database Management System.

</details>

**Câu 5 (Điền từ):** State whether this is True or False: "When you change the value of a cell in a spreadsheet, you must manually recalculate the total." _____________

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 5 (Điền từ):**
*   **False** — Giá trị bảng tính sẽ tự động tính toán lại nhờ các công thức lập sẵn.

</details>

**Câu 6 (Trắc nghiệm):** In a database, fields are grouped together to form:
- a. columns
- b. records
- c. spreadsheets

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 6 (Trắc nghiệm):**
*   **b. records ✓** — Tập hợp các trường thông tin tạo thành một bản ghi.
*   - a. columns ✗ — Cột là cấu trúc bảng tính.
*   - c. spreadsheets ✗ — Bảng tính là tệp tin lớn.

</details>

**Câu 7 (Nối):** Nối thuật ngữ với định nghĩa tương ứng:
1. cell — A. Một tập hợp các trường thông tin về một đối tượng trong database
2. record — B. Hàm trích xuất dữ liệu theo các tiêu chí xác định
3. query — C. Giao điểm giữa một hàng và một cột trong bảng tính

---

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 7 (Nối):**
*   **1-C** (cell — Giao điểm giữa một hàng và một cột trong bảng tính)
*   **2-A** (record — Một tập hợp các trường thông tin về một đối tượng trong database)
*   **3-B** (query — Hàm trích xuất dữ liệu theo các tiêu chí xác định)

---

</details>


## 5. GLOSSARY TỔNG HỢP

| Thuật ngữ | Nghĩa | Gợi nhớ | Xuất hiện ở |
|---|---|---|---|
| **anti-spyware** | chống gián điệp | anti = chống, spy = gián điệp | Letter |
| **cell** | ô tính | | Reading 1, Ex A |
| **column** | cột | | Reading 1, Ex A |
| **database** | cơ sở dữ liệu | | Reading 3, Ex E |
| **DBMS** | hệ quản trị cơ sở dữ liệu | Database Management System | Reading 3, Ex D |
| **description** | mô tả | describe = mô tả | Ex B |
| **formula (formulae)** | công thức | | Reading 1, Ex B |
| **grand total** | tổng thanh toán | grand = lớn, total = tổng | Ex B |
| **index** | chỉ mục, danh mục | | Reading 3, Ex E |
| **invoice** | hóa đơn | | Reading 2, Ex B |
| **key field** | trường khóa liên kết | key = khóa, field = trường | Reading 3, Ex C |
| **password** | mật khẩu | pass = đi qua, word = từ | Reading 3, Ex D |
| **quantity** | số lượng | quantity | Ex B |
| **query** | truy vấn | | Reading 3, Ex E |
| **recalculate** | tính toán lại | re- = lại, calculate = tính | Reading 1 |
| **record** | bản ghi dữ liệu | | Reading 3, Ex E |
| **relational database** | cơ sở dữ liệu quan hệ | relation = mối quan hệ | Reading 3, Ex E |
| **row** | hàng | | Reading 1, Ex A |
| **sort** | sắp xếp, phân loại | | Reading 3, Ex E |
| **spreadsheet** | bảng tính | spread = trải rộng, sheet = tờ giấy | Reading 1 |
| **VAT** | thuế giá trị gia tăng | Value Added Tax | Ex B |
| **worksheet** | trang tính | work = làm việc, sheet = trang | Reading 1 |

---
> *Tạo mới file Unit 05 từ bản dịch song ngữ và các bài tập đi kèm.*
