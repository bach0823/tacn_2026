# UNIT 09 — Graphics and Design

## 1. TỪ VỰNG CHÍNH (Vocabulary)

| Từ/Cụm từ (EN) | Phiên âm | Nghĩa (VI) | Gợi nhớ |
|---|---|---|---|
| **raster graphics / bitmap** | | đồ họa raster (ảnh điểm) | lưu trữ dưới dạng tập hợp các pixel |
| **vector graphics** | | đồ họa vector | vẽ bằng công thức toán học hình học |
| **pixel** | /ˈpɪk.səl/ | điểm ảnh | picture + element |
| **resolution** | /ˌrez.əˈluː.ʃən/ | độ phân giải | số lượng điểm ảnh hiển thị |
| **jagged edge** | | nét răng cưa | xảy ra khi phóng lớn ảnh raster |
| **composite** | /kəmˈpɒz.ɪt/ | ghép ảnh | kết hợp các phần ảnh lại |
| **CAD (Computer Aided Design)** | | thiết kế hỗ trợ bằng máy tính | dùng thiết kế kỹ thuật, cơ khí |
| **wireframe** | /ˈwaɪə.freɪm/ | khung dây | bản vẽ trong suốt thể hiện các cạnh |
| **solid modeling** | | dựng hình khối 3D | solid = thể rắn, model = dựng hình |
| **texturing** | /ˈteks.tʃər.ɪŋ/ | tạo vân, kết cấu bề mặt | thêm màu, chất liệu lên vật thể |
| **rendering** | /ˈren.dər.ɪŋ/ | kết xuất đồ họa | tạo bóng, phản chiếu để vật thể như thật |
| **fractal** | /ˈfræk.təl/ | hình phân hình (fractal) | hình học lặp lại vô tận |
| **GIS (Geographic Info System)** | | hệ thống thông tin địa lý | phân tích dữ liệu bản đồ địa lý |
| **animation** | /ˌæn.ɪˈmeɪ.ʃən/ | hoạt họa, ảnh động | tạo chuỗi hình chuyển động |
| **primitive** | /ˈprɪm.ɪ.tɪv/ | hình cơ bản (đường tròn, đa giác) | nguyên bản, cơ bản |
| **attribute** | /ˈæt.rɪ.bjuːt/ | thuộc tính (màu sắc, độ rộng viền) | đặc tính của đối tượng |
| **translation** | /trænsˈleɪ.ʃən/ | phép tịnh tiến (di chuyển) | di chuyển vật thể sang vị trí khác |
| **rotation** | /rəʊˈteɪ.ʃən/ | phép quay | quay vật thể quanh một trục |
| **scaling** | /ˈskeɪ.lɪŋ/ | phép co giãn tỷ lệ | làm vật thể to hoặc nhỏ hơn |
| **toolbox** | /ˈtuːl.bɒks/ | hộp công cụ | tool = công cụ, box = hộp |

---

### BẢNG TỔNG HỢP — RASTER VS VECTOR GRAPHICS

⚠️ Bảng này là nguồn ôn chính cho dạng bài "phân biệt đồ họa bitmap và vector" và "nối định dạng tệp".

| Đặc tính | Đồ họa Raster (Bitmap) | Đồ họa Vector |
|---|---|---|
| **Cách lưu trữ** | Tập hợp các điểm ảnh màu (pixels). | Các đối tượng hình học (đường, đa giác) dựa trên công thức toán học. |
| **Độ phân giải** | Phụ thuộc vào độ phân giải (phóng to sẽ có nét răng cưa **jagged edges**). | Không phụ thuộc độ phân giải (phóng to không bao giờ vỡ hình). |
| **Phần mềm phổ biến** | Adobe Photoshop. | Adobe Illustrator, Corel Draw, Macromedia Freehand. |
| **Định dạng tệp phổ biến** | JPEG, GIF, TIFF, PNG. | EPS, SVG, PDF (dạng vector). |
| **Ứng dụng chính** | Chỉnh sửa ảnh chụp, tạo hiệu ứng chuyển sắc mịn. | Thiết kế logo, minh họa sách, vẽ kỹ thuật đồ bản. |

---

## 2. BÀI ĐỌC SONG NGỮ (Reading — EN | VI)

### Computer Graphics & Design Application

