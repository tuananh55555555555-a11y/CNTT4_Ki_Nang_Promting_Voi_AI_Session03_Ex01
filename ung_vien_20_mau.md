# Bảng tóm tắt 20 ứng viên

| STT | Họ tên | Số điện thoại | Email | Vị trí ứng tuyển | Năm kinh nghiệm | Kỹ năng chính |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | Nguyễn Văn An | +84912345678 | nguyen.van.a@gmail.com | Backend Developer | 3 | Python, Django, PostgreSQL |
| 2 | Trần Thị Bình | +84988776655 | tranthib@yahoo.com | Frontend Engineer | 2 | ReactJS, TypeScript, TailwindCSS |
| 3 | Lê Vũ | +84355123456 | levu.dev@gmail.com | Junior Python Developer | 0 | FastAPI, MySQL, Docker, Git |
| 4 | Hoàng Văn Nam | +84903112233 | hoangnam95@outlook.com | Data Analyst | 4 | SQL, Python, Power BI, Excel |
| 5 | Phạm Thị Dung | +84978112233 | pham.thị.dung@gmail.com | QA Engineer | 2 | Selenium, Appium, Java, Postman |
| 6 | Nguyễn Hoàng Long | +84911222333 | alex.nguyen99@gmail.com | DevOps Engineer | 3.5 | AWS, Docker, Kubernetes, Terraform |
| 7 | Bùi Đức Hoàng | +84933445566 | buihoang.ptit@gmail.com | Fullstack Developer | 5 | Node.js, React, MongoDB, Docker |
| 8 | Võ Minh Thư | null | vo.minh.thu@gmail.com | UI/UX Designer | 2 | Figma, Adobe XD, Illustrator |
| 9 | Đỗ Anh Tuấn | +84909888777 | tuan.architect@gmail.com | Solutions Architect | 7 | System Design, Microservices, Java, Kubernetes, Kafka |
| 10 | Ngô Thanh Hướng | +84966554433 | ngo.thanh.huong@gmail.com | Business Analyst | 3 | SQL, Agile, JIRA, Wireframing, Excel |
| 11 | Nguyễn Mai Phương | +84347890123 | phuong.intern@gmail.com | AI Research Intern | null | Python, PyTorch, Pandas, NLP |
| 12 | Cao Đức Mạnh | +84912998877 | cao.duc.manh@gmail.com | null | 6 | C#, .NET Core, SQL Server, Azure |
| 13 | Hà Thục Quyên | +84981234567 | ha.thuc.quyen@gmail.com | HR Executive | 2.5 | Tuyển dụng IT, Employer Branding, LinkedIn Recruiter, HRIS |
| 14 | Vũ Hải Đăng | +84905123123 | vu.hai.dang@gmail.com | Mobile Developer (Flutter / React Native) | 3 | Flutter, Dart, React Native, RESTful API, Firebase |
| 15 | Bùi Thị Lan | +84938765432 | bui.thi.lan@gmail.com | Kế toán tổng hợp | 8 | MISA, Excel nâng cao, Báo cáo thuế, Kiểm toán |
| 16 | Lê Quang Vinh | +84977889900 | null | Security Engineer | 4 | Penetration Testing, OWASP Top 10, Wireshark, Linux Security |
| 17 | Hoàng Ngọc Yến | +84366778899 | hoang.yen.design@gmail.com | UI/UX Designer | 2 | Figma, Photoshop, After Effects, User Research |
| 18 | Trần Gia Huy | +84903334455 | tran.gia.huy.lead@gmail.com | Engineering Manager / Tech Lead | 10 | Team Management, Agile/Scrum, System Architecture, Python, Go, Kubernetes |
| 19 | Mai Thị Chi | +84399112233 | mai.chi.content@gmail.com | Content Creator | null | Viết bài SEO, Canva, Quản lý Fanpage |
| 20 | Phạm Hoàng Quân | +84922334455 | pham.hoang.quan@gmail.com | Golang Developer | 3 | Go, Microservices, gRPC, Redis, MySQL |

## Quy tắc chuẩn hóa và lưu ý dữ liệu

- Số điện thoại Việt Nam được chuẩn hóa sang dạng quốc tế `+84`, bỏ số `0` đầu và dấu cách.
- `experience_years = 0` ở ứng viên Email 3 vì email nêu rõ chưa có kinh nghiệm làm việc chính thức; thời gian làm đồ án không được tính là kinh nghiệm làm việc.
- `experience_years = null` ở Email 11 và Email 19 vì chỉ nêu tình trạng sinh viên/thực tập, không nêu số năm kinh nghiệm.
- `position = null` ở Email 12 vì ứng viên không nêu vị trí ứng tuyển cụ thể.
- `phone = null` ở Email 8 và `email = null` ở Email 16 vì thiếu dữ liệu tương ứng.
- Email của Email 5 được giữ nguyên chuỗi Unicode như nguồn: `pham.thị.dung@gmail.com`; cần xác nhận hệ thống nhận email quốc tế hóa (EAI) trước khi import nếu DB/ứng dụng chỉ hỗ trợ ASCII.
- Tên công nghệ được chuẩn hóa cách viết thông dụng như `Power BI`, `React Native`; không bổ sung kỹ năng ngoài nội dung email.
