# 🖥️ Remote Desktop Services via GitHub Actions

[![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/windows)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![RDP](https://img.shields.io/badge/RDP-Remote_Desktop-0078D4?style=for-the-badge)](https://github.com)

Tự động triển khai Remote Desktop (RDP) với nhiều hệ điều hành Windows và Linux ngay trên GitHub Actions - hoàn toàn miễn phí!

## ✨ Tính năng chính

- 🚀 **Triển khai nhanh chóng** - Khởi tạo RDP chỉ trong vài phút
- 🌐 **Truy cập từ xa** - Kết nối RDP từ bất kỳ đâu qua Internet
- 💻 **Đa nền tảng** - Hỗ trợ nhiều phiên bản Windows và Ubuntu
- 🔒 **Bảo mật** - Tài khoản và mật khẩu được cấu hình sẵn
- ⏱️ **Session dài** - Duy trì kết nối lên đến 6 giờ
- 🌍 **Web Viewer** - Theo dõi quá trình cài đặt trực tiếp qua trình duyệt

## 📋 Hệ điều hành được hỗ trợ

### Windows Server
- ✅ **Windows Server 2025** (Native - 4vCPU | 16GB RAM)
- ✅ **Windows Server 2025** (Docker - 4vCPU | 8GB RAM)
- ✅ **Windows Server 2022** (Docker - 4vCPU | 8GB RAM)
- ✅ **Windows Server 2019** (Docker - 4vCPU | 8GB RAM)
- ✅ **Windows Server 2012** (Docker - 4vCPU | 8GB RAM)

### Windows Desktop
- ✅ **Windows 11 Professional** (Docker - 4vCPU | 8GB RAM)
- ✅ **Windows 10 Professional** (Docker - 4vCPU | 8GB RAM)

### Linux Desktop
- ✅ **Ubuntu 24.04 Desktop RDP** (Native - 4vCPU | 16GB RAM)

## 🚀 Hướng dẫn sử dụng

### Bước 1: Fork Repository
1. Click nút **Fork** ở góc trên bên phải
2. Đợi quá trình fork hoàn tất

### Bước 2: Kích hoạt GitHub Actions
1. Vào tab **Actions** trong repository của bạn
2. Click **I understand my workflows, go ahead and enable them**

### Bước 3: Chạy Workflow
1. Chọn workflow **🖥️ REMOTE DESKTOP SERVICES**
2. Click nút **Run workflow**
3. Chọn hệ điều hành mong muốn từ dropdown
4. Click **Run workflow** màu xanh

### Bước 4: Lấy thông tin kết nối
1. Đợi workflow chạy (2-5 phút)
2. Mở job đang chạy
3. Tìm step **🌐 Connection Information**
4. Sao chép thông tin RDP:
   - 🌐 **RDP Address** (IP:Port)
   - 👤 **Username**
   - 🔐 **Password**

### Bước 5: Kết nối RDP

#### Trên Windows:
```cmd
mstsc /v:IP_ADDRESS:PORT
```

#### Trên macOS:
- Sử dụng **Microsoft Remote Desktop** từ App Store
- Nhập địa chỉ IP:Port

#### Trên Linux:
```bash
rdesktop IP_ADDRESS:PORT
# hoặc
xfreerdp /u:Admin /p:PASSWORD /v:IP_ADDRESS:PORT
```

## 🔐 Thông tin đăng nhập mặc định

### Windows Systems
- 👤 **Username:** `Admin`
- 🔐 **Password:** `Window@123456`
- 📍 **Port:** `3389`

### Ubuntu Desktop
- 👤 **Username:** `Admin`
- 🔐 **Password:** `Ubuntu@123456`
- 📍 **Port:** `3389`
- 🎨 **Desktop Environment:** XFCE4

## 🌐 Web Viewer (Chỉ Windows Docker)

Các phiên bản Windows chạy trên Docker hỗ trợ Web Viewer để theo dõi quá trình cài đặt:

```
http://WEB_IP:8006
```

Web Viewer cho phép bạn:
- 👀 Xem quá trình cài đặt Windows theo thời gian thực
- 🖱️ Tương tác với giao diện cài đặt
- 📊 Giám sát tiến độ boot

## ⏱️ Thời gian session

- **Native runners:** 340 phút (5 giờ 40 phút)
- **Docker runners:** 360 phút (6 giờ)

> ⚠️ **Lưu ý:** Session sẽ tự động đóng khi hết thời gian. Hãy lưu dữ liệu trước khi hết giờ!

## 🛠️ Công nghệ sử dụng

- **GitHub Actions** - Nền tảng CI/CD
- **Docker** - Container hóa Windows (dockurr/windows)
- **Kami Tunnel** - Tunneling service để expose RDP
- **XRDP** - RDP server cho Ubuntu
- **XFCE4** - Desktop environment cho Ubuntu

## 📊 Tài nguyên hệ thống

### Windows Server 2025 (Native)
- ⚡ **CPU:** 4 vCPU
- 🧠 **RAM:** 16GB
- 💾 **Storage:** SSD GitHub Runner

### Windows (Docker) & Others
- ⚡ **CPU:** 4 vCPU
- 🧠 **RAM:** 8GB
- 💾 **Storage:** 60GB Virtual Disk

### Ubuntu 24.04 Desktop (Native)
- ⚡ **CPU:** 4 vCPU
- 🧠 **RAM:** 16GB
- 💾 **Storage:** SSD GitHub Runner

## ⚠️ Lưu ý quan trọng

1. **Không lưu trữ dữ liệu quan trọng** - Máy ảo sẽ bị xóa sau khi session kết thúc
2. **Tuân thủ GitHub Actions Usage Limits** - Đừng lạm dụng free tier
3. **Sử dụng hợp pháp** - Chỉ dùng cho mục đích học tập, testing hợp pháp
4. **Bảo mật** - Đổi mật khẩu ngay sau khi kết nối lần đầu
5. **Thời gian giới hạn** - Tối đa 6 giờ/session

## 🔧 Troubleshooting

### Không lấy được IP address
- Đợi thêm 2-3 phút
- Kiểm tra logs của step "Connection Information"
- Chạy lại workflow

### Không kết nối được RDP
- Kiểm tra firewall/antivirus
- Đảm bảo port 3389 không bị chặn
- Thử RDP client khác

### Windows boot chậm (Docker)
- Sử dụng Web Viewer để theo dõi
- Đợi 5-10 phút cho Windows khởi động hoàn toàn
- Phiên bản Native boot nhanh hơn Docker

## 📝 License

MIT License - Sử dụng tự do cho mục đích cá nhân và học tập

## 🤝 Đóng góp

Mọi đóng góp đều được chào đón! Vui lòng:
1. Fork repository
2. Tạo branch mới (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Mở Pull Request

## 📧 Liên hệ & Hỗ trợ

- 🐛 **Issues:** [GitHub Issues](https://github.com/yourusername/repo/issues)
- 💬 **Discussions:** [GitHub Discussions](https://github.com/yourusername/repo/discussions)

## ⭐ Star History

Nếu project này hữu ích, hãy cho một ⭐ để ủng hộ!

---

<div align="center">

**Made with ❤️ using GitHub Actions**

[![GitHub stars](https://img.shields.io/github/stars/yourusername/repo?style=social)](https://github.com/yourusername/repo/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yourusername/repo?style=social)](https://github.com/yourusername/repo/network/members)

</div>
