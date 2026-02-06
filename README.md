# 🖥️ Dịch Vụ Remote Desktop Miễn Phí (RDP) - GitHub Actions

[![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/windows)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![Kami Tunnel](https://img.shields.io/badge/Kami-Tunnel-00D9FF?style=for-the-badge&logo=cloudflare&logoColor=white)](https://github.com/kami2k1/tunnel)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

> **🚀 Dịch vụ Remote Desktop (RDP) miễn phí sử dụng GitHub Actions với Kami Tunnel - Truy cập Windows & Ubuntu Desktop từ mọi nơi trên thế giới!**

<div align="center">

### 🌐 Powered by [Kami Tunnel](https://github.com/kami2k1/tunnel)
*Giải pháp tunneling mạnh mẽ cho kết nối RDP qua IP Public*

</div>

---

## 📋 Mục Lục

- [✨ Tính Năng](#-tính-năng)
- [🌐 Về Kami Tunnel](#-về-kami-tunnel)
- [💻 Hệ Điều Hành Hỗ Trợ](#-hệ-điều-hành-hỗ-trợ)
- [🚀 Bắt Đầu Nhanh](#-bắt-đầu-nhanh)
- [📖 Hướng Dẫn Sử Dụng](#-hướng-dẫn-sử-dụng)
- [🌍 Hỗ Trợ Ngôn Ngữ](#-hỗ-trợ-ngôn-ngữ)
- [⚙️ Tài Nguyên Hệ Thống](#-tài-nguyên-hệ-thống)
- [🔌 Thông Tin Kết Nối](#-thông-tin-kết-nối)
- [❓ Câu Hỏi Thường Gặp](#-câu-hỏi-thường-gặp)
- [🔒 Lưu Ý Bảo Mật](#-lưu-ý-bảo-mật)
- [🤝 Đóng Góp](#-đóng-góp)
- [📜 Giấy Phép](#-giấy-phép)

---

## ✨ Tính Năng

<table>
<tr>
<td width="50%">

### 🚀 Hiệu Năng Cao
- ⚡ Windows Server 2025 Native với **16GB RAM**
- 🐧 Ubuntu 24.04 Desktop với **XFCE4**
- 💪 **4 vCPU** cho tất cả hệ thống
- 💾 **60GB** dung lượng lưu trữ

</td>
<td width="50%">

### 🌍 Kết Nối Toàn Cầu
- 🌐 **IP Public** qua Kami Tunnel
- 🔒 Giao thức **RDP** (Cổng 3389)
- 🔐 Bảo mật với **tường lửa**
- ⚡ Kết nối **nhanh & ổn định**

</td>
</tr>
<tr>
<td width="50%">

### ⏱️ Phiên Làm Việc Dài
- ⏰ Lên đến **6 giờ** mỗi phiên
- 🔄 Hỗ trợ **tự động kết nối lại**
- 📊 Giám sát trạng thái **real-time**
- 🎯 **Miễn phí 100%** với GitHub Actions

</td>
<td width="50%">

### 🎨 Dễ Sử Dụng
- 🖱️ Triển khai **một cú nhấp chuột**
- 👁️ Trình xem **web** để giám sát
- ⚙️ **Không cần cấu hình** phức tạp
- 🌐 Hỗ trợ **đa ngôn ngữ** (EN/VI)

</td>
</tr>
</table>

---

## 🌐 Về Kami Tunnel

<div align="center">

### 🔗 [Kami Tunnel](https://github.com/kami2k1/tunnel) - Giải Pháp Tunneling Chuyên Nghiệp

</div>

**Kami Tunnel** là công cụ tunneling mạnh mẽ giúp tạo **IP Public** cho dịch vụ RDP của bạn, cho phép truy cập từ mọi nơi trên thế giới.

#### 🎯 Tại Sao Sử Dụng Kami Tunnel?

| Tính Năng | Mô Tả |
|-----------|-------|
| 🌍 **IP Public Toàn Cầu** | Nhận IP public để truy cập RDP từ bất kỳ đâu |
| ⚡ **Tốc Độ Cao** | Kết nối nhanh với độ trễ thấp |
| 🔒 **Bảo Mật** | Mã hóa dữ liệu end-to-end |
| 🆓 **Miễn Phí** | Hoàn toàn miễn phí sử dụng |
| 🔧 **Dễ Tích Hợp** | Tích hợp đơn giản với GitHub Actions |

#### 📡 Cách Hoạt Động

```
┌─────────────────┐      ┌──────────────┐      ┌─────────────────┐
│  GitHub Actions │ ───► │ Kami Tunnel  │ ───► │   IP Public     │
│   (RDP Server)  │      │  (Tunneling) │      │ (Your Computer) │
└─────────────────┘      └──────────────┘      └─────────────────┘
     Local Port              Tunnel                Global Access
       :3389              Connection                  :3389
```

<div align="center">

**💡 Tìm hiểu thêm:** [github.com/kami2k1/tunnel](https://github.com/kami2k1/tunnel)

</div>

---

## 💻 Hệ Điều Hành Hỗ Trợ

### 🪟 Hệ Thống Windows (Dựa trên Docker)

<div align="center">

| Hệ Điều Hành | CPU | RAM | Lưu Trữ | Trạng Thái |
|--------------|:---:|:---:|:-------:|:----------:|
| Windows Server 2025 | 4 vCPU | 8GB | 60GB | ✅ Sẵn Sàng |
| Windows Server 2022 | 4 vCPU | 8GB | 60GB | ✅ Sẵn Sàng |
| Windows Server 2019 | 4 vCPU | 8GB | 60GB | ✅ Sẵn Sàng |
| Windows Server 2012 | 4 vCPU | 8GB | 60GB | ✅ Sẵn Sàng |
| Windows 11 Professional | 4 vCPU | 8GB | 60GB | ✅ Sẵn Sàng |
| Windows 10 Professional | 4 vCPU | 8GB | 60GB | ✅ Sẵn Sàng |

</div>

### 🚀 Hệ Thống Native Hiệu Năng Cao

<div align="center">

| Hệ Điều Hành | CPU | RAM | Loại | Đề Xuất |
|--------------|:---:|:---:|:----:|:-------:|
| Windows Server 2025 | 4 vCPU | **16GB** | Native | ⭐⭐⭐⭐⭐ |
| Ubuntu 24.04 Desktop | 4 vCPU | **16GB** | Native + XFCE4 | ⭐⭐⭐⭐⭐ |

</div>

---

## 🚀 Bắt Đầu Nhanh

### 1️⃣ Fork Repository Này
```bash
🍴 Nhấp vào nút "Fork" ở góc trên bên phải trang này
```

### 2️⃣ Kích Hoạt GitHub Actions
```yaml
📍 Vào tab "Actions" trong repository đã fork
✅ Nhấp "I understand my workflows, go ahead and enable them"
```

### 3️⃣ Chạy Workflow
```yaml
🎯 Nhấp vào tab "Actions"
🔧 Chọn workflow "Windows RDP" hoặc "Native RDP"
▶️  Nhấp nút "Run workflow"
🌍 Chọn hệ điều hành và ngôn ngữ mong muốn
🚀 Nhấp "Run workflow"
```

### 4️⃣ Lấy Thông Tin Kết Nối
```yaml
⏳ Đợi 3-5 phút để khởi tạo
📋 Kiểm tra logs workflow để xem chi tiết kết nối
🌐 IP Public sẽ được cung cấp bởi Kami Tunnel
🖥️ Sử dụng bất kỳ RDP client nào để kết nối
```

---

## 📖 Hướng Dẫn Sử Dụng

### 🪟 Windows RDP (Dựa trên Docker)

```yaml
Workflow: Windows-RDP.yml

Tùy chọn:
  🖥️  Hệ điều hành: Chọn phiên bản Windows
  🌍 Ngôn ngữ: English / Tiếng Việt
  
Thời gian khởi tạo: 3-5 phút
```

<div align="center">

#### 📦 Bạn Sẽ Nhận Được:

</div>

<table>
<tr>
<td width="50%">

**🔌 Kết Nối RDP**
- 🌐 IP Public từ Kami Tunnel
- 📍 Cổng: `3389`
- ⚡ Kết nối trực tiếp

</td>
<td width="50%">

**👤 Thông Tin Đăng Nhập**
- 👤 Tài khoản: `Admin`
- 🔐 Mật khẩu: `Window@123456`
- 🛡️ Quyền: Administrator

</td>
</tr>
<tr>
<td colspan="2">

**🖥️ Web Viewer** (Cổng 8006)
- 👁️ Theo dõi tiến trình cài đặt qua trình duyệt
- 📊 Giám sát trạng thái real-time
- 🔍 Debug và troubleshooting

</td>
</tr>
</table>

---

### 🚀 Native RDP (Hiệu Năng Cao)

```yaml
Workflow: Native-RDP.yml

Tùy chọn:
  🖥️  Hệ điều hành: Windows Server 2025 / Ubuntu 24.04
  🌍 Ngôn ngữ: English / Tiếng Việt
  
Thời gian khởi tạo: 2-3 phút
```

<div align="center">

#### ⚡ Bạn Sẽ Nhận Được:

</div>

<table>
<tr>
<td width="33%">

**💪 Hiệu Năng**
- 🔥 RAM cao hơn (16GB)
- ⚡ Hiệu năng Native
- 🚀 Tốc độ xử lý nhanh

</td>
<td width="33%">

**🖥️ Môi Trường**
- 🎨 Desktop đầy đủ
- 🔧 Công cụ phát triển
- 📦 Ứng dụng đồ họa

</td>
<td width="33%">

**🔐 Đăng Nhập**
- 👤 Tài khoản: `Admin`
- 🔐 Windows: `Window@123456`
- 🐧 Ubuntu: `Ubuntu@123456`

</td>
</tr>
</table>

---

## 🌐 Hỗ Trợ Ngôn Ngữ

<div align="center">

### Dự Án Hỗ Trợ Đa Ngôn Ngữ

</div>

<table>
<tr>
<td width="50%">

### 🇬🇧 English (Tiếng Anh)
```yaml
Setup:
  - Select "English" when running workflow
  - All logs and messages in English
  - Global standard interface
```

**✅ Bao Gồm:**
- Logs tiếng Anh
- Thông báo hệ thống
- Tài liệu đầy đủ

</td>
<td width="50%">

### 🇻🇳 Tiếng Việt (Vietnamese)
```yaml
Cài Đặt:
  - Chọn "Tiếng Việt" khi chạy workflow
  - Tất cả logs và thông báo bằng tiếng Việt
  - Giao diện thân thiện người Việt
```

**✅ Bao Gồm:**
- Logs tiếng Việt
- Thông báo hệ thống
- Tài liệu đầy đủ

</td>
</tr>
</table>

---

## ⚙️ Tài Nguyên Hệ Thống

<div align="center">

### 📊 Cấu Hình Chi Tiết

</div>

#### 🐳 Hệ Thống Docker
<table>
<tr>
<th>Tài Nguyên</th>
<th>Cấu Hình</th>
<th>Mô Tả</th>
</tr>
<tr>
<td>💻 CPU</td>
<td><b>4 vCPU</b></td>
<td>Xử lý đa nhiệm mượt mà</td>
</tr>
<tr>
<td>🧠 RAM</td>
<td><b>8GB</b></td>
<td>Đủ cho hầu hết tác vụ</td>
</tr>
<tr>
<td>💾 Lưu Trữ</td>
<td><b>60GB</b></td>
<td>SSD tốc độ cao</td>
</tr>
<tr>
<td>⏰ Phiên</td>
<td><b>6 giờ</b></td>
<td>Làm việc liên tục</td>
</tr>
<tr>
<td>🌐 Kết Nối</td>
<td><b>Kami Tunnel</b></td>
<td>IP Public toàn cầu</td>
</tr>
</table>

#### ⚡ Hệ Thống Native
<table>
<tr>
<th>Tài Nguyên</th>
<th>Cấu Hình</th>
<th>Mô Tả</th>
</tr>
<tr>
<td>💻 CPU</td>
<td><b>4 vCPU</b></td>
<td>Hiệu năng native tối đa</td>
</tr>
<tr>
<td>🧠 RAM</td>
<td><b>16GB</b></td>
<td>Gấp đôi cho tác vụ nặng</td>
</tr>
<tr>
<td>💾 Lưu Trữ</td>
<td><b>Mặc định</b></td>
<td>Tùy theo runner</td>
</tr>
<tr>
<td>⏰ Phiên</td>
<td><b>6 giờ</b></td>
<td>Làm việc liên tục</td>
</tr>
<tr>
<td>🌐 Kết Nối</td>
<td><b>Kami Tunnel</b></td>
<td>IP Public toàn cầu</td>
</tr>
</table>

---

## 🔌 Thông Tin Kết Nối

### 🌐 IP Public từ Kami Tunnel

<div align="center">

```
╔════════════════════════════════════════════════════════╗
║                                                        ║
║  🎯 Kami Tunnel đã tạo IP Public cho bạn!            ║
║                                                        ║
║  Kết nối RDP từ bất kỳ đâu trên thế giới             ║
║  với IP Public được cung cấp trong logs workflow      ║
║                                                        ║
╚════════════════════════════════════════════════════════╝
```

</div>

---

### 🖥️ Cách Kết Nối Từ Các Nền Tảng

<table>
<tr>
<td width="50%">

#### 🪟 Windows RDP Client

```powershell
1. Nhấn Win + R
2. Gõ: mstsc
3. Nhấn Enter
4. Nhập IP Public từ Kami Tunnel
5. Đăng nhập với thông tin đã cung cấp
```

**📝 Lưu Ý:**
- ✅ Hỗ trợ copy-paste
- ✅ Chia sẻ clipboard
- ✅ Chuyển file dễ dàng

</td>
<td width="50%">

#### 🍎 macOS

```bash
1. Tải Microsoft Remote Desktop
   từ App Store
2. Thêm PC mới
3. Nhập IP Public từ Kami Tunnel
4. Cổng: 3389
5. Nhập thông tin đăng nhập
```

**📝 Lưu Ý:**
- ✅ Giao diện thân thiện
- ✅ Hỗ trợ Retina
- ✅ Multi-monitor

</td>
</tr>
<tr>
<td width="50%">

#### 🐧 Linux

```bash
# Sử dụng rdesktop
rdesktop [IP_PUBLIC]:3389

# Hoặc xfreerdp (khuyên dùng)
xfreerdp /u:Admin \
         /p:Window@123456 \
         /v:[IP_PUBLIC]:3389 \
         /cert:ignore
```

**📝 Lưu Ý:**
- ✅ Hỗ trợ nhiều protocol
- ✅ Tùy chỉnh độ phân giải
- ✅ Âm thanh chuyển tiếp

</td>
<td width="50%">

#### 📱 Di Động (Android/iOS)

```yaml
1. Cài đặt Microsoft Remote Desktop
2. Thêm kết nối mới:
   - IP: [IP Public từ Kami Tunnel]
   - Port: 3389
   - User: Admin
   - Password: [Mật khẩu]
3. Lưu và kết nối
```

**📝 Lưu Ý:**
- ✅ Touch-friendly
- ✅ Hỗ trợ gesture
- ✅ Làm việc mọi lúc

</td>
</tr>
</table>

---

## 📊 Định Dạng Chi Tiết Kết Nối

<div align="center">

### Sau Khi Workflow Hoàn Tất, Bạn Sẽ Thấy:

</div>

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║    ✅  WINDOWS SERVER 2025 - SẴN SÀNG KẾT NỐI              ║
║                                                              ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  🌐  THÔNG TIN KẾT NỐI REMOTE DESKTOP (RDP)                ║
║  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━  ║
║                                                              ║
║  🔌  IP Công Khai     : XXX.XXX.XXX.XXX:3389               ║
║  🚀  Powered by       : Kami Tunnel                         ║
║  👤  Tài Khoản        : Admin                               ║
║  🔐  Mật Khẩu         : Window@123456                       ║
║  📍  Cổng RDP         : 3389                                ║
║                                                              ║
║  🌍  Kết nối từ mọi nơi trên thế giới!                     ║
║                                                              ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  📊  WEB VIEWER (Chỉ Docker)                                ║
║  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━  ║
║                                                              ║
║  🌐  URL              : http://XXX.XXX.XXX.XXX:8006        ║
║  👁️   Mục đích        : Giám sát cài đặt                   ║
║                                                              ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  ⏰  THÔNG TIN PHIÊN                                        ║
║  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━  ║
║                                                              ║
║  ⏳  Thời gian        : 6 giờ                               ║
║  🔄  Tự động kết nối  : Có                                  ║
║  📊  Giám sát         : Real-time                           ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝

💡 Mẹo: Thay đổi mật khẩu ngay sau khi đăng nhập đầu tiên!
🔗 Tìm hiểu thêm về Kami Tunnel: https://github.com/kami2k1/tunnel
```

---

## ❓ Câu Hỏi Thường Gặp

<details>
<summary><b>⏰ Tôi có thể sử dụng RDP trong bao lâu?</b></summary>

<br>

**Đáp:** Mỗi phiên kéo dài tới **6 giờ**. Sau khi phiên kết thúc:
- ✅ Bạn có thể khởi động lại workflow cho phiên mới
- ✅ Không giới hạn số lần khởi động lại
- ⚠️ Lưu ý về giới hạn phút GitHub Actions (2,000 phút/tháng cho free account)

</details>

<details>
<summary><b>🔐 Tôi có thể thay đổi mật khẩu không?</b></summary>

<br>

**Đáp:** **Có**, và bạn **nên** thay đổi mật khẩu ngay sau khi kết nối:

**Windows:**
```
1. Nhấn Ctrl + Alt + Del
2. Chọn "Change Password"
3. Nhập mật khẩu hiện tại: Window@123456
4. Nhập mật khẩu mới (mạnh & phức tạp)
5. Xác nhận mật khẩu mới
```

**Ubuntu:**
```bash
passwd
# Nhập mật khẩu hiện tại
# Nhập mật khẩu mới
# Xác nhận mật khẩu mới
```

</details>

<details>
<summary><b>💰 Dịch vụ này có miễn phí không?</b></summary>

<br>

**Đáp:** **Có, hoàn toàn miễn phí!**

- ✅ Sử dụng **GitHub Actions** (free tier)
- ✅ **Kami Tunnel** miễn phí
- ✅ **Không cần thẻ tín dụng**
- ⚠️ GitHub cung cấp **2,000 phút/tháng** cho free account
- 💎 Nâng cấp lên GitHub Pro để có thêm phút

**Tính toán:**
- 1 phiên = 6 giờ = 360 phút
- 2,000 phút ÷ 360 = ~5.5 phiên/tháng

</details>

<details>
<summary><b>📦 Tôi có thể cài đặt phần mềm không?</b></summary>

<br>

**Đáp:** **Có, hoàn toàn!** Bạn có **quyền Administrator đầy đủ**:

**✅ Có Thể Cài Đặt:**
- 🎨 Phần mềm đồ họa (Photoshop, GIMP, etc.)
- 💻 IDE và công cụ phát triển (VS Code, Visual Studio, etc.)
- 🌐 Trình duyệt web (Chrome, Firefox, etc.)
- 📊 Office suite (Microsoft Office, LibreOffice, etc.)
- 🎮 Game nhẹ (chú ý về hiệu năng)
- 🔧 Bất kỳ phần mềm nào bạn cần

**⚠️ Lưu Ý:**
- Phiên chỉ kéo dài 6 giờ
- Tất cả dữ liệu sẽ bị xóa sau khi kết thúc
- Hãy backup công việc quan trọng

</details>

<details>
<summary><b>🎯 Tôi nên chọn hệ thống nào?</b></summary>

<br>

**Đáp:** Tùy thuộc vào nhu cầu của bạn:

| Nhu Cầu | Khuyến Nghị | Lý Do |
|---------|------------|-------|
| 📝 **Công việc văn phòng** | Windows Server 2025 (Docker) | Đủ RAM, ổn định |
| 🚀 **Tác vụ nặng** | Windows Server 2025 (Native) | 16GB RAM, hiệu năng cao |
| 💻 **Lập trình** | Ubuntu 24.04 Desktop | Môi trường Linux, XFCE4 |
| 🎨 **Thiết kế đồ họa** | Windows Native hoặc Ubuntu | Cần 16GB RAM |
| 🎮 **Gaming nhẹ** | Windows Native | Hiệu năng tốt nhất |
| 🧪 **Testing/Development** | Bất kỳ | Linh hoạt theo dự án |

**💡 Mẹo:**
- Bắt đầu với Docker để test
- Nâng cấp lên Native khi cần hiệu năng

</details>

<details>
<summary><b>🐧 Tại sao Ubuntu Desktop thay vì Server?</b></summary>

<br>

**Đáp:** Chúng tôi cung cấp **Ubuntu Desktop 24.04** với **XFCE4** vì:

**✅ Ưu Điểm:**
- 🖥️ **Giao diện đồ họa** đầy đủ (GUI)
- 🎨 **XFCE4**: Nhẹ, nhanh, tiết kiệm tài nguyên
- 🔧 **Công cụ phát triển** sẵn sàng
- 🌐 **Trình duyệt web** tích hợp
- 📊 **IDE và editors** dễ sử dụng
- 🎯 **RDP hoạt động mượt mà**

**📊 So Sánh:**
| Tính Năng | Desktop | Server |
|-----------|:-------:|:------:|
| GUI | ✅ Có | ❌ Không |
| RDP | ✅ Tốt | ⚠️ Cần cấu hình |
| Phát triển | ✅ Dễ dàng | ⚠️ CLI only |
| Đồ họa | ✅ Hỗ trợ | ❌ Không |

</details>

<details>
<summary><b>🌐 Web Viewer là gì?</b></summary>

<br>

**Đáp:** **Web Viewer** là công cụ giám sát qua trình duyệt web:

**🎯 Chức Năng:**
- 👁️ **Xem tiến trình cài đặt** Windows (Docker only)
- 📊 **Giám sát real-time** quá trình boot
- 🔍 **Debug** khi có vấn đề
- 📷 **Screenshot** màn hình Windows

**🔌 Truy Cập:**
```
URL: http://[IP_PUBLIC]:8006
Port: 8006
```

**⚠️ Lưu Ý:**
- Chỉ có trên **hệ thống Docker**
- Không có trên **Native**
- Đợi **5-10 phút** sau khi khởi động
- Dùng để **theo dõi**, không phải **điều khiển**

**💡 Mẹo:**
- Mở trong **Chrome/Firefox** để xem tốt nhất
- Refresh trang nếu không tải được
- Check logs nếu port 8006 không hoạt động

</details>

<details>
<summary><b>🌐 Kami Tunnel hoạt động như thế nào?</b></summary>

<br>

**Đáp:** **Kami Tunnel** là giải pháp tunneling tạo IP Public:

**🔧 Cách Hoạt Động:**
```
GitHub Actions Runner (Private IP)
          ↓
    Kami Tunnel Client
          ↓
    Kami Tunnel Server
          ↓
  Public IP (Accessible từ internet)
```

**✅ Ưu Điểm:**
- 🌍 **Truy cập toàn cầu** từ mọi nơi
- ⚡ **Tốc độ cao** với độ trễ thấp
- 🔒 **Bảo mật** end-to-end encryption
- 🆓 **Miễn phí** sử dụng
- 🔧 **Dễ tích hợp** với GitHub Actions

**📚 Tìm Hiểu Thêm:**
- Repository: [github.com/kami2k1/tunnel](https://github.com/kami2k1/tunnel)
- Documentation: Xem README trong repo
- Issues: Báo lỗi nếu gặp vấn đề

</details>

<details>
<summary><b>🔒 Kết nối có an toàn không?</b></summary>

<br>

**Đáp:** **Có**, nhưng bạn cần thực hiện các bước bảo mật:

**✅ Bảo Mật Có Sẵn:**
- 🔐 **RDP Protocol** mã hóa
- 🔒 **Kami Tunnel** mã hóa end-to-end
- 🛡️ **Firewall** được cấu hình

**⚠️ Bạn Cần Làm:**
1. **Đổi mật khẩu** ngay sau khi đăng nhập
2. Sử dụng **mật khẩu mạnh** (12+ ký tự, số, chữ, ký hiệu)
3. **Không chia sẻ** thông tin kết nối
4. **Tắt workflow** khi không dùng
5. Cài đặt **antivirus** nếu cần
6. **Backup** dữ liệu quan trọng

**🔐 Mật Khẩu Mạnh:**
```
❌ Yếu:   admin123
❌ Yếu:   Window@123456 (mặc định)
✅ Mạnh:  Rd#p_Sec!2025$Vn
✅ Mạnh:  K@m1Tun&3l#2025
```

</details>

---

## 🔒 Lưu Ý Bảo Mật

<div align="center">

### ⚠️ **BẢO MẬT LÀ ƯU TIÊN HÀNG ĐẦU**

</div>

<table>
<tr>
<td width="33%">

### 🔐 Mật Khẩu

**Bắt Buộc:**
- ✅ Đổi mật khẩu **ngay lập tức**
- ✅ Dùng mật khẩu **12+ ký tự**
- ✅ Kết hợp: `chữ + số + ký tự đặc biệt`
- ❌ Không dùng mật khẩu mặc định

**Ví Dụ Mật Khẩu Mạnh:**
```
✅ Rd#p_Sec!2025$Vn
✅ K@m1Tun&3l#2025
✅ Gh@ction$Rdp!26
```

</td>
<td width="33%">

### 🛡️ Thực Hành Tốt

**Luôn Làm:**
- ✅ Tắt workflow khi không dùng
- ✅ Giám sát logs thường xuyên
- ✅ Backup dữ liệu quan trọng
- ✅ Cài antivirus nếu cần
- ✅ Cập nhật hệ thống

**Không Bao Giờ:**
- ❌ Chia sẻ thông tin kết nối
- ❌ Lưu mật khẩu trên file text
- ❌ Dùng cho dữ liệu nhạy cảm
- ❌ Để workflow chạy không cần thiết

</td>
<td width="33%">

### 🌐 Kết Nối

**Khuyến Nghị:**
- ✅ Sử dụng VPN thêm bảo mật
- ✅ Kết nối từ mạng tin cậy
- ✅ Kiểm tra IP trước khi kết nối
- ✅ Đóng session sau khi xong

**Cảnh Báo:**
- ⚠️ IP Public tiếp xúc internet
- ⚠️ Phiên chỉ tồn tại 6 giờ
- ⚠️ Dữ liệu xóa sau khi kết thúc
- ⚠️ Không lưu thông tin cá nhân

</td>
</tr>
</table>

---

### 📋 Checklist Bảo Mật

<div align="center">

**Làm Theo Checklist Này Trước Khi Sử Dụng:**

</div>

- [ ] ✅ **Đã đọc hướng dẫn bảo mật**
- [ ] ✅ **Đã chuẩn bị mật khẩu mạnh mới**
- [ ] ✅ **Hiểu rằng phiên chỉ kéo dài 6 giờ**
- [ ] ✅ **Không lưu dữ liệu nhạy cảm**
- [ ] ✅ **Sẽ đổi mật khẩu ngay sau đăng nhập**
- [ ] ✅ **Sẽ tắt workflow khi không dùng**
- [ ] ✅ **Đã cài RDP client an toàn**

---

## 🛠️ Khắc Phục Sự Cố

<details>
<summary><b>🚫 Không thể kết nối RDP?</b></summary>

<br>

**Nguyên Nhân & Giải Pháp:**

1. **Workflow chưa hoàn tất:**
   - ⏳ Đợi thêm 2-3 phút
   - 📋 Kiểm tra logs trong tab Actions
   - ✅ Tìm dòng "✅ SẴN SÀNG KẾT NỐI"

2. **IP Public không đúng:**
   - 📍 Copy chính xác IP từ logs
   - 🔍 Kiểm tra định dạng: `XXX.XXX.XXX.XXX:3389`
   - 🔄 Refresh logs nếu không thấy IP

3. **Firewall chặn cổng 3389:**
   - 🔧 Tắt firewall tạm thời để test
   - 🌐 Kiểm tra router/modem settings
   - 📞 Liên hệ ISP nếu cổng bị chặn

4. **RDP Client lỗi:**
   - 🔄 Thử client khác (mstsc, Microsoft Remote Desktop, etc.)
   - 📦 Cài đặt lại RDP client
   - 💻 Restart máy tính của bạn

5. **Kami Tunnel chưa kết nối:**
   - 📊 Xem logs Kami Tunnel trong workflow
   - 🔄 Restart workflow nếu tunnel failed
   - 🐛 Báo lỗi tại [Kami Tunnel Issues](https://github.com/kami2k1/tunnel/issues)

**Debug Command:**
```bash
# Test kết nối đến IP và port
telnet [IP_PUBLIC] 3389

# Hoặc sử dụng nc (netcat)
nc -zv [IP_PUBLIC] 3389

# Nếu kết nối được = RDP server đang chạy
# Nếu không = Kiểm tra workflow logs
```

</details>

<details>
<summary><b>🖥️ Ubuntu Desktop hiển thị màn hình đen?</b></summary>

<br>

**Vấn đề này đã được sửa trong phiên bản mới!**

**✅ Giải Pháp:**
- Phiên bản hiện tại đã cấu hình XFCE4 đúng cách
- Nếu vẫn gặp vấn đề:
  1. Đợi thêm 2-3 phút sau khi kết nối
  2. Disconnect và connect lại
  3. Kiểm tra logs workflow để xem XFCE4 đã cài đặt chưa
  4. Thử kết nối với độ phân giải khác

**Nếu vẫn bị đen:**
```bash
# Trong session RDP, mở terminal (Ctrl+Alt+T)
# Restart display manager
sudo systemctl restart lightdm

# Hoặc restart XFCE4
xfce4-session --logout
```

</details>

<details>
<summary><b>⏱️ Phiên kết thúc quá sớm?</b></summary>

<br>

**Nguyên Nhân:**

1. **Hết quota GitHub Actions:**
   - 📊 Kiểm tra: Settings → Billing → Actions minutes
   - 🆓 Free: 2,000 phút/tháng
   - 💎 Pro: 3,000 phút/tháng

2. **Workflow bị cancel:**
   - ⏰ Kiểm tra timeout settings
   - 🔍 Xem logs để tìm lỗi
   - 🐛 Báo lỗi nếu bị cancel không rõ lý do

**Giải Pháp:**
```yaml
✅ Nâng cấp lên GitHub Pro
✅ Tối ưu thời gian sử dụng
✅ Chia nhỏ công việc thành nhiều session
✅ Sử dụng vào cuối tháng khi quota reset
```

**Tính Quota:**
```
1 phiên = 6 giờ = 360 phút
2,000 phút ÷ 360 = ~5.5 phiên/tháng (Free)
3,000 phút ÷ 360 = ~8.3 phiên/tháng (Pro)
```

</details>

<details>
<summary><b>🌐 Web Viewer không tải?</b></summary>

<br>

**Checklist:**

1. **Đợi đủ thời gian:**
   - ⏳ Windows cần 5-10 phút để cài đặt
   - 📊 Xem logs để tracking tiến trình
   - ✅ Chờ đến khi thấy "Web Viewer ready"

2. **URL đúng chưa:**
   - 🔍 Format: `http://[IP_PUBLIC]:8006`
   - ⚠️ Phải dùng `http://` không phải `https://`
   - 📋 Copy chính xác từ logs

3. **Trình duyệt:**
   - 🔄 Thử Chrome/Firefox
   - 🗑️ Xóa cache và cookies
   - 🚫 Tắt ad-blocker
   - 🔓 Tắt extension bảo mật

4. **Network:**
   - 🌐 Kiểm tra port 8006 không bị chặn
   - 🔧 Tắt firewall để test
   - 📡 Thử mạng khác (mobile data, etc.)

5. **Workflow:**
   - 📊 Kiểm tra logs Docker container
   - 🔍 Tìm lỗi trong quá trình khởi động
   - 🔄 Restart workflow nếu cần

**⚠️ Lưu Ý:**
- Web Viewer chỉ có trên **Docker system**
- Native system **không có** Web Viewer
- Chỉ dùng để **theo dõi**, không điều khiển

</details>

<details>
<summary><b>🐛 Copy/Paste không hoạt động?</b></summary>

<br>

**Windows Client:**
```
1. Mở RDP Connection Settings
2. Chọn "Local Resources"
3. Click "More..." trong Clipboard
4. Check ✅ "Clipboard"
5. Connect lại
```

**macOS Microsoft Remote Desktop:**
```
1. Preferences → Devices
2. Enable "Clipboard"
3. Reconnect
```

**Linux (xfreerdp):**
```bash
xfreerdp /u:Admin \
         /p:Window@123456 \
         /v:[IP_PUBLIC]:3389 \
         /cert:ignore \
         +clipboard  # ← Thêm tham số này
```

</details>

<details>
<summary><b>💾 Làm sao backup dữ liệu?</b></summary>

<br>

**Phương Pháp:**

1. **Google Drive:**
   ```
   1. Mở trình duyệt trong RDP
   2. Truy cập drive.google.com
   3. Upload files cần backup
   ```

2. **GitHub:**
   ```bash
   # Cài Git trong RDP session
   git config --global user.name "Your Name"
   git config --global user.email "your@email.com"
   git add .
   git commit -m "Backup from RDP"
   git push
   ```

3. **FTP/SFTP:**
   ```
   1. Cài FileZilla/WinSCP
   2. Connect tới server của bạn
   3. Transfer files
   ```

4. **Cloud Storage:**
   - ☁️ Dropbox
   - ☁️ OneDrive
   - ☁️ MEGA
   - ☁️ pCloud

**⚠️ Quan Trọng:**
- 💾 Backup **trước khi phiên kết thúc**
- ⏰ Set reminder 30 phút trước hết giờ
- 📦 Nén files lớn trước khi upload
- 🔒 Mã hóa dữ liệu nhạy cảm

</details>

---

## 🤝 Đóng Góp

<div align="center">

### 💖 Đóng Góp Luôn Được Chào Đón!

</div>

<table>
<tr>
<td width="50%">

### 🔧 Làm Thế Nào?

1. **🍴 Fork** repository này
   ```bash
   Click nút "Fork" ở trên
   ```

2. **🔧 Tạo** nhánh tính năng
   ```bash
   git checkout -b feature/TinhNangMoi
   ```

3. **💾 Commit** thay đổi
   ```bash
   git commit -m 'Thêm tính năng mới'
   ```

4. **📤 Push** lên nhánh
   ```bash
   git push origin feature/TinhNangMoi
   ```

5. **🔃 Mở** Pull Request
   ```
   Từ GitHub interface
   ```

</td>
<td width="50%">

### 🎯 Lĩnh Vực Đóng Góp

**Tài Liệu:**
- 📝 Cải thiện README
- 🌍 Thêm bản dịch mới
- 📚 Viết hướng dẫn chi tiết
- 🎥 Tạo video tutorial

**Code:**
- 🐛 Sửa bugs
- ✨ Thêm tính năng
- ⚡ Tối ưu hiệu năng
- 🔒 Cải thiện bảo mật

**Hệ Thống:**
- 🖥️ Hỗ trợ OS mới
- 🔧 Cải thiện workflow
- 🌐 Tích hợp tools mới
- 📊 Thêm monitoring

</td>
</tr>
</table>

---

### 🏆 Người Đóng Góp

<div align="center">

**Cảm ơn tất cả những người đã đóng góp cho dự án này!**

[![Contributors](https://contrib.rocks/image?repo=yourusername/rdp-github-actions)](https://github.com/yourusername/rdp-github-actions/graphs/contributors)

</div>

---

## 📺 Video Hướng Dẫn

<div align="center">

### 🎬 **Coming Soon on YouTube!**

</div>

Chúng tôi đang chuẩn bị video hướng dẫn chi tiết:

<table>
<tr>
<td width="33%">

**📹 Video 1**
### Bắt Đầu Nhanh
- Fork repository
- Setup workflow
- Kết nối RDP đầu tiên
- Tips & tricks

⏱️ **~10 phút**

</td>
<td width="33%">

**📹 Video 2**
### Nâng Cao
- Tối ưu hiệu năng
- Cài đặt phần mềm
- Backup dữ liệu
- Troubleshooting

⏱️ **~15 phút**

</td>
<td width="33%">

**📹 Video 3**
### Use Cases
- Development
- Design work
- Testing
- Gaming

⏱️ **~12 phút**

</td>
</tr>
</table>

<div align="center">

**🔔 Đăng ký và bật thông báo để không bỏ lỡ!**

[📺 YouTube Channel](#) | [📱 Facebook](#) | [💬 Discord](#)

</div>

---

## ⭐ Ủng Hộ Dự Án

<div align="center">

### 💝 Nếu Dự Án Này Hữu Ích Cho Bạn

</div>

<table>
<tr>
<td width="25%">

**⭐ Star**
```
Nhấn nút Star
ở góc trên
repository
```

</td>
<td width="25%">

**🍴 Fork**
```
Fork và
chia sẻ
với bạn bè
```

</td>
<td width="25%">

**📢 Share**
```
Chia sẻ trên
mạng xã hội
của bạn
```

</td>
<td width="25%">

**💬 Feedback**
```
Báo lỗi và
đề xuất
cải tiến
```

</td>
</tr>
</table>

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/yourusername/rdp-github-actions?style=social)](https://github.com/yourusername/rdp-github-actions/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yourusername/rdp-github-actions?style=social)](https://github.com/yourusername/rdp-github-actions/network/members)
[![GitHub watchers](https://img.shields.io/github/watchers/yourusername/rdp-github-actions?style=social)](https://github.com/yourusername/rdp-github-actions/watchers)

</div>

---

## 📜 Giấy Phép

<div align="center">

### ⚖️ MIT License

Dự án này được cấp phép theo **Giấy phép MIT**

**Bạn có thể:**
- ✅ Sử dụng miễn phí
- ✅ Chỉnh sửa và phân phối
- ✅ Sử dụng cho mục đích thương mại
- ✅ Tích hợp vào dự án khác

**Điều kiện:**
- 📄 Giữ thông báo bản quyền
- 📋 Giữ license text

[📖 Xem License đầy đủ](LICENSE)

</div>

---

## 📞 Liên Hệ & Hỗ Trợ

<div align="center">

### 🤝 Cần Giúp Đỡ? Chúng Tôi Ở Đây!

</div>

<table>
<tr>
<td width="33%">

**🐛 Báo Lỗi**
```
GitHub Issues
→ Bug Report Template
→ Chi tiết vấn đề
→ Logs & screenshots
```
[📝 Tạo Issue](https://github.com/yourusername/rdp-github-actions/issues/new)

</td>
<td width="33%">

**💡 Đề Xuất**
```
GitHub Discussions
→ Feature Request
→ Ý tưởng cải tiến
→ Thảo luận với cộng đồng
```
[💬 Mở Discussion](https://github.com/yourusername/rdp-github-actions/discussions)

</td>
<td width="33%">

**❓ Hỏi Đáp**
```
GitHub Discussions
→ Q&A Section
→ Tìm câu trả lời
→ Chia sẻ kinh nghiệm
```
[❓ Đặt Câu Hỏi](https://github.com/yourusername/rdp-github-actions/discussions/categories/q-a)

</td>
</tr>
</table>

---

## 🙏 Ghi Nhận

<div align="center">

### 💙 Cảm Ơn Các Dự Án & Cộng Đồng

</div>

<table>
<tr>
<td width="50%">

**🔧 Công Nghệ & Tools:**

- 🚀 **[GitHub Actions](https://github.com/features/actions)**
  - Cơ sở hạ tầng CI/CD miễn phí
  - Runners mạnh mẽ và đáng tin cậy

- 🌐 **[Kami Tunnel](https://github.com/kami2k1/tunnel)**
  - Giải pháp tunneling xuất sắc
  - IP Public ổn định và nhanh

- 🐳 **[Dockurr](https://github.com/dockur)**
  - Windows Docker images chất lượng
  - Hỗ trợ nhiều phiên bản Windows

</td>
<td width="50%">

**🎨 Cộng Đồng & Dự Án:**

- 🐧 **[XRDP Project](http://xrdp.org/)**
  - RDP server cho Linux
  - Tích hợp hoàn hảo

- 🖥️ **[XFCE4 Desktop](https://www.xfce.org/)**
  - Desktop environment nhẹ
  - Hiệu năng tuyệt vời

- 👥 **Contributors & Users**
  - Tất cả những người đóng góp
  - Cộng đồng người dùng
  - Feedback và bug reports

</td>
</tr>
</table>

---

## 📈 Thống Kê Dự Án

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/yourusername/rdp-github-actions?style=for-the-badge&logo=github)
![GitHub forks](https://img.shields.io/github/forks/yourusername/rdp-github-actions?style=for-the-badge&logo=github)
![GitHub issues](https://img.shields.io/github/issues/yourusername/rdp-github-actions?style=for-the-badge&logo=github)
![GitHub pull requests](https://img.shields.io/github/issues-pr/yourusername/rdp-github-actions?style=for-the-badge&logo=github)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/rdp-github-actions?style=for-the-badge&logo=github)
![GitHub contributors](https://img.shields.io/github/contributors/yourusername/rdp-github-actions?style=for-the-badge&logo=github)

</div>

---

## 🔄 Lịch Sử Phát Hành

<details>
<summary><b>📌 Phiên bản 2.1.0 (Mới nhất) - Feb 2026</b></summary>

<br>

### ✨ Tính Năng Mới:
- ✅ Tích hợp **Kami Tunnel** cho IP Public
- ✅ Cải thiện README với thiết kế đẹp hơn
- ✅ Thêm nhiều FAQ và troubleshooting
- ✅ Cập nhật documentation đầy đủ hơn

### 🐛 Sửa Lỗi:
- ✅ Fix Ubuntu Desktop màn hình đen
- ✅ Cải thiện XFCE4 configuration
- ✅ Tối ưu workflow startup time

### 📚 Documentation:
- ✅ Hướng dẫn chi tiết về Kami Tunnel
- ✅ Video tutorial roadmap
- ✅ Thêm use cases và examples

</details>

<details>
<summary><b>📌 Phiên bản 2.0.0 - Jan 2026</b></summary>

<br>

### ✨ Tính Năng:
- ✅ Hỗ trợ đa ngôn ngữ (English/Tiếng Việt)
- ✅ Cải thiện logging system
- ✅ Đổi tên biến rõ ràng hơn (PUBLIC_IP)
- ✅ Tách Native workflow riêng biệt
- ✅ Tăng cường bảo mật

</details>

<details>
<summary><b>📌 Phiên bản 1.0.0 - Dec 2025</b></summary>

<br>

### 🎉 Phát Hành Đầu Tiên:
- ✅ Windows Server (2025, 2022, 2019, 2012)
- ✅ Windows 10/11 Professional
- ✅ Ubuntu Desktop RDP
- ✅ Web viewer cho Docker systems
- ✅ Tài liệu cơ bản

</details>

---

<div align="center">

### 💖 Được Tạo Ra Với Tình Yêu Cho Cộng Đồng

<br>

**⭐ Star repo này nếu bạn thấy hữu ích! ⭐**

<br>

[![Star History Chart](https://api.star-history.com/svg?repos=yourusername/rdp-github-actions&type=Date)](https://star-history.com/#yourusername/rdp-github-actions&Date)

<br>

[🐛 Báo Lỗi](https://github.com/yourusername/rdp-github-actions/issues) · 
[💡 Yêu Cầu Tính Năng](https://github.com/yourusername/rdp-github-actions/issues/new?template=feature_request.md) · 
[📚 Tài Liệu](https://github.com/yourusername/rdp-github-actions/wiki) · 
[💬 Discussions](https://github.com/yourusername/rdp-github-actions/discussions)

<br>

---

<sub>🔧 Được xây dựng bởi cộng đồng · ⚡ Được hỗ trợ bởi GitHub Actions · 🌐 Powered by Kami Tunnel</sub>

<br>

**🌟 Made with ❤️ in Vietnam 🇻🇳**

</div>
