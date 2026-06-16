# UNIT 04 — The Operating System (OS)

## 1. TỪ VỰNG CHÍNH (Vocabulary)

| Thuật ngữ | Nghĩa | Gợi nhớ | Xuất hiện ở |
|---|---|---|---|
| **accessibility** | khả năng tiếp cận | access = truy cập | Reading 2 |
| **anti-spyware** | phần mềm chống gián điệp | spy = gián điệp | Reading 3, Ex C |
| **appliance** | thiết bị gia dụng | | Reading 3 |
| **applications software** | phần mềm ứng dụng | apply = áp dụng | Reading 1 |
| **command-line** | giao diện dòng lệnh | command = lệnh, line = dòng | Ex F |
| **compatibility** | tính tương thích | compatible = tương thích | Reading 3 |
| **consistency** | tính nhất quán | consistent = đồng nhất | Reading 2 |
| **desktop** | màn hình nền | desk = bàn, top = trên | Reading 2, Ex B |
| **device driver** | trình điều khiển thiết bị | driver = người lái | Reading 1 |
| **dock** | thanh công cụ phím tắt (Mac) | | Ex B |
| **double-click** | nhấp đúp | | Reading 2 |
| **drop-down menu** | trình đơn thả xuống | drop = rơi, down = xuống | Ex B |
| **firewall** | tường lửa | fire = lửa, wall = tường | Reading 3 |
| **folder icon** | biểu tượng thư mục | folder = kẹp tài liệu | Ex B |
| **graphical user interface (GUI)** | giao diện đồ họa người dùng | graph = hình vẽ | Reading 2 |
| **icon** | biểu tượng, hình vẽ | | Reading 2 |
| **intuitive** | trực quan, dễ hiểu ngay | | Reading 2 |
| **launch** | khởi chạy (chương trình) | launch = phóng tên lửa | Reading 2 |
| **Linux** | hệ điều hành nguồn mở Linux | Linus Torvalds | Reading 3, Ex D |
| **Mac OS** | hệ điều hành Mac OS | Macintosh | Reading 3 |
| **multitasking** | đa nhiệm | multi = nhiều, task = việc | Reading 2 |
| **nested folder** | thư mục lồng nhau | nest = tổ chim/lồng | Reading 2 |
| **open-source** | nguồn mở | open = mở, source = nguồn | Reading 3 |
| **operating system (OS)** | hệ điều hành | operate = vận hành | Reading 1 |
| **platform** | nền tảng máy tính | | Reading 3 |
| **prompt** | dấu nhắc lệnh | command prompt | Reading 2 |
| **proprietary software** | phần mềm độc quyền | property = sở hữu | Ex D |
| **scroll bar** | thanh cuộn màn hình | scroll = cuộn | Ex B |
| **source code** | mã nguồn | source = nguồn, code = mã | Reading 3 |
| **system software** | phần mềm hệ thống | system = hệ thống | Reading 1 |
| **Unix** | hệ điều hành Unix | Unix | Reading 3 |
| **user interface** | giao diện người dùng | user = người dùng | Reading 2 |
| **user-friendly** | thân thiện người dùng | friendly = thân thiện | Reading 2 |
| **WIMP** | môi trường WIMP | Windows, Icons, Menus, Pointer | Reading 2 |
| **window** | cửa sổ hiển thị | window = cửa sổ | Reading 2 |

---

### BẢNG TỔNG HỢP — CÁC HỆ ĐIỀU HÀNH PHỔ BIẾN

⚠️ Bảng này là nguồn ôn chính cho dạng bài "so sánh đặc trưng các hệ điều hành" và "nối OS với nền tảng".

| Hệ điều hành | Hãng phát triển | Nền tảng đích | Đặc tính nổi bật |
|---|---|---|---|
| **Windows** | Microsoft | Máy tính cá nhân (PC) | Phổ biến nhất, tương thích hàng ngàn ứng dụng |
| **Mac OS** | Apple | Máy tính Macintosh (Mac) | Giao diện đồ họa (GUI) đầu tiên năm 1984 |
| **Unix** | Nhiều nhà phát triển | Máy tính lớn (Mainframe) | Đa người dùng (multi-user), bảo mật doanh nghiệp |
| **Linux** | Cộng đồng nguồn mở | Máy chủ, PC gia đình, thiết bị nhúng | Mã nguồn mở (open-source), miễn phí, linh hoạt |
| **Windows Mobile** | Microsoft | PDA, Điện thoại thông minh | Dùng cho thiết bị bỏ túi (Pocket PC) |
| **Symbian OS** | Symbian Ltd. | Điện thoại di động (Nokia, Siemens) | Phổ biến trên các dòng máy di động đời cũ |

