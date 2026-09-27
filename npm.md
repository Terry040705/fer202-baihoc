# Các lệnh npm cơ bản

## Kiểm tra phiên bản

```bash
node -v
npm -v
```

## Khởi tạo dự án

```bash
npm init
npm init -y
```

## Cài package

```bash
npm install
npm install express
npm install --save-dev nodemon
```

## Gỡ package

```bash
npm uninstall express
```

## Chạy dự án

```bash
node index.js
npm start
npm run dev
```

## Kiểm tra và cập nhật package

```bash
npm list --depth=0
npm outdated
npm update
npm audit
npm audit fix
```

## Script mẫu trong package.json

```json
{
  "scripts": {
    "start": "node index.js",
    "dev": "nodemon index.js"
  }
}
```

Sau đó chạy server bằng:

```bash
npm start
```

Mở trình duyệt tại http://localhost:3000
