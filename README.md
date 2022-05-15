# Optimization_And_Application_DS106
THUẬT TOÁN TỐI ƯU

- Chọn trình tối ưu hóa được coi là một trong những quyết định thiết
kế quan trọng nhất trong học sâu và nó không phải là một việc dễ
dàng. Các tài liệu đang phát triển hiện nay liệt kê hàng trăm phương
pháp tối ưu hóa. Trong bài báo cáo này, chúng tôi đề xuất ra 3 trong
số các thuật toán tối ưu mới trong kết quả của bài báo cáo "Descending through a Crowded Valley - Benchmarking Deep Learning
Optimizers". Chúng tôi sẽ tìm hiểu lý thuyết và cách hoạt động của
3 thuật toán: **SAM (SHARPNESS-AWARE MINIMIZATION FOR
EFFICIENTLYIMPROVING GENERALIZATION)[1], ADAMP[2]
(Slowing Down the Slowdown for Momentum Optimizers on Scaleinvariant Weights), EXPECTIGRAD[3]( Fast Stochastic Optimization
with Robust Convergence Properties)**. Từ đó, chúng tôi sẽ tiến hành
sử dụng bộ dữ liệu MNIST( Nhận dạng chữ viết tay)[4] kết hợp với
mạng tích chập(CNN) của Deeplearning để tiến hành thực nghiệm,
sau đó so sánh, đánh giá kết quả. Từ đó đưa ra nhận xét, so sánh
hiệu quả của các thuật toán tối ưu với các trường hợp khác nhau
