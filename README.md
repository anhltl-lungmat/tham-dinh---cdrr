# Màn thẩm định MRC — prototype

Static prototype, 1 file. Không cần build step.

## Nội dung

- `index.html` — toàn bộ giao diện (HTML + CSS + JS đã inline, chạy offline)
- `vercel.json` — cấu hình static cho Vercel

## Chạy local

Mở `index.html` bằng trình duyệt, hoặc:

```bash
npx serve .
```

## Deploy Vercel

```bash
git init && git add . && git commit -m "MRC review prototype"
git remote add origin git@github.com:<user>/<repo>.git
git push -u origin main
```

Trên Vercel: **Add New → Project → Import** repo vừa push. Framework Preset chọn **Other**, Build Command để trống, Output Directory để trống (hoặc `.`). Deploy.

Hoặc deploy trực tiếp từ máy:

```bash
npx vercel --prod
```