**English (Original)**
Computer graphics are pictures and drawings produced by computer. There are two main categories:

> **[VI]** Đồ họa máy tính là các hình ảnh và bản vẽ được tạo ra bởi máy tính. Có hai nhóm chính:
>
> 📌 *Tóm tắt:* Đồ họa gồm dạng raster (lưu điểm ảnh pixels, dễ vỡ khi phóng to) và vector (lưu hình học toán học, không vỡ).

- **Raster graphics**, or **bitmaps**, are stored as a collection of pixels. The sharpness of an image depends on the density of pixels, or **resolution**. For example, text or pictures that are scaled up - that is, made bigger - may show **jagged edges**. Paint and photo-editing programs like *Adobe Photoshop* focus on the manipulation of bitmaps. Popular raster formats are `JPEG`, `GIF` and `TIFF`.

> **[VI]** - **Đồ họa raster**, hay **bitmaps**, được lưu trữ dưới dạng một tập hợp các điểm ảnh (pixels). Độ sắc nét của một hình ảnh phụ thuộc vào mật độ của các điểm ảnh, hay **độ phân giải** (resolution). Ví dụ: văn bản hoặc hình ảnh được phóng to - nghĩa là làm cho lớn hơn - có thể hiển thị **nét răng cưa** (jagged edges). Các chương trình vẽ và chỉnh sửa ảnh như *Adobe Photoshop* tập trung vào việc thao tác các ảnh bitmap. Các định dạng raster phổ biến là `JPEG`, `GIF` và `TIFF`.
>
> 📌 *Tóm tắt:* Phần mềm CAD giúp thiết kế cơ khí qua các bước tạo wireframe, texturing và kết xuất rendering.

- **Vector graphics** represent images through the use of geometric objects, such as lines, curves and polygons, based on mathematical equations. They can be changed or scaled without losing quality. Vector data can be handled by drawing programs like *Adobe Illustrator*. `EPS` is the most popular file format for exchanging vector drawings.

> **[VI]** - **Đồ họa vector** biểu diễn hình ảnh thông qua việc sử dụng các đối tượng hình học, chẳng hạn như các đường thẳng, đường cong và đa giác, dựa trên các phương trình toán học. Chúng có thể được thay đổi hoặc thu phóng mà không bị giảm chất lượng. Dữ liệu vector có thể được xử lý bởi các chương trình vẽ như *Adobe Illustrator*. `EPS` là định dạng tệp phổ biến nhất để trao đổi các bản vẽ vector.
>
> 📌 *Tóm tắt:* GIS dùng lập bản đồ địa lý.

Mechanical engineers use **CAD** (Computer Aided Design) software to develop, model and test car designs before the actual parts are made. This can save a lot of time and money. Designers start a project by making a **wireframe** (outlines of all edges in a transparent drawing). They then fill the surfaces to give the appearance of a 3-D solid object (solid modeling). Next, they add colour and filters: this is called **texturing**. Finally, they **render** the object (adding lighting, shading, and reflections) to make it look real.

> **[VI]** Kỹ sư cơ khí sử dụng phần mềm **CAD** (Thiết kế hỗ trợ bằng máy tính) để phát triển, mô hình hóa và kiểm thử các thiết kế ô tô trước khi các bộ phận thực tế được chế tạo. Điều này có thể tiết kiệm rất nhiều thời gian và tiền bạc. Các nhà thiết kế bắt đầu một dự án bằng cách tạo ra một **khung dây** (wireframe - biểu diễn hiển thị phác thảo của tất cả các cạnh trong một bản vẽ trong suốt). Sau đó, họ tô đầy các bề mặt để tạo ra diện mạo của một vật thể rắn 3D (mô hình hóa vật thể rắn). Tiếp theo, họ thêm màu sắc và bộ lọc: quá trình này gọi là **tạo kết cấu bề mặt** (texturing). Cuối cùng, họ **kết xuất** (render) vật thể (thêm ánh sáng, đổ bóng và phản chiếu) để làm cho nó trông như thật.
>
> 📌 *Tóm tắt:* 

Artists and scientists use special graphic applets to create amazing **fractals** (geometrical patterns repeated at small scales). Government agencies use **GIS** (Geographic Information Systems) to understand geographic data and predict natural disasters. Cartographers use GIS to make detailed maps. **Animators** use computer animation software to create animated cartoons or add effects in movies.

> **[VI]** Các nghệ sĩ và nhà khoa học sử dụng các applet đồ họa đặc biệt để tạo ra các **hình phân hình** (fractals - các mẫu hình học lặp lại ở tỷ lệ nhỏ). Các cơ quan chính phủ sử dụng **GIS** (Hệ thống thông tin địa lý) để hiểu dữ liệu địa lý và dự đoán thiên tai. Bản đồ học sử dụng GIS để tạo ra các bản đồ chi tiết. **Nhà làm hoạt hình** sử dụng phần mềm hoạt hình máy tính để tạo ra phim hoạt hình hoặc thêm các hiệu ứng trong phim.
>
> 📌 *Tóm tắt:*

### Graphics Tools and Object Transformations

**English (Original)**
Graphics programs usually have a toolbox - a collection of drawing and **painting** tools that enable you to type, **select**, draw, paint, edit, move, and view images. The basic shapes used to make graphical objects are called **primitives** (lines, arcs, circles, polygons). You can specify the **attributes** of each primitive, such as its colour, line type, and fill area.

> **[VI]** Các chương trình đồ họa thường có một hộp công cụ - một tập hợp các công cụ vẽ và **tô màu** cho phép bạn nhập văn bản, **chọn**, vẽ, tô màu, chỉnh sửa, di chuyển và xem hình ảnh. Các hình dạng cơ bản được sử dụng để tạo ra các đối tượng đồ họa được gọi là **hình cơ bản** (primitives - các đường thẳng, cung tròn, hình tròn, đa giác). Bạn có thể chỉ định các **thuộc tính** của từng hình cơ bản, chẳng hạn như màu sắc, kiểu đường viền và vùng tô đầy.
>
> 📌 *Tóm tắt:* Hộp công cụ đồ họa chứa các primitives (hình cơ bản) kèm attributes (thuộc tính màu/viền).

You can transform an object by translating, **rotating** or scaling it. **Translation** means moving an object to a different location. **Rotation** is turning the object around an axis (for example, rotating it 90 or 180 degrees). **Scaling** is making the object larger or smaller.

> **[VI]** Bạn có thể biến đổi một đối tượng bằng cách tịnh tiến, **xoay** hoặc co giãn tỷ lệ của nó. **Tịnh tiến** (translation) có nghĩa là di chuyển một đối tượng đến một vị trí khác. **Xoay** (rotation) là quay đối tượng xung quanh một trục (ví dụ: xoay đối tượng 90 hoặc 180 độ). **Co giãn** (scaling) là làm cho đối tượng lớn hơn hoặc nhỏ hơn.
>
> 📌 *Tóm tắt:* Người dùng có thể biến đổi vật thể bằng các phép: dịch chuyển (translation), xoay (rotation) và co giãn tỉ lệ (scaling).

## 3. NGỮ PHÁP (Grammar)

### Các cách dùng của dạng "-ing" (The -ing Form)

Trong tiếng Anh kỹ thuật, các từ kết thúc bằng `-ing` được sử dụng dưới 3 vai trò ngữ pháp chính:

#### 3.1 Danh động từ (Gerund)
Đóng vai trò như một danh từ chỉ hành động hoặc quá trình.
- **Làm chủ ngữ:** **Compositing** is combining parts of different images...
- **Làm tân ngữ của động từ:** I enjoy **editing** pictures.
- **Đứng sau giới từ:** Designers start a project by **making** a wireframe.
- **Sau các động từ bắt buộc đi với -ing:** *avoid, enjoy, suggest, finish, keep, involve, look forward to...* (Ví dụ: *I suggest **using** PowerPoint.*)

#### 3.2 Phân từ hiện tại (Present Participle)
- **Dùng trong các thì tiếp diễn:** She **is designing** a logo.
- **Dùng rút gọn mệnh đề quan hệ dạng chủ động:** The Internet is a network **linking** (*= which links*) other networks.

#### 3.3 Tính từ (Adjective)
Đứng trước danh từ bổ nghĩa hoặc sau động từ liên kết.
- *Ví dụ:* special applets to create **amazing** fractals. (amazing = tính từ chỉ đặc điểm của fractals).
- *Ví dụ:* to make information more **interesting** visually.

