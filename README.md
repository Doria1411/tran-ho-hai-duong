# CV — Trần Hồ Hải Dương

- **Xem CV:** https://doria1411.github.io/tran-ho-hai-duong/
- **Tải PDF:** https://doria1411.github.io/tran-ho-hai-duong/assets/CV-Tran-Ho-Hai-Duong.pdf

Trang CV một trang, ứng tuyển **Trợ lý Social · Content · Chăm sóc cộng đồng**.
Chỉ dùng HTML/CSS/JS thuần, không cần cài đặt hay build gì.

```
index.html      ← trang CV
assets/         ← 5 ảnh + CV-Tran-Ho-Hai-Duong.pdf (bản PDF 1 trang A4)
.nojekyll       ← để GitHub Pages phục vụ file nguyên trạng
README.md       ← file hướng dẫn này
```

## Sửa nội dung

- Sửa ngay trên GitHub: mở `index.html`, bấm biểu tượng bút chì, sửa xong bấm **Commit changes**. Khoảng 1 phút sau trang tự cập nhật.
- **Ngày bắt đầu đi làm:** tìm `Sẵn sàng trao đổi` trong `index.html` và thay bằng ngày thật.
- Sau khi sửa, nhớ **xuất lại PDF** (xem mục bên dưới), vì file PDF không tự cập nhật theo trang.

## Xuất lại file PDF

1. Mở trang CV bằng Chrome hoặc Edge, bấm **Ctrl + P**.
2. Chọn **Save as PDF / Lưu dưới dạng PDF**, khổ **A4**. Trong *Tùy chọn khác*, bật **Đồ họa nền** và tắt **Đầu trang và chân trang**.
3. Lưu với tên `CV-Tran-Ho-Hai-Duong.pdf`, rồi upload đè lên file cũ trong thư mục `assets` của repo.

## Đưa lên một repo khác (nếu cần)

1. Tạo repo **Public** mới trên https://github.com/new.
2. Bấm **uploading an existing file**, kéo cả `index.html`, thư mục `assets`, `.nojekyll` và `README.md` vào, rồi bấm **Commit changes**.
3. Vào **Settings → Pages**, chọn **Deploy from a branch**, **Branch: `main`**, thư mục **`/ (root)`**, bấm **Save**.
4. Trong `index.html`, đổi các link `https://doria1411.github.io/tran-ho-hai-duong/` (dòng `og:image`, `og:url`, `canonical`) thành link mới.

## Lưu ý

Repo **Public** thì ai cũng xem được số điện thoại và email trên trang.
Địa chỉ đã được rút gọn còn "P. Tân Hưng, TP. Hồ Chí Minh", không ghi số nhà hay tên đường.