---

## 2. BÀI ĐỌC SONG NGỮ (Reading — EN | VI)

### Software & Operating System Classification

**English (Original)**
The set of program instructions that tell the computer what to do is known as **software**. It can be classified into two basic categories:

> **[VI]** Tập hợp các hướng dẫn chương trình cho máy tính biết phải làm gì được gọi là **phần mềm**. Nó có thể được phân loại thành hai nhóm cơ bản:
>
> 📌 *Tóm tắt:* Phần mềm được chia làm hai loại: phần mềm hệ thống (điều khiển hoạt động cơ bản như OS, driver) và phần mềm ứng dụng (thực hiện tác vụ cụ thể như Office, game).

- The **system software**, which includes all the programs that control the basic functions of a computer (e.g. operating systems, programming software, device drivers and utilities).

> **[VI]** - **Phần mềm hệ thống** (system software), bao gồm tất cả các chương trình kiểm soát các chức năng cơ bản của máy tính (ví dụ: hệ điều hành, phần mềm lập trình, trình điều khiển thiết bị và tiện ích).
>
> 📌 *Tóm tắt:* OS quản lý tài nguyên phần cứng và phần mềm của máy tính.

- The **applications software**, which comprises programs that let you do specific tasks. Typical applications include word processing, databases, educational programs, email and video games.

> **[VI]** - **Phần mềm ứng dụng** (applications software), bao gồm các chương trình cho phép bạn thực hiện các tác vụ cụ thể. Các ứng dụng điển hình bao gồm xử lý văn bản, cơ sở dữ liệu, chương trình giáo dục, email và trò chơi video.
>
> 📌 *Tóm tắt:* 

The **operating system** (OS) is a set of programs that control the hardware and software resources of a computer system. Typical functions include handling input/output operations, running programs and organizing files on disks.

> **[VI]** **Hệ điều hành** (OS) là một tập hợp các chương trình kiểm soát tài nguyên phần cứng và phần mềm của một hệ thống máy tính. Các chức năng điển hình bao gồm xử lý các hoạt động đầu vào/đầu ra, chạy các chương trình và tổ chức các tệp tin trên đĩa.
>
> 📌 *Tóm tắt:*

### Graphical User Interfaces (GUI)

**English (Original)**
The term **user interface** refers to the standard procedures that the user follows in order to interact with a computer. In the late 1970s and early 80s, the way users accessed computer systems was very complex. They had to memorize and type a lot of commands just to see the contents of a disk, to copy files or to respond to a single **prompt**. In fact, it was only experts who used computers, so there was no need for a **user-friendly** interface.

> **[VI]** Thuật ngữ **giao diện người dùng** đề cập đến các thủ tục tiêu chuẩn mà người dùng tuân theo để tương tác với máy tính. Vào cuối những năm 1970 và đầu những năm 80, cách người dùng truy cập hệ thống máy tính rất phức tạp. Họ phải ghi nhớ và gõ rất nhiều lệnh chỉ để xem nội dung của đĩa, sao chép tệp hoặc phản hồi một **dấu nhắc lệnh** duy nhất. Thực tế, chỉ có các chuyên gia mới sử dụng máy tính, vì vậy không cần giao diện **thân thiện với người dùng**.
>
> 📌 *Tóm tắt:* Giao diện đồ họa (GUI) ra đời năm 1984 với Mac của Apple thay thế giao diện dòng lệnh phức tạp.

In 1984, Apple produced the Macintosh, the first computer with a mouse and a **graphical user interface** (GUI). Macs were designed with one clear aim: to facilitate interaction with the computer. A few years later, Microsoft launched Windows, another operating system based on graphics and intuitive tools. Nowadays, computers are used by all kinds of people, and as a result there is a growing emphasis on **accessibility** and user-friendly systems.

> **[VI]** Vào năm 1984, Apple đã sản xuất Macintosh, chiếc máy tính đầu tiên có chuột và **giao diện đồ họa người dùng** (GUI). Máy Mac được thiết kế với một mục tiêu rõ ràng: tạo điều kiện thuận lợi cho việc tương tác với máy tính. Vài năm sau, Microsoft ra mắt Windows, một hệ điều hành khác dựa trên đồ họa và các công cụ trực quan. Ngày nay, máy tính được sử dụng bởi mọi đối tượng người dùng, và kết quả là ngày càng có sự nhấn mạnh vào **khả năng tiếp cận** và các hệ thống thân thiện với người dùng.
>
> 📌 *Tóm tắt:* GUI dùng môi trường WIMP (cửa sổ, biểu tượng, menu, con trỏ) giúp máy tính thân thiện và dễ tiếp cận hơn, hỗ trợ đa nhiệm (multitasking).

A GUI makes use of a **WIMP environment**: windows, icons, menus and pointer. The background of the screen is called the **desktop**, which contains labeled pictures called **icons**. These icons represent files or folders. Double-clicking a folder opens a **window** which contains programs, documents, or more **nested folders**. When you are in a folder, you can launch a program or document by double-clicking the icon or you can drag it to another location. When you run a program, your PC opens a window that lets you work with different tools. All the programs have a high level of **consistency**, with similar toolbars, menu bars, buttons and dialog boxes. A modern OS also provides access to networks and allows **multitasking**, which means you can run several programs - and do various tasks - at the same time.

> **[VI]** Giao diện GUI sử dụng **môi trường WIMP**: cửa sổ, biểu tượng, menu và con trỏ. Nền của màn hình được gọi là màn hình nền (**desktop**), chứa các hình ảnh có nhãn gọi là các biểu tượng (**icons**). Các biểu tượng này đại diện cho các tệp tin hoặc thư mục. Nhấp đúp vào một thư mục sẽ mở ra một **cửa sổ** chứa các chương trình, tài liệu hoặc nhiều **thư mục lồng nhau** hơn. Khi ở trong một thư mục, bạn có thể khởi chạy một chương trình hoặc tài liệu bằng cách nhấp đúp vào biểu tượng hoặc có thể kéo nó sang vị trí khác. Khi bạn chạy một chương trình, PC sẽ mở ra một cửa sổ cho phép bạn làm việc với các công cụ khác nhau. Tất cả các chương trình đều có tính **nhất quán** cao, với các thanh công cụ, thanh menu, các nút và hộp thoại tương tự nhau. Một hệ điều hành hiện đại cũng cung cấp quyền truy cập vào mạng và cho phép **đa nhiệm**, có nghĩa là bạn có thể chạy nhiều chương trình - và thực hiện nhiều tác vụ - cùng một lúc.
>
> 📌 *Tóm tắt:*

### Windows Vista Editions

**English (Original)**
Windows Vista is designed to meet different user needs. **Home Basic** is designed for users with basic needs, such as email and Internet access. **Home Premium** is for advanced home computing and **entertainment**. The **Business Edition** is ideal for **business organizations**, while the **Ultimate Edition** is the most complete.

> **[VI]** Windows Vista được thiết kế để đáp ứng các nhu cầu khác nhau của người dùng. **Home Basic** được thiết kế cho những người dùng có nhu cầu cơ bản, chẳng hạn như truy cập email và Internet. **Home Premium** dành cho máy tính gia đình nâng cao và **giải trí**. Phiên bản **Business** lý tưởng cho **các tổ chức doanh nghiệp**, trong khi phiên bản **Ultimate** là đầy đủ nhất.
>
> 📌 *Tóm tắt:* Windows Vista có nhiều phiên bản (Home Basic, Home Premium, Business, Ultimate) với giao diện thiết kế lại trực quan hơn, tích hợp phần mềm chống gián điệp, tường lửa bảo vệ máy tính và bộ công cụ văn phòng Microsoft Office.

The user interface has been redesigned with new icons and a new **visual style**. It offers support for the latest technologies, from DVD creation to **speech recognition**. Internet Explorer is more reliable and secure. The Security Centre includes an **anti-spyware** program called *Windows Defender*, and a firewall that protects your computer from **Internet attacks**. The most popular office application suite is still **Microsoft Office**, which includes the **word processor** Word, the Excel spreadsheet, and the **presentation graphics** program PowerPoint.

