Sau khi xem thử ở tab **Preview** và thấy ưng ý, bạn nhớ bấm nút xanh lá **Commit changes...** ở góc phải trên cùng để lưu file nàyTuyệt vời, bạn đã tạo đúng file `README.md` rồi! GitHub có tích hợp sẵn chức năng xem trước (Preview) rất tiện lợi.

Bạn hãy **copy toàn bộ đoạn mã trong khung dưới đây**, dán thẳng vào vùng soạn thảo màu đen (chỗ có chữ *Enter file contents here*) trong hình của bạn. 

Sau khi dán xong, bạn hãy bấm sang tab **Preview** (nằm ngay bên cạnh tab **Edit**) để xem kết quả trực quan nhé!
```markdown
# 📚 Hướng dẫn Markdown Cơ bản
Dưới đây là các ký tự và cú pháp thường dùng nhất để trang trí file README.md.

---

## 1. Tiêu đề (Headings)
Sử dụng dấu `#` và khoảng trắng. Càng nhiều `#`, chữ càng nhỏ.
### Đây là tiêu đề 3 (dùng 3 dấu #)
#### Đây là tiêu đề 4 (dùng 4 dấu #)

---

## 2. Định dạng chữ (Text Formatting)
* **In đậm**: Bao quanh chữ bằng 2 dấu sao `**như thế này**`.
* *In nghiêng*: Bao quanh chữ bằng 1 dấu sao `*như thế này*`.
* ~~Gạch ngang~~: Bao quanh chữ bằng 2 dấu ngã `~~như thế này~~`.
* **_In đậm và nghiêng_**: Kết hợp cả hai `**_như thế này_**`.

---

## 3. Danh sách (Lists)

**Danh sách không thứ tự (dùng dấu `-` hoặc `*`):**
- Mua cà phê
- Code tính năng đăng nhập
  - Thiết kế database (lùi vào bằng phím Tab hoặc 2 dấu cách)
  - Viết API

**Danh sách có thứ tự:**
1. Mở máy tính
2. Gõ `git pull`
3. Bắt đầu làm việc

**Danh sách công việc (Task lists):**
- [x] Việc đã làm xong (điền chữ x vào giữa 2 ngoặc vuông)
- [ ] Việc chưa làm (để trống khoảng cách giữa 2 ngoặc)

---

## 4. Chèn Code & Highlight

**Làm nổi bật chữ trong dòng (Inline code):** 
Dùng 1 dấu gạch ngược (\`) để làm nổi bật tên file hoặc biến. Ví dụ: Bạn cần chạy lệnh `git push` để đẩy code.

**Khối code (Code block):** 
Dùng 3 dấu gạch ngược (\`\`\`) và thêm tên ngôn ngữ (VD: java, sql, bash) để GitHub tô màu chữ cho đẹp.

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, Quốc!");
    }
}
