# Forex-Rates-Prediction-Using-RNN
Ứng dụng các mô hình mạng thần kinh hồi quy RNN để dự đoán tỷ giá ngoại hối

Bộ dữ liệu gồm những mã ký tự (mã tiền tệ) để định nghĩa cho tên của tiền tệ do Tổ chức Tiêu chuẩn hóa quốc tế (ISO) ban hành. Danh sách mã ISO 4217 là chuẩn hiện hành trong niêm yết ngân hàng và kinh doanh trên toàn thế giới để xác định những loại tiền tệ khác nhau. Đây là những tỷ giá hối đoái và ký hiệu được giao dịch nhiều nhất trên các sàn giao dịch ngoại hối, được cung cấp bởi thư viện yfinance. 

Việc sử dụng mạng thần kinh hồi quy (Recurrent Neural Network) dự đoán những giá trị này giúp những nhà đầu tư nhỏ lẻ đưa ra quyết định giao dịch nhằm tối đa hóa lợi nhuận hoặc giảm thiểu rủi ro. Doanh nghiệp hoạt động xuất nhập khẩu có thể dựa vào dự đoán tỷ giá để bảo vệ mình trước biến động tiền tệ, giúp quản lý chi phí và lợi nhuận. Ngoài ra, việc dự đoán giá dầu và vàng giúp các công ty năng lượng, sản xuất và tổ chức tài chính lập kế hoạch chi tiêu và đầu tư dài hạn. Các tổ chức tài chính và ngân hàng trung ương cũng sử dụng thông tin này để đưa ra các chính sách tiền tệ phù hợp với tình hình kinh tế. Đồng thời, nó hỗ trợ các nhà phân tích hiểu rõ hơn về xu hướng kinh tế toàn cầu và ảnh hưởng của các sự kiện địa chính trị đối với thị trường.

5 mã ngoại hối được dự đoán là USDJPY, GBPUSD, EURUSD, USOIL, XAUUSD.
3 mô hình học máy được tác giả sử dụng là Simple RNN, LSTM và ARIMA. 
5 phương pháp đánh giá hiệu quả mô hình học máy được sử dụng là MAE, MSE, R-Squared, MAPE.
