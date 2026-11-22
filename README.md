# Kho Game HTML5

Trang tổng hợp game HTML5 + JavaScript thuần, chơi ngay trên trình duyệt.

## Cấu trúc

```
index.html        Trang chủ: danh sách, tìm kiếm, lọc theo thể loại
games.js          Danh sách game
games/<id>/       Mỗi game một thư mục, có index.html
```

## Thêm game mới

1. Tạo thư mục `games/<id>/` chứa `index.html` của game (nên có link `../../` để quay về trang chủ).
2. Thêm một mục vào `games.js`:

```js
{ id: "snake", name: "Rắn săn mồi", icon: "🐍", color: "#2ecc71",
  tags: ["Hành động"], desc: "Mô tả ngắn", added: "2026-11-22" }
```

Game thêm trong 14 ngày gần nhất được gắn nhãn **MỚI**.
