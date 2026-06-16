# UNIT 08 — Internet Security

## 1. TỪ VỰNG CHÍNH (Vocabulary)

| Từ/Cụm từ (EN) | Phiên âm | Nghĩa (VI) | Gợi nhớ |
|---|---|---|---|
| **cybercrime** | /ˈsaɪ.bə.kraɪm/ | tội phạm mạng | cyber = mạng, crime = tội phạm |
| **piracy** | /ˈpaɪ.rə.si/ | sự vi phạm bản quyền | phần mềm lậu |
| **plagiarism** | /ˈpleɪ.dʒər.ɪ.zəm/ | sự đạo văn | lấy tác phẩm người khác làm của mình |
| **malicious software / malware** | | phần mềm độc hại | malicious = hiểm độc, software = phần mềm |
| **phishing** | /ˈfɪʃ.ɪŋ/ | giả mạo lừa đảo | lừa lấy mật khẩu, thông tin thẻ |
| **IP spoofing** | | giả mạo địa chỉ IP | spoof = đánh lừa, giả mạo |
| **cyberstalking** | | quấy rối trên mạng | stalk = rình rập, theo dõi |
| **hacker** | /ˈhæk.ər/ | tin tặc / lập trình viên giỏi | nghĩa gốc là người đam mê máy tính |
| **cracker** | /ˈkræk.ər/ | kẻ bẻ khóa (tin tặc mũ đen) | crack = bẻ khóa, phá hoại |
| **white hat** | | tin tặc mũ trắng (bảo mật) | mũ trắng = người tốt |
| **black hat** | | tin tặc mũ đen (phá hoại) | mũ đen = kẻ xấu |
| **confidential information** | | thông tin bảo mật, bí mật | confident = tin tưởng |
| **cookie** | /ˈkʊk.i/ | tệp cookie lưu trữ dữ liệu | tệp nhỏ lưu thông tin web |
| **digital certificate** | | chứng thư số | certificate = chứng nhận |
| **SSL (Secure Sockets Layer)** | | giao thức bảo mật truyền tải | lớp cổng bảo mật |
| **encryption** | /ɪnˈkrɪp.ʃən/ | sự mã hóa dữ liệu | encrypt = mã hóa |
| **decryption** | /dɪˈkrɪp.ʃən/ | sự giải mã dữ liệu | decrypt = giải mã |
| **worm** | /wɜːm/ | sâu máy tính (tự nhân bản) | tự nhân bản lây qua mail |
| **Trojan horse** | | mã độc Trojan (ẩn danh) | ngụy trang phần mềm hữu ích |
| **spyware** | /ˈspaɪ.weər/ | phần mềm gián điệp | spy = gián điệp |
| **adware** | /ˈæd.weər/ | phần mềm quảng cáo | ad (advertisement) = quảng cáo |
| **prosecute** | /ˈprɒs.ɪ.kjuːt/ | truy tố, khởi tố | |
| **extort** | /ɪkˈstɔːt/ | tống tiền | |
| **copyright infringement** | | vi phạm bản quyền | infringe = xâm phạm |

---

### BẢNG TỔNG HỢP — CÁC MÃ ĐỘC HẠI (Malware Types)

⚠️ Bảng này là nguồn ôn chính cho dạng bài "phân biệt các loại mã độc" và "nối loại malware với cách lây lan".

| Loại Malware | Định nghĩa / Cách lây lan | Tác hại chính |
|---|---|---|
| **Virus** | Tự gắn vào một tệp tin thông thường, lây lan khi tệp tin đó được chạy. | Phá hủy dữ liệu ổ cứng, làm hỏng hệ thống. |
| **Worm (Sâu)** | Tự nhân bản và tự động gửi bản sao qua danh bạ đính kèm email. | Gây nghẽn mạng, tê liệt hệ thống thư điện tử. |
| **Trojan Horse** | Ngụy trang dưới dạng một chương trình hữu ích/miễn phí. | Đánh cắp thông tin đăng nhập, tạo cổng hậu (backdoor). |
| **Spyware** | Thu thập thông tin cá nhân trên PC mà không có sự đồng ý. | Rò rỉ thông tin cá nhân, theo dõi thói quen lướt web. |
| **Adware** | Đi kèm phần mềm miễn phí, tự hiển thị quảng cáo đột ngột. | Xuất hiện các cửa sổ pop-ups gây phiền toái. |

---

## 2. BÀI ĐỌC SONG NGỮ (Reading — EN | VI)

### Cybercrimes Definitions

**English (Original)**
- **Piracy**: the illegal copy and distribution of copyrighted software, games or music files.

> **[VI]** - **Vi phạm bản quyền (Piracy)**: sao chép và phân phối bất hợp pháp phần mềm, trò chơi hoặc các tệp nhạc có bản quyền.
>
> 📌 *Tóm tắt:* Tội phạm mạng gồm vi phạm bản quyền (piracy), đạo văn (plagiarism), phát tán mã độc, lừa đảo qua email (phishing), giả mạo IP (IP spoofing), quấy rối mạng (cyberstalking) và phát tán tài liệu đồi trụy.

- **Plagiarism and theft of intellectual property**: pretending that someone else's work is your own.

> **[VI]** - **Đạo văn và trộm cắp sở hữu trí tuệ (Plagiarism)**: giả vờ rằng tác phẩm của người khác là của riêng mình.
>
> 📌 *Tóm tắt:* 

- **Spreading of malicious software**: distributing programs designed to damage systems.

> **[VI]** - **Phát tán phần mềm độc hại**: phân phối các chương trình được thiết kế để gây hại cho hệ thống máy tính.
>
> 📌 *Tóm tắt:* 

- **Phishing**: getting passwords for online bank accounts or credit card numbers by using emails that look like they are from real organizations, but are in fact fake.

> **[VI]** - **Giả mạo lừa đảo (Phishing)**: lấy mật khẩu tài khoản ngân hàng trực tuyến hoặc số thẻ tín dụng bằng cách sử dụng các email trông giống như từ các tổ chức thực tế, nhưng thực chất là giả mạo.
>
> 📌 *Tóm tắt:* 

- **IP spoofing**: making one computer look like another in order to gain unauthorized access.

> **[VI]** - **Giả mạo IP (IP spoofing)**: làm cho một máy tính trông giống như một máy tính khác nhằm giành quyền truy cập trái phép.
>
> 📌 *Tóm tắt:* 

- **Cyberstalking**: online harassment or abuse, mainly in chat rooms or newsgroups.

> **[VI]** - **Quấy rối mạng (Cyberstalking)**: quấy rối hoặc lạm dụng trực tuyến, chủ yếu trong các phòng trò chuyện hoặc nhóm tin.
>
> 📌 *Tóm tắt:* 

- **Distribution of indecent or offensive material**: spreading illegal or inappropriate content.

> **[VI]** - **Phát tán tài liệu đồi trụy hoặc xúc phạm**: lan truyền các nội dung bất hợp pháp hoặc không phù hợp.
>
> 📌 *Tóm tắt:*

### Security and Privacy on the Internet

**English (Original)**
There are many benefits from an open system like the Internet, but one of the risks is that we are often exposed to **hackers**, who break into computer systems just for fun, to steal information, or to spread viruses.

> **[VI]** Có nhiều lợi ích từ một hệ thống mở như Internet, nhưng một trong những rủi ro là chúng ta thường xuyên phải tiếp xúc với các **tin tặc** (hackers), những người đột nhập vào hệ thống máy tính chỉ để giải trí, đánh cắp thông tin hoặc phát tán virus.
>
> 📌 *Tóm tắt:* Internet là hệ thống mở nên tiềm ẩn nhiều nguy cơ.

#### Security on the Web

> **[VI]** #### Bảo mật trên Web
>
> 📌 *Tóm tắt:* Bảo mật web cần tắt cookies, kiểm tra biểu tượng khóa SSL và dùng chứng thư số.

Security is crucial when you send **confidential information** online. When you buy something, your credit card number passes through intermediary computers. If one of these computers is infiltrated by hackers, your data can be copied. To avoid risks, you should set all security alerts to high. *Mozilla Firefox* displays a lock when the website is secure and allows you to disable or delete **cookies** — small files placed on your hard drive by web servers to recognize your PC. Online banking services must use **digital certificates** (digital identification cards) and browsers compliant with **SSL** (*Secure Sockets Layer*), a protocol that provides secure transactions.

> **[VI]** Bảo mật là tối quan trọng khi bạn gửi **thông tin bảo mật** trực tuyến. Khi bạn mua hàng, số thẻ tín dụng của bạn đi qua các máy tính trung gian. Nếu một trong các máy tính này bị tin tặc xâm nhập, dữ liệu của bạn có thể bị sao chép. Để tránh rủi ro, bạn nên đặt tất cả các cảnh báo bảo mật ở mức cao. *Mozilla Firefox* hiển thị một ổ khóa khi trang web an toàn và cho phép bạn vô hiệu hóa hoặc xóa các **cookies** — các tệp nhỏ được máy chủ web đặt trên ổ cứng của bạn để nhận diện máy tính của bạn. Các dịch vụ ngân hàng trực tuyến phải sử dụng **chứng thư số** (chứng minh thư kỹ thuật số) và các trình duyệt tương thích với **SSL** (Lớp cổng bảo mật), một giao thức cung cấp các giao dịch an toàn.
>
> 📌 *Tóm tắt:* Email cần được mã hóa bằng PGP.

#### Email privacy & Network security

> **[VI]** #### Bảo mật Email & Bảo mật mạng
>
> 📌 *Tóm tắt:* Mạng doanh nghiệp được bảo vệ bằng mật khẩu, tường lửa (firewalls) và mã hóa dữ liệu.

As email travels across the Net, it is copied temporarily. To protect it, you should encode it using **encryption**. *Pretty Good Privacy* (PGP) is a popular freeware program written by Phil Zimmerman for this purpose. Private networks can also be attacked by intruders. Protection methods include passwords, **firewalls**, and **encryption** & **decryption** systems. Encryption changes data into a secret code, and decryption converts it back.

> **[VI]** Khi email truyền qua Mạng, nó sẽ được sao chép tạm thời. Để bảo vệ thư, bạn nên mã hóa nó bằng phương pháp **mã hóa** (encryption). *Pretty Good Privacy* (PGP) là một chương trình miễn phí phổ biến được viết bởi Phil Zimmerman cho mục đích này. Các mạng nội bộ cũng có thể bị tấn công bởi những kẻ xâm nhập. Các phương pháp bảo vệ bao gồm mật khẩu để kiểm soát truy cập, **tường lửa** (firewalls), và các hệ thống **mã hóa** & **giải mã** (decryption). Mã hóa chuyển đổi dữ liệu thành mật mã, và giải mã chuyển đổi nó trở lại dạng gốc.
>
> 📌 *Tóm tắt:*

### History of Hacking & Internet Landmarks

**English (Original)**
- **1969**: US Defense Department establishes `ARPANET`, connecting research centres.

> **[VI]** - **1969**: Bộ Quốc phòng Mỹ thiết lập mạng `ARPANET`, kết nối các trung tâm nghiên cứu.
>
> 📌 *Tóm tắt:* Lịch sử Internet chứng kiến sự phát triển song hành giữa các cột mốc công nghệ (ARPANET 1969, email 1971, TCP/IP 1988, Web 1991) và lịch sử tin tặc (John Draper 1971, Kevin Mitnick, Captain Zap, sâu Melissa, virus ILoveYou và Code Red).

- **1971**: *John Draper* used a Cap'n Crunch toy whistle to generate a 2,600Hz signal, making free phone calls. *Ray Tomlinson* invented the first email program.

