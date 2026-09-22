# Java Networking Examples

Bộ ví dụ minh họa lập trình mạng (Java Networking) cơ bản, được xây dựng bằng **Java** và quản lý bằng **Maven**. Dự án dùng cho mục đích học tập, giúp hiểu cách Java làm việc với địa chỉ IP, URL và kết nối HTTP thông qua các lớp trong gói `java.net`.

---

## Giới thiệu (About)

**java-networking-examples** là bài tập/nghiên cứu cá nhân về lập trình mạng trong Java, tập trung vào ba lớp cốt lõi của gói `java.net`:

- `InetAddress` – tra cứu và làm việc với địa chỉ IP / tên miền.
- `URL` – phân tích và thao tác với các thành phần của một địa chỉ URL.
- `URLConnection` – mở kết nối tới một URL để đọc dữ liệu (request/response) qua HTTP.

Mục tiêu của dự án là cung cấp các ví dụ code ngắn gọn, dễ chạy thử trực tiếp trên terminal/IDE, phù hợp cho người mới bắt đầu tìm hiểu Java Networking.

---

## Tính năng chính

- Ví dụ tra cứu địa chỉ IP bằng `InetAddressExample.java`
  ---
  <img width="750" alt="image" src="https://github.com/user-attachments/assets/2eab37d0-98b3-4cb4-84df-53876bf865cd" />
  <img width="750" alt="image" src="https://github.com/user-attachments/assets/c51740ce-ac3b-478e-a1be-74b6a284ee16" />
- Ví dụ thao tác với `URL` bằng `UrlExample.java`
  ---
  <img width="750" alt="image" src="https://github.com/user-attachments/assets/6f0d7293-56c0-4c25-abf2-0da0a1b3fb2e" />
  <img width="750" alt="image" src="https://github.com/user-attachments/assets/d84dec51-775d-4c36-b0be-4e8bbefd32bc" />
- Ví dụ mở kết nối và đọc dữ liệu HTTP bằng `URLConnectionExample.java`
  ---
  <img width="750" alt="image" src="https://github.com/user-attachments/assets/69c392c4-14aa-49df-a74a-a427cae145a1" />
  <img width="750" alt="image" src="https://github.com/user-attachments/assets/52b780de-2989-436a-b8fe-9bfc2e944a49" />
- Chạy trực tiếp trên console/terminal, không cần cấu hình phức tạp

---

## Công nghệ sử dụng

| Thành phần | Phiên bản / Công cụ |
|---|---|
| Ngôn ngữ | Java 17+ |
| Build tool | Maven |
| IDE khuyến nghị | IntelliJ IDEA (Community/Ultimate), Eclipse hoặc VS Code |
| Plugin (nếu dùng IntelliJ) | Git Integration, Java Compiler |

---

## Cấu trúc dự án

```
java-networking-examples/
├── .idea/                          # Cấu hình IntelliJ IDEA
├── src/
│   └── main/
│       └── java/
│           ├── InetAddressExample.java
│           ├── URLConnectionExample.java
│           └── UrlExample.java
├── .gitignore
├── pom.xml                         # Cấu hình Maven
└── README.md
```

---

## Bắt đầu (Getting Started)

### Yêu cầu

- [JDK 17+](https://www.oracle.com/java/technologies/downloads/)
- [Maven](https://maven.apache.org/) (hoặc dùng Maven Wrapper nếu có)
- IntelliJ IDEA / Eclipse / VS Code (tùy chọn)

### Cài đặt

```bash
git clone https://github.com/nhunguy-swe/java-networking-examples.git
cd java-networking-examples
```

### Chạy chương trình

Với IntelliJ IDEA / Eclipse: mở project, chọn file ví dụ muốn chạy (ví dụ `InetAddressExample.java`) và nhấn **Run**.

Hoặc biên dịch và chạy trực tiếp bằng terminal:

```bash
cd src/main/java
javac InetAddressExample.java
java InetAddressExample
```

Tương tự với `UrlExample.java` và `URLConnectionExample.java`.

---

## Tài liệu tham khảo

- [Lập trình mạng với Java – viettuts.vn](https://viettuts.vn/lap-trinh-mang-voi-java)
- [Lập trình mạng với Java – gpcoder.com](https://gpcoder.com/3664-lap-trinh-mang-voi-java/)

---

## Tác giả

- GitHub: [@nhunguy-swe](https://github.com/nhunguy-swe)

---

## 📄 Giấy phép

Dự án này được thực hiện cho mục đích học tập/bài tập cá nhân. Bạn có thể tham khảo, sử dụng lại code cho mục đích học tập.

