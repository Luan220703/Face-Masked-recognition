# Face-Masked-recognition-Easy-Using-Face-Recognition-Library
Face-Masked not training model (Resnet50,VGG16...)

Face-Masked recognition là 1 vấn đề rất khó khăn khi nhận diện đặc biệt là khi đeo khẩu trang rất kín đáo. Chính vì vậy để sử dụng và nhận diện nó dễ dàng hơn thì chúng tôi sẽ sử dụng phương pháp sử dụng thư viện face recognition để nhận diện nó nhanh chóng hơn so với việc train model hoặc dùng các model khác trên github vốn rất phức tạp và mất thời gian. 
 
 
Chúng tôi sử dụng thư viện Face Recognition trong bài toán trên để phân loại khuôn mặt mà không cần sử dụng model hoặc train các model. Đây là 1 phương pháp tạm thời nhận diện trong bài toán này nhưng các giá trị và accuracy nó mang lại khá ổn đối với việc sử dụng ngay lập tức hoặc có thể ứng dụng trong các real time thực tế.

Thực tế thì library face recognition trên được ứng dụng cho face recognition hơn cho face masked nhiều hơn. Tuy nhiên khi đeo khẩu trang 1 phần thì nó vẫn có thể nhận diện 1 phần được. Tuy nhiên hạn chế của nó là khi đeo quá kín thì chắc chắn nó sẽ không thể nhận diện ra được. Vì vậy các model như retina face hay ghostface net sẽ hoạt động tốt hơn đây khá nhiều nhưng hạn chế của nó là phải hiểu biết 1 phần code để sử dụng. Vì vậy đây có thể là phương án tối ưu dành cho các bạn chưa có hiểu biêt vể AI

Cách sử dụng đầu tiên cho code này là chụp hình khuôn mặt ta rồi viết cái tên file.jpg theo tên mình và bỏ vào 1 folder rồi chình path vào trong def encode_face trong file recognition.py trên sau đó là chạy file recognition để real time nhận diện nó.







