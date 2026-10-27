
lookup_value (Giá trị cần tìm): Là mã linh kiện nằm ở sheet Don_Hang (ví dụ: ô A2 chứa giá trị LK01), đại diện cho đối tượng cần dò tìm thông tin.

table_array (Bảng chứa dữ liệu tra cứu): Là toàn bộ vùng dữ liệu bên sheet Danh_Muc chứa thông tin mã, tên linh kiện và đơn giá (ví dụ: Danh_Muc!A$2:C$100).

col_index_num (Số thứ tự cột cần lấy kết quả):

Điền số 2 nếu bạn muốn lấy giá trị từ cột Tên linh kiện (tính từ cột đầu tiên của bảng table_array).

Điền số 3 nếu bạn muốn lấy giá trị từ cột Đơn giá.

range_lookup (Kiểu tìm kiếm): Bắt buộc điền FALSE (hoặc số 0) để yêu cầu Excel tìm kiếm chính xác tuyệt đối mã linh kiện, tránh trả về kết quả gần đúng sai lệch.
