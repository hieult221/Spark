# lời mở đầu
Khung xử lý dữ liệu của spark được xây dựng để chứng minh bằng cách sử dụng lại dữ liệu qua lặp lại, cung cấp giá trị mà Hadoop MapReduce hoạt động kém.
spark được phát triển để trở thành một khung xử lý dữ liệu
spark là khung dữ liệu dựa trên JVM, nó hoạt động trên các ứng dụng JVM.
Ngôn ngữ lập trình của spark là Scala, python, java và R.
Việc khai thác dữ liệu Spark cơ bản là dữ liêu phân phối có khả năng phục hồi (RDD) dựa trên tất cả các thư viện khác được xây dựng.Mô hình lập trình Spark dựa trên RDD là mức thấp nhất mà các nhà phát triển có thể xây dựng các ứng dụng xử lý dữ liệu.
Thư viện Spark SQL trên Spark Core, với DataFrame abstraction của nó, được xây dựng để đáp ứng nhu cầu của rất nhiều người phát triển rất quen thuộc với SQL phổ biến.
Bằng cách sử dụng R API cho Spark, việc xử lý dữ liệu có thể được thực hiện song song trên Hadoop hoặc Mesos, phát triển vượt xa giới hạn của bộ nhớ cư trú của máy chủ.
Thư viện Spark Streaming, được xây dựng trên Spark Core, thực hiện chính xác như nhau.
Dữ liệu ở trạng thái không sử dụng và dữ liệu đang truyền được đưa vào thuật toán học máy để tạo mô hình dữ liệu và sử dụng chúng để cung cấp câu trả lời cho các câu hỏi. Spark không có bất kỳ hạn chế nào và do đó thư viện học máy Spark MLlib, được xây dựng trên Spark Core và Spark DataFrames.
Đồ thị là một cấu trúc dữ liệu hữu ích được sử dụng rất nhiều trong một số trường hợp sử dụng đặc biệt. Các thuật toán được sử dụng để xử lý dữ liệu trong cấu trúc dữ liệu đồ thị đòi hỏi tính toán cao.
Thư viện Spark GraphX, được xây dựng trên Spark, đã lấp đầy khoảng cách này để xử lý dữ liệu và xử lý đồ thị như các hoạt động nối lưới.
# What is this book cover
Chương 1, Spark Fundamentals, thảo luận về các nguyên tắc cơ bản của Spark như là một khuôn khổ với các API và các thư viện đi cùng với nó, cùng với toàn bộ hệ sinh thái xử lý dữ liệu mà Spark đang tương tác.
Chương 2, Mô hình Lập trình Spark, thảo luận về mô hình lập trình thống nhất, dựa trên các nguyên lý của phương pháp lập trình chức năng, được sử dụng trong Spark, và bao gồm các nguyên tắc cơ bản của các bộ dữ liệu phân tán khả năng phục hồi (RDD), các phép biến đổi Spark và các hành động Spark.
Lời nói đầu
Chương 3, Spark SQL, thảo luận về Spark SQL, một trong những thư viện Spark mạnh mẽ nhất được sử dụng để thao tác dữ liệu bằng cách sử dụng các cấu trúc SQL phổ biến cùng với Spark DataFrame API và cách thức hoạt động với các chương trình Spark. Chương này cũng thảo luận cách Spark SQL được sử dụng để truy cập dữ liệu từ các nguồn dữ liệu khác nhau, cho phép thống nhất các nguồn dữ liệu khác nhau để xử lý dữ liệu.
Chương 4, Lập trình Spark với R, thảo luận về SparkR hoặc R trên Spark, đó là R API cho Spark; điều này cho phép người dùng R sử dụng khả năng xử lý dữ liệu của Spark bằng cách sử dụng khung hình dữ liệu quen thuộc của họ. Nó tạo ra một nền tảng rất tốt cho người sử dụng R để làm quen với hệ sinh thái xử lý dữ liệu Spark.
 Chương 5, Spark Phân tích dữ liệu với Python, thảo luận về việc sử dụng Spark để xử lý dữ liệu và Python để làm phân tích dữ liệu, sử dụng rất nhiều các biểu đồ và các thư viện vẽ sẵn cho Python. Chương này thảo luận kết hợp hai hoạt động liên quan với nhau như là một ứng dụng Spark với Python như là ngôn ngữ lập trình được lựa chọn.
 Chương 6, Spark Stream Processing, thảo luận Spark Streaming, một trong những thư viện Spark mạnh mẽ nhất nắm bắt và xử lý dữ liệu được nhập vào như là một luồng. Kafka làm môi giới thông báo phân tán và một ứng dụng Spark Streaming như là người tiêu dùng cũng được thảo luận.
 Chương 7, Spark Machine Learning, thảo luận về Spark MLlib, một trong những thư viện Spark mạnh mẽ nhất được sử dụng để phát triển các ứng dụng học máy ở mức giới thiệu.
Chương 8, Spark Graph Processing, thảo luận về Spark GraphX, một trong những thư viện Spark mạnh mẽ nhất để xử lý các cấu trúc dữ liệu đồ hoạ và có nhiều thuật toán để xử lý dữ liệu trong các đồ thị. Chương này bao gồm các vấn đề cơ bản của GraphX ​​và một số trường hợp sử dụng được thực hiện bằng cách sử dụng các thuật toán được cung cấp bởi GraphX.
Chương 9, Thiết kế Spark Applications, thảo luận về việc thiết kế và phát triển ứng dụng xử lý dữ liệu Spark, bao gồm các tính năng khác nhau của Spark đã được đề cập trong các chương trước của cuốn sách này.
