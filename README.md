<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3E2A3B,100:8A3B63&height=170&section=header&text=Hoàng%20Quang%20Thắng&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=Fresher%20Backend%20Developer&descSize=18&descAlignY=60" alt="Hoàng Quang Thắng - Fresher Backend Developer" />

**Xây dựng API · Thiết kế cơ sở dữ liệu · Triển khai hệ thống thực tế**

<a href="#-dự-án"><img src="https://img.shields.io/badge/Xem_dự_án-8A3B63?style=for-the-badge" alt="Xem dự án" /></a>
<a href="mailto:thanghoang182004@gmail.com"><img src="https://img.shields.io/badge/Email-3E2A3B?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/hoangthang183204?tab=repositories"><img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>

</div>

<br>

## 👋 Xin chào

Mình là **Thắng**, vừa tốt nghiệp **Lập trình web tại Cao đẳng FPT Polytechnic** (GPA 3.63/4.0). Mình từng thực tập tại **JITS Innovation Labs** và làm **Trưởng nhóm** đồ án tốt nghiệp.

Mình thích những bài toán backend cần dữ liệu chính xác: giữ ghế khi nhiều người cùng đặt, tính lương không bị trùng, cập nhật trạng thái theo thời gian thực. Cả ba dự án dưới đây đều có mã nguồn, hai trong số đó có demo để dùng thử ngay.

<br>

## 🚀 Dự án

<table>
<tr>
<td width="33%" valign="top">

### 🎬 Cinema Booking
*Đặt vé và quản lý rạp chiếu phim*

Khách đặt vé, nhân viên bán vé tại quầy, quản trị viên theo dõi doanh thu.

![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core_6-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Vue](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)

<a href="https://cinema-booking-vue.vercel.app/"><img src="https://img.shields.io/badge/Dùng_thử_ngay-2ea44f?style=for-the-badge" alt="Demo Cinema Booking" /></a>

[Frontend](https://github.com/hoangthang183204/CinemaBooking-Vue) · [Backend](https://github.com/hoangthang183204/CinemaBooking-API)

</td>
<td width="33%" valign="top">

### ✅ TaskFlow
*Quản lý công việc nhóm*

Phân công việc, theo dõi tiến độ, trạng thái cập nhật theo thời gian thực. Dự án thực tập.

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

<a href="https://taskflow-frontend-virid.vercel.app/"><img src="https://img.shields.io/badge/Dùng_thử_ngay-2ea44f?style=for-the-badge" alt="Demo TaskFlow" /></a>

[Frontend](https://github.com/hoangthang183204/taskflow-frontend) · [Backend](https://github.com/hoangthang183204/taskflow-backend)

</td>
<td width="33%" valign="top">

### 👥 HR Flow
*Quản lý nhân sự*

Hồ sơ, hợp đồng, chấm công, nghỉ phép, tính lương, 5 vai trò. Đồ án tốt nghiệp.

![Laravel](https://img.shields.io/badge/Laravel_12-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

<img src="https://img.shields.io/badge/Demo-Đang_cập_nhật-lightgrey?style=for-the-badge" alt="Demo đang cập nhật" />

[Mã nguồn](https://github.com/hoangthang183204/doantotnghiep)

</td>
</tr>
</table>

<br>

### Mỗi dự án có gì?

<details open>
<summary><b>🎬 Cinema Booking</b>: hệ thống đặt vé chạy thật</summary>

<br>

- **Giữ ghế có thời hạn**, tự hủy đơn quá hạn thanh toán và trả lại ghế, bắp nước, lượt mã giảm giá
- **Thanh toán:** VNPay (Return URL và IPN), MoMo (Sandbox), QR chuyển khoản, tại quầy
- **Đăng nhập:** JWT và Google OAuth 2.0, phân quyền Khách hàng, Nhân viên, Quản trị viên
- **Nhân viên:** POS bán vé, quét QR soát vé, tồn kho bắp nước, mở ca và bàn giao ca
- **Quản trị:** dashboard doanh thu và tỷ lệ lấp đầy ghế, quản lý phim, suất chiếu, khuyến mãi, xuất báo cáo Excel
- **Kiến trúc:** Clean Architecture 4 tầng (Domain, Application, Infrastructure, API)
- **Triển khai:** Vercel, Docker trên Render, SQL Server cloud, có CORS, biến môi trường và health check

```mermaid
flowchart LR
    A["Vue 3<br>Vercel"] --> B["ASP.NET Core 6 API<br>Docker · Render"]
    B --> C[("SQL Server<br>Cloud")]
    B --> D["VNPay · MoMo<br>Google OAuth"]
```

</details>

<details>
<summary><b>✅ TaskFlow</b>: quản lý công việc theo thời gian thực</summary>

<br>

- **API:** RESTful bằng Node.js và Sails.js, xác thực JWT và phân quyền
- **Dữ liệu:** MongoDB với Index, Pagination, xử lý truy vấn N+1
- **Hiệu năng:** Redis Cache và Rate Limiting
- **Thời gian thực:** WebSocket cập nhật trạng thái công việc
- **Giao diện:** Next.js, Optimistic UI để phản hồi nhanh
- **Triển khai:** Docker, CI/CD

</details>

<details>
<summary><b>👥 HR Flow</b>: nhân sự, chấm công và tính lương</summary>

<br>

- **Chấm công bằng nhận diện khuôn mặt** chạy nền, chỉ lưu đặc trưng khuôn mặt, không lưu ảnh gốc
- **Tính lương an toàn:** khóa kỳ lương theo tháng, khóa dòng đơn nghỉ khi duyệt, tránh tạo trùng bảng lương hoặc trừ phép hai lần
- **Bảo mật:** mã hóa CCCD, mã số thuế, số BHXH, tài khoản ngân hàng; ghi nhật ký giá trị cũ và mới khi sửa lương, giờ công
- **Phân quyền 5 vai trò:** Super Admin, HR, Kế toán, Trưởng phòng, Nhân viên
- **Vai trò của mình:** Trưởng nhóm, chia việc và theo dõi tiến độ, tham gia thiết kế cơ sở dữ liệu MySQL

</details>

<br>

## 🛠️ Công nghệ

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vue](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

</div>

<br>

## 📚 Đang học thêm

| Lĩnh vực | Nội dung |
|---|---|
| **Cấu trúc dữ liệu và giải thuật** | Hash Map, Linked List, Tree, Graph, Dynamic Programming |
| **System Design** | Scalability, Load Balancing, Caching, API Gateway |
| **Database** | Indexing, Transactions, Query Optimization |
| **DevOps** | Docker, CI/CD, Nginx |

<br>

<div align="center">

### 📫 Liên hệ

**thanghoang182004@gmail.com** · Hà Nội, Việt Nam

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3E2A3B,100:8A3B63&height=90&section=footer" alt="" />

</div>
