<h1 align="center">Nguyễn Đức Mạnh</h1>

<p align="center">
  <b>Cử nhân Toán – Tin</b> · Đại học Bách khoa Hà Nội<br>
  Học máy · Mạng nơ-ron gắn vật lý (PINN) · Agentic AI · Toán ứng dụng
</p>

<p align="center">
  <a href="https://manhnguyenhp.github.io/"><img src="https://img.shields.io/badge/Portfolio-manhnguyenhp.github.io-0a66c2?style=flat-square&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/manh-nguyen-duc-68753b322"><img src="https://img.shields.io/badge/LinkedIn-manh--nguyen--duc-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:manh.nd2824@gmail.com"><img src="https://img.shields.io/badge/Email-manh.nd2824%40gmail.com-c14438?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://doi.org/10.1016/j.euromechsol.2025.105844"><img src="https://img.shields.io/badge/DOI-10.1016%2Fj.euromechsol.2025.105844-fcb426?style=flat-square&logo=doi&logoColor=white" alt="DOI"></a>
</p>

<p align="center"><i>English version: <a href="README.md">README.md</a></i></p>

---

## Giới thiệu

Sinh viên năm cuối ngành Toán – Tin, Đại học Bách khoa Hà Nội (GPA **3.67/4.0**, dự kiến tốt nghiệp
tháng 7/2026). Tôi làm việc ở giao điểm giữa **học máy và toán ứng dụng**: mô hình thay thế
(surrogate model) cho cơ học kết cấu, mạng nơ-ron gắn vật lý để giải phương trình đạo hàm riêng, và
hệ đa tác tử dựa trên LLM cho quy trình nghiên cứu khoa học.

Tôi thích những bài toán mà phần toán phải đúng *và* hệ thống phải chạy được trên phần cứng thật.

## Nghiên cứu &amp; Công bố

**Highly Efficient Prediction of Beating Phenomena in Laminated Nanocomposite Plates Using a Hybrid Neural–Numerical–Analytical Framework**
*European Journal of Mechanics – A/Solids*, tập 116 (2026), 105844 · Q1
[10.1016/j.euromechsol.2025.105844](https://doi.org/10.1016/j.euromechsol.2025.105844)
Đóng góp: thiết kế kiến trúc mạng nơ-ron, huấn luyện và đánh giá mô hình cho surrogate model giai đoạn 1.

**Adaptive Hard–Soft Physics-Informed Neural Networks for Robust Boundary-Constrained PDE Solving**
Bản thảo đang phản biện.
Đóng góp: cài đặt PINN, phân tích hình thức, rà soát bản thảo.

Sinh viên nghiên cứu tại [Nhóm Vật liệu và Kết cấu (MAS Group)](https://sites.google.com/view/mas-group-hust/home), ĐHBK Hà Nội, từ 2025.

## Dự án tiêu biểu

### AgenticTS — Khung đa tác tử Agentic AI cho dự báo chuỗi thời gian
`02/2026 – 05/2026` · Agentic AI · Suy luận LLM · Hệ đa tác tử · Bài báo nghiên cứu

Khung đa tác tử điều khiển bằng suy luận, tự động hoá toàn bộ quy trình dự báo, được hình thức hoá
thành một quá trình ra quyết định tuần tự có ràng buộc với bộ nhớ phân cấp (episodic / semantic / vector).

- **Chín tác tử chuyên biệt** — Orchestrator, Guardrail, Ingestion, Diagnostics, Feature, Model Strategy, Training, Evaluation, Report — suy luận qua **Gemini 2.5 Flash Lite** trên tầng điều phối container hoá.
- **Chọn mô hình theo ràng buộc chẩn đoán**: kiểm định tính dừng ADF, ACF/PACF, phát hiện điểm dị thường Z-score và tính mùa vụ thu hẹp động không gian tìm kiếm trên ARIMA, LSTM, DLinear, thay cho tìm kiếm vét cạn theo lưới/AIC.
- Đánh giá trên Hanoi Energy, Hanoi Weather và ETTh1 ở các tầm dự báo 96/192/336/720. So với Auto-ARIMA trên Hanoi Energy (H=96): **giảm 10,6% MAE và 27,6% MSE**.
- Nghiên cứu loại bỏ (ablation) tách riêng vai trò của tác tử Feature / Diagnostics / Model Strategy. Mọi bước đều ghi log vào một JSON manifest truy vết được, đảm bảo tái lập hoàn toàn.

### Kho dữ liệu hàng không — Phân tích chậm chuyến &amp; huỷ chuyến
`09/2025 – 01/2026` · Big Data · triển khai trên máy chủ doanh nghiệp vật lý (12 vCore, 31 GB RAM)

- Thiết kế và triển khai kho dữ liệu **Galaxy Schema** trên cụm Hadoop vật lý, với pipeline nạp dữ liệu đầu-cuối tự động hoàn toàn bằng **Apache NiFi** và **Apache Oozie**, không cần thao tác thủ công.
- **Giảm 91,47% dung lượng lưu trữ** nhờ nén Parquet/Snappy và **tăng tốc truy vấn 6,1 lần** so với lưu trữ theo dòng, thông qua phân vùng và thiết kế lược đồ.
- Đo hiệu năng trên phần cứng thật thay vì mô phỏng. Xử lý các vấn đề tương thích và phân quyền ở mức môi trường doanh nghiệp thực tế.
- Xây dựng dashboard phân tích mẫu chậm chuyến theo hãng bay, đường bay, mùa và sân bay.

### Hệ thống chấm trắc nghiệm tự động
`03/2025 – 06/2025` · Thị giác máy tính · **đề tài chính thức của Khoa, đang vận hành** tại Khoa Toán – Tin, ĐHBK Hà Nội

- Pipeline đầu-cuối nhận diện ô tô và chưa tô trong điều kiện quét thực tế: chất lượng scan kém, tẩy xoá một phần, ánh sáng không đồng đều.
- Bộ dữ liệu xây bằng Roboflow (thu thập, gán nhãn, tăng cường). **YOLOv8** được huấn luyện và tối ưu đạt **mAP@0.5 ≈ 99%** trên tập kiểm thử độc lập.
- Tiền xử lý OpenCV (căn nghiêng, nhị phân hoá, khử nhiễu) chuẩn hoá chất lượng ảnh đầu vào trước khi suy luận.
- Hậu xử lý bằng **phân cụm K-means** ánh xạ vị trí ô đã phát hiện sang vị trí đáp án logic, cho phép chấm điểm hoàn toàn tự động.
- Được Khoa ghi nhận bằng giấy chứng nhận tham gia tích cực.

## Kinh nghiệm

**Thực tập sinh Lập trình** — 1C Việt Nam, Hà Nội · `2025`
Xây dựng hệ thống quản lý chuỗi nhà thuốc bán lẻ trên nền **1C:Enterprise**, phát triển các phân hệ
quản lý tồn kho, bán hàng, đặt hàng nhà cung cấp và báo cáo tự động. Làm việc trực tiếp với kiến
trúc phần mềm doanh nghiệp, mô hình hoá quy trình nghiệp vụ và cấu hình cơ sở dữ liệu quan hệ.

## Học vấn

**Cử nhân Toán – Tin** — Đại học Bách khoa Hà Nội · `2022 – 2026 (dự kiến tháng 7)`
GPA **3.67/4.0** (9,18/10)

Môn học tiêu biểu: Phương pháp tối ưu (A+), Xác suất thống kê (A+), Cấu trúc dữ liệu &amp; Giải thuật (A),
Cơ sở dữ liệu (A), Mật mã &amp; Độ phức tạp thuật toán (A+), Giải tích số (B), Phân tích &amp; Thiết kế hệ thống (A).

## Giải thưởng, Học bổng &amp; Chương trình

| Năm | Thành tích |
| --- | --- |
| 2026 – | Thành viên [Chương trình VINIF Talent](https://vinif.org/en/sponsor-programs/talent-camps/) |
| 2025 | Học bổng Quỹ Mirae Asset |
| 2025 | Trường hè Toán học sinh viên VIASM, ban Toán ứng dụng, Đại học FPT Đà Nẵng (xét tuyển cạnh tranh) |
| 2024, 2025 | Giấy khen Sinh viên xuất sắc năm học 2023–2024, Khoa Toán – Tin, ĐHBK Hà Nội |
| 2023 – | Học bổng khuyến khích học tập ĐHBK Hà Nội (kỳ 2023.1, 2023.2, 2024.1, 2024.2) |
| — | Học bổng FAMI · Học bổng Nhà giáo Bùi Long Biên · Học bổng Con đường tơ lụa |

Thành viên Câu lạc bộ Toán ứng dụng &amp; Tin học (AMIC), Khoa Toán – Tin, ĐHBK Hà Nội, từ 2022.

## Chứng chỉ

- **WorldQuant** — Chứng chỉ BRAIN · Challenge Gold Certificate · IQC 2026 Stage 1
- **DeepLearning.AI / Coursera** — Machine Learning Specialization: Supervised ML (Regression &amp; Classification), Advanced Learning Algorithms, Unsupervised Learning &amp; Recommenders
- **Toán cho học máy** — Calculus for Machine Learning and Data Science · Probability &amp; Statistics for Machine Learning
- **Dữ liệu** — SQL for Data Science · Python for Everybody
- **Microsoft Office Specialist** — Excel

**Ngoại ngữ** — Tiếng Anh (TOEIC 790) · Tiếng Việt (bản ngữ)

## Công nghệ sử dụng

**ML / DL**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=yolo&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Ngôn ngữ**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Dữ liệu &amp; Big Data**
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=flat-square&logo=apachehadoop&logoColor=black)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![NiFi](https://img.shields.io/badge/NiFi-728E9B?style=flat-square&logo=apachenifi&logoColor=white)

**Công cụ**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![1C:Enterprise](https://img.shields.io/badge/1C:Enterprise-FFCC00?style=flat-square&logoColor=black)

## Hồ sơ minh chứng

Bảng điểm, chứng chỉ, quyết định học bổng, giấy khen và bản PDF các công bố được tập hợp tại:
**[Proof of achievement (Google Drive)](https://drive.google.com/drive/folders/1Co7_COynE8MLSbvILPosyaCuAVKiTP4C?usp=sharing)**

## Liên hệ

- Email — [manh.nd2824@gmail.com](mailto:manh.nd2824@gmail.com)
- LinkedIn — [manh-nguyen-duc](https://www.linkedin.com/in/manh-nguyen-duc-68753b322)
- Địa điểm — Hà Nội, Việt Nam

<p align="center"><sub>Sẵn sàng cho các cơ hội trợ lý nghiên cứu, kỹ sư học máy và nghiên cứu sau đại học.</sub></p>
