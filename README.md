# Omni Artifical

Kho chứa nhiều trang web HTML độc lập, mỗi trang phục vụ một mục đích riêng — không giới hạn ở một chủ đề cụ thể.

## Cấu trúc
```
Omni-Artifical/
├── index.html              ← trang chủ, liệt kê các công cụ
├── ielts-writing/
│   └── index.html          ← mô phỏng phòng thi IELTS Writing
└── README.md
```

## Cách chạy online (GitHub Pages)
1. Vào **Settings → Pages** của repo
2. Ở mục "Source", chọn branch `main`, thư mục `/ (root)`, bấm **Save**
3. Sau khoảng 1 phút, trang sẽ có tại:
   `https://<username>.github.io/Omni-Artifical/`

## Thêm công cụ mới
1. Tạo thư mục mới, ví dụ `ten-cong-cu/`
2. Đặt file HTML chính của công cụ đó tên là `index.html` trong thư mục
3. Mở `index.html` ở gốc repo, thêm 1 thẻ `<a class="card">` mới trong phần `.list` trỏ tới `./ten-cong-cu/`
4. Công cụ mới sẽ có tại `https://<username>.github.io/Omni-Artifical/ten-cong-cu/`

## Công cụ hiện có
- **IELTS Writing Simulator** (`/ielts-writing/`) — mô phỏng phòng thi IELTS Writing: 2 sheet Task 1/Task 2, đếm giờ, đếm từ, ô nhập đề song song. Chỉ chạy trong trình duyệt, không lưu server.
