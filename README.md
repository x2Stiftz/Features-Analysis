# 📌 **Features & Analysis**

## 🟢 **1. Features ที่สามารถทำได้ (Implemented or Feasible)**

| Feature | เทคโนโลยีที่ใช้ | Feamework|
|----------|------------|-----------|
| **`อ่านเอกสาร (Document)`** | HTML, CSS, JavaScript (Frontend), PHP/Python (Backend) | Bootstrap |
| **`อัปโหลดรูปภาพสลิป`** | HTML Input File, JavaScript, PHP/Python (File Handling) |
| **`เปิดกล้องและถ่ายภาพสลิป / รองรับการเลือกกล้องที่ใช้`** | WebRTC, MediaDevices API, OpenCV, Javascript, php |
| **`ระบบหลังบ้าน / จัดการผู้ใช้`** | php, mysql |
<!-- | **`scan_qr()`**| เปิดกล้องแล้วอ่าน QR Code ในรูปภาพ | -->


## ⚙️ **ที่ยังทำไม่ได้ (ต้องรอดูว่าขอ api ได้ไหม)**
| Feature | GAP (สิ่งที่ยังขาด) | เทคโนโลยีที่ใช้ | แนวทางปิด GAP |
|-------------|------------|------------|----------------|
| `การสร้าง api/app ให้ผู้พัฒนา/และบุคคลธรรมดามาใช้งาน` | รอการขอ api bank | Node.js (JavaScript/TypeScript), php(Laravel) |
| `ตรวจสอบ Slip อัตโนมัติให้แม่นยำ` | OCR อาจอ่านข้อมูลผิดพลาด | php, Node.js(Javascript/TypeScript) |
| `แจ้งเตือนผ่าน Line/Discord` | Line Notify อาจปิดตัวเร็ว ๆ นี้ | python, node.js | หาทางเลือกอื่น เช่น Telegram Bot หรือ Email Notifications |


---
# เทคโนโลยีที่ต้องศึกษาเพิ่มเติม
`Webhook & API Development` : `Flask/FastAPI, Express.js`
`AI/ML สำหรับ OCR` : `TensorFlow, EasyOCR, OpenCV`
---

📌 **สรุป:** 
- เราสามารถพัฒนาแอพที่อ่านเอกสาร อัปโหลดสลิป ตรวจสอบสลิป และส่ง Webhook ได้แล้ว
- ยังมี GAP ด้านความแม่นยำของ OCR, การเปิดกล้อง Phone Link อัตโนมัติ, และความปลอดภัยของข้อมูล
- ต้องศึกษา AI/ML, WebRTC, และ Security เพื่อลด GAP และทำให้แอพใช้งานได้เต็มประสิทธิภาพ
