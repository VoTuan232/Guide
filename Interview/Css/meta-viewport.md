*** Viewport trong html

Viewport là khu vực hiển thị nội dung mà người dùng nhìn thấy trên website (có thể hiểu là khung nhìn). Viewport sẽ thay đổi theo thiết bị, viewport trên điện thoại di động sẽ nhỏ hơn so với trên màn hình máy tính.

Viewport không chính xác sẽ khiến người dùng phải cuộn ngang trong khi duyệt web (nội dung tràn màn hình) thay vì website sẽ hiện thị hoàn hảo trên màn hình thiết bị của họ. Thông qua thẻ <meta>, các nhà thiết kế website có thể kiểm soát chế độ xem (kiểm soát kích thước và tỷ lệ của trang web).

width: Chiều rộng của khung nhìn. Thông thường, chiều rộng này sẽ được đặt bằng với chiều rộng thiết bị (device-width) hoặc kích thước responsive thường thấy.

initial-scale: Mức thu phóng của website và chiều rộng của chế độ xem. initial-scale thường được đặt bằng 1 (có thể tăng giá trị lên nhưng không được khuyến nghị)

minimum-scale: Mức thu phóng tối thiểu. Nghĩa là người dùng có thể thu nhỏ bao nhiêu. Điều này sẽ khiến người dùng mất kiểm soát và yếu tố này cũng không được khuyến nghị.

maximum-scale: Mức thu phóng tối đa. Cũng giống như mức thu phóng tối thiểu, thuộc tính này không được khuyến khích vì đánh mất quyền kiểm soát của người dùng.

user-scalable: Cho phép người dùng phóng to: giá trị "no" là không cho phép, giá trị "yes" là cho phép. Thực sự thì bạn KHÔNG NÊN sử dụng thuộc tính này trong thẻ meta viewport của mình!