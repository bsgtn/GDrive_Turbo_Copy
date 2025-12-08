<p align="center">
  <img src="https://img.icons8.com/3d-fluency/94/google-drive.png" width="80"/>
</p>

<h1 align="center">🚀 GDrive Turbo Copy</h1>

<p align="center">
  <b>⚡ Công cụ sao chép Google Drive mạnh mẽ nhất</b><br>
  <sub>Copy hàng triệu file • Không giới hạn dung lượng • Tự động resume</sub>
</p>

<p align="center">
  <a href="https://colab.research.google.com/github/kazeidk/GDrive_Turbo_Copy/blob/main/GDrive_Turbo_Copy.ipynb">
    <img src="https://img.shields.io/badge/▶_MỞ_NGAY-Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Open In Colab"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/python-3.x-yellow?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/platform-Google_Colab-orange?style=flat-square"/>
</p>

---

## 🎯 Tại sao chọn GDrive Turbo Copy?

<table>
<tr>
<td width="50%">

### 😫 Vấn đề thường gặp
- ❌ Copy thủ công chậm, tốn thời gian
- ❌ Giới hạn dung lượng download/upload
- ❌ Mất kết nối phải làm lại từ đầu
- ❌ Không copy được Shared Drive
- ❌ Không biết tiến độ đang ở đâu

</td>
<td width="50%">

### 🎉 GDrive Turbo Copy giải quyết
- ✅ Copy **server-side**, siêu nhanh
- ✅ **♾️ KHÔNG GIỚI HẠN** dung lượng
- ✅ **Tự động resume** khi timeout
- ✅ Hỗ trợ **Shared Drive** đầy đủ
- ✅ **Real-time stats** chi tiết

</td>
</tr>
</table>

---

## ✨ Tính năng nổi bật

<table>
<tr>
<td align="center" width="25%">
<img src="https://img.icons8.com/3d-fluency/50/infinity.png" width="40"/><br>
<b>♾️ Không giới hạn</b><br>
<sub>Copy 100GB, 1TB, 10TB+<br>Không lo dung lượng</sub>
</td>
<td align="center" width="25%">
<img src="https://img.icons8.com/3d-fluency/50/speed.png" width="40"/><br>
<b>⚡ Siêu nhanh</b><br>
<sub>Copy trực tiếp server<br>20-100 MB/s</sub>
</td>
<td align="center" width="25%">
<img src="https://img.icons8.com/3d-fluency/50/save.png" width="40"/><br>
<b>💾 Auto Resume</b><br>
<sub>Checkpoint thông minh<br>Không mất tiến độ</sub>
</td>
<td align="center" width="25%">
<img src="https://img.icons8.com/3d-fluency/50/shield-done.png" width="40"/><br>
<b>🛡️ An toàn</b><br>
<sub>Chỉ copy, không xóa<br>File gốc nguyên vẹn</sub>
</td>
</tr>
</table>

### 📋 Danh sách đầy đủ

| Icon | Tính năng | Mô tả |
|:---:|:---|:---|
| ♾️ | **Unlimited Copy** | Không giới hạn dung lượng - Copy bao nhiêu cũng được |
| ⚡ | **Server-side Copy** | Copy trực tiếp trên server Google, không qua máy bạn |
| 🔄 | **Auto Resume** | Timeout? Chạy lại là tự động tiếp tục, không mất gì |
| 💾 | **Smart Checkpoint** | Lưu tiến độ mỗi 10 file + backup tự động |
| 🔁 | **Auto Retry** | Lỗi API? Tự retry 5 lần với exponential backoff |
| 📊 | **Real-time Stats** | Xem trực tiếp: số file, dung lượng, tốc độ, thời gian |
| 🎯 | **Exact Match** | Kiểm tra file trùng chính xác 100% |
| 🔍 | **Smart Filter** | Lọc theo tên, đuôi file linh hoạt |
| 📄 | **Export Docs** | Xuất Google Docs/Sheets/Slides → PDF |
| 🔗 | **Shortcut Detection** | Phát hiện và báo cáo shortcuts |
| 🔔 | **Sound Alert** | Âm thanh thông báo khi hoàn tất |
| 🧹 | **Auto GC** | Tự động dọn RAM, chạy ổn định |
| 📝 | **Full Logging** | Ghi log chi tiết mọi hoạt động |