> **[VI]** - **1971**: *John Draper* phát hiện tiếng còi đồ chơi Cap'n Crunch phát ra tần số 2.600Hz trùng khớp tín hiệu AT&T để gọi điện miễn phí. *Ray Tomlinson* phát minh ra chương trình email đầu tiên.
>
> 📌 *Tóm tắt:* 

- **1974**: *Kevin Mitnick* hacked banking networks. His NADC hack later inspired the 1983 film *War Games*.

> **[VI]** - **1974**: *Kevin Mitnick* hack mạng ngân hàng. Vụ hack NADC của ông sau này truyền cảm hứng cho bộ phim *War Games* năm 1983.
>
> 📌 *Tóm tắt:* 

- **1981**: *Ian Murphy* (Captain Zap) hacked the White House and Pentagon.

> **[VI]** - **1981**: *Ian Murphy* (Captain Zap) đột nhập vào Nhà Trắng và Lầu Năm Góc.
>
> 📌 *Tóm tắt:* 

- **1988**: *Nicholas Whitely* was arrested for spreading viruses. The Union Bank of Switzerland almost lost £32 million to hackers. `TCP/IP` was adopted as the standard language of the Net.

> **[VI]** - **1988**: *Nicholas Whitely* bị bắt vì phát tán virus. Ngân hàng Thụy Sĩ suýt mất 32 triệu bảng. Giao thức `TCP/IP` được chọn làm chuẩn chung của Internet.
>
> 📌 *Tóm tắt:* 

- **1989**: A 15-year-old hacked US defence computer.

> **[VI]** - **1989**: Cậu bé 15 tuổi hack thành công máy tính quân sự Mỹ.
>
> 📌 *Tóm tắt:* 

- **1991**: *Kevin Poulsen* (Dark Dante) stole military files. `CERN` created the World Wide Web.

> **[VI]** - **1991**: *Kevin Poulsen* (Dark Dante) đánh cắp hồ sơ quân sự. `CERN` tạo ra mạng lưới World Wide Web.
>
> 📌 *Tóm tắt:* 

- **1992**: *David L. Smith* **was** prosecuted for writing the Melissa virus.

> **[VI]** - **1992**: *David L. Smith* **bị** truy tố vì viết virus Melissa lây qua tệp Word.
>
> 📌 *Tóm tắt:* 

- **1997**: The German Chaos Computer Club **showed** on TV how to extract money from bank accounts.

> **[VI]** - **1997**: Câu lạc bộ Chaos Computer (Đức) **trình chiếu** trên TV cách trộm tiền từ tài khoản.
>
> 📌 *Tóm tắt:* 

- **2000**: A Russian hacker **attempted** to extort money from CD Universe. A Canadian hacker **launched** a DoS attack. The *ILoveYou* virus **spread** rapidly and **overwrote** files.

> **[VI]** - **2000**: Tin tặc Nga **tống tiền** CD Universe. Tin tặc Canada **khởi chạy** tấn công từ chối dịch vụ. Virus *ILoveYou* **phát tán** cực nhanh và **ghi đè** các tệp tin.
>
> 📌 *Tóm tắt:* 

- **2001**: The *Code Red* worm **infected** thousands of PCs. *Napster* P2P music sharing was ruled as copyright infringement.

> **[VI]** - **2001**: Sâu *Code Red* **lây nhiễm** hàng vạn máy tính. Mạng chia sẻ nhạc *Napster* bị tòa tuyên vi phạm bản quyền.
>
> 📌 *Tóm tắt:*

## KEY CONCEPTS

