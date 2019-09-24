# Borrow ME - An Book Exchange Social Network

## I. Tổng quan

**BorrowMe** là một nền tảng kết nối những người đọc sách, cho phép người dùng mượn và chia sẻ thông tin về sách. 
##### Cơ chế trao đổi sách
+ Người có sách muốn trao đổi tại website, viết review về quyển sách
+ Nếu có người mượn sách thì bắt đầu trao đổi trực tiếp với nhau qua tin nhắn về thời gian, địa điểm, … để mượn sách.

## II. Giải quyết vấn đề

Mỗi tháng mọi người đều dành một khoản từ 200.000-500.000 nghìn đồng để mua sách. Đọc lần đầu sách vẫn còn mới và đọc thì lần đầu thường kiểu cưỡi ngựa xem hoa, vẫn nên lưu lại để đọc lại ,mà số lần đọc lại cực kỳ hiếm, chưa kể có những cuốn sách mua về nhưng không đọc. Như vậy sẽ rất lãng phí.

Bên cạnh đó, có rất nhiều người muốn đọc sách nhưng họ không đủ tiền để mua quyển sách đó, đa phần họ là sinh viên các trường đại học, cao đẳng. Việc được đọc cuốn sách mà không cần bỏ ra nhiều tiền để mua chúng rất là tuyệt vời, tạo điều kiện cho sinh viên trau dồi tri thức, là động lực giúp họ đạt được ước mơ một cách chân thực hơn.

Chính vì thế, việc trao đổi sách sẽ giúp mọi người chia sẻ giá trị, kiến thức mà còn tiết kiệm thêm một khoản nhỏ để dành cho bạn vào những chi tiêu khác, tạo điều kiện cho tất cả mọi người đều được đọc sách.

## III. Mô tả chức năng 

**Borrow Me** bao gồm các chức năng chính sau:



<table class="tg">
  <tr>
    <th class="tg-7btt">STT</th>
    <th class="tg-7btt">Chức năng</th>
    <th class="tg-7btt">Actor</th>
    <th class="tg-7btt">Mô tả</th>
  </tr>
  <tr>
    <td class="tg-c3ow">1</td>
    <td class="tg-c3ow">Đăng ký</td>
    <td class="tg-c3ow">Guest</td>
    <td class="tg-0pky">Đăng ký tài khoản để đăng nhập vào hệ thống. Có thể đăng ký bằng gmail, facebook</td>
  </tr>
  <tr>
    <td class="tg-c3ow">2</td>
    <td class="tg-c3ow">Đăng nhập</td>
    <td class="tg-c3ow">Guest</td>
    <td class="tg-0pky">Nhập tài khoản và mật khẩu để đăng nhập vào hệ thống</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3</td>
    <td class="tg-c3ow">Tạo bài review</td>
    <td class="tg-c3ow">User</td>
    <td class="tg-0pky">Tạo một bài review về cuốn sách ưa thích. Bài review sẽ hiện thị lên trang cá nhân của người viết</td>
  </tr>
  <tr>
    <td class="tg-c3ow">4</td>
    <td class="tg-c3ow">Xem các bài review</td>
    <td class="tg-c3ow">User, Guess</td>
    <td class="tg-0pky">Người dùng có thể xem bài review của người dùng khác.</td>
  </tr>
  <tr>
    <td class="tg-c3ow">5</td>
    <td class="tg-c3ow">Đánh giá bài review</td>
    <td class="tg-c3ow">User</td>
    <td class="tg-0pky">Bình luận, đánh giá sao cho các bài review.</td>
  </tr>
  <tr>
    <td class="tg-c3ow">6</td>
    <td class="tg-c3ow">Thêm tủ sách</td>
    <td class="tg-c3ow">User</td>
    <td class="tg-0pky">Thêm sách mà người dùng sở hữu.</td>
  </tr>
  <tr>
    <td class="tg-c3ow">7</td>
    <td class="tg-c3ow">Mượn sách</td>
    <td class="tg-c3ow">User</td>
    <td class="tg-0pky">Tạo một yêu cầu mượn cuốn sách mà người dùng khác sở hữu.</td>
  </tr>
  <tr>
    <td class="tg-c3ow">8</td>
    <td class="tg-c3ow">Xem thông tin sách</td>
    <td class="tg-c3ow">Guess, User</td>
    <td class="tg-0pky">Xem thông tin chi tiết của một cuốn sách như tác giả, nội dung chính, nhà xuất bản, những người sở hữu, ...</td>
  </tr>
  <tr>
    <td class="tg-c3ow">9</td>
    <td class="tg-c3ow">Nhắn tin </td>
    <td class="tg-c3ow">User</td>
    <td class="tg-0pky">2 người có thể nhắn tin trao đổi về thời gian, địa điểm mượn sách hay chém gió về các cuốn sách hay,...</td>
  </tr>
  <tr>
    <td class="tg-c3ow">10</td>
    <td class="tg-c3ow">Xem thông tin người dùng</td>
    <td class="tg-c3ow">User</td>
    <td class="tg-0pky">Xem thông tin, các bài review, sách hiện có của người khác.</td>
  </tr>
  <tr>
    <td class="tg-c3ow">11</td>
    <td class="tg-c3ow">Tìm kiếm</td>
    <td class="tg-c3ow">User, guess</td>
    <td class="tg-0pky">Tìm kiếm sách, người dùng, tác giả có trên hệ thống.</td>
  </tr>
  <tr>
    <td class="tg-c3ow">12</td>
    <td class="tg-c3ow">Cập nhật trạng thái mượn sách</td>
    <td class="tg-c3ow">User</td>
    <td class="tg-0pky">Khi có người mượn sách, người dùng có thể thay đổi trạng thái mượn. Có các trạng thái như đợi mượn, đã mượn, đã trả. </td>
  </tr>
  <tr>
    <td class="tg-c3ow">13</td>
    <td class="tg-c3ow">Thông báo</td>
    <td class="tg-c3ow">System</td>
    <td class="tg-0pky">Hệ thống sẽ thông báo cho người dùng khi có người mượn sách, đến hạn trả sách,...</td>
  </tr>
</table>







