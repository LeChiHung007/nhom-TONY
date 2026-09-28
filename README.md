# 🎮 VŨ THÀNH UY // FUTURISTIC GAME DEVELOPER PORTFOLIO

<p align="center">
  <img src="https://images.unsplash.com/photo-1566492031773-4f4e44671857?auto=format&fit=crop&w=300&q=80" alt="Avatar Vũ Thành Uy" width="130" style="border-radius: 50%; border: 3px solid #00f0ff; box-shadow: 0 0 20px rgba(0, 240, 255, 0.4);" />
</p>

<p align="center">
  <strong>Trang web Hồ sơ cá nhân & Portfolio phong cách Game Hiện Đại Tương Lai (Cyberpunk / Sci-Fi HUD)</strong><br>
  Thiết kế dành riêng cho <strong>Vũ Thành Uy</strong> — Game Developer & Futuristic UI/UX Architect.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Online%20%2F%20Lvl.99-00f0ff?style=for-the-badge&logo=electron" alt="Status Badge" />
  <img src="https://img.shields.io/badge/Theme-5%20Colors%20HUD-b026ff?style=for-the-badge&logo=palette" alt="Theme Colors" />
  <img src="https://img.shields.io/badge/Tech-HTML5%20%7C%20CSS3%20%7C%20JS%20ES6+-ff2a5f?style=for-the-badge&logo=javascript" alt="Tech Stack" />
  <img src="https://img.shields.io/badge/Audio-Web%20Audio%20API-00ff88?style=for-the-badge&logo=soundcharts" alt="Web Audio" />
  <img src="https://img.shields.io/badge/FPS-60%20FPS%20Canvas-ffb703?style=for-the-badge&logo=webgl" alt="FPS" />
</p>

---

## 🌟 Giới Thiệu Dự Án

Trang Portfolio được kiến tạo theo phong cách **Sci-Fi / Cyberpunk Gaming**, mô phỏng bảng điều khiển chiến đấu (HUD - Heads-Up Display) của một phi thuyền hoặc nhân vật viễn tưởng tương lai cấp độ 99. Dự án tối ưu hóa trải nghiệm người dùng với bố cục 2 cột (Desktop) thu gọn thành 1 cột (Mobile), đi kèm hệ thống âm thanh Procedural Synth và một Minigame phản xạ tương tác thực tế ngay trên trang.

---

## 🚀 Tính Năng Nổi Bật (Key Features)

### 1. 🎨 Thanh Đổi Màu 5 Tông Sắc HUD Thông Minh
Giao diện tích hợp thanh chọn 5 gam màu chủ đạo có thể kích hoạt trực tiếp từ **Navbar**, **Sidebar** hoặc mục **Design Tokens**:
* 🔹 **Xanh Dương (Cyber Cyan - `#00f0ff`)**: Ánh sáng vi mạch tương lai, lạnh lùng và công nghệ cao.
* 🟣 **Tím Neon (Cyber Violet - `#b026ff`)**: Sắc thái Cyberpunk huyền ảo, đậm chất RPG.
* 🔴 **Đỏ Mecha (Mecha Crimson - `#ff2a5f`)**: Sức mạnh chiến binh cơ giáp, rực lửa và sắc bén.
* 🌸 **Hồng Synthwave (Cyber Pink - `#ff007f`)**: Phong cách Neon Arcade, Retro-Wave nổi bật.
* ⚪ **Xám Titan (Stealth Gray - `#cbd5e1`)**: Hợp kim giáp bảo vệ tinh giản, sắc sảo.

> *Hệ thống tự động đồng bộ biến CSS toàn cục (`:root`), lưu cấu hình vào `localStorage` để ghi nhớ màu yêu thích của người dùng qua các phiên truy cập.*

### 2. 🎯 Mini Game: "Cyber Target Reflex"
* Trải nghiệm bắn mục tiêu năng lượng phản xạ trực tiếp trên khung Arena 15 giây.
* Hệ thống tính toán điểm số (Score), độ chính xác (Accuracy %), thời gian thực và phân loại thứ hạng chiến binh (`Rank S+ Thần Xạ Cyber`, `Rank A`, `Rank B`).

### 3. 🔊 Bộ Âm Thanh Synth Tự Nhiên (Web Audio API)
* Không cần file MP3 nặng nề, toàn bộ tiếng click nút, tiếng bắn mục tiêu và tiếng đổi theme đều được tổng hợp thời gian thực bằng bộ tạo dao động âm tần (Oscillator Nodes) của trình duyệt.
* Tích hợp nút bật/tắt âm thanh tiện lợi trên thanh điều hướng.

### 4. 🌌 Canvas Mạng Lưới Hạt Năng Lượng 60 FPS
* Hiệu ứng Cyber Grid và các hạt dữ liệu trôi nổi tự động kết nối bằng tia laser năng lượng tương tác theo vị trí. Có nút bật/tắt để tiết kiệm pin trên thiết bị yếu.

### 5. 📱 Bố Cục Đáp Ứng Đa Nền Tảng (Responsive 2-Col -> 1-Col)
* **Desktop (> 768px)**: Cột trái cố định (Sticky Sidebar ID Card) hiển thị thông số nhân vật (Reticle xoay radar, thanh EXP/Mana, các nút sao chép 1 chạm có fallback); Cột phải hiển thị Quest Log, Cây kỹ năng và Form truyền tin.
* **Mobile (< 768px)**: Tự động chuyển thành 1 cột liền mạch, thanh menu trượt dạng Drawer mượt mà.

### 6. 🖨️ Chuẩn Xuất In CV A4 (Print Stylesheet)
* Nhấn nút **"XUẤT CV"** hoặc tổ hợp `Ctrl + P`, toàn bộ hiệu ứng nền và minigame sẽ tự động ẩn đi, văn bản chuyển sang định dạng đen trắng chuẩn trang A4 sắc nét để nộp tuyển dụng.

---

## 🛠️ Công Nghệ Sử Dụng (Tech Stack)

| Công Nghệ | Vai Trò & Điểm Nổi Bật |
| :--- | :--- |
| **HTML5 Semantic** | Cấu trúc chuẩn ngữ nghĩa W3C, tối ưu SEO và trợ năng (a11y). |
| **CSS3 & Design Tokens** | Quản lý biến màu CSS `:root`, hiệu ứng Glow Neon, Grid & Flexbox. |
| **Vanilla JavaScript (ES6+)** | Logic mượt mà, độc lập, không phụ thuộc thư viện nặng nề (Zero Dependencies). |
| **HTML5 Canvas 2D API** | Vẽ hiệu ứng hạt laser chuyển động 60 FPS mượt mà. |
| **Web Audio API** | Tổng hợp âm thanh Procedural Sound FX điện tử trực tiếp trên trình duyệt. |
| **Google Fonts** | Bộ font `Orbitron` (Tiêu đề Sci-Fi) & `Plus Jakarta Sans` (Nội dung). |
| **Font Awesome 6** | Bộ biểu tượng đồ họa công nghệ và mạng xã hội. |

---

## 📂 Cấu Trúc Thư Mục

```text
vu-thanh-uy-game-portfolio/
│
├── index.html        # Mã nguồn giao diện chính (HTML5 + CSS + JavaScript tích hợp)
└── README.md         # Tài liệu hướng dẫn sử dụng và giới thiệu dự án
```

---

## ⚡ Hướng Dẫn Sử Dụng & Khởi Chạy

### 1. Chạy trực tiếp từ máy tính (Offline)
* Nhấp đúp chuột vào file `index.html` hoặc mở bằng bất kỳ trình duyệt web nào (Chrome, Microsoft Edge, Firefox, Brave, Safari).

### 2. Triển khai lên GitHub Pages (Miễn phí)
1. Khởi tạo kho chứa Git trên máy tính:
   ```bash
   git init
   git add .
   git commit -m "feat: Khoi tao Portfolio Game Vu Thanh Uy"
   ```
2. Đẩy mã nguồn lên kho chứa GitHub của bạn:
   ```bash
   git remote add origin https://github.com/vuthanhuy/game-portfolio.git
   git branch -M main
   git push -u origin main
   ```
3. Truy cập vào **Settings** của Repository trên GitHub > mục **Pages** > chọn nhánh `main` và nhấn **Save**. Trang web sẽ được xuất bản trực tuyến sau vài giây!

---

## ⚙️ Hướng Dẫn Tùy Biến (Customization)

* **Thay đổi Avatar**: Mở file `index.html`, tìm đến thẻ `<img class="avatar" src="..." alt="Avatar Vũ Thành Uy Game Dev">` và thay bằng link ảnh đại diện hoặc file ảnh nội bộ của bạn.
* **Thay đổi liên kết cá nhân**: Tìm các dòng có `vuthanhuy.dev@gmail.com`, `vuthanhuy#2077` hoặc link `github.com/vuthanhuy` trong thẻ `aside` để cập nhật tọa độ liên lạc của bạn.
* **Thêm kỹ năng mới**: Thêm thẻ `<div class="skill-item" data-category="...">` vào mục `#skills`.

---

## 👤 Tác Giả & Bản Quyền

* **Họ và tên**: **Vũ Thành Uy**
* **Vị trí**: Game Developer & Futuristic UI/UX Architect
* **Email**: [vuthanhuy.dev@gmail.com](mailto:vuthanhuy.dev@gmail.com)
* **GitHub**: [@vuthanhuy](https://github.com/vuthanhuy)
* **Bản quyền**: © 2026 Vũ Thành Uy. Mã nguồn mở phục vụ học tập và phát triển cá nhân.
