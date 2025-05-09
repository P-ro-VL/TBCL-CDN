Đọc lại bài viết trước đó **Tư duy Agile trong phát triển phần mềm** tại [đây](https://tuybutcualinh.vercel.app/posts/tu-duy-agile-trong-phat-trien-phan-mem)

Scrum là một phương pháp Agile, một quy trình phát triển phần mềm vô cùng phổ biến hiện nay. Từ những dự án đơn giản với một nhóm phát triển nhỏ, đến các công ty lớn có uy tín hàng đầu; đều tin dùng Scrum như một khung quản lý dự án hiệu quả.

# 1. Bản chất của Scrum

Trong Scrum, công việc được thực hiện bởi **nhóm** người gọi là một **Scrum Team** thông qua từng phân đoạn lặp liên tiếp nhau được gọi là **Sprint**. Scrum hoạt động dựa trên 03 trụ cột như sau:

- Minh bạch: Mọi thông tin liên quan tới quá trình phát triển phần mềm phải cực kỳ rõ ràng và thông suốt.
- Kiểm tra/Thanh tra: Theo dõi và tiến hành chặt chẽ các hoạt động trong Scrum
- Thích ứng: Các nỗ lực minh bạch và kiểm tra/thanh tra bên trên sẽ hướng tới hành động thích ứng với thay đổi một cách nhanh chóng, hiệu quả

03 trụ cột trên của Scrum được thể hiện rõ nét thông qua các hoạt động diễn ra trong một Sprint.

# 2. Sprint và các hoạt động trong Sprint

Sprint - thường kéo dài từ 2 đến 4 tuần - là khoảng thời gian mà đội ngũ phát triển tập trung phát triển sản phẩm dựa trên một mục tiêu cụ thể nào đó của Sprint. Mỗi Sprint có một mục tiêu khác nhau, gọi là **Sprint Goal**. Nhưng nhìn chung **Sprint Goal** này đều hướng tới hoàn thiện sản phẩm.

Các hoạt động trong Sprint bao gồm: Grooming, Planning, Daily Meeting, Review và Retrospective

## 2.1. Sprint Grooming

Mục tiêu của buổi Grooming là trả lời cho câu hỏi **Là gì?**
Tại buổi Grooming, Product Owner (Quản lý sản phẩm) sẽ giới thiệu đến team các tính năng, vấn đề sẽ được xử lý ở Sprint tiếp theo. Cả team cùng họp bàn để làm rõ các chi tiết về tính năng, vấn đề đó. Lưu ý, không bàn đến giải pháp, chỉ bàn các tính năng, vấn đề đó là gì? Chúng có chứa những gì? Tại sao phải làm chúng?

## 2.2. Spring Planning

Sau buổi Grooming, team tiếp tục họp trong buổi Planning để trả lời cho câu hỏi **Làm như thế nào?**.

Tại đây, team bàn luận để đưa ra giải pháp thực hiện các tính năng, vấn đề đã được nêu ở buổi Grooming. Sau đó, team thực hiện chia nhỏ chúng thành các **Task** và nhỏ hơn nữa là **Subtask**. Đồng thời, từng thành viên (hoặc từng vai trò) trong team sẽ ước lượng khoảng thời gian cần thiết để hoàn thành Task/Subtask đó. Quá trình này gọi là **Estimation**.

Việc tính toán thời gian sẽ được quy đổi sang dạng **Story Point**. Story Point thể hiện độ khó của công việc đó. Story Point càng cao tức là công việc càng phức tạp và càng cần nhiều thời gian; và ngược lại. Tuỳ tổ chức, doanh nghiệp mà việc quy ước Story Point sẽ khác nhau. Để cho đơn giản, người ta thường đặt **1 story point = 2 giờ làm việc** (giả sử một ngày làm 8 tiếng --> 1 ngày = 4 points)[^1].

Estimate thời gian chính là estimate Story Point.

Sau buổi Planning, team chính thức bước vào Sprint và thực hiện các công việc như đã bàn.

## 2.3. Daily Meeting

Mỗi ngay, team dành ra khoảng 15 phút để họp nhanh. Trong buổi này, từng thành viên sẽ báo cáo về việc **hôm qua đã làm được gì và hôm nay sẽ làm gì**. Team trao đổi về các vấn đề xảy ra trong quá trình thực hiện Sprint (nếu có).

## 2.4. Sprint Review

Team cùng nhau review chức năng đã được xây dựng trong Sprint. Đồng thời, team có thể thảo luận về tình hình sản phẩm.

## 2.5. Sprint Retrospective

Cả team họp để đánh giá Sprint Goal (xem Pass hay Fail). Đồng thời, team đánh giá quá trình thực hiện Sprint vừa rồi để rút kinh nghiệm (nếu có).

Thông thường, trong buổi này, team nên chỉ ra:

- Điều đã làm tốt
- Điều cần cải thiện
- Hành động cần thực hiện với từng điều cần cải thiện

Một công cụ hữu ích để thực hiện Retro lại Sprint là [IdeaBoardz](https://ideaboardz.com/).
![IdeaBoardz for retro](https://www.teamretro.com/wp-content/uploads/2023/07/TeamRetro-choose-the-right-retro-for-your-team-IdeaBoardz-1024x643.png)

Một số doanh nghiệp thực hiện gộp buổi Sprint Review và Sprint Retrospective vào làm một để dễ dàng đánh giá, rút kinh nghiệm hơn.

# 3. Thành phần của một Scrum team

Trong một Scrum team, có 3 thành phần chính

- **Product Owner**: Quản lý sản phẩm. Tham gia tích cực vào quá trình phát triển. Quyết định các tính năng của sản phẩm, đánh giá và sắp xếp độ ưu tiên của từng hạng mục, những hạng mục có độ ưu tiên cao thì sẽ được đưa vào phát triển trước, những hạng mục có độ ưu tiên thấp hơn thì sẽ được phát triển sau.
- **Scrum Master**: Người đảm bảo cho việc vận hành quy trình Scrum của team được liên tục, mượt mà, trơn tru
- **Nhóm phát triển**: Đội ngũ trực tiếp làm ra sản phẩm

[^1]: Bản chất của Story Point trong Scrum không phải quy đổi ra thành giờ, nhưng ta thường làm thế cho đơn giản.
