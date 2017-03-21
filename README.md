# QUẢN LÝ GIAO DỊCH
1. **Lịch sử giao dịch**
    * Chủ yếu bao gồm những filter để lọc lược sử giao dịch
    * Tất cả những giao dịch xảy ra trong thời gian : tất cả , 3 tháng gần nhất , tuần ...
    * Nâng cao : 
        1. Lọc theo ngày-tháng-năm chính xác các giao dịch 
        2. Loại giao dịch : chuyển tiền , hoàn tiền , nạp tiền ...
        3. Trạng thái : chưa xác nhận , tạm hủy , đã hủy , từ khóa ...
        4. Trong trường : mã giao dịch , mã hóa đơn , email đối tác , điện thoại đối tác.
2. **Nạp tiền** có 4 hình thức nạp tiền chính : 
    * Nạp tiền bằng thể MasterCard , Visa , JCB.
    * Nạp bằng thẻ ATM / Tài khoản ngân hàng.
        #### Workflow các thao tác khi tương tác nạp tiền với hệ thống sandbox
        1. Nhập thông tin vào khung form rồi nhấn **Nạp Tiền**
        2. Nhập mã OTP , phí giao dịch là 10% số tiền được nạp vào.
        3. Trạng thái giao dịch thành công
        ![Ảnh Minh Họa Giao Dịch](http://i.imgur.com/agbmn6Bl.jpg)
        ![Ảnh Minh Họa Lược Sử Giao Dịch](http://i.imgur.com/quMObyM.png)
             
    * Chuyển khoản bằng Internet Banking , ATM , quầy giao dịch.
    * Nạp tiền bằng thẻ cào điện thoại : Vina , Viettel , Mobi , GATE
3. **Rút tiền**
    * Rút tiền từ tài khoản *Ngân Lượng* về tài khoản ngân hàng bạn muốn
4. **Chuyển tiền**
    * Đơn giản là nhập thông tin người muốn gửi và số tiền bạn muốn gửi vào form.
5. **Yêu cầu thanh toán**
    * Nhập thông tin người muốn gửi và số tiền bạn muốn gửi vào form.
6. **Nhận hoàn lại**
    * Tiền hoàn lại sẽ được lưu lại vào lược sử
7. **Khiếu nại**
    * Khiếu nại khi cảm thấy có gian lận , lừa đảo , scam ...khi thực hiện giao dịch trên hệ thống của **Ngân Lượng**

> Khi sử dụng các hình thức giao dịch với *Ngân Lượng* chúng ta bắt buộc phải đăng ký rồi xác minh **Chứng Thực** tài khoản 

# QUẢN TRỊ TÀI KHOẢN
1. **Thông tin tài khoản**
    * Thông tin cá nhân của chủ tài khoản.
    * Các giao dịch gần đây
    * Số dư khả dụng , số dư chờ nhận , số dư chờ chuyển , bị đóng băng.
2. **Đổi mật khẩu đăng nhập**
    * Điền thông tin cần thiết vào form
3. **Đổi mật khẩu giao dịch**
    * Nếu sử dụng phương thức *xác thực giao dịch bằng OTP* thì không thể sử dụng được chức năng này 
4. **Quên mật khẩu giao dịch**
    * Nếu sử dụng phương thức *xác thực giao dịch bằng OTP* thì không thể sử dụng được chức năng này
5. **Tài khoản ngân hàng**
    * Thêm thẻ tài khoản của những ngân hàng khác vào hệ thống của **Ngân Lượng**
6. **Địa chỉ Email**
    * Cho phép nhận và không nhận thông báo khi có sự thay đổi hoặc phát sinh giao dịch trên hệ thống của **Ngân Lượng**
    * Cho phép đổi email nhận thông báo
7. **Điện thoại di động**
    * Cho phép đổi số điện thoại xác thực giao dịch.
    * Giống như email , số điện thoại có thể nhận và không nhận thông báo khi có sự thay đổi hoặc phát sinh bất kỳ giao dịch nào trên hệ thống của **Ngân Lượng** đều sẽ có tin nhắn báo về số điện thoại đã được thêm vào đây .

8. **Hình thức xác thực GD**
    * Xác thực bằng OTP (One Time Password) :
        * Ưu điểm : Mật khẩu chỉ dùng 1 lần , độ an toàn gần như tuyệt đối.
        * Nhược điểm : phụ thuộc vào nhà cung cấp dịch vụ di động mà bạn đang sử dụng.
    * Xác thực bằng mật khẩu giao dịch :
        * Phải khai báo 1 mật khẩu khác với mật khẩu tài khoản bạn dùng để đăng nhập.
        * Ưu điểm : nhanh chóng , tiện lợi , sử dụng được kể cả khi bạn không có mặt ở Việt Nam.
        * Nhược điểm : vì nó là 1 mật khẩu mặc định nên nếu không thường xuyên thay đổi thì độ an toàn không cao bằng OTP
    > Có thể chuyển đổi qua lại giữa 2 hình thức trên
9. **Cấu hình tài khoản**
    * Có 2 loại tài khoản mà chúng ta có thể chuyển đổi : tài khoản ví **Cá Nhân** và tài khoản ví **Doanh Nghiệp**
    * Có thể sửa lại thông tin.
    > Lưu ý : Khi thay đổi loại tài khoản, tên chủ tài khoản sẽ không được thay đổi, một số thông tin khác sẽ bị xoá và bạn phải chứng thực lại tài khoản. Nếu tên chủ tài khoản không khớp với tên trong giấy chứng thực, NgânLượng.vn sẽ từ chối yêu cầu của bạn. Nếu bạn thay đổi từ loại tài khoản Doanh nghiệp sang loại dành cho Cá nhân, các thông tin về người đại diện của doanh nghiệp và toàn bộ các tài khoản con truy cập vào tài khoản doanh nghiệp và quyền của họ sẽ bị huỷ.

# TÍCH HỢP THANH TOÁN
1. **Tích hợp thanh toán**
    * Tích hợp thanh toán các dịch vụ bên thứ 3 : website , ứng dụng
    > VD : kết hợp thanh toán sàn TMĐT 

# THẺ CÀO
1. **Thẻ cào tổng hợp**
    * Thông tin tổng hợp 
    * Số dư thẻ cào
    * Sản lượng giao dịch theo ngày
    * Danh sách thiết lập phí mới cập nhật
2. **Thống kê sản lượng**
    * Thống kê sản lượng thẻ cào theo ngày bao gồm các thông tin :
        * Loại thẻ : viettel , mobi , GATE ...
        * Số lượng thẻ đúng
        * Sản lượng 
        * Phí giao dịch 
        * Thực nhận 
3. **Tra cứu giao dịch thẻ cào**
    * Dùng những filter để check tình trạng thẻ cào trong 2 tháng gần nhất :
        * Ngày giao dịch từ xx/yy/zz -> aa/bb/cc
        * Mã giao dịch
        * Mã tham chiếu
        * Mã thẻ
        * Serial
        * Loại thẻ : viettel , mobi , vina ...
        * Trạng thái : thẻ sai , timeout , thẻ chưa bị gạch , thành công.
        * Số điện thoại.
        * Khi đã nhập 1 trong những trường kia sẽ check trên hệ thống . Và xuất ra kết quả tìm kiếm ở dưới dựa theo những filter trên.
4. **Rút tiền**
    * Rút tiền giao dịch bằng thẻ cào.
5. **Danh sách yêu cầu rút tiền**
    * Danh sách những người đã yêu cầu rút tiền