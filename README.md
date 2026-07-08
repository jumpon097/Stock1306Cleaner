# 1306 Cleaner Pro ALL stock

PWA สำหรับ Clean ไฟล์ 1306 ทั้งคลังใหญ่และคลังย่อยในหน้าเดียว ใช้งานบน GitHub Pages ได้

## Deploy ด้วย GitHub Pages

1. สร้าง repository ใหม่บน GitHub
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ไปที่ root ของ repository
3. เปิด `Settings > Pages`
4. เลือก `Build and deployment: GitHub Actions`
5. workflow ใน `.github/workflows/pages.yml` จะ deploy ให้อัตโนมัติ

## การใช้งาน

- เลือกโหมด `คลังใหญ่` หรือ `คลังย่อย`
- เลือกไฟล์ `.xls`, `.xlsx`, หรือ `.csv`
- กดประมวลผล
- ดาวน์โหลดผลลัพธ์

ข้อมูลถูกประมวลผลใน browser ของผู้ใช้ ไม่มีการอัปโหลดไฟล์ Excel ไปที่ server
