เปลี่ยน Favicon
พื้นฐาน
คุณคงไม่อยากให้โลโก้ของ Symfony โชว์อยู่บนไอค่อนของ browser เวลาที่มีคนเข้าชมเว็บไซต์คุณ นั่นเป็นเหตุผลว่าทำไมคุณต้องแก้ไข favicon เสียใหม่ให้เป็นไอค่อนของคุณเอง

แค่ทำการทับไฟล์เดิมที่มีอยู่คือ `web/favicon.ico`.

สำหรับสร้าง favicon ใหม่คุณสามารถใช้เครื่องมือเหล่านี้ช่วย:

* เครื่องมือสร้างไอค่อนออนไลน์ [favicon.cc](http://www.favicon.cc) สำหรับสร้างไฟล์ `.ico`
* หรือจะใช้ไฟล์ PNG เป็นไอค่อนก็ได้ แต่นั่นแปลว่าคุณต้องแก้ไขแท็ก `link` ใน HTML เป็น: `<link rel="icon" type="image/png" href="yourFavIcon.png">`