---

## 🚀 Bắt đầu ngay (3 bước)

<table>
<tr>
<td align="center" width="33%">

### 1️⃣ Mở Colab
<a href="https://colab.research.google.com/github/kazeidk/GDrive_Turbo_Copy/blob/main/GDrive_Turbo_Copy.ipynb">
<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Click nút trên để mở

</td>
<td align="center" width="33%">

### 2️⃣ Nhập link
```
📁 Folder đích: [link của bạn]
📂 Folder nguồn: [link cần copy]
```
Chạy **Cell 1** → Nhập link

</td>
<td align="center" width="33%">

### 3️⃣ Copy!
```
▶️ Chạy Cell 2
⏳ Đợi hoàn tất
🎉 Done!
```
Timeout? Chạy lại Cell 2

</td>
</tr>
</table>

---

## 📖 Hướng dẫn chi tiết

### 🎮 Các Cell trong Notebook

| Cell | Tên | Chức năng | Khi nào dùng |
|:---:|:---|:---|:---|
| 1️⃣ | 📝 Nhập thông tin | Nhập link folder, cài đặt bộ lọc | Bắt đầu sử dụng |
| 2️⃣ | 🚀 Run Copy | Thực hiện copy | Sau khi nhập xong Cell 1 |
| 3️⃣ | 🗑️ Xóa checkpoint | Reset để copy lại từ đầu | Muốn copy lại từ đầu |
| 4️⃣ | 📋 Xem Log & Lỗi | Xem thống kê, file lỗi, shortcuts | Kiểm tra kết quả |

### ⚙️ Các tùy chọn

| Tùy chọn | Mô tả | Mặc định | Gợi ý |
|:---|:---|:---:|:---|
| 📁 **Folder đích** | Link folder Google Drive của bạn | - | Folder bạn có quyền edit |
| 📂 **Folder nguồn** | Link folder cần copy | - | Có thể là Shared Drive |
| 🚫 **Bỏ qua chứa** | Skip file có tên chứa text này | - | VD: `.tmp, backup` |
| ✅ **Chỉ lấy đuôi** | Chỉ copy file có đuôi này | - | VD: `.mp4, .pdf` |
| ❌ **Bỏ qua đuôi** | Skip file có đuôi này | - | VD: `.log, .bak` |
| ⏭️ **Skip file đã có** | Bỏ qua file trùng tên | ✅ | Nên bật để tránh trùng |
| 📄 **Export Docs** | Xuất Google Docs → PDF | ❌ | Bật nếu cần lưu Docs |
| 👁️ **Dry-run** | Chỉ xem preview, không copy | ❌ | Test trước khi copy thật |

---

## 💡 Mẹo sử dụng

<table>
<tr>
<td width="50%">

### 🌟 Để copy nhanh nhất
- 🌙 Chạy **ban đêm** (ít rate limit)
- 💪 Dùng **Colab Pro** + **High RAM**
- 📶 Mạng ổn định
- 🔄 Timeout? Chạy lại ngay Cell 2

</td>
<td width="50%">

### 📋 Theo dõi tiến độ
- 📊 Xem real-time trên màn hình
- 📝 Log chi tiết: `/content/gdrive_copy.log`
- 📋 Chạy **Cell 4** xem thống kê đầy đủ
- 🔗 Xem danh sách shortcuts bị bỏ qua

</td>
</tr>
</table>

---

## ❓ Câu hỏi thường gặp

<details>
<summary><b>🤔 Copy được bao nhiêu dung lượng?</b></summary>