> **[VI]** Giao diện người dùng đã được thiết kế lại với các biểu tượng mới và **phong cách trực quan** mới. Nó hỗ trợ các công nghệ mới nhất, từ tạo DVD đến **nhận dạng giọng nói**. Internet Explorer đáng tin cậy và an toàn hơn. Trung tâm Bảo mật bao gồm chương trình **chống phần mềm gián điệp** gọi là *Windows Defender*, và tường lửa bảo vệ máy tính của bạn khỏi các **cuộc tấn công từ Internet**. Bộ ứng dụng văn phòng phổ biến nhất vẫn là **Microsoft Office**, một bộ ứng dụng bao gồm phần mềm **xử lý văn bản** Word; chương trình bảng tính Excel; và chương trình **đồ họa thuyết trình** PowerPoint.
>
> 📌 *Tóm tắt:*

## KEY CONCEPTS

| Concept | Short Explanation | Giải thích tiếng Việt |
|---|---|---|
| **operating system (OS)** | a set of programs that controls the hardware and runs application software. | Hệ điều hành: tập hợp chương trình điều khiển phần cứng và chạy phần mềm ứng dụng. |
| **GUI** | Graphical User Interface, using windows, icons, menus, and pointers. | Giao diện đồ họa (GUI): giao diện sử dụng cửa sổ, biểu tượng, menu và con trỏ. |
| **CLI** | Command Line Interface, requiring users to type text commands. | Giao diện dòng lệnh (CLI): giao diện yêu cầu người dùng tự gõ câu lệnh. |
| **multitasking** | the ability to run more than one program or task at the same time. | Đa nhiệm: khả năng chạy nhiều chương trình hoặc tác vụ cùng một lúc. |

---

## POSSIBLE EXAM QUESTIONS

Q: What is the primary purpose of an operating system?
A: To manage computer hardware and software resources and act as an interface.
*(Dịch: Mục đích chính của hệ điều hành là gì? - Quản lý tài nguyên phần cứng, phần mềm và làm giao diện cho người dùng.)*

Q: What does WIMP stand for in GUI?
A: Windows, Icons, Menus, and Pointer.
*(Dịch: WIMP trong giao diện đồ họa viết tắt của từ gì? - Cửa sổ (Windows), Biểu tượng (Icons), Menu (Menus) và Con trỏ (Pointer).)*

Q: Explain the concept of multitasking.
A: Running multiple programs or applications concurrently on a computer.
*(Dịch: Giải thích khái niệm đa nhiệm. - Chạy đồng thời nhiều chương trình hoặc ứng dụng trên máy tính.)*

Q: Why is Linux considered an open-source OS?
A: Its source code is free to read, modify, and redistribute by anyone.
*(Dịch: Tại sao Linux được coi là mã nguồn mở? - Mã nguồn của nó cho phép bất kỳ ai cũng có thể đọc, sửa đổi và phân phối miễn phí.)*

---

## ONE-LINE ANSWERS

- The OS controls hardware and manages software programs. (Hệ điều hành kiểm soát phần cứng và quản lý phần mềm.)
- GUI makes computers user-friendly through visual elements. (GUI giúp máy tính thân thiện qua các yếu tố trực quan.)
- CLI commands must be typed and memorized by users. (Lệnh CLI phải được gõ và học thuộc lòng bởi người dùng.)
- Multitasking runs several programs concurrently. (Đa nhiệm chạy song song nhiều chương trình cùng lúc.)
- Open-source software allows free modifications and sharing. (Phần mềm mã nguồn mở cho phép chỉnh sửa và chia sẻ tự do.)

---

## TEACHER TRAPS (DỄ NHẦM LẪN)

### ⚠️ GUI vs CLI
GUI trực quan, dùng chuột (thân thiện). CLI dùng văn bản câu lệnh, chỉ dùng bàn phím (đòi hỏi nhớ lệnh kỹ thuật).

### ⚠️ Windows vs Linux
Windows là hệ điều hành độc quyền thương mại (phải mua bản quyền). Linux là mã nguồn mở (miễn phí và tự do tùy biến).

---

## WEBSITE / SOFTWARE / APPLICATION IDENTIFICATION

| Name | Type | Main Function (EN) | Chức năng chính (VI) |
|---|---|---|---|
| **Windows** | Operating System | Proprietary OS for personal and business PCs | Hệ điều hành độc quyền cho máy tính cá nhân/doanh nghiệp |
| **macOS** | Operating System | Proprietary OS for Apple Macintosh systems | Hệ điều hành độc quyền cho các dòng máy Apple Mac |
| **Linux** | Operating System | Open-source OS widely used on servers and PCs | Hệ điều hành mã nguồn mở dùng cho máy chủ và máy tính cá nhân |

---

## 3. NGỮ PHÁP (Grammar)

### Danh từ đếm được và không đếm được (Countable & Uncountable Nouns)

Trong tiếng Anh chuyên ngành CNTT, việc phân biệt danh từ đếm được và không đếm được là rất quan trọng để tránh các lỗi ngữ pháp khi viết tài liệu kỹ thuật.

| Danh từ đếm được (Countable) | Danh từ không đếm được (Uncountable) |
|---|---|
| - Chỉ các đối tượng riêng lẻ có thể đếm bằng số. <br> - Có dạng số ít và số nhiều (thêm *s/es*). <br> - Ở dạng số ít, **bắt buộc** phải có mạo từ (*a, an, the, my, this*). | - Chỉ chất liệu, khái niệm trừu tượng không đếm được. <br> - **Không** có dạng số nhiều (không thêm *s*). <br> - Đi với động từ chia ở **số ít**. <br> - **Không** dùng mạo từ *a/an*. |
| *Ví dụ:* file/files, program/programs, workstation/workstations, system/systems. | *Ví dụ:* software, hardware, firmware, storage, connectivity, bandwidth, music. |
| *Ví dụ câu:* I have **a program** (số ít). <br> These **programs** are expensive (số nhiều). | *Ví dụ câu:* Much **software** is open-source. *(Không viết: softwares are)*. <br> This **equipment** is modern. *(Không viết: equipments)*. |

⚠️ **Lưu ý đặc biệt cho từ vựng IT:**
1. Một số danh từ đếm được trong tiếng Việt nhưng lại là danh từ **không đếm được trong tiếng Anh**:
   - *advice* (lời khuyên), *equipment* (thiết bị), *research* (nghiên cứu), *news* (tin tức), *progress* (sự tiến bộ), *homework* (bài tập về nhà).
   - Ví dụ: *The school bought new **equipment**.* (Không dùng: *equipments* hoặc *an equipment*).
2. Lượng từ đi kèm:
   - Đi với danh từ đếm được: **many, few, a few**.
   - Đi với danh từ không đếm được: **much, little, a little, a great deal of**.

---

## 4. BÀI TẬP & ĐÁP ÁN (Exercises & Answer Key)

### Exercise A — GUI Descriptors

Read the GUI reading section and decide which adjectives from the box best describe a GUI:
*user-friendly, slow, accessible, text-based, intuitive, complex, graphics-based*

1. Simple and easy for non-experts to learn: ________________
2. Easy to navigate and reach: ________________
3. Easy to understand immediately without complex learning: ________________
4. Built using pictures, layouts, and visual menus instead of command-lines: ________________

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **user-friendly** — Thân thiện, dễ dùng cho mọi đối tượng.
2. **accessible** — Dễ tiếp cận.
3. **intuitive** — Trực quan, nhìn vào hiểu ngay cách thao tác.
4. **graphics-based** — Dựa trên hình ảnh đồ họa thay vì dòng lệnh chữ.

</details>

### Exercise B — Interface Features Identification

Match the descriptions (1-10) with the user interface features from the bold list:
*menu bar, drop-down menu, program icon, folder icon, document icon, window, hard drive icon, scroll bar, desktop, dock*

1. The main background area of the screen where icons are located.
2. A graphical representation of a folder used to store files.
3. An icon representing a specific text file, sheet or PDF document.
4. An icon representing a program that can be run.
5. An icon representing the local storage hard drive.
6. A bar at the top containing lists of command menus (File, Edit, etc.).
7. A menu that appears downward when you click on a menu option.
8. A rectangular area on the screen showing the program currently running.
9. A bar on the side or bottom used to move the page view up, down, or sideways.
10. A bar of shortcuts to programs usually located at the bottom of Mac OS.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **desktop** — Màn hình nền của hệ điều hành.
2. **folder icon** — Biểu tượng thư mục lưu trữ.
3. **document icon** — Biểu tượng tệp tài liệu.
4. **program icon** — Biểu tượng ứng dụng.
5. **hard drive icon** — Biểu tượng đĩa cứng lưu trữ hệ thống.
6. **menu bar** — Thanh thực đơn trên cùng màn hình.
7. **drop-down menu** — Trình đơn thả xuống khi click chọn.
8. **window** — Khung cửa sổ hiển thị tác vụ của chương trình đang chạy.
9. **scroll bar** — Thanh cuộn trang màn hình.
10. **dock** — Thanh công cụ phím tắt chứa ứng dụng (đặc trưng của Mac OS).