| Concept | Short Explanation | Giải thích tiếng Việt |
|---|---|---|
| **malware** | malicious software designed to damage or exploit systems. | Malware (phần mềm độc hại): phần mềm thiết kế để gây hại hệ thống. |
| **virus** | malicious code that replicates by attaching to other programs. | Virus: mã độc tự nhân bản bằng cách bám vào chương trình khác. |
| **worm** | standalone malware that spreads automatically over networks. | Sâu máy tính (worm): mã độc độc lập tự lây lan qua mạng. |
| **phishing** | fraudulent emails/sites pretending to be trustworthy to steal data. | Phishing: lừa đảo trực tuyến bằng giả mạo email/website uy tín. |

---

## POSSIBLE EXAM QUESTIONS

Q: What is the difference between a virus and a worm?
A: A virus needs to attach to a host program; a worm is standalone and spreads automatically.
*(Dịch: Khác biệt giữa virus và sâu? - Virus cần bám vào chương trình vật chủ; sâu hoạt động độc lập tự lan qua mạng.)*

Q: Explain phishing.
A: A scam using fake websites and emails to trick users into giving away sensitive details.
*(Dịch: Giải thích lừa đảo phishing. - Chiêu trò giả mạo email/web uy tín để lừa người dùng giao nộp tài khoản.)*

Q: How does a firewall protect a computer?
A: By monitoring and filtering network traffic based on security rules.
*(Dịch: Tường lửa bảo vệ máy tính thế nào? - Bằng cách giám sát và lọc lưu lượng mạng dựa trên quy tắc bảo mật.)*

Q: What is encryption?
A: Converting data into ciphertext to prevent unauthorized access.
*(Dịch: Mã hóa là gì? - Chuyển đổi dữ liệu thành bản mã khó đọc để ngăn truy cập trái phép.)*

---

## ONE-LINE ANSWERS

- Malware refers to programs designed to harm computer systems. (Malware chỉ các chương trình thiết kế để gây hại hệ thống.)
- Viruses infect host files to replicate and spread. (Virus lây nhiễm file vật chủ để nhân bản và phát tán.)
- Worms exploit network vulnerabilities to spread automatically. (Sâu khai thác lỗ hổng mạng để tự phát tán tự động.)
- Firewalls block unauthorized traffic into private networks. (Tường lửa chặn lưu lượng trái phép vào mạng nội bộ.)
- Encryption secures online transactions using cryptography. (Mã hóa bảo vệ giao dịch mạng bằng mật mã học.)

---

## TEACHER TRAPS (DỄ NHẦM LẪN)

### ⚠️ Virus vs Worm
Virus cần người dùng chạy file bị nhiễm để kích hoạt. Sâu tự động chui qua mạng lây lan không cần người dùng làm gì.

### ⚠️ Phishing vs Spam
Phishing là lừa đảo ăn cắp mật khẩu/thẻ tín dụng. Spam chỉ là thư quảng cáo rác gây phiền toái.

---

## WEBSITE / SOFTWARE / APPLICATION IDENTIFICATION

| Name | Type | Main Function (EN) | Chức năng chính (VI) |
|---|---|---|---|
| **Firewall** | Security System | Monitor and filter network traffic | Giám sát và lọc lưu lượng mạng ra vào |
| **Anti-virus** | Security Software | Detect and destroy computer malware | Phát hiện và tiêu diệt phần mềm độc hại |
| **HTTPS** | Secure Protocol | Transfer secure encrypted web pages | Giao thức truyền tải trang web bảo mật mã hóa |

---


## 3. NGỮ PHÁP (Grammar)

### Thì quá khứ đơn (The Past Simple)

Thì quá khứ đơn dùng để diễn tả các hành động, sự kiện đã hoàn thành và chấm dứt tại một thời điểm cụ thể trong quá khứ (thường đi kèm mốc năm *1971, 1988, last week, ago*).

#### 3.1 Thể chủ động (Active Voice)
- **Động từ có quy tắc:** thêm `-ed` hoặc `-d` vào sau động từ nguyên thể.
  - *Ví dụ:* discover -> **discovered**, hack -> **hacked**, launch -> **launched**.
- **Động từ bất quy tắc:** tra cột 2 trong bảng động từ bất quy tắc.
  - *Ví dụ:* begin -> **began**, spread -> **spread**, steal -> **stole**, write -> **wrote**.
