#  Movie Revenue Analysis 2025

##  Mục tiêu
Phân tích dữ liệu doanh thu phim trong năm 2025 theo:
- Từng tháng (month-by-month performance)
- Mức độ viral của từng phim dựa trên doanh thu
- Ảnh hưởng của từng nhà phát hành (Distributor) đến tổng thị trường

##  Câu hỏi phân tích chính
1. Tháng nào có doanh thu cao nhất và thấp nhất? Tại sao?
2. Nhà phát hành nào chiếm thị phần lớn nhất?
3. Số lượng rạp chiếu (Theaters) có ảnh hưởng đến doanh thu không?
4. Phim viral xuất hiện vào tháng nào? Có trùng với thời điểm cao điểm doanh thu?

## Công cụ sử dụng
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

##  Kết quả nổi bật
- Tháng 8 là tháng có doanh thu cao nhất (nhờ Galaxy Studio)
- CJ Entertainment có số rạp lớn nhưng doanh thu không cao → hiệu suất thấp
- Số lượng rạp nhiều không đảm bảo doanh thu nếu nhu cầu thị trường thấp
## Hướng giải quyết

- Galaxy Studio: Tối ưu thời gian phát hành phim để tận dụng tháng cao điểm (ví dụ tháng 8) nhằm tăng lợi nhuận và viral marketing.
- CJ Entertainment: Giảm số lượng rạp chiếu cho các phim dự báo doanh thu thấp, đồng thời triển khai khuyến mãi (học sinh – sinh viên, voucher) để thu hút khán giả.
- Cuối năm (tháng 11–12): Thường ít phim, nên tăng các chương trình khuyến mãi để duy trì doanh thu.
- Số rạp chiếu không phải lúc nào cũng tăng doanh thu → cần dựa vào nhu cầu thực tế và độ nổi bật của phim.
### Files
- `movie_analysis.ipynb` — notebook phân tích
- `data.csv` — dữ liệu gốc

