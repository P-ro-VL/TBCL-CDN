Đọc lại bài viết trước đó **Mở đầu: Phát triển phần mềm 101** tại [đây](https://tuybutcualinh.vercel.app/posts/mo-djau-phat-trien-phan-mem-101)

# 1. Tư duy cố định
Không phải lúc nào trong quá trình phát triển phần mềm mọi thứ đều diễn ra như ta đã dự tính. Nhìn chung, như bao công việc khác, những vấn đề phát sinh là chuyện cơm bữa với phát triển sản phẩm phần mềm. 

Một người anh của tôi từng chia sẻ rằng: "Giữ nguyên một góc nhìn, một phương hướng, một cách nghĩ về phần mềm; thậm chí là phần mềm do chính mình tạo ra, là cách nhanh nhất để giết chết phần mềm đó".

Khi bắt đầu phát triển phần mềm, bạn thường nghĩ về những tính năng, những hướng phát triển và những cách khai thác tiềm năng trong tương lai của nó. Bạn mong muốn rằng tất cả những điều bạn vạch ra đều sẽ được thực hiện và đáp ứng được mong đợi của bạn. Thực tế, ai cũng mong muốn như vậy: Mong muốn mọi việc sẽ diễn ra suôn sẻ như những gì đã dự định, đã lên kế hoạch. Nhưng, nếu như bỗng một ngày, có một yêu cầu thay đổi về tính năng, yêu cầu thêm mới một quy trình hay thậm chí là cố gắng khắc phục một vấn đề nhưng lại ảnh hưởng đến cả hệ thống; bạn sẽ làm thế nào? Cố gắng chữa cháy và quay về với định hướng ban đầu, hay chuyển đổi sang một định hướng mới?

Cả hai đều là những điều khó lựa chọn.

Ngay cả khi bạn cố gắng giữ định hướng, góc nhìn, suy nghĩ ban đầu và chấp nhận rủi ro sẽ xảy ra; tại sao không thử chuyển sang một cách nghĩ mới trong khi vẫn phải đối diện với rủi ro?

# 2. Đằng nào cũng rủi ro, thôi thì ... nghĩ khác !

> _Agile thực chất là một **triết lý** hay một **khung tư duy** để nhanh chóng thích ứng và phản hồi với thay đổi, từ đó đạt được thành công trong một môi trường liên tục biến động và không chắc chắn._ - hocvienagile.com

Tôi phải nhấn mạnh vào hai chữ **triết lý** và **khung tư duy**. Nhiều người vẫn lầm tưởng rằng, Agile là một phương pháp, một quy trình, một cách thức tổ chức vận hành; bởi người ta thường hay đính kèm Agile cùng với quy trình phát triển Scrum (sẽ được nhắc tới ở bài viết sau). Xin đính chính lại, Agile là **mindset**, là **cách nghĩ, cách nhìn nhận, tư duy**. 

Trước đây, người ta thường phát triển phần mềm theo mô hình thác nước (hay mô hình Waterfall). Cụ thể như sau:

![Waterfall](https://1office.vn/wp-content/uploads/2025/02/Mo-hinh-Waterfall-la-gi-Cac-giai-doan-cot-loi-trong-mo-hinh-Waterfall.png)

Hạn chế của mô hình Waterfall này là nó hạn chế việc đáp ứng kịp thời với các thay đổi. Hay nếu có sai sót trong yêu cầu đầu vào thì sẽ kéo theo toàn bộ các giai đoạn tiếp theo bị sai sót. Thời gian hoàn thành dự án cũng thường kéo dài do phải chờ đợi từng giai đoạn. Nguồn lực con người cũng không được tận dụng tối ưu, vì phải chờ giai đoạn trước hoàn thành.

Thực ra, hiện tại vẫn còn một số doanh nghiệp sử dụng mô hình này, do quy trình của họ đã gắn chặt với Waterfall, để thay đổi thì cần thời gian; hoặc do chi phí quá lớn nên họ không thể thay đổi.

Ngược lại, với Agile, nhà phát triển lập kế hoạch thích ứng, phát triển tăng dần, chuyển giao sớm và cải tiến liên tục nhằm thích ứng nhanh với sự thay đổi. Do vậy, Agile linh hoạt hơn, tiện lợi hơn và đáp ứng nhu cầu thực tiễn của thời đại mới tốt hơn. 

Báo cáo CHAOS của Standish Group năm 2015 đã cho thấy các dự án Agile so với các dự án truyền thống (Waterfall) có tỷ lệ thành công cao hơn 3 lần. 

|Quy mô dự án|	Phương pháp	|Thành công|	Thử thách	|Thất bại|
|---|---|---|---|---|
|Tổng kết|	Agile |	39% |               	52% |	9%|
||Waterfall| 	11%|                	60%|	29%|
|Lớn|	Agile| 	18%|	59%| 	23%|
||Waterfall| 	3%| 	55% |	42%|
|Vừa| 	Agile| 	27% | 	62% |	11%|
||Waterfall |	7%|	68% |	25%|
|Nhỏ|	Agile| 	58% |	38%  |	4%|
||Waterfall |	44%  | 	45%  | 	11%|

# 3. Tuyên ngôn Agile
Gồm 05 điều sau:
- Con người và sự tương tác hơn là quy trình và công cụ
- Phần mềm chạy tốt hơn là tài liệu đầy đủ
- Cộng tác với khách hàng hơn là đàm phán hợp đồng _(đây có thể coi là một góc nhìn khác của việc áp dụng customer-centric hơn là product-centric)_
- Phản hồi với sự thay đổi hơn là bám theo kế hoạch
- Đánh giá cao giá trị của vế trái hơn vế phải (ở 04 điều bên trên)

Nhìn chung, dễ dàng nhận thấy rằng, Agile ưu tiên
- Con người và sự tương tác của con người trong quá trình phát triển phần mềm
- Phần mềm cần chạy tốt
- Làm việc song hành cùng khách hàng để đưa ra sản phẩm tốt nhất
- Phản ứng nhanh với các thay đổi trong quá trình phát triển sản phẩm

# 4. 12 nguyên tắc của Agile
![12 principals of Agile](https://hocvienagile.com/wp-content/uploads/2023/12/noi-dung-12-nguyen-ly-agile.jpg)

Trong các bài sau, ta sẽ cùng tìm hiểu về một số phương pháp áp dụng tư duy Agile trong phát triển phần mềm.