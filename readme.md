Nhóm học tập : d2l.aivivn.com/intro_vn.html  , machinelearningcoban.com/2017/09/24/fundaml
# Em học pandas
- what DataFrame is ? : trong toán là matrix , trong OOP là table, trong programming là mảng 2 chiều.
- Series là gì : trong toán là vector, trong OOP là column, trong programming là mảng 1 chiều.

## Vector và Các phép toán cơ bản của một vector
- vector là một tập hợp có cùng kiểu dữ liệu, ví dụ  A = [5,2,5,3,6] là một vector
![fgh](https://user-images.githubusercontent.com/86332370/158285632-222ac2f8-7e9a-462f-9fa5-bc60823da267.png)

- vector có thể biểu diễn được 1 điểm trong không gian. Ví dụ, trong không gian 1 chiều [...,-2,-1, 0, 1, 2,...] lấy 1 điểm có tọa độ x0=5 thì ta có vector của điểm x0 là [5]. Trong không gian 2 chiều lấy một điểm có tọa độ (x0,y0)=(3,2) thì vector của điểm đó là [3.2] . Trong không gian ba chiều lấy một điểm có tọa độ (x0,y0,z0)=(1,1,1) thì điểm này có vector là [1,1,1] . Một vector có 4 phần tử [2,5,3,3] biểu diễn một điểm trong không gian 4 chiều ( và đương nhiên rồi, không gian 4 chiều hiện tại chưa đủ hình thức để hình dung ra được)
![t](https://user-images.githubusercontent.com/86332370/158283558-870f24e0-9b54-4cc6-85e1-550d4e08e6a1.png)
- vector có thể biểu diễn được 1 ĐOẠN VECTOR trong không gian với tọa độ ban đầu lấy mặc định là tọa độ gốc của hệ trục tọa độ (ĐOẠN VECTOR : là một đoạn thẳng có hướng , tức là phân biệt được điểm bắt đầu và điểm kết thúc). Ví dụ : cho vector [-5], ĐOẠN VECTOR của nó là tia xuất phát từ gốc tọa độ (0) cà chấm dứt tại tọa độ (-5).
![t](https://user-images.githubusercontent.com/86332370/158283929-b93b877b-d99b-4eb3-b9e9-1e4c1f2c67ac.png)
- PHÉP CÁC PHÉP TOÁN SƠ CẤP GIỮA 2 VECTOR :  
chúng ta có các phép toán sơ cấp cộng/trừ/nhân/chia/mũ  giữa 2 vector (các phép toán nâng cao abs/log/exp/sin/cos/tan đc xây dựng từ các phép cơ bản). chú ý 2 vector muốn thực hiện tính toán với nhau cần có cùng số lượng phần tử. Khi thực hiện các phép toán giữa 2 vector kết quả sẽ ra một vector mới, là kết quả của việc thao tác phép toán như toán cơ bản lên từng phần tử tương ứng giữa 2 vector. Ví dụ A=[1,2,3] B=[2,2,2] ta có A+B sẽ ra C=[3,4,5]
- PHÉP TOÁN GIỮA VECTOR VÀ 1 SỐ :  
Cho vector A và một scalar n, phép tính toán giữa A và n được chuyển về dạng các phép tính toán giữa 2 vector.  
Ví dụ :  cho A=[1.2.3] ,    ta có 2<span>+</span>A <=> [2,2,2]<span>+</span>[1,2,3]
- 