- **Câu hỏi và phủ định:** mượn trợ động từ **did / didn't** + động từ nguyên thể.
  - *Ví dụ phủ định:* He **didn't expect** that...
  - *Ví dụ câu hỏi:* **When did** Captain Zap **hack** into the Pentagon?

#### 3.2 Thể bị động (Passive Voice)
Dùng để nhấn mạnh đối tượng chịu tác động của hành động trong quá khứ.
$$\text{S} + \text{was/were} + \text{Past Participle (P2)} + (\text{by O})$$
- *Ví dụ khẳng định:* IBM network **was paralysed** by hackers. (was/were + P2).
- *Ví dụ phủ định:* He **wasn't sent** to prison.
- *Ví dụ câu hỏi:* Why **was** Nicholas Whitely **arrested**?

---

## 4. BÀI TẬP & ĐÁP ÁN (Exercises & Answer Key)

### Exercise A — Cybercrimes Matching

Match the cybercrimes (1-5) with their correct definitions (a-e):
1. Piracy
2. Plagiarism
3. Phishing
4. IP spoofing
5. Cyberstalking

- a. Stealing online banking passwords using fake emails representing real organizations.
- b. Online harassment or abuse in chat rooms and newsgroups.
- c. Illegal copying and distribution of copyrighted software or music.
- d. Making one computer masquerade as another to gain unauthorized access.
- e. Stealing someone else's work and presenting it as one's own.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **c** (Piracy — sao chép lậu phần mềm bản quyền).
2. **e** (Plagiarism — đạo văn tác phẩm).
3. **a** (Phishing — lừa đảo lấy thông tin thẻ/tài khoản).
4. **d** (IP spoofing — giả mạo địa chỉ IP để truy cập).
5. **b** (Cyberstalking — quấy rối người dùng khác trên mạng).

</details>

### Exercise B — Security & Privacy Questions

Answer the following questions based on the Unit 8 reading text:
1. Why is security so important on the Internet?
2. What security features are offered by the Mozilla Firefox browser?
3. What security protocol is used by banks to secure online transactions?
4. How can we protect our email messages and keep them private?
5. What methods are used by companies to secure their private networks?
6. In what ways can a virus enter a computer system?
7. How does a computer worm spread itself?

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **Because the Internet is an open system** and users are exposed to hackers who can steal confidential information (như số thẻ tín dụng) or spread malware.
2. **Mozilla Firefox displays a lock icon** when the site is secure, and allows users to disable/delete cookies.
3. **Banks use SSL (Secure Sockets Layer)** protocol to provide secure online transactions.
4. **By using encryption software** like Pretty Good Privacy (PGP) to encode the message.
5. **Passwords for access control, firewalls, and encryption/decryption systems**.
6. **Via infected storage discs** or downloaded files/attachments from the Internet.
7. **It spreads through email attachments**, replicating itself and sending copies to everyone in the user's address book.

</details>

### Exercise C — Hacking History Part 1 Questions

Answer the questions about early hacking history:
1. Which hacking case inspired the 1983 film *War Games*?
2. When did Captain Zap hack into the Pentagon?
3. Why was Nicholas Whitely arrested in 1988?
4. How old was the hacker that broke into the US defence computer in 1989?

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **Kevin Mitnick's hack** into the North American Defense Command in Colorado Springs.
2. **In 1981** (Ian Murphy, known as Captain Zap, hacked the White House and Pentagon).
3. **In connection with virus spreading** (gắn liền với việc phát tán virus).
4. **Fifteen years old** (cậu bé 15 tuổi bẻ khóa máy tính quốc phòng Mỹ).

</details>

### Exercise D — Grammar: Hacking History Part 2 (Verb Conjugation)

Complete the text about the history of hacking using the Past Simple (active or passive) of the verbs in the box:
*be, spread, steal, launch, attempt, overwrite, infect, show, prosecute*

