# 🧸 Youngtoy Webshop

Youngtoy Webshop คือเว็บแอปร้านค้าออนไลน์ (Webshop) สำหรับแสดงสินค้า จัดการตะกร้าสินค้า และทำรายการสั่งซื้อ เหมาะสำหรับใช้เป็นโปรเจกต์ฝึกทำเว็บหรือระบบร้านค้าออนไลน์ขนาดเล็ก

---

## ✨ Features

- แสดงรายการสินค้า
- ดูรายละเอียดสินค้า
- ระบบตะกร้าสินค้า (Cart)
- ระบบสั่งซื้อสินค้า
- ระบบชำระเงิน
- พิมพ์ใบสั่งซื้อ / ใบเสร็จ
- ใช้งานร่วมกับฐานข้อมูล MySQL

---

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript, Bootstrap 5  
- **Backend:** PHP  
- **Database:** MySQL  
- **Additional:** Node.js / React (บางส่วนของโปรเจกต์)

---

## 📂 Project Structure

Youngtoy_webshop/  
├── admin/  
├── bootstrap-5.3.3-dist/  
├── image/  
├── public/  
├── src/  
├── cart.php  
├── condb.php  
├── menu.php  
├── menu.css  
├── show_product.php  
├── insert_cart.php  
├── order.php  
├── payment.php  
├── insertpayment.php  
├── print_order.php  
├── package.json  
├── .gitignore  
└── README.md  
  
---

## 🚀 Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Thizler/Youngtoy_webshop.git
```
2️⃣ Setup Database
สร้างฐานข้อมูลใน MySQL

Import ตารางฐานข้อมูล (ถ้ามีไฟล์ SQL)

แก้ไขไฟล์ condb.php

```
<?php
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "your_database_name";

$conn = mysqli_connect($servername, $username, $password, $dbname);
if (!$conn) {
    die("Connection failed: " . mysqli_connect_error());
}
?>
```
3️⃣ Run with XAMPP / WAMP / MAMP
ย้ายโฟลเดอร์โปรเจกต์ไปที่ htdocs

เปิด Apache และ MySQL

เข้าเว็บผ่านเบราว์เซอร์

```
http://localhost/Youngtoy_webshop
```
⚛️ Run React (Optional)
หากต้องการรันส่วนที่เป็น React

```bash
npm install
npm start
```
```
http://localhost:3000
```
📄 Pages Overview
show_product.php — หน้าแสดงสินค้า

cart.php — หน้าตะกร้าสินค้า

order.php — หน้าสั่งซื้อสินค้า

payment.php — หน้าชำระเงิน

print_order.php — พิมพ์ใบสั่งซื้อ

💡 Future Improvements
เพิ่มระบบ Login / Register

ระบบจัดการสินค้า (Admin Dashboard)

เชื่อมต่อระบบชำระเงินจริง (Payment Gateway)

ปรับ UI/UX ให้รองรับมือถือมากขึ้น
  
## Authors  
Department of Computer Science, Srinakharinwirot University
- Kunanon Hareutaitam - kunanon.mas@g.swu.ac.th
- Renuka Pollok - renuka.pollok@g.swu.ac.th
- Iladageokping Chua - iladageokping.chua@g.swu.ac.th
- Jinnapat Thongbanguay - jinnapat.thongbanguay@g.swu.ac.th