> **♾️ KHÔNG GIỚI HẠN!** Tool sử dụng Google Drive API `files().copy()` - copy trực tiếp trên server Google, không download/upload qua máy bạn. Bạn có thể copy 100GB, 1TB, thậm chí 10TB+ mà không gặp vấn đề gì.

</details>

<details>
<summary><b>🤔 Copy được Shared Drive không?</b></summary>

> **Có!** Tool hỗ trợ đầy đủ Shared Drive. Chỉ cần bạn có quyền **view** folder nguồn là copy được.

</details>

<details>
<summary><b>🤔 Colab Free dùng được không?</b></summary>

> **Có!** Colab Free hoạt động tốt, chỉ có điều hay bị timeout (~90 phút). Đừng lo - chỉ cần **chạy lại Cell 2** là tự động resume từ chỗ dừng, không mất gì cả!

</details>

<details>
<summary><b>🤔 Có mất dữ liệu gốc không?</b></summary>

> **Không!** Tool chỉ **copy**, không xóa hay sửa gì file gốc. Dữ liệu nguồn luôn an toàn 100%.

</details>

<details>
<summary><b>🤔 Tốc độ copy bao nhiêu?</b></summary>

> Tùy thuộc vào Google API và thời điểm, trung bình **20-100 MB/s**. Ban đêm thường nhanh hơn do ít người dùng.

</details>

<details>
<summary><b>🤔 Sao không copy được Google Docs?</b></summary>

> Google Docs/Sheets/Slides là file đặc biệt, không có dung lượng thực. Mặc định tool bỏ qua. Nếu cần, bật **"Export Docs → PDF"** để xuất ra PDF.

</details>

<details>
<summary><b>🤔 Bị lỗi rate limit thì sao?</b></summary>

> Tool tự động **retry 5 lần** với exponential backoff. Nếu vẫn lỗi, đợi vài phút rồi chạy lại Cell 2. Mẹo: chạy ban đêm ít bị limit hơn.

</details>

---

## 📝 Changelog

### 🎉 v1.0 - Phiên bản đầu tiên
```
✨ Tính năng chính:
   • ♾️ Copy không giới hạn dung lượng
   • ⚡ Server-side copy siêu nhanh
   • 🔄 Auto resume khi timeout
   • 💾 Checkpoint + backup thông minh
   • 🔁 Auto retry 5 lần
   • 📊 Real-time stats
   • 📄 Export Google Docs → PDF
   • 🔗 Shortcut detection
   • 🔍 Smart filter
   • 🔔 Sound alert
   • 🧹 Auto GC
```

---

## 👨‍💻 Tác giả

<table>
<tr>
<td align="center">
<h3>Nguyễn Ngọc Anh Tú</h3>

[![Messenger](https://img.shields.io/badge/📢_Kênh_thông_báo-Messenger-00B2FF?style=for-the-badge&logo=messenger&logoColor=white)](https://www.messenger.com/channel/NguyenNgocAnhTu.VN)

[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white)](https://www.facebook.com/NguyenNgocAnhTu.VN)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/NguyenNgocAnhTu)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/kazeidk)

</td>
</tr>
</table>

> 💬 **Có thắc mắc?** Liên hệ qua [Messenger](https://www.messenger.com/channel/NguyenNgocAnhTu.VN) để được hỗ trợ!

---

## ⭐ Ủng hộ dự án

Nếu tool hữu ích với bạn, hãy:
- ⭐ **Star** repo này
- 🔄 **Share** cho bạn bè
- 📢 **Follow** [kênh thông báo](https://www.messenger.com/channel/NguyenNgocAnhTu.VN) để nhận update

---

<p align="center">
<img src="https://img.shields.io/badge/Made_with-❤️-red?style=flat-square"/>
<img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
</p>

<p align="center">
<sub>© 2024 Nguyễn Ngọc Anh Tú. Tự do sử dụng và chỉnh sửa.</sub>
</p>
