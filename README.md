# Phân tích dữ liệu vật phẩm trò chơi Liên Minh Huyền Thoại
## Mô tả
Project này thu thập dữ liệu về vật phẩm trong trò chơi Liên Minh Huyền Thoại từ API của Riot Games. Sau đó dữ liệu được tiền xử lý và tính toán giá trị của mỗi vật phẩm dựa trên các chỉ số như máu, giáp, năng lượng, ... Cuối cùng, kết quả được lưu dưới dạng các file .csv để dễ dàng trực quan hóa.
## Kết quả
Kết quả được lưu trong 2 file:
- item.csv: Thông tin chi tiết về các vật phẩm
- min_price.csv: Chỉ số cơ sở của từng loại để tính giá trị vật phẩm
## Lưu ý: 
- Giá trị vật phẩm được tính ở đây không phản ánh đầy đủ giá trị của vật phẩm trong thực tế. Nhiều vật phẩm còn có giá trị nội tại khó đo lường chỉ bằng các chỉ số. Vì vậy, kết quả chỉ nên được tham khảo.
- Giá trị vật phẩm có thể khác nhau dựa trên cách tính toán. Ở đây, tôi sử dụng tỉ lệ thấp nhất để tính giá trị của các chỉ số (các vật phẩm cơ sở sẽ được lưu trong min_price.csv).


Hy vọng project này sẽ hữu ích cho những ai quan tâm đến dữ liệu của game Liên Minh Huyền Thoại!
