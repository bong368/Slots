Khe cắm 5 reels & 30 multipayline
===

Slots Skinnable trò chơi sử dụng CreateJS ở phía khách hàng và node.js, express, mongoose, và hộ chiếu ở phía máy chủ.
Bạn có thể nhìn thấy nó trong trạng thái mặc định của nó [ở đây](http://oquistador-slots.herokuapp.com/).

Cài đặt

---

    $ npm install
    $ grunt
    $ node app/app
    
Cấu hình
---

Hầu hết cấu hình có thể được thực hiện trong tệp cấu hình chia sẻ file [app/config/shared.json]( https://github.com/oquistador/Slots/blob/master/app/config/shared.json). Tệp JSON này được hợp nhất vào các tập lệnh phía máy khách và máy chủ thông qua [Grunt](https://github.com/gruntjs/grunt). Tất cả ** trình bày logic ** là trong [app/assets/javascripts/app.coffee](https://github.com/oquistador/Slots/blob/master/app/assets/javascripts/app.coffee) Và tất cả các ** chiến thắng logic tính toán ** là trong [app/spin.js](https://github.com/oquistador/Slots/blob/master/app/spin.js) Nếu bạn cần phải tinh chỉnh bất cứ điều gì.
Vì ứng dụng này sử dụng trình trung gian nút tuyệt vời [passport] (https://github.com/jaredhanson/passport), có * tấn * các chiến lược xác thực khác mà bạn có thể sử dụng.