</details>

### Exercise C — Windows Vista and Software Suites

Complete this fact file about Windows Vista and its programs using these words:
*anti-spyware, Business, entertainment, Home Basic, Internet attacks, Microsoft Office, presentation graphics, speech recognition, visual style, word processor*

Windows Vista is designed for users with basic needs, such as email and internet access. (1) ________________ is the entry edition. Home Premium is for advanced computing and (2) ________________. The (3) ________________ edition is ideal for organizations. The user interface has a new (4) ________________. It supports advanced features like (5) ________________. For security, it features an (6) ________________ program called Windows Defender, protecting the system from (7) ________________. The most popular office suite is still (8) ________________, which includes Word (a (9) ________________) and PowerPoint (a (10) ________________ program).

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **Home Basic** — Phiên bản cơ bản cho duyệt web và đọc email.
2. **entertainment** — Giải trí gia đình nâng cao (Home Premium).
3. **Business** — Phiên bản phục vụ các tổ chức doanh nghiệp.
4. **visual style** — Phong cách hiển thị trực quan mới của Vista.
5. **speech recognition** — Tính năng nhận dạng giọng nói tích hợp.
6. **anti-spyware** — Phần mềm chống phần mềm gián điệp Windows Defender.
7. **Internet attacks** — Các cuộc tấn công đe dọa bảo mật từ Internet.
8. **Microsoft Office** — Bộ phần mềm văn phòng nổi tiếng.
9. **word processor** — Trình xử lý soạn thảo văn bản Word.
10. **presentation graphics** — Phần mềm tạo đồ họa trình chiếu PowerPoint.

</details>

### Exercise D — Article Usage: Linux

Complete the text about Linux with a, an, the, or nothing (∅):
Linux is (1) _____ operating system and it was initially created as (2) _____ hobby by a young student, Linus Torvalds. Version 1.0 of the Linux Kernel was released in 1994. (3) _____ Kernel, at the heart of all Linux systems, is developed and released under GNU General Public License. Apart from the fact that it's freely distributed, (4) _____ Linux's functionality and robustness has made it the main alternative for Unix. IBM and other giants have embraced Linux. More than (5) _____ decade after its release, Linux is being adopted worldwide, primarily as (6) _____ server platform. The OS can also be incorporated directly into (7) _____ microchips in a process called (8) _____ embedding.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **an** — Bắt đầu bằng một nguyên âm trong phát âm (operating system).
2. **a** — hobby bắt đầu bằng phụ âm, dùng mạo từ không xác định số ít.
3. **The** — Danh từ Kernel đã được nhắc đến ở câu trước đó (danh từ xác định).
4. **∅** (nothing) — Trước danh từ sở hữu cách "Linux's functionality" không dùng mạo từ.
5. **a** — cụm từ chỉ thời gian "more than a decade" (hơn một thập kỷ).
6. **a** — server platform ở dạng số ít, chưa xác định.
7. **∅** (nothing) — microchips ở dạng số nhiều không xác định.
8. **∅** (nothing) — embedding là danh từ không đếm được chỉ quá trình tích hợp.

</details>

### Exercise E — Grammar: Countable vs Uncountable Nouns

Classify the following IT words into Countable (C) or Uncountable (U):
1. software: _____
2. computer: _____
3. equipment: _____
4. file: _____
5. information: _____
6. database: _____
7. research: _____
8. mouse: _____

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. software: **U** (danh từ không đếm được).
2. computer: **C** (danh từ đếm được).
3. equipment: **U** (danh từ không đếm được trong tiếng Anh).
4. file: **C** (danh từ đếm được).
5. information: **U** (danh từ không đếm được).
6. database: **C** (danh từ đếm được, số nhiều: databases).
7. research: **U** (danh từ không đếm được).
8. mouse: **C** (danh từ đếm được).

</details>

### Exercise F — Reading Comprehension Questions

Answer the following questions based on the Unit 4 text:
1. What kind of OS was used in the early 80s: text-based or graphic-based?
2. What was the contribution of Macintosh computers to the development of graphic environments?
3. What does the acronym WIMP stand for?
4. How do you run a program on a computer with a graphical interface (GUI)?
5. What is multitasking?
6. Which multi-user OS is used on large corporate computers and mainframes?
7. What is the benefit of using open-source software like Linux?
8. Which Microsoft platform is used for pocket PCs and smartphones?

---

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **Text-based OS** — Giao diện dòng lệnh bằng chữ rất phức tạp và phải ghi nhớ nhiều lệnh.
2. **Apple Macintosh was the first computer with a mouse and graphical user interface (GUI)** in 1984, facilitating natural human-computer interaction.
3. **Windows, Icons, Menus, Pointer** — Đây là cấu trúc cơ bản của giao diện đồ họa.
4. **By double-clicking the program icon** — Nhấp đúp chuột vào biểu tượng để khởi chạy chương trình.
5. **The ability of the operating system to run several programs and perform various tasks at the same time** (chạy đa nhiệm đồng thời).
6. **Unix** — Hệ điều hành đa người dùng mạnh mẽ cho doanh nghiệp.
7. **It is free, adaptable, and its source code is open for anyone to modify and distribute** (tiết kiệm chi phí, dễ tùy biến mã nguồn).
8. **Windows Mobile** — Hệ điều hành di động của Microsoft.

</details>

### 🧪 Mini Quiz

**Câu 1 (Trắc nghiệm):** Which of the following is an uncountable noun in English?
- a. device
- b. advice
- c. tool

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 1 (Trắc nghiệm):**
*   **b. advice ✓** — Lời khuyên là danh từ không đếm được trong tiếng Anh.
*   - a. device ✗ — Thiết bị, là danh từ đếm được (devices).
*   - c. tool ✗ — Công cụ, là danh từ đếm được (tools).

</details>

**Câu 2 (Trắc nghiệm):** What does the 'P' in WIMP stand for?
- a. Program
- b. Processor
- c. Pointer

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 2 (Trắc nghiệm):**
*   **c. Pointer ✓** — P trong WIMP là Pointer (con trỏ chuột).
*   - a. Program ✗ — Sai định nghĩa viết tắt.
*   - b. Processor ✗ — Sai định nghĩa viết tắt.

</details>

**Câu 3 (Điền từ):** The type of software license that allows anyone to inspect, modify and distribute its source code is called _____________ software.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 3 (Điền từ):**
*   **open-source** (hoặc **nguồn mở**) — Định nghĩa của phần mềm nguồn mở công khai code.

</details>

**Câu 4 (Điền từ):** Correct the error: "He gave me a lot of good advices on installing Linux." Corrected noun: _____________.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 4 (Điền từ):**
*   **advice** — Bỏ "s" vì advice là danh từ không đếm được, không đi với "a lot of advices" mà dùng "a lot of advice".

</details>

**Câu 5 (Điền từ):** State whether this is True or False: "Linux is a proprietary operating system developed by Microsoft." _____________

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 5 (Điền từ):**
*   **False** — Linux là phần mềm nguồn mở miễn phí, không thuộc Microsoft.

</details>

**Câu 6 (Trắc nghiệm):** Which operating system is multi-user and commonly found on corporate mainframes?
- a. Mac OS
- b. Unix
- c. Windows Mobile

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 6 (Trắc nghiệm):**
*   **b. Unix ✓** — Hệ điều hành đa người dùng trên các máy tính lớn.
*   - a. Mac OS ✗ — Hệ điều hành cho máy trạm cá nhân của Apple.
*   - c. Windows Mobile ✗ — Hệ điều hành cho thiết bị di động.

</details>

**Câu 7 (Nối):** Nối thuật ngữ với nghĩa tương ứng:
1. user interface — A. Khởi chạy/mở một chương trình
2. multitasking — B. Giao diện/phương thức giao tiếp giữa người dùng và máy tính
3. launch a program — C. Khả năng chạy nhiều chương trình cùng một lúc

---

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 7 (Nối):**
*   **1-B** (user interface — Giao diện/phương thức giao tiếp giữa người dùng và máy tính)
*   **2-C** (multitasking — Khả năng chạy nhiều chương trình cùng một lúc)
*   **3-A** (launch a program — Khởi chạy/mở một chương trình)

---

</details>

