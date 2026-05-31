# Máy tính phí sàn Shopee & TikTok Shop

Website tĩnh để tính phí sàn, chi phí vận hành, thuế và đề xuất giá bán.

## Cách deploy một lần để dùng link cố định

Khuyến nghị dùng GitHub + Netlify:

1. Tạo một repository trên GitHub.
2. Upload toàn bộ thư mục dự án này lên repository.
3. Vào Netlify, chọn **Add new site** → **Import an existing project**.
4. Chọn repository GitHub vừa tạo.
5. Netlify sẽ đọc `netlify.toml` và publish thư mục `outputs`.
6. Sau khi deploy xong, Netlify cấp một link cố định. Mọi lần cập nhật sau chỉ cần sửa file rồi push lên GitHub, link đó tự cập nhật.

## File chính

- `index.html`: giao diện và logic tính toán.
- `shopee_mall_categories.js`: dữ liệu ngành hàng Shopee Mall.

## Cách cập nhật sau này

Sửa `index.html` hoặc `shopee_mall_categories.js`, commit/push lên GitHub. Netlify sẽ tự deploy lại trong vài chục giây, không cần upload zip lại.
