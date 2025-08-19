---

# FrontEnd

Dự án này được khởi tạo bằng [Angular CLI](https://github.com/angular/angular-cli) phiên bản **19.2.7**. Đây là phần giao diện người dùng (FrontEnd) của hệ thống, được xây dựng nhằm cung cấp trải nghiệm trực quan, dễ sử dụng, và có thể mở rộng trong tương lai.

---

## 🚀 Bắt đầu với dự án

### 1. Cài đặt môi trường

Trước khi chạy dự án, bạn cần chuẩn bị:

* **Node.js** (phiên bản >= 20.x khuyến nghị)
* **npm** hoặc **yarn**
* **Angular CLI**: cài đặt toàn cục bằng lệnh:

  ```bash
  npm install -g @angular/cli
  ```

### 2. Cài đặt thư viện

Tại thư mục dự án, chạy:

```bash
npm install
```

Điều này sẽ tải về toàn bộ dependencies được định nghĩa trong `package.json`.

---

## 🖥️ Development server

Để khởi chạy server phát triển cục bộ, chạy lệnh:

```bash
ng serve
```

Mặc định, ứng dụng sẽ chạy tại địa chỉ:
👉 `http://localhost:4200/`

Mỗi khi bạn chỉnh sửa mã nguồn trong thư mục `src/`, ứng dụng sẽ tự động **reload** để hiển thị thay đổi.

---

## 🛠️ Code scaffolding

Angular CLI hỗ trợ sinh code tự động để tăng tốc phát triển. Ví dụ:

* Tạo component mới:

  ```bash
  ng generate component component-name
  ```
* Tạo directive mới:

  ```bash
  ng generate directive directive-name
  ```
* Tạo pipe mới:

  ```bash
  ng generate pipe pipe-name
  ```
* Tạo service mới:

  ```bash
  ng generate service service-name
  ```

👉 Để xem toàn bộ lệnh hỗ trợ, chạy:

```bash
ng generate --help
```

---

## 📦 Build

Để build dự án (compile sang mã tối ưu hóa):

```bash
ng build
```

Kết quả sẽ nằm trong thư mục `dist/`.

* Mặc định, Angular sẽ tối ưu cho **production** (hiệu suất, tốc độ, kích thước gọn nhẹ).
* Bạn cũng có thể build theo môi trường custom:

  ```bash
  ng build --configuration=staging
  ```

---

## 🧪 Running unit tests

Để chạy **unit test** với [Karma](https://karma-runner.github.io):

```bash
ng test
```

Kết quả kiểm thử sẽ hiển thị trực tiếp trong terminal và có thể mở thêm ở trình duyệt.

---

## 🌐 Running end-to-end tests

Để chạy **end-to-end (e2e) tests**:

```bash
ng e2e
```

Lưu ý: Angular CLI không kèm framework e2e mặc định. Bạn có thể chọn Cypress, Protractor hoặc Playwright để cấu hình tuỳ theo nhu cầu.

---

## 📂 Cấu trúc thư mục

```plaintext
src/
 ├── app/                # Các module, component, service chính
 ├── assets/             # Hình ảnh, file tĩnh
 ├── environments/       # File cấu hình cho các môi trường (dev, prod, staging)
 ├── index.html          # File HTML gốc
 ├── main.ts             # Điểm khởi chạy ứng dụng
 └── styles.css          # Style toàn cục
```

---

## 🔧 Các lệnh hữu ích khác

* **Lint code** (kiểm tra coding convention):

  ```bash
  ng lint
  ```

* **Tạo production build và deploy**:

  ```bash
  ng build --prod
  ```

* **Phân tích bundle size** (giúp tối ưu hiệu năng):

  ```bash
  ng build --stats-json
  npx webpack-bundle-analyzer dist/front-end/stats.json
  ```

---

## 📘 Tài liệu & Tham khảo

* [Angular Official Documentation](https://angular.dev/)
* [Angular CLI Overview & Command Reference](https://angular.dev/tools/cli)
* [RxJS Documentation](https://rxjs.dev/) (sử dụng trong quản lý dữ liệu bất đồng bộ)
* [TypeScript Documentation](https://www.typescriptlang.org/)

---

## ✅ Kết luận

Dự án FrontEnd này sử dụng Angular với cấu trúc chuẩn, hỗ trợ mở rộng dễ dàng và quản lý hiệu quả. Với các công cụ CLI mạnh mẽ, bạn có thể nhanh chóng scaffold, build, test và deploy ứng dụng.
---
