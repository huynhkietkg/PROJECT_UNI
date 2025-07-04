# Những gì học được:
1.Gán nhãn phân vùng ảnh:

-Hiểu cách gán nhãn cho các đối tượng trong ảnh để phân biệt chúng, đảm bảo các pixel thuộc cùng một đối tượng có giá trị giống nhau.

-Nắm được ý nghĩa của việc phân vùng ảnh theo vùng (Region) để tách biệt các đối tượng.

2.Dò tìm cạnh và đặc trưng hình học:

-Học cách phát hiện cạnh trong ảnh, bao gồm cả cạnh theo chiều dọc và sử dụng bộ lọc Sobel với kernel.

-Hiểu cách xác định góc của đối tượng.

-Sử dụng Hough Transform để dò tìm.

3.So sánh và khớp ảnh (Image Matching):

-Nắm được quy trình tìm điểm tương đồng giữa hai ảnh.

-Sử dụng Harris Corner Detector để xác định các điểm đặc trưng (keypoints).

-Phân tích vùng hình chữ nhật xung quanh các điểm đặc trưng.

-So sánh độ tương đồng giữa hai ảnh dựa trên các đặc trưng này.
4.Thay đổi ảnh:
-Học cách chỉnh sửa hoặc thay đổi nội dung ảnh dựa trên các kỹ thuật xử lý ảnh đã học.
# Kỹ thuật áp dụng:
Gán nhãn ảnh:Connected Component Labeling

Phân vùng ảnh theo Region:Region-based Segmentation

Dò tìm cạnh:Sobel Filter,dò tìm cạnh theo chiều dọc có thể sử dụng kernel Sobel riêng cho hướng dọc.

Xác định góc của đối tượng:Sử dụng các kỹ thuật như tính gradient hoặc phân tích đặc trưng hình học để xác định hướng của đối tượng.