---

## 4. BÀI TẬP & ĐÁP ÁN (Exercises & Answer Key)

### Exercise A — Computer Graphics Comprehension

Answer these questions based on the computer graphics reading:
1. What are the differences between raster graphics and vector graphics?
2. Which graphics file formats are mentioned in the text?
3. What is the definition of "compositing"?
4. What does the acronym CAD stand for?
5. What are the benefits of using CAD graphics in the car manufacturing industry?
6. What type of graphics software is used to make maps and analyze geographic data?
7. Who uses computer animation software? How do they use it?

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **Raster graphics** are stored as a collection of pixels and lose quality (show jagged edges) when scaled up. **Vector graphics** use mathematical equations representing geometric objects and can be scaled without losing quality.
2. **JPEG, GIF, TIFF, EPS**.
3. **Compositing is combining parts of different images** to create a single image.
4. **Computer Aided Design**.
5. Mechanical engineers can **develop, model, and test car designs** before building actual parts, saving time and money.
6. **GIS (Geographic Information Systems)** software is used to make maps and predict disasters.
7. **Animators use it to create animated cartoons** and add visual effects in movies and games.

</details>

### Exercise B — Graphics Terminology Matching

Match the words (1-6) with the correct definitions (a-f):
1. resolution
2. jagged
3. filters
4. wireframe
5. rendering
6. fractals

- a. special effects that can be applied to pictures.
- b. a technique that generates realistic reflections, shadows and highlights.
- c. geometrical figures with repeating self-similar properties at different scales.
- d. irregular or uneven (like pixels on a low-resolution scaled image).
- e. the density or number of pixels in an image.
- f. a transparent outline drawing of a model using edges and lines.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **e** (resolution — mật độ điểm ảnh).
2. **d** (jagged — nét răng cưa vỡ hình).
3. **a** (filters — bộ lọc hiệu ứng đặc biệt).
4. **f** (wireframe — khung dây trong suốt).
5. **b** (rendering — kết xuất tạo bóng, ánh sáng).
6. **c** (fractals — hình học phân hình lặp quy mô nhỏ).

</details>

### Exercise C — Graphics Tools and Transformations Fill-in-the-blank

Complete the text using these words from the toolbox lesson:
*clicking, draw, drawing, make, painting, rotating, scaling, select, turning*

Graphics programs usually have a toolbox - a collection of drawing and (1) ________________ tools that enable you to type, (2) ________________, draw, paint, edit, move, and view images. The basic shapes used to (3) ________________ graphical objects are called primitives. To use a tool, you activate it by (4) ________________ on its icon. For example, if you want to (5) ________________ a rectangle, you activate the rectangle tool, giving you the option of (6) ________________ it with square or rounded corners. You can transform objects by translating, (7) ________________ or scaling. Translation is moving, rotation is (8) ________________ the object, and (9) ________________ is making it larger or smaller.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **painting** — công cụ vẽ tô màu (painting tools).
2. **select** — chọn vùng ảnh.
3. **make** — tạo nên các đối tượng đồ họa.
4. **clicking** — kích hoạt công cụ bằng cách click chuột.
5. **draw** — vẽ một hình.
6. **drawing** — hành động vẽ góc vuông hoặc góc tròn.
7. **rotating** — xoay vật thể.
8. **turning** — quay vật thể xung quanh một trục.
9. **Scaling** — co giãn kích thước.

</details>

### Exercise D — -ing Form Function Identification

Decide if the -ing forms in these sentences are gerunds (*g*), present participles (*pp*) or adjectives (*a*):
1. PCs generate graphics by performing mathematical calculations on data. [ _____ ]
2. Businesspeople use graphics to make information more interesting visually. [ _____ ]
3. Graphs and diagrams can be more effective ways of communicating with clients. [ _____ ]
4. She is designing a logo for the company. [ _____ ]
5. If you need to make a presentation, I suggest using PowerPoint. [ _____ ]
6. The Internet is a network linking other networks. [ _____ ]

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **g** (gerund) — Đứng sau giới từ "by" (by performing...).
2. **a** (adjective) — Bổ nghĩa cho "information" (interesting information).
3. **g** (gerund) — Đứng sau giới từ "of" (of communicating...).
4. **pp** (present participle) — Thì hiện tại tiếp diễn (is designing).
5. **g** (gerund) — Đứng sau động từ "suggest".
6. **pp** (present participle) — Rút gọn mệnh đề quan hệ dạng chủ động (linking = which links).

</details>

### Exercise E — -ing Form Grammatical Correction

Correct the grammatical errors in these sentences (there are 7 errors in total):
1. Computer animation is the process of create objects which move across the screen.
2. Texturing involves add paint, colour and filters to drawings and designs.
3. You can open the colour palette by click on the corresponding icon.
4. CAD programs are very fast at to perform drawing functions.
5. A lot of time and money is saved by test a car design before to make the product.
6. To render refers to the techniques used to make realistic images.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. create -> **creating** (sau giới từ "of").
2. add -> **adding** (sau động từ "involves").
3. click -> **clicking** (sau giới từ "by").
4. to perform -> **performing** (sau giới từ "at").
5. test -> **testing** (sau giới từ "by"); to make -> **making** (sau giới từ "before").
6. To render -> **Rendering** (suy luận - dùng danh động từ làm chủ ngữ đứng đầu câu thay cho động từ nguyên mẫu có to).

</details>

### Exercise F — Photoshop Toolbox Functions

Match the tools from the Photoshop toolbox (1-10) with their functions (a-j):
1. Marquee select tools
2. Move tool
3. Crop tool
4. Paintbrush / pencil
5. Eraser
6. Paint bucket
7. Type tool
8. Colour picker (Eyedropper)
9. Zoom
10. Colour tools and palette

- a. cuts down the dimensions (crop) of a picture.
- b. selects a particular rectangular or elliptical part of an image.
- c. fills in a closed area with a background colour.
- d. controls the foreground and background colour options.
- e. selects a specific colour from a pixel in a photo.
- f. magnifies areas of an image for close, detailed work.
- g. deletes the part of the picture you drag it over.
- h. inserts text characters into your document.
- i. draws and paints strokes in different shapes and patterns.
- j. moves a selection or entire layer by dragging.

---

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

1. **b** (Marquee select tools — chọn vùng chọn hình chữ nhật/elip).
2. **j** (Move tool — di chuyển vùng chọn/layer).
3. **a** (Crop tool — cắt nhỏ kích thước ảnh).
4. **i** (Paintbrush/pencil — vẽ nét cọ theo hình dạng).
5. **g** (Eraser — xóa phần ảnh di chuột qua).
6. **c** (Paint bucket — đổ đầy màu vào vùng kín).
7. **h** (Type tool — chèn ký tự chữ).
8. **e** (Colour picker — chọn màu từ điểm ảnh).
9. **f** (Zoom — phóng to/thu nhỏ để thao tác chi tiết).
10. **d** (Colour tools and palette — chọn màu vẽ và màu nền).

</details>

### 🧪 Mini Quiz

**Câu 1 (Trắc nghiệm):** Which of the following is the most popular vector file format?
- a. JPEG
- b. EPS
- c. GIF

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 1 (Trắc nghiệm):**
*   **b. EPS ✓** — Định dạng chuẩn để trao đổi các bản vẽ vector.
*   - a. JPEG ✗ — Định dạng ảnh raster nén.
*   - c. GIF ✗ — Định dạng ảnh raster hỗ trợ ảnh động.

</details>

**Câu 2 (Trắc nghiệm):** In "I suggest using Adobe Illustrator", what is the function of the word **using**?
- a. adjective
- b. present participle
- c. gerund

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 2 (Trắc nghiệm):**
*   **c. gerund ✓** — Động từ suggest bắt buộc đi kèm danh động từ (gerund).
*   - a. adjective ✗ — Sai từ loại trong ngữ cảnh này.
*   - b. present participle ✗ — Không đóng vai trò tiếp diễn hay rút gọn mệnh đề ở đây.

</details>

**Câu 3 (Điền từ):** The 3D modeling process of showing all outlines of edges as transparent lines is called a _____________.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 3 (Điền từ):**
*   **wireframe** — Bản vẽ khung dây phác thảo 3D.

</details>

**Câu 4 (Điền từ):** Correct the error: "He avoided to download that unknown file." Corrected verb: _____________.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 4 (Điền từ):**
*   **downloading** — Động từ avoid yêu cầu động từ đi kèm ở dạng V-ing (gerund).