1992 – David L. Smith (1) ________________ prosecuted for writing the Melissa virus.
1997 – The German Chaos Computer Club (2) ________________ on TV how to obtain money from bank accounts.
2000 – A Russian hacker (3) ________________ to extort $100,000 from CD Universe. 
2000 – A Canadian hacker (4) ________________ a massive DoS attack against Yahoo! and Amazon.
2000 – The *ILoveYou* virus (5) ________________ so quickly that email had to be shut down. The worm (6) ________________ image and sound files.
2001 – The Code Red worm (7) ________________ tens of thousands of machines.
2006 – Hackers (8) ________________ the credit card details of almost 20,000 AT&T customers. Fortunately, most subscribers (9) (not) ________________ affected.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **was** — câu bị động quá khứ đơn (was prosecuted).
2. **showed** — quá khứ đơn của động từ có quy tắc show.
3. **attempted** — quá khứ đơn của động từ attempt.
4. **launched** — quá khứ đơn của động từ launch.
5. **spread** — quá khứ đơn bất quy tắc của spread (giữ nguyên hình thức).
6. **overwrote** — quá khứ đơn của động từ bất quy tắc overwrite.
7. **infected** — quá khứ đơn của động từ infect.
8. **stole** — quá khứ đơn của động từ bất quy tắc steal.
9. **were not** (hoặc **was not** / **wasn't** / **weren't**) — đi kèm với "affected" tạo thành câu bị động phủ định quá khứ: "were not affected" (không bị ảnh hưởng).

</details>

### Exercise E — Internet History Landmarks

Fill in the correct years (1969, 1971, 1982, 1991, 2001) for these Internet landmarks:
1. Ray Tomlinson invents an email program using the @ sign: ____________
2. CERN creates the World Wide Web: ____________
3. The US Defense Department establishes ARPANET: ____________
4. TCP/IP is adopted as the standard language of the Net: ____________
5. Napster's peer-to-peer file-sharing is ruled as a copyright infringement: ____________

---

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **1971** — Ray Tomlinson phát minh ra email sử dụng ký tự @.
2. **1991** — CERN tạo ra mạng lưới World Wide Web (WWW).
3. **1969** — Bộ Quốc phòng Mỹ thiết lập mạng ARPANET tiền thân Internet.
4. **1982** — TCP/IP được chấp nhận làm chuẩn truyền thông mạng.
5. **2001** — Tòa án tuyên bố Napster vi phạm luật bản quyền.

</details>

### 🧪 Mini Quiz

**Câu 1 (Trắc nghiệm):** In the computer industry, security consultants who hack to find flaws are called:
- a. black hats
- b. white hats
- c. crackers

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 1 (Trắc nghiệm):**
*   **b. white hats ✓** — Tin tặc mũ trắng làm việc bảo mật hợp pháp.
*   - a. black hats ✗ — Tin tặc mũ đen phá hoại phi pháp.
*   - c. crackers ✗ — Kẻ phá hoại bảo mật.

</details>

**Câu 2 (Trắc nghiệm):** What is the past simple passive form of "arrest" for a singular subject?
- a. arrested
- b. was arrested
- c. did arrest

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 2 (Trắc nghiệm):**
*   **b. was arrested ✓** — Bị động quá khứ đơn số ít (chủ ngữ He/She/It).
*   - a. arrested ✗ — Chủ động quá khứ đơn.
*   - c. did arrest ✗ — Trợ động từ nhấn mạnh chủ động.

</details>

**Câu 3 (Điền từ):** A program that replicates itself and sends copies to everyone in an address book is a _____________.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 3 (Điền từ):**
*   **worm** (sâu máy tính) — Tự nhân bản và phát tán qua danh bạ email.

</details>

**Câu 4 (Điền từ):** Complete with the past simple of **steal**: "Hackers _____________ the credit card details last year."

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 4 (Điền từ):**
*   **stole** — Quá khứ đơn của động từ bất quy tắc steal.

