# TECH-STEM — เว็บฝ่ายเทคโนโลยีสารสนเทศและสเต็มศึกษา

เว็บฝ่ายรวมงานเทคโนโลยี (Network / School Connex / พัฒนาระบบ) + STEM Innovation Lab
ของโรงเรียน มอ.วิทยานุสรณ์ พร้อมแผนสร้างรายได้ (STEM Shop, บริการวิชาการ, Smart Farm)

## โครงสร้าง
- `PLAN.md` — แผนงานรวมฝ่าย ปีการศึกษา 2569 (โครงสร้าง 4 กลุ่มงาน, โมเดลรายได้, KPI, ปฏิทิน)
- `docs/index.html` — เว็บฝ่าย Phase 1 (static, พร้อม deploy GitHub Pages จากโฟลเดอร์ `docs/`)

## Deploy (Phase 1)
1. สร้าง repo GitHub → push โฟลเดอร์นี้
2. Settings → Pages → Source: `main` / folder `docs/`

## Phase ถัดไป (ตามแพทเทิร์น MIDTERM-RESULTS / EQUIPMENT-LOAN)
- Phase 2: STEM Shop — Cloudflare Worker + D1 (products / orders / bookings) + หน้าแอดมิน
- Phase 3: ระบบจองใช้เครื่อง + จองคอร์สอบรม + แดชบอร์ดรายได้
- Phase 4: เชื่อมข้อมูล Smart Farm (BARNMAN) + สั่งจองผลผลิตล่วงหน้า

## สิ่งที่ต้องแก้ก่อนใช้จริง
- ใส่ลิงก์จริงของแต่ละระบบในส่วน "ระบบบริการดิจิทัล" (`docs/index.html` ตอนนี้เป็น `#`)
- ใส่ช่องทางติดต่อจริง (School Connex / เบอร์ / อีเมล) ในส่วน Contact
- ปรับราคาสินค้า-บริการตามราคากลางที่ฝ่ายกำหนด
