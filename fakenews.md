# Fakenews 

# Nội dung chính:
* [Giới thiệu về Fake news](#Giới-thiệu-về-Fake-news)
* [Công nghệ sử dụng](#Công-nghệ-sử-dụng)
## Giới thiệu về Fake news.
```
+ Fakenews được chúng tôi xây dựng nhằm giúp người đọc có thể tiếp cận
những nguồn thông tin chính xác và đã xác thực từ các nguồn chính thống
cũng như giúp người đọc có thể tránh xa khỏi những tin giả gây ảnh hưởng xấu tới xã hội.

+ Fakenews sửa dụng công nghệ Flutter để xây dựng app đa nền tảng vừa có thể sử dụng trên Android và IOS
một cách linh hoạt và dễ dàng. Về phần database chúng tôi sử dụng Entity framework và SQL server để xây dựng hệ thống database.
Phần sử lý thông tin chúng tôi sử dụng ASP .net core 6 và mô hình MVC.
Chúng tôi cũng có xây dựng một trang web admin để admin có thể quản lý những thông tin trên đó.
Hiện tại ứng dụng đã được deploy lên windows server 2019 và sắp tới sẽ triển khai lên google play.
```

## Công nghệ sử dụng
```
+ Database:
    - SQL server.
    - Entity framework.
+ Server:
    - ASP .net core.
    - MVC.
+ Mobile app:
    - flutter.
+ Web admin:
    - ReactJS.
```

## Hướng dẫn sử dụng
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic1.png" width="200" height="400" />
</p>
<p align="center">
    
   + Giao diện khi khởi động ứng dụng.
        - Khi đăng nhập vào sẽ thấy icon của hệ thống và xin chào.

</p>

___
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic2.png" width="200" height="400" />
</p>
<p align="center">
    
   + Người dùng có thể đăng nhập bằng tài khoản đã đăng ký, tài khoản facebook và google.
        - Khi đăng nhập lần đầu, người phải đăng ký thông tin, thông tin sẽ được lưu lại.
        - Khi đăng nhập bằng tài khoản google, facebook mà trước đó đã có tài khoản sẽ không cần nhập thông tin lại.
        - Khi thoát ứng dụng ra màn hình chính sẽ duy trì đăng nhập, không cần đăng nhập lại.
        - Có thể tùy chỉnh ngôn ngữ hệ thống và ngôn ngữ tin tức ở phía trên bên phải.
        - Chọn đồng ý điều khoản dịch vụ để sử dụng ứng dụng.
</p>

___
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic3.png" width="200" height="400" />
</p>
<p align="center">
    
   + Giao diện đổi ngôn ngữ (ngôn ngữ ứng dụng, ngôn ngữ đọc tin tức).
        - Có thể tùy chỉnh ngôn ngữ hệ thống và ngôn ngữ tin tức(tiếng anh, tiếng việt).
        - Mặc định của hệ thống là tiếng anh.
</p>

___
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic4.png" width="200" height="400" />
</p>
<p align="center">
    
   + Giao diện các chủ đề.
        - Có nhiều chủ đề cho người dùng chọn, có thể chọn nhiều chủ đề.
        - Người dùng có thể thấy được các chủ đề theo ngôn ngữ mà họ đã chọn, khi bấm nút “Khám phá” thì vào trang đăng nhập.
        - Lần đầu tiên đăng nhập, người dùng phải chọn ít nhất 4 chủ đề khác nhau.
        - Người dùng cũng có thể tùy chỉnh ngôn ngữ hệ thống ở đây.
</p>

___
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic5.png" width="200" height="400" />
</p>
<p align="center">
    
   + Giao diện đọc trước tin tức khi chưa đăng nhập.
        - Người dùng có thể xem các tin tức mới nhất của hệ thống.
        - Các tin tức người dùng xem khi chưa đăng nhập là các tin mới và hot nhất trong ngày của nhiều chủ đề khác nhau.
</p>

___
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic6.png" width="200" height="400" />
</p>
<p align="center">
    
   + Khi đăng nhập người dùng bắt buộc phải chọn ít nhất 4 chủ đề để có thể đăng nhập và đọc tin tức.
</p>

___
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic7.png" width="200" height="400" />
</p>
<p align="center">
    
   + Giao diện trang chủ
    
        - Khi đăng nhập xong người dùng có thể đọc tin và bình chọn tin tức đó có đáng tin cậy hay không.
        - Người dùng có thể theo dõi các chủ đề yêu thích và xem các story của các tin tức ở đây.
        - Người dùng có thể xem các thông báo ở chuông phía trên bên phải trang chủ.
</p>

___
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic8.png" width="200" height="400" />
</p>
<p align="center">
    
   + Giao diện câu chuyện ( gần giống như story trên facebook, instagram).
        - có thể xem Story của các tin tức nhanh trong 24h.
</p>

___
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic9.png" width="200" height="400" />
</p>
<p align="center">
    
   + Giao diện đọc tin tức
    
        - Người dùng có thể đọc, chọn độ tin cậy của tin tức, chia sẻ tin,…
        - Người dùng có thể bình luận trao đổi với nhau về tin tức đó.
</p>

___
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic10.png" width="200" height="400" />
</p>
<p align="center">
    
   + Giao diện tìm kiếm.
        - Người dùng có thể tìm kiếm theo tên tin tức, nội dung tin tức, desc.
        
</p>

___
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic11.png" width="200" height="400" />
</p>
<p align="center">
    
   + Giao diện tin tức đã được phân loại.
        - Các tin tức đã được kiểm duyệt sẽ được hiển thị ở đây.
        - Các tin tức được xác nhận là chính xác sẽ hiện bên ô Tin Thật.
        - Các tin tức được xác nhận là sai sự thật sẽ hiện bên ô Tin Giả.
        - Mọi Người có thể đọc thông báo ở đây bằng cách chọn chuông ở gói phải phía trên trang.
</p>

___
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic12.png" width="200" height="400" />
</p>
<p align="center">
    
   + Giao diện đóng góp tin tức.
        - Người dùng có thể đóng góp tin tức lên hệ thống, admin sẽ kiểm duyệt và đăng lên hệ thống nếu tin tức hợp lý.
        - Người dùng có thể tìm các tin tức mà người dùng khác đóng góp ở đây.
        - Ở đây sẽ hiện thông tin số bài viết đã đóng góp của người dùng.
        - Người dùng có thể xem hướng dẫn chi tiết ở ô xem hướng dẫn.
</p>

___
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic13.png" width="200" height="400" />
</p>
<p align="center">
    
   + Giao diện cài đặt, trang cá nhân.
        - Chỉnh sửa thông tin cá nhân của người dùng ở đây.
        - Người dùng có thể tùy chỉnh ngôn ngữ hệ thống và ngôn ngữ tin tức ở đây.
        - Người dùng có thể thay đổi các chủ đề đã theo dõi.
        - Người dùng có thể kết nối các mạng xã hội khác với tài khoản cá nhân.
        - Người dùng có thể xem các thông tin khác về FNF.
        - Người dùng có thể đánh giá chất lượng ứng dụng.
        - Người dùng nếu gặp khó khăn khi sử dụng hệ thống thì có thể sử dụng tính năng giúp đỡ của hệ thống.
</p>

___
### thanks for reading. :)
###### Create by LXThanh