</details>

**Câu 5 (Điền từ):** The protocol designed to send email privately by Phil Zimmerman is called _____________.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 5 (Điền từ):**
*   **Pretty Good Privacy** (hoặc **PGP**) — Chương trình mã hóa thư điện tử của Phil zimmerman.

</details>

**Câu 6 (Trắc nghiệm):** Which malware is disguised as a useful program but compromises system security?
- a. worm
- b. Trojan horse
- c. spyware

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 6 (Trắc nghiệm):**
*   **b. Trojan horse ✓** — Mã độc Trojan ẩn danh dưới dạng phần mềm hữu ích.
*   - a. worm ✗ — Sâu tự nhân bản, không giả dạng.
*   - c. spyware ✗ — Phần mềm gián điệp âm thầm thu thập thông tin.

</details>

**Câu 7 (Nối):** Nối thuật ngữ bảo mật với nghĩa tương ứng:
1. encryption — A. Chuyển đổi dữ liệu mật mã trở lại dạng ban đầu đọc được
2. decryption — B. Tệp tin nhỏ lưu thông tin nhận diện người dùng trên web
3. cookie — C. Mã hóa dữ liệu thành các đoạn mã bí mật để bảo mật

---

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 7 (Nối):**
*   **1-C** (encryption — Mã hóa dữ liệu thành các đoạn mã bí mật để bảo mật)
*   **2-A** (decryption — Chuyển đổi dữ liệu mật mã trở lại dạng ban đầu đọc được)
*   **3-B** (cookie — Tệp tin nhỏ lưu thông tin nhận diện người dùng trên web)

---

</details>


## 5. GLOSSARY TỔNG HỢP

| Thuật ngữ | Nghĩa | Gợi nhớ | Xuất hiện ở |
|---|---|---|---|
| **adware** | phần mềm quảng cáo | ad = quảng cáo, ware = đồ | Reading 4 |
| **black hat / cracker** | tin tặc mũ đen | black = đen, hat = mũ | Reading 2 |
| **confidential** | bảo mật, bí mật | confident = tin cậy | Reading 2, Ex B |
| **cookie** | tệp cookie lưu thông tin | cookie = bánh quy | Reading 2 |
| **cybercrime** | tội phạm mạng | crime = tội phạm | Reading 1, Ex A |
| **cyberstalking** | quấy rối mạng | stalk = rình rập | Reading 1 |
| **decryption** | sự giải mã | de- = giải, crypt = mật mã | Reading 2 |
| **digital certificate** | chứng thư số | certificate = chứng nhận | Reading 2 |
| **encryption** | sự mã hóa | en- = làm cho, crypt = mã | Reading 2 |
| **extort** | tống tiền | | Reading 3, Ex D |
| **firewall** | tường lửa | fire = lửa, wall = tường | Reading 2 |
| **hacker** | tin tặc | hack = đột nhập | Reading 2 |
| **IP spoofing** | giả mạo IP | spoof = đánh lừa | Reading 1 |
| **malware** | phần mềm độc hại | malicious + software | Reading 2 |
| **phishing** | giả mạo lừa đảo | password fishing | Reading 1 |
| **piracy** | vi phạm bản quyền | pirate = cướp biển | Reading 1 |
| **plagiarism** | đạo văn | | Reading 1 |
| **prosecute** | truy tố | | Reading 3, Ex D |
| **spyware** | phần mềm gián điệp | spy = gián điệp | Reading 4 |
| **SSL** | lớp cổng bảo mật | Secure Sockets Layer | Reading 2 |
| **Trojan horse** | mã độc Trojan | Trojan horse = ngựa gỗ Troia | Reading 4 |
| **white hat** | tin tặc mũ trắng | white = trắng | Reading 2 |
| **worm** | sâu máy tính | worm = con sâu | Reading 4 |

---
> *Tạo mới file Unit 08 từ bản dịch song ngữ và các bài tập đi kèm.*