</details>

**Câu 5 (Điền từ):** Geometrical patterns that are repeated at small scales to generate irregular shapes are called _____________.

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 5 (Điền từ):**
*   **fractals** — Định nghĩa của hình học phân hình tự lặp lại.

</details>

**Câu 6 (Trắc nghiệm):** Which rendering effect simulates light bounces and reflections?
- a. texturing
- b. shading
- c. wireframing

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 6 (Trắc nghiệm):**
*   **b. shading ✓** — Đổ bóng và tạo ánh sáng là một phần của kỹ thuật rendering.
*   - a. texturing ✗ — Đây là tạo vân bề mặt chất liệu.
*   - c. wireframing ✗ — Đây là phác thảo khung dây sơ khởi.

</details>

**Câu 7 (Nối):** Nối phép biến đổi hình học với định nghĩa tương ứng:
1. translation — A. Thay đổi kích thước vật thể phóng to hoặc thu nhỏ
2. rotation — B. Di chuyển vật thể sang một vị trí tọa độ mới
3. scaling — C. Quay vật thể xung quanh một trục xác định

---

<details>
<summary><b>Xem đáp án chi tiết</b></summary>

**Câu 7 (Nối):**
*   **1-B** (translation — Phép tịnh tiến dịch chuyển tọa độ)
*   **2-C** (rotation — Phép quay quanh trục)
*   **3-A** (scaling — Phép co giãn thay đổi kích thước)

---

</details>


## 5. GLOSSARY TỔNG HỢP

| Thuật ngữ | Nghĩa | Gợi nhớ | Xuất hiện ở |
|---|---|---|---|
| **animation** | hoạt ảnh, hoạt họa | animate = tạo chuyển động | Reading 1 |
| **attribute** | thuộc tính | | Reading 2 |
| **bitmap / raster** | đồ họa bitmap (raster) | bit = hạt màu, map = bản đồ | Reading 1 |
| **CAD** | thiết kế hỗ trợ bằng máy tính | Computer Aided Design | Reading 1 |
| **composite** | ghép ảnh | composite = hỗn hợp | Reading 1 |
| **crop** | cắt cúp ảnh | crop = thu hoạch/cắt ngắn | Ex F |
| **density** | mật độ | dense = dày đặc | Reading 1 |
| **eyedropper** | công cụ hút màu | eye = mắt, dropper = ống nhỏ giọt | Ex F |
| **filter** | bộ lọc hiệu ứng | | Reading 1, Ex B |
| **fractal** | hình học phân hình | fraction = phần nhỏ | Reading 1, Ex B |
| **geometric** | thuộc hình học | geometry = hình học | Reading 1 |
| **GIS** | hệ thống thông tin địa lý | Geographic Information Systems | Reading 1 |
| **illustration** | hình minh họa | illustrate = minh họa | Reading 1 |
| **jagged edge** | nét răng cưa vỡ hình | jagged = lởm chởm, edge = cạnh | Reading 1, Ex B |
| **pixel** | điểm ảnh | picture element | Reading 1 |
| **primitive** | hình học cơ bản | primitive = sơ khởi | Reading 2 |
| **rendering** | kết xuất đồ họa | render = trả về/kết xuất | Reading 1, Ex B |
| **resolution** | độ phân giải | resolve = phân tích rõ | Reading 1, Ex B |
| **rotation** | phép xoay | rotate = xoay | Reading 2, Ex G |
| **scaling** | co giãn tỉ lệ | scale = thang đo/tỷ lệ | Reading 1, Reading 2 |
| **solid modeling** | dựng hình khối đặc | solid = thể rắn | Reading 1 |
| **texturing** | tạo kết cấu bề mặt | texture = vân/vải dệt | Reading 1 |
| **translation** | phép tịnh tiến, di chuyển | translate = chuyển dịch | Reading 2 |
| **vector graphics** | đồ họa vector | vector = hướng/đoạn thẳng | Reading 1 |
| **wireframe** | bản vẽ khung dây | wire = dây, frame = khung | Reading 1, Ex B |

---
> *Tạo mới file Unit 09 từ bản dịch song ngữ và các bài tập đi kèm.*
