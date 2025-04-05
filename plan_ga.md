# Vấn đề
- Dự án liên miên, **dự án mới nhưng chúng ta toàn dùng công nghệ đã từng làm** => Lối mòn ko phát triển được gì nhiều, code dự án mới với cách code cũ rồi cũng chán
- Công nghệ mới phụ thuộc vào đội nghiên cứu + cũng ko phải lúc nào cũng ra cái mới để mình học được
- Xu thế bên ngoài rất phát triển, dù làm product hay outsource thì việc biết thêm nhiều công nghệ, hay biết các partern tất nhiên là tốt hơn.
- Khi tự nghiên cứu, mọi người chắc chắn đôi lúc sẽ ko biết sâu đến đâu là đủ, chứ chạy đc sample code thôi thì ez. 
- *Ví dụ như kafka, mình dùng nhưng chưa làm chủ được hoàn toàn. Các cơ chế partition, các thông số setup là cũng dùng lại của bdrd chứ mình cũng ko phải nghiên cứu gì. Ngoài ra việc failover với kafka cũng tương đối phức tạp và mình mới hiểu và chưa làm chủ được nó hoàn toàn, nên có nhiều rủi ro tiềm ẩn.*

---
# Ý tưởng: Team nghiên cứu công nghệ
- AE trong team mỗi năm làm 1-2 chủ đề công nghệ, hoặc nhiều hơn nếu cần
- Yêu cầu nghiên cứu sâu và chi tiết làm chủ công nghệ đó,
- VD 1 chủ đề công nghệ mới sẽ phải có 1 số mục.
  - Cách setup, nuget ...
  - Cách nó hoạt động thế nào => Hay cơ chế của nó
  - Sample Code đơn giản
  - Nó có ưu điểm gì với các cái khác cùng loại (vd rabit vs kafka, api vs grpc, sql vs nosql...) 
  - => Từ đó nên dùng trong trường hợp nào thì dùng cái nào
  - Có thể áp dụng thử vào luồng nghiệp vụ nào của hệ thống
  - ... Nhiều tiêu chí nữa mình sẽ quy định rõ ràng sau
- Tất nhiên phải có **Output** sau khi nghiên cứu:
  - Cứng: docs là bắt buộc, ở dạng gì cũng đc nhưng phải đầy đủ, markdown thì càng ngon
  - Mềm: Có thể mở buổi chia sẻ nếu cần
- 👉 **Phạm vi** : 
  - Chủ đề: Công nghệ mới, hoặc partern, clean code, cách quản lý code, áp dụng API vào coding... 
  - Con người: Trong các buổi chia sẻ, GA thì bắt buộc, FRE thì cứ mời, ai thích thì tham gia, ko ép.
- (Tất nhiên là với 1 sốt tips code thì ko cần thuyết trình rườm rà, docs nhanh hoặc gì đó, rồi lưu lại vào 1 folder chung là được)
---
# AE được gì

- Tất nhiên là bản thân sẽ phát triển và có giá trị hơn, ko phải sợ ko làm đây thì khó xin chỗ khác
- Sếp đánh giá cao hơn, thông qua 1 số cách:
  - Có các tài liệu docs giới thiệu đến mọi người
  - Có các buổi chia sẻ công nghệ, mời sếp và các ace FRE tham gia xem, đánh giá...
  - *(Thề là nếu ae 1 năm làm 1, 2 chủ đề tử tế chắc chắn sếp éo tăng lương thì chắc cũng thấy ngại :))*
- Ngoài ra, dạy lại người khác luôn là cách làm mình hiểu sâu nhất.
- Cũng giúp ae biết cách khi học công nghệ mới, lưu trữ, ghi chép tài liệu thế nào, cũng có thể làm đẹp github của mình.
- Bớt chán
---
# Triển khai
- Đầu tiên là ae có đồng ý không đã, ok thì tính tiếp
- Nếu ok thì trc mắt Long với Dũng chủ động làm admin của team
- Thời gian: Trước mắt đang bận sắp xong với KRX, sau KRX mình sẽ triển khai, chủ đề thì có thể chọn ngay từ bây giờ.

  
