<div align="center">

![Windy AI logo](media/readme.png)

</div>

<h1 align="center">Windy AI - Trợ lý Lập trình Cá nhân Hóa</h1>

<div align="center">

**Windy AI là một trợ lý AI mã nguồn mở giúp lập trình viên tăng tốc công việc, được xây dựng dựa trên Continue**

</div>

<div align="center">

<a target="_blank" href="https://opensource.org/licenses/Apache-2.0" style="background:none">
    <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg" style="height: 22px;" />
</a>
<a target="_blank" href="https://docs.continue.dev" style="background:none">
    <img src="https://img.shields.io/badge/windy_docs-%23BE1B55" style="height: 22px;" />
</a>
<a target="_blank" href="https://discord.gg/vapESyrFmJ" style="background:none">
    <img src="https://img.shields.io/badge/discord-join-windy.svg?labelColor=191937&color=6F6FF7&logo=discord" style="height: 22px;" />
</a>

<p></p>

## Tính năng chính

### 💬 Chat
Hỏi AI ngay trong IDE với ngữ cảnh mã nguồn hiện tại

![chat](docs/static/img/chat.gif)

### ✨ Autocomplete
Gợi ý mã ngay khi bạn đang gõ

![autocomplete](docs/static/img/autocomplete.gif)

### 🛠️ Edit
Yêu cầu AI sửa đoạn code hiện tại bằng lệnh ngắn gọn

![edit](docs/static/img/edit.gif)

### ⚡ Actions
Tập hợp các lệnh thường dùng để tương tác nhanh với AI

![actions](docs/static/img/actions.gif)

</div>

---

## 🚀 Hướng dẫn cài đặt Windy AI

### 1. Clone dự án từ GitHub

```bash
git clone https://github.com/ten-ban/windy-ai.git
cd windy-ai/extensions/vscode
```

> Hãy chắc chắn bạn đã cài Node.js >= 20.11.0 trước khi thực hiện các bước tiếp theo.

### 2. Cài đặt gói phụ thuộc và build extension

```bash
npm install
npx vsce package
```

Lệnh trên sẽ tạo file `windy-ai-1.1.17.vsix` trong thư mục hiện tại.

### 3. Cài đặt vào VS Code

#### Thực hiện các bước sau:

1. Mở **Visual Studio Code**
2. Nhấn `Ctrl + Shift + P`, chọn `Extensions: Install from VSIX`
3. Chọn file `windy-ai-1.1.17.vsix`
4. Chờ cài đặt và khởi động lại VSCode nếu được yêu cầu

---

## 🧪 Kiểm tra sau khi cài đặt

- Mở thanh sidebar, bạn sẽ thấy icon hoặc tab **Windy AI**
- Hoặc mở Command Palette (`Ctrl + Shift + P`) và gõ "Windy"

---

## Đóng góp

Bạn có thể fork dự án và gửi pull request. Hãy cùng nhau cải tiến Windy AI để phù hợp hơn với nhu cầu của cộng đồng!
