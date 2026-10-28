# Cài điện thoại "Phần mềm gọi điện thân nhân"

**Dành cho người cài máy.** Làm theo thứ tự, mỗi máy khoảng 15–20 phút. Nếu kẹt ở bước nào, chụp màn hình gửi cho kỹ thuật viên.

Phiên bản app hiện tại: **0.4.7**

## Chuẩn bị

- Điện thoại Samsung Galaxy A26 đã sạc trên 50%, đã lắp SIM.
- Cáp USB của điện thoại và **một máy tính Windows (hoặc Mac) có trình duyệt Chrome hoặc Edge**. Không cần cài phần mềm gì lên máy tính.
- Nếu máy đã từng dùng: đăng xuất tài khoản Google và Samsung trước khi đặt lại (bước 1), nếu không máy sẽ đòi mật khẩu tài khoản cũ.

## Cài lần đầu

### 1. Đưa máy về như mới mua

Máy mới bóc hộp thì bỏ qua bước này.

Máy đã dùng: **Cài đặt** → **Quản lý chung** → **Đặt lại** → **Khôi phục cài đặt gốc** → **Đặt lại**. Máy tự khởi động lại và hiện màn hình chào mừng.

Máy đã cài "Phần mềm gọi điện thân nhân": vào quản trị → **Thiết lập máy** → **Mở Cài đặt của máy**, rồi làm như trên.

> [!CAUTION]
> Khôi phục cài đặt gốc xoá hết dữ liệu của app (danh sách người dùng, nhật ký cuộc gọi, ghi âm) trên máy.

### 2. Cài máy như máy mới, không đăng nhập tài khoản

Làm theo các màn hình chào mừng như bình thường. **Ở mọi bước đăng nhập tài khoản Google hoặc Samsung, bấm Bỏ qua.**

> [!WARNING]
> Máy có tài khoản thì không cài được ở bước 4. Khi đó phải làm lại từ bước 1.

### 3. Bật Gỡ lỗi USB

- **Cài đặt** → **Thông tin điện thoại** → **Thông tin phần mềm** → chạm **7 lần** vào **Số hiệu bản tạo** cho tới khi máy báo đã bật chế độ nhà phát triển.
- Quay lại **Cài đặt** → **Bảo mật và quyền riêng tư** → **Tự động chặn** → tắt. Nếu chưa tắt, mục Gỡ lỗi USB báo "Bị chặn bởi Tự động chặn" và không bật được.
- Quay lại **Cài đặt** → **Tùy chọn nhà phát triển** (cuối danh sách) → bật **Gỡ lỗi USB** → **OK**.

### 4. Cài app bằng trang cài máy

Cắm điện thoại vào máy tính, mở trang **https://nihammer.github.io/family-call-releases/cai-may/** bằng Chrome hoặc Edge, bấm **Cài đặt** rồi làm theo hướng dẫn trên trang:

- Chọn điện thoại trong danh sách trình duyệt hiện ra → **Kết nối**.
- Trên điện thoại, nếu hiện "Cho phép gỡ lỗi USB?": đánh dấu **Luôn cho phép** → **Cho phép**.

Trang tự tải app, cài vào điện thoại và khoá máy cho app. Khi app **Phần mềm gọi điện thân nhân** mở ra, máy hỏi **2 lần** "đặt Phần mềm gọi điện thân nhân làm mặc định": lần nào cũng chọn **Phần mềm gọi điện thân nhân** rồi bấm **Đặt làm mặc định**. Đây là bước bật chặn cuộc gọi đến và chặn gọi số lạ. Nếu máy hỏi quyền (truy cập nhật ký cuộc gọi, gọi điện, âm thanh…), lần nào cũng bấm **Cho phép**. Sau đó rút cáp; Gỡ lỗi USB cứ để bật.

### 5. Đặt mật khẩu quản trị

Trên bàn phím số của app, nhập `000000` rồi bấm **OK**. Lần đầu app yêu cầu đặt mật khẩu quản trị (ít nhất 6 ký tự, nên có cả chữ và số). Ghi mật khẩu vào sổ, giữ cẩn thận.

> [!NOTE]
> Quên mật khẩu quản trị: kỹ thuật viên có một **mật khẩu chủ** mở được trang quản trị của mọi máy. Liên hệ kỹ thuật viên, nhập mã quản trị (mặc định `000000`) rồi nhập mật khẩu chủ vào ô mật khẩu, sau đó vào **Cài đặt** đặt mật khẩu quản trị mới. Nếu mã quản trị cũng bị đổi mà không ai biết, kỹ thuật viên còn có một **mã chủ** dùng thay mã quản trị.

### 6. Bật ghi âm cuộc gọi

Trong trang quản trị, chọn **Thiết lập máy** → **Mở app điện thoại (Bật ghi âm, gọi điện)**. Trong app Điện thoại: **⋮** → **Cài đặt** → **Ghi âm cuộc gọi** → bật **Tự động ghi âm** cho **mọi cuộc gọi**. Xong thì bấm nút **Home** để về app.

> [!TIP]
> Nếu ở đầu trang Thiết lập máy có khung vàng "Chưa bật chặn cuộc gọi", bấm **Bật chặn cuộc gọi** và làm như ở bước 4.

### 7. Cài đặt ban đầu và nhập danh sách

Vào **Cài đặt**: sửa tên đơn vị (ô đầu tiên; dòng xem trước cho thấy tên sẽ hiện thế nào) và thời lượng mỗi phiên nếu cần, rồi bấm lưu ở cuối trang.

Vào mục đầu tiên của trang quản trị, bấm nút **+ Thêm …** và nhập từng người dùng cùng 1–3 số điện thoại được phép gọi. Làm theo hướng dẫn sử dụng dành cho người quản lý do kỹ thuật viên gửi.

### 8. Gọi thử

Bấm **Đăng xuất quản trị**. Nhập mã một người dùng, gọi thử tới một số đã đăng ký, nói vài câu rồi bấm **Kết thúc cuộc gọi**. Vào lại quản trị → **Nhật ký cuộc gọi**, thấy cuộc gọi vừa rồi và nghe lại được ghi âm là xong.

## Đổi Wi‑Fi hoặc cài đặt khác của máy

Vào quản trị → **Thiết lập máy** → **Mở Cài đặt của máy**. Đổi Wi‑Fi, độ sáng, âm lượng… như điện thoại bình thường. Xong thì bấm nút **Home** để về app. Trong lúc này máy vẫn khóa: không mở được app nào khác.

## Khi có bản cập nhật

Bật Wi‑Fi cho máy (hoặc dùng 4G của SIM). Vào quản trị → **Thiết lập máy** → **Kiểm tra bản mới** → **Cài bản …**. App tự tải, tự cài và tự mở lại. Dữ liệu trong app vẫn giữ nguyên.

---

<details>
<summary>Dành cho kỹ thuật viên: các file trong repo này</summary>

Repo này chỉ chứa file phát hành; mã nguồn ở repo riêng.

- `FamilyCall.apk`: trang cài máy và nút "Kiểm tra bản mới" tải file này (versionCode 11).
- `update.json`: phiên bản và SHA-256 của file APK, app đọc khi kiểm tra bản mới.
- `cai-may/`: trang cài máy một nút (GitHub Pages), cài app và đặt làm Device Owner qua WebUSB.

</details>
