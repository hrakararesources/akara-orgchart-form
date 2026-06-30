# Akara Org Chart — HR Admin (deploy)

หน้าเว็บ HR Admin สำหรับระบบ Organization Chart ของ Akara Resources
deploy ผ่าน GitHub Pages — มีไฟล์เดียวคือ `index.html`

- Backend: Supabase (schema `orgchart` ใน project Akara HR)
- เข้าถึงได้เฉพาะ HR Admin (login + RLS) — anon key ในไฟล์เป็น public key ปลอดภัย
- **repo นี้ตั้งใจให้มีแค่ตัวฟอร์ม** ไม่มีไฟล์ SQL / seed / ข้อมูลพนักงาน (เก็บแยกในเครื่อง)
