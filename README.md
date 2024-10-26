# MOVIES-RECOMMENDER-SYSTEM

## Objective
Dataset is collected from [Kaggle](https://www.kaggle.com/code/ibtesama/getting-started-with-a-movie-recommendation-system/input)
The Full Dataset: Consists of 26,000,000 ratings and 750,000 tag applications applied to 45,000 movies by 270,000 users. Includes tag genome data with 12 million relevance scores across 1,100 tags.
**Bối cảnh**

Những tập tin này chứa thông tin về metadata cho tất cả 45,000 bộ phim được liệt kê trong Bộ dữ liệu Full MovieLens. Bộ dữ liệu này bao gồm các bộ phim được phát hành vào hoặc trước tháng 7 năm 2017. Các điểm dữ liệu bao gồm diễn viên, đoàn làm phim, từ khóa cốt truyện, ngân sách, doanh thu, poster, ngày phát hành, ngôn ngữ, công ty sản xuất, quốc gia, số lượng phiếu bầu TMDB và điểm bình chọn trung bình TMDB.

Bộ dữ liệu này cũng chứa các tập tin chứa 26 triệu đánh giá từ 270,000 người dùng cho tất cả 45,000 bộ phim. Đánh giá được đưa ra trên một thang điểm từ 1-5 và đã được thu thập từ trang web chính thức của GroupLens.

**Nội dung**

Bộ dữ liệu này bao gồm các tập tin sau:

- movies_metadata.csv: Tệp chính chứa thông tin về metadata của 45,000 bộ phim trong Bộ dữ liệu Full MovieLens. Các đặc điểm bao gồm poster, hình nền, ngân sách, doanh thu, ngày phát hành, ngôn ngữ, quốc gia sản xuất và công ty.

- keywords.csv: Chứa các từ khóa cốt truyện cho các bộ phim MovieLens của chúng tôi. Có sẵn dưới dạng một Object JSON được chuỗi hóa.

- credits.csv: Bao gồm thông tin về Diễn viên và Đoàn làm phim cho tất cả các bộ phim của chúng tôi. Có sẵn dưới dạng một Object JSON được chuỗi hóa.

- links.csv: Tệp chứa các ID TMDB và IMDB của tất cả các bộ phim xuất hiện trong Bộ dữ liệu Full MovieLens.

- ratings_small.csv: Tập con của 100,000 đánh giá từ 700 người dùng với 9,000 bộ phim.


## Explore
![image](https://github.com/user-attachments/assets/c4c29870-d5bd-42a2-a233-5310710c06d6)

Dựa trên phân phối thời gian của ngày giờ xem phim, bạn có thể đưa ra những nhận xét hợp lý về thói quen xem phim của người dùng. Dưới đây là một số nhận xét có thể áp dụng:

Khung giờ xem phim: Nếu có một đỉnh lớn tại các giờ tối, có thể người xem thường xem phim vào buổi tối sau khi kết thúc công việc hoặc các hoạt động hàng ngày. Điều này có thể phản ánh thói quen giải trí sau giờ làm việc.

Mùa trong năm: Nếu có sự tăng đột ngột trong lượng xem phim ở cuối năm hoặc mùa hè, có thể đó là thời điểm mà người xem thường có nhiều thời gian rảnh hơn, chẳng hạn như trong kỳ nghỉ lễ hoặc kỳ nghỉ mùa hè.

Ngày trong tuần: Bạn cũng có thể xem xét thói quen xem phim trong các ngày cụ thể của tuần. Có thể có sự gia tăng vào cuối tuần khi mọi người có nhiều thời gian rảnh hơn so với các ngày trong tuần.

## Visualize
