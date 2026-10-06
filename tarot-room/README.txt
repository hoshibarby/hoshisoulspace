HoshiSoulSpace — Tarot Room
===========================

เว็บไซต์ Tarot Room แบบ standalone สำหรับใช้งานส่วนตัว ทำงานด้วย HTML, CSS และ JavaScript ไม่มี backend

เริ่มใช้
1. แตกไฟล์ hoshisoulspace-tarot.zip
2. เปิดโฟลเดอร์ Hoshi-Daily-Tarot
3. ดับเบิลคลิก index.html

เผยแพร่ด้วย GitHub Pages
1. สร้าง repository ใหม่บน GitHub
2. อัปโหลด index.html, style.css, script.js, README.txt และโฟลเดอร์ assets ทั้งหมดไว้ที่ root
3. เข้า Settings > Pages
4. เลือก Deploy from a branch, branch main และโฟลเดอร์ /(root) แล้วกด Save
5. รอให้ GitHub Pages แสดงลิงก์เว็บไซต์

ระบบเปิดไพ่
- ไพ่ประจำวัน, One Card, Three Card, ความรัก 5 ใบ, การงาน/การเงิน 5 ใบ, YES or NO, Celtic Cross 10 ใบ, Free Draw 1–78 ใบ และ Custom Spread
- สับไพ่แล้วลำดับสำรับจะเปลี่ยนจริง เลือกไพ่คว่ำให้ครบก่อนยืนยัน จากนั้นเปิดทีละใบ
- การเลือกไพ่ไม่เปิดเผยหน้าไพ่ และไพ่ที่เลือกจะถูกล็อกไม่ให้เลือกซ้ำ
- ผลแสดงตำแหน่ง ไพ่ตั้งตรง/กลับหัว คีย์เวิร์ด ความหมายและคำแนะนำ
- YES/NO แสดงแนวโน้ม เหตุผลและคำแนะนำ ส่วน Celtic Cross มีผัง 10 ตำแหน่งและภาพรวม

สมุดบันทึก
- หลังเปิดครบ บันทึกผลใน Tarot Journal แล้วเปิดดู แก้หัวข้อ แก้โน้ต หรือลบได้
- ไพ่ประจำวันจำไพ่ คำถามและ orientation ด้วย localStorage ตามวันที่ Asia/Bangkok
- ข้อมูลอยู่ในเบราว์เซอร์ของเครื่องนี้ ไม่ซิงก์ข้ามเครื่อง

ภาพไพ่ Rider–Waite–Smith
- รวมภาพสำรับจริงครบ 78 ใบไว้ใน assets/cards/ แยกตาม Major Arcana และชุดไพ่ 4 ชุด
- ภาพโหลดจากไฟล์ในเว็บไซต์ ไม่ hotlink จึงใช้ได้บน GitHub Pages และเมื่อเปิดแบบออฟไลน์
- เครดิต ที่มา และสถานะสิทธิ์ของภาพอยู่ใน assets/cards/ATTRIBUTION.txt

ไฟล์หลัก
- index.html — หน้าเว็บและเมนู
- style.css — ธีม Hoshi และ responsive layout สำหรับมือถือ
- script.js — สำรับ ความหมาย สถานะอ่านไพ่และ localStorage
- assets/cards/ — ภาพหน้าไพ่ทั้ง 78 ใบ, ภาพหลังไพ่ และเครดิต
