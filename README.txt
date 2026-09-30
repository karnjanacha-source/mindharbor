MindHarbor Interactive Offline Demo
===================================
เปิด index.html ใน Chrome / Edge / Firefox ได้โดยตรง (ไม่ต้องติดตั้งเซิร์ฟเวอร์)

ระบบทดลองที่ทำงานได้:
- แบบประเมิน 5 ข้อ พร้อมบันทึกผลจำลอง (ไม่ใช่เครื่องมือวินิจฉัย)
- เลือกผู้เชี่ยวชาญ หัวข้อ วัน เวลา และยืนยันการจองจำลอง พร้อมป้องกันเวลาซ้ำในเบราว์เซอร์เดียวกัน
- ดูและยกเลิกการจอง
- บันทึกแบบฟอร์มติดต่อจำลองและแพ็กเกจที่สนใจ
- รายงาน HR สาธิต และดาวน์โหลด CSV
- Demo Workspace: ดูข้อมูล ส่งออก JSON ลบข้อมูลในเบราว์เซอร์
- โปรไฟล์ผู้เชี่ยวชาญ รีวิว และช่องทางติดต่อเป็นข้อมูลสมมติทั้งหมด

ข้อจำกัดสำคัญ:
- เก็บข้อมูลใน localStorage ของเบราว์เซอร์เครื่องเดียว ไม่ซิงก์ข้ามอุปกรณ์
- ไม่มีเซิร์ฟเวอร์ ยืนยันตัวตน การส่งอีเมล การชำระเงิน การนัดหมายผู้เชี่ยวชาญจริง
- ไม่ใช่ระบบ Zero-Knowledge หรือระบบพร้อมใช้กับข้อมูลสุขภาพจริง
- ห้ามกรอกข้อมูลส่วนบุคคลหรือข้อมูลสุขภาพจริงในระบบสาธิต
- ตัวเลข HR ที่อยู่ในภาพ/กราฟเดิมเป็นข้อมูลสมมติ ส่วน Demo Workspace แสดงจำนวนที่เกิดจากการทดลอง
- ภาพพื้นหลังบางส่วนใช้ Unsplash และฟอนต์/ไอคอนจาก CDN ต้องใช้อินเทอร์เน็ตเพื่อแสดงครบ

ไฟล์หลัก: index.html, demo.js, demo.css, assets/

BOOKING UPGRADE:
- Choose one of four fictional experts, date (next 60 days), and available time based on sample weekly schedules.
- Book, block duplicate times on this browser, view/cancel bookings, export .ics calendar event.
- Booking data is localStorage only; other devices cannot see it. No real experts or appointments.
- Production needs verified licensed professionals, server-side database, authentication, shared atomic slot locking, notifications, consent and PDPA safeguards.
