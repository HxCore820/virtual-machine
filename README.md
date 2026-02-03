# 🖥️ Dịch Vụ Remote Desktop Miễn Phí (RDP) - GitHub Actions

[![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/windows)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

> **Dịch vụ Remote Desktop (RDP) miễn phí sử dụng GitHub Actions - Truy cập Windows & Ubuntu Desktop từ mọi nơi!**

---

## 📋 Mục Lục

- [Tính Năng](#-tính-năng)
- [Hệ Điều Hành Hỗ Trợ](#-hệ-điều-hành-hỗ-trợ)
- [Bắt Đầu Nhanh](#-bắt-đầu-nhanh)
- [Hướng Dẫn Sử Dụng](#-hướng-dẫn-sử-dụng)
- [Hỗ Trợ Ngôn Ngữ](#-hỗ-trợ-ngôn-ngữ)
- [Tài Nguyên Hệ Thống](#-tài-nguyên-hệ-thống)
- [Thông Tin Kết Nối](#-thông-tin-kết-nối)
- [Câu Hỏi Thường Gặp](#-câu-hỏi-thường-gặp)
- [Lưu Ý Bảo Mật](#-lưu-ý-bảo-mật)
- [Đóng Góp](#-đóng-góp)
- [Giấy Phép](#-giấy-phép)

---

## ✨ Tính Năng

🚀 **Hiệu Năng Cao**
- Windows Server 2025 Native với 16GB RAM
- Ubuntu 24.04 Desktop với XFCE4
- 4 vCPU cho tất cả hệ thống

🌍 **Hỗ Trợ Đa Ngôn Ngữ**
- Tiếng Anh (English)
- Tiếng Việt (Vietnamese)

🔒 **Kết Nối Bảo Mật**
- Giao thức RDP (Cổng 3389)
- Tài khoản được cấu hình sẵn
- Bảo vệ tường lửa

⏱️ **Phiên Dài**
- Lên đến 6 giờ mỗi phiên
- Hỗ trợ tự động kết nối lại
- Giám sát trạng thái thời gian thực

🎯 **Dễ Sử Dụng**
- Triển khai một cú nhấp chuột
- Trình xem web để giám sát
- Không cần cấu hình

---

## 💻 Hệ Điều Hành Hỗ Trợ

### 🪟 Hệ Thống Windows (Dựa trên Docker)

| Hệ Điều Hành | CPU | RAM | Lưu Trữ |
|--------------|-----|-----|---------|
| Windows Server 2025 | 4 vCPU | 8GB | 60GB |
| Windows Server 2022 | 4 vCPU | 8GB | 60GB |
| Windows Server 2019 | 4 vCPU | 8GB | 60GB |
| Windows Server 2012 | 4 vCPU | 8GB | 60GB |
| Windows 11 Professional | 4 vCPU | 8GB | 60GB |
| Windows 10 Professional | 4 vCPU | 8GB | 60GB |

### 🚀 Hệ Thống Native Hiệu Năng Cao

| Hệ Điều Hành | CPU | RAM | Loại |
|--------------|-----|-----|------|
| Windows Server 2025 | 4 vCPU | 16GB | Native |
| Ubuntu 24.04 Desktop | 4 vCPU | 16GB | Native + XFCE4 |

---

## 🚀 Bắt Đầu Nhanh

### 1️⃣ Fork Repository Này
Nhấp vào nút **Fork** ở góc trên bên phải trang này.

### 2️⃣ Kích Hoạt GitHub Actions
- Vào tab **Actions** trong repository đã fork
- Nhấp **"I understand my workflows, go ahead and enable them"**

### 3️⃣ Chạy Workflow
- Nhấp vào tab **Actions**
- Chọn workflow **"Windows RDP"** hoặc **"Native RDP"**
- Nhấp nút **"Run workflow"**
- Chọn hệ điều hành và ngôn ngữ mong muốn
- Nhấp **"Run workflow"**

### 4️⃣ Lấy Thông Tin Kết Nối
- Đợi 3-5 phút để khởi tạo
- Kiểm tra logs workflow để xem chi tiết kết nối
- Sử dụng bất kỳ RDP client nào để kết nối

---

## 📖 Hướng Dẫn Sử Dụng

### Với Windows RDP (Dựa trên Docker)

```yaml
Workflow: Windows-RDP.yml
Tùy chọn:
  - Hệ điều hành: Chọn phiên bản Windows
  - Ngôn ngữ: English / Tiếng Việt
```

**Bạn sẽ nhận được:**
- 🌐 Kết nối RDP (Cổng 3389)
- 🖥️ Web Viewer (Cổng 8006) - Theo dõi tiến trình cài đặt
- 👤 Tài khoản: `Admin`
- 🔐 Mật khẩu: `Window@123456`

### Với Native RDP (Hiệu Năng Cao)

```yaml
Workflow: Native-RDP.yml
Tùy chọn:
  - Hệ điều hành: Windows Server 2025 / Ubuntu 24.04
  - Ngôn ngữ: English / Tiếng Việt
```

**Bạn sẽ nhận được:**
- 🚀 RAM cao hơn (16GB)
- ⚡ Hiệu năng Native
- 🖥️ Môi trường desktop đầy đủ
- 👤 Tài khoản: `Admin`
- 🔐 Mật khẩu: `Window@123456` (Windows) / `Ubuntu@123456` (Ubuntu)

---

## 🌐 Hỗ Trợ Ngôn Ngữ

Dự án này hỗ trợ nhiều ngôn ngữ:

### Tiếng Anh (English)
```
Chọn "English" khi chạy workflow
Tất cả logs và thông báo sẽ bằng tiếng Anh
```

### Tiếng Việt
```
Chọn "Tiếng Việt" khi chạy workflow
Tất cả logs và thông báo sẽ bằng tiếng Việt
```

---

## ⚙️ Tài Nguyên Hệ Thống

### Hệ Thống Docker
| Tài Nguyên | Cấu Hình |
|------------|----------|
| CPU | 4 vCPU |
| RAM | 8GB |
| Lưu Trữ | 60GB |
| Phiên | 6 giờ |

### Hệ Thống Native
| Tài Nguyên | Cấu Hình |
|------------|----------|
| CPU | 4 vCPU |
| RAM | 16GB |
| Lưu Trữ | Mặc định |
| Phiên | 6 giờ |

---

## 🔌 Thông Tin Kết Nối

### Cách Kết Nối

#### Windows RDP Client:
1. Nhấn `Win + R`
2. Gõ `mstsc` và nhấn Enter
3. Nhập Public IP từ logs workflow
4. Đăng nhập với thông tin đã cung cấp

#### macOS:
1. Tải **Microsoft Remote Desktop** từ App Store
2. Thêm PC mới với Public IP
3. Nhập thông tin đăng nhập

#### Linux:
```bash
rdesktop PUBLIC_IP:3389
# hoặc
xfreerdp /u:Admin /p:PASSWORD /v:PUBLIC_IP:3389
```

#### Di Động (Android/iOS):
1. Cài đặt ứng dụng **Microsoft Remote Desktop**
2. Thêm kết nối mới
3. Nhập Public IP và thông tin đăng nhập

---

## 📊 Định Dạng Chi Tiết Kết Nối

Sau khi workflow bắt đầu, bạn sẽ thấy:

```
╔═══════════════════════════════════════════════════════╗
║    ✅ TÊN HỆ THỐNG - SẴN SÀNG KẾT NỐI               ║
╠═══════════════════════════════════════════════════════╣
║                                                       ║
║  🖥️  KẾT NỐI REMOTE DESKTOP (RDP)                    ║
║  ───────────────────────────────────────────────     ║
║  🌐  IP Công khai   : XXX.XXX.XXX.XXX:3389          ║
║  👤  Tài khoản      : Admin                          ║
║  🔐  Mật khẩu       : Window@123456                  ║
║  📍  Cổng RDP       : 3389                           ║
║                                                       ║
╚═══════════════════════════════════════════════════════╝
```

---

## ❓ Câu Hỏi Thường Gặp

### H: Tôi có thể sử dụng RDP trong bao lâu?
**Đ:** Mỗi phiên kéo dài tới 6 giờ. Bạn có thể khởi động lại workflow cho phiên mới.

### H: Tôi có thể thay đổi mật khẩu không?
**Đ:** Có, sau khi kết nối, bạn có thể thay đổi mật khẩu qua cài đặt hệ thống.

### H: Dịch vụ này có miễn phí không?
**Đ:** Có! Sử dụng gói miễn phí của GitHub Actions. GitHub cung cấp 2,000 phút/tháng cho tài khoản miễn phí.

### H: Tôi có thể cài đặt phần mềm không?
**Đ:** Có, bạn có quyền quản trị viên đầy đủ. Cài đặt bất kỳ phần mềm nào bạn cần.

### H: Tôi nên chọn hệ thống nào?
**Đ:**
- **Sử dụng chung**: Windows Server 2025 (Docker)
- **Hiệu năng cao**: Windows Server 2025 (Native) hoặc Ubuntu (Native)
- **Phát triển phần mềm**: Ubuntu 24.04 Desktop

### H: Tại sao Ubuntu Desktop thay vì Server?
**Đ:** Chúng tôi cung cấp Ubuntu **Desktop** với giao diện XFCE4, hoàn hảo cho ứng dụng đồ họa và phát triển.

### H: Web Viewer là gì?
**Đ:** Với Windows dựa trên Docker, bạn có thể theo dõi tiến trình cài đặt qua trình duyệt web trên cổng 8006.

---

## 🔒 Lưu Ý Bảo Mật

⚠️ **Thông Tin Bảo Mật Quan Trọng:**

1. **Thay Đổi Mật Khẩu Mặc Định**: Luôn thay đổi mật khẩu mặc định sau lần đăng nhập đầu tiên
2. **Sử Dụng Mật Khẩu Mạnh**: Tạo mật khẩu phức tạp với chữ cái, số và ký hiệu
3. **Không Chia Sẻ Thông Tin**: Giữ thông tin kết nối của bạn ở chế độ riêng tư
4. **Giám Sát Sử Dụng**: Kiểm tra logs GitHub Actions thường xuyên
5. **Sử Dụng Tạm Thời**: Các hệ thống này là tạm thời - không lưu trữ dữ liệu nhạy cảm
6. **IP Công Khai**: Kết nối được tiếp xúc với internet - sử dụng thực hành bảo mật

### Thực Hành Tốt Nhất:
```
✅ Thay đổi mật khẩu ngay sau khi kết nối
✅ Kích hoạt tường lửa nếu cần
✅ Cài đặt phần mềm diệt virus
✅ Tải xuống tệp trước khi phiên kết thúc
✅ Sử dụng VPN để bảo mật thêm
```

---

## 🛠️ Khắc Phục Sự Cố

### Không thể kết nối RDP?
1. Kiểm tra xem workflow vẫn đang chạy
2. Xác minh Public IP chính xác
3. Đảm bảo cổng RDP 3389 không bị chặn bởi tường lửa
4. Thử RDP client khác

### Ubuntu Desktop hiển thị màn hình đen?
Vấn đề này đã được **sửa** trong phiên bản mới nhất với cấu hình XFCE4 phù hợp.

### Phiên kết thúc quá sớm?
- Gói miễn phí có giới hạn sử dụng
- Kiểm tra hạn ngạch phút GitHub Actions của bạn
- Cân nhắc nâng cấp lên GitHub Pro để có thêm phút

### Web Viewer không tải?
- Đợi 5-10 phút để Windows cài đặt
- Xóa bộ nhớ cache trình duyệt
- Thử trình duyệt khác
- Kiểm tra xem cổng 8006 có thể truy cập được không

---

## 🤝 Đóng Góp

Đóng góp luôn được chào đón! Đây là cách bạn có thể giúp đỡ:

1. 🍴 Fork repository
2. 🔧 Tạo nhánh tính năng (`git checkout -b feature/TinhNangTuyetVoi`)
3. 💾 Commit thay đổi (`git commit -m 'Thêm TinhNangTuyetVoi'`)
4. 📤 Push lên nhánh (`git push origin feature/TinhNangTuyetVoi`)
5. 🔃 Mở Pull Request

### Lĩnh Vực Đóng Góp:
- 🌍 Thêm bản dịch ngôn ngữ
- 🖥️ Hỗ trợ thêm hệ điều hành
- 📝 Cải thiện tài liệu
- 🐛 Sửa lỗi và tối ưu hóa
- ✨ Tính năng mới

---

## 📺 Video Hướng Dẫn

🎬 **Sắp ra mắt trên YouTube!**

Đăng ký và bật thông báo để được thông báo khi video hướng dẫn được xuất bản.

---

## ⭐ Ủng Hộ Dự Án

Nếu dự án này giúp ích cho bạn, vui lòng:
- ⭐ Star repository này
- 🍴 Fork và chia sẻ với người khác
- 📢 Chia sẻ trên mạng xã hội
- 💬 Báo cáo vấn đề và đề xuất

---

## 📜 Giấy Phép

Dự án này được cấp phép theo **Giấy phép MIT** - xem tệp [LICENSE](LICENSE) để biết chi tiết.

---

## 📞 Liên Hệ & Hỗ Trợ

- 📧 **Issues**: [GitHub Issues](https://github.com/HxCore820/virtual-machine/issues/1)
- 🐛 **Báo cáo lỗi**: Sử dụng mẫu issue
- 💡 **Yêu cầu tính năng**: Mở thảo luận

---

## 🙏 Ghi Nhận

- Nhóm GitHub Actions vì cung cấp cơ sở hạ tầng CI/CD miễn phí
- Dockurr cho hình ảnh Windows Docker
- Cộng đồng XRDP và XFCE4
- Kami Tunnel cho giải pháp tunneling mạng
- Tất cả những người đóng góp và người dùng

---

## 📈 Thống Kê Dự Án

![GitHub stars](https://img.shields.io/github/stars/yourusername/rdp-github-actions?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/rdp-github-actions?style=social)
![GitHub issues](https://img.shields.io/github/issues/yourusername/rdp-github-actions)
![GitHub pull requests](https://img.shields.io/github/issues-pr/yourusername/rdp-github-actions)

---

<div align="center">

### Được tạo ra với ❤️ cho cộng đồng

**⭐ Star repo này nếu bạn thấy hữu ích! ⭐**

[Báo Lỗi](https://github.com/yourusername/rdp-github-actions/issues) · [Yêu Cầu Tính Năng](https://github.com/yourusername/rdp-github-actions/issues) · [Tài Liệu](https://github.com/yourusername/rdp-github-actions/wiki)

</div>

---

## 🔄 Lịch Sử Thay Đổi

### Phiên bản 2.0.0 (Mới nhất)
- ✅ Thêm hỗ trợ đa ngôn ngữ (English/Tiếng Việt)
- ✅ Cải thiện logging - cập nhật trạng thái một dòng
- ✅ Đổi tên biến cho rõ ràng hơn (PUBLIC_IP)
- ✅ Tách hệ thống Native sang workflow riêng
- ✅ Tăng cường khuyến nghị bảo mật

### Phiên bản 1.0.0
- 🎉 Phát hành ban đầu
- 🪟 Hỗ trợ Windows Server (2025, 2022, 2019, 2012)
- 💻 Hỗ trợ Windows 10/11 Professional
- 🐧 Hỗ trợ Ubuntu Desktop RDP
- 🌐 Web viewer cho hệ thống Docker

---

<div align="center">
  <sub>Được xây dựng bởi 🔧 cộng đồng · Được hỗ trợ bởi ⚡ GitHub Actions</sub>
</div>
