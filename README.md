# Figure World – เว็บไซต์ร้านขายฟิกเกอร์

เว็บไซต์ตัวอย่างสำหรับธุรกิจร้านขายฟิกเกอร์  
พัฒนาโดยใช้ **HTML + CSS พื้นฐาน**  
เหมาะสำหรับการฝึกสร้างเว็บไซต์แบบหลายหน้า (Multi-page Website)

------------------------------------------------------------

## โครงสร้างไฟล์โปรเจกต์ (File Structure)

my-business-web/
├── index.html          # หน้าแรก
├── about.html          # หน้าเกี่ยวกับบริษัท
├── services.html       # หน้าบริการ
├── contact.html        # หน้าติดต่อ
├── css/
│   └── styles.css      # ไฟล์ CSS หลัก
├── images/
│   ├── logo.png        # โลโก้เว็บไซต์
│   ├── hero-bg.jpg     # รูปพื้นหลัง Hero section
│   ├── 1.jpg           # รูปทีมงาน
│   ├── 2.jpg           # รูปทีมงาน
│   ├── 3.jpg           # รูปทีมงาน
└── README.md

------------------------------------------------------------

## ลิงก์เข้าไปในแต่ละหน้าเว็บไซต์

> (เปิดผ่าน Live Server หรือ Web Server)

- หน้าแรก (Home):  
  http://127.0.0.1:5500/index.html

- เกี่ยวกับเรา (About):  
  http://127.0.0.1:5500/about.html

- บริการ (Services):  
  http://127.0.0.1:5500/services.html

- ติดต่อ (Contact):  
  http://127.0.0.1:5500/contact.html

------------------------------------------------------------

## รูปหน้าจอเว็บไซต์ (Screenshots)

> รูปทั้งหมดเก็บไว้ในโฟลเดอร์ `images/`

### หน้าแรก (Index)
![Home](images/screenshot-home.png)

### หน้าเกี่ยวกับ (About)
![About](images/1.jpg)  
![About](images/2.jpg)  
![About](images/3.jpg)

### หน้าบริการ (Services)
![Services](images/screenshot-services.png)

### หน้าติดต่อ (Contact)
![Contact](images/screenshot-contact.png)

------------------------------------------------------------

## รายละเอียดเนื้อหาแต่ละหน้าเว็บ

### 1. index.html (หน้าแรก)
- Header แสดงชื่อบริษัทและโลโก้
- Navigation menu เชื่อมไปยังทุกหน้า
- Hero section พร้อมรูปพื้นหลัง (hero-bg.jpg)
- แสดงบริการหลักของร้าน
- Footer แสดงลิขสิทธิ์เว็บไซต์

### 2. about.html (เกี่ยวกับเรา)
- เรื่องราวและที่มาของบริษัท
- แสดงทีมงานโดยใช้ `<figure>` และ `<figcaption>`
- Vision / Mission ของบริษัท
- ลิงก์หรือปุ่มกลับไปหน้าแรก

### 3. services.html (บริการ)
- แสดงรายการบริการของร้าน
- ใช้ `<section>` แยกแต่ละบริการ
- ตารางเปรียบเทียบแพ็กเกจบริการ

### 4. contact.html (ติดต่อ)
- แบบฟอร์มติดต่อ (Contact Form)
- ที่อยู่บริษัท
- แผนที่ Google Maps (iframe)

------------------------------------------------------------

© 2025 Figure World
