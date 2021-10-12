# Bài tập nhóm 7 - Corp Vision
Dear mọi người, như thống nhất nhóm 7 chọn đề bài clone trang Corp Vision theo địa chỉ bên dưới:
https://demo.w3layouts.com/demos_new/template_demo/01-04-2021/corpvision-liberty-demo_Free/1954827273/web/index.html?_ga=2.162940031.294405999.1632622921-1478088941.1629376450
>**Thời gian bắt đầu: 01-10, hạn chót hoàn thành: 12-10. Nộp bài: 15-10**

Mọi người đăng ký tài khoản Trello, Join vào bảng này: https://trello.com/invite/b/HYLd3zo6/11909b3dcc1eee70834f08f7635a0889/bootcam-20-b%C3%A0i-t%E1%BA%ADp-nh%C3%B3m-7, kiểm tra và hoàn thành các task trên Trello theo đúng tiến độ dự án nha.

**Up date: 12/10: Thêm trang báo test lỗi, nhấn đây xem nha **👉 [about page](about.md)

**Up date: 12/10: Bảng phân công công việc sẽ nộp và tiến trình các progress**

![progress.png](https://2.pik.vn/20217fd862bd-f19b-495f-b0c8-a22b12aba734.png)

**B1:**

_hạn chót 02/10_
Tòng sẽ làm file HTML + CSS trước up lên GIt.

Anh em lên clone hết về, lập brand tên của mình rồi cần gì pull request vô xong tự apply luôn nhe.

**B2:**

_Hạn chót 02/10_
@Duy phụ trách phần tải ảnh từ web gốc về, xong up lên lại, anh em kéo về rồi bắt đầu làm các phần được chia dưới B3 đây nhe:


**B3:**

## Web tạm thời chia làm 11 phần từ trên xuống dưới và chia các anh em như sau:

_Hạn chót hoàn thành 13/10_

###### Duy làm up ảnh mẫu + phần đầu:
1. Header
2. Banner
3. About Us (kể cả nút Dark Mode)

![Duy.jpg](https://2.pik.vn/2021b4cff978-88f5-4873-a10d-6dc34c2229b1.jpg)

###### Tân làm 4 phần tiếp:

4. Features (phần EVERY DAY BRINGS NEW CHALLENGES...)
5. Our Services
6. Our Galery
7. Progress (bao gồm cả phần company logo)


![Tân Vỹ.jpg](https://2.pik.vn/20219e5dfe6c-a948-469e-849e-b3005627e4d1.jpg)

###### Tòng làm 4 phần còn lại:

8. Testimonical
9. Blogs
10. Subscribe
11. Footer (kèm nút back to top)


![Tòng.jpg](https://2.pik.vn/202183ef5fba-f29a-4991-91ef-8d6026f19c94.jpg)

Anh em làm luôn reponsive phần của mình luôn nhe. 

**Update 06/10 - PHẦN REPONSIVE:

Web mẫu thiết kế reponsive theo kiểu Desktop First với 4 điểm breakpoint như bên dưới, anh em để ý chỗ này để thống nhất nhe.

@media only screen and (max-width: 1440px) {...}

@media only screen and (max-width: 1199px) {...}

@media only screen and (max-width: 991px) {...}

@media only screen and (max-width: 480px) {...}

=> Chú ý phần thay đổi về padding và font-size nha, phần này quan trọng
**B4:**
_Hạn chót 13/10_

Anh em test chéo các phần của nhau:

- Duy test phần của Tòng

- Tòng test phần của Tân

- Tân test phần của Duy

**B5: thống nhất nộp bài**
_Hạn chót 15/10_

## Các thuộc tính chung:

###### Font chủ đạo:

- BlinkMacSystemFont: Dùng trong các thẻ a, button, input, select, label, li, span.
- Jost, sans-serif: Dùng trong thẻ Body, h1-5, p, ...

###### Các màu chủ đạo của đề:
    --primary-color: #009f4d;
    --secondary-color: #213364;
    --font-color: #666;
    --heading-color: #3f3a64;
    
###### Bố cục:
Mỗi phần nếu có canh giữa sẽ bọc trong 1 class chung là ~~.container~~ => anh em sửa thành .cover nha để tránh trùng với class của Bootstrap có {max-width: 960px; margin: 0 auto; padding top+bottom: 48px}

=> Các thuộc tính chung sẽ được khai báo trong đầu file style.css đính kèm, anh em clone hết về rồi làm nha.
    
Dùng thư viện Bootstrap v4.6: https://getbootstrap.com/docs/4.6/components/alerts/

>Tham khảo các class dùng CSS nhanh của thư viện:
>https://xuanthulab.net/cac-tien-ich-css-co-ban-cua-bootstrap.html

Tạm thời vậy trước, có gì sẽ bổ sung sau. Anh em coi cần gì góp ý thêm nha!
