<h1 align="center">Sumetha</h1>

<p align="center">
  <b>Full-Stack Developer</b> · Intern at COM7
</p>

<p align="center">
  Full-Stack Developer · Software Engineer · Data Analyst · DevOps Engineer
</p>

<p align="center">
  <a href="mailto:sumetra2@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,nextjs,react,nodejs,tailwind,postgres,supabase,prisma,git,vercel&perline=11" alt="Skills" />
</p>

---

## About Me

ผมเป็นนักพัฒนาเว็บ ตอนนี้ฝึกงานอยู่ที่ **COM7**  
ทำระบบภายในให้ทีมสรรหาบุคลากรและทีมดูแลสต็อกสินค้า

ผมทำครบวงจร ตั้งแต่การเชื่อมฐานข้อมูล เขียนหน้าเว็บ เขียนหลังบ้าน เชื่อมต่อ LINE กับอีเมล ไปจนถึงเอาขึ้นใช้งานจริง

**ตำแหน่งที่สนใจ:** Full-Stack Developer, Software Engineer, Data Analyst, DevOps Engineer

### What I can help with
- สร้างระบบภายในองค์กร (Internal Tools)
- ระบบที่มีสิทธิ์ผู้ใช้หลายระดับ (Role-based Access)
- เชื่อมต่อ Supabase , Google Sheets , LINE และ Email
- พัฒนาระบบตั้งแต่ต้นจนถึงขั้นตอน Deploy จริง

### Currently Exploring
- Building better internal tools with clean architecture
- Improving performance when using Google Sheets as a database
- Exploring Supabase Realtime and Edge Functions

---

## Projects

| โปรเจกต์ | ช่วยอะไร | เทคโนโลยี | ลิงก์ |
|---------|----------|----------|------|
| **Assignment Management** | สั่งงาน ตรวจงาน ให้คะแนน มี Leaderboard + Mission | Next.js, Prisma, PostgreSQL | [Repo](https://github.com/SorayuthJapanya/com7-assignment-system) |
| **Interview Queue** | เช็คชื่อ ออกเลขคิว ส่งบัตรคิวให้ผู้สมัคร | Next.js, Supabase, Brevo | [Repo](https://github.com/sumetha-rgb/com7-Queue) |
| **Job Vacancy** | ค้นหางานตามจังหวัด ส่งอีเมลยืนยันเป็นชุด | Google Apps Script, Brevo | [Repo](https://github.com/sumetha-rgb/Com7-Job_Vacancy) |
| **Stock Req** | เบิก คืน เช็คสต็อก แจ้งเตือนผ่าน LINE | Next.js, Google Sheets, NextAuth | [Repo](https://github.com/sumetha-rgb/com7-Stock) |
| **NextStep Onboarding** | ยืนยันตัวตนด้วย OTP + แยกสิทธิ์ + หน้ากฎระเบียบ | Next.js, NextAuth, Google Sheets | [Repo](https://github.com/sumetha-rgb/COM7-NextStep) |

### รายละเอียดแต่ละโปรเจกต์

<details>
<summary><b>1. ระบบจัดการงานที่ได้รับมอบหมาย (Assignment Management)</b></summary>

ระบบ Full-stack สำหรับสั่งงาน ตรวจงาน ให้คะแนน และจัดอันดับ  
พัฒนาหลักผ่านบัญชี **Puff-code16** และ **SorayuthJapanya** (repo ต้นฉบับ: [SorayuthJapanya/com7-assignment-system](https://github.com/SorayuthJapanya/com7-assignment-system))

**ฟีเจอร์หลัก**
- สร้าง / ส่ง / ตรวจงาน พร้อมให้คะแนนและเขียนความเห็น
- มีระบบ Mission Quest เพิ่มเติม (แต้มพิเศษ, Early Bird, Negative Point)
- Role-based Access: Staff, Admin, Super Admin
- Leaderboard แยกตามช่วงเวลา + ระบบ Level & Badge ที่ตั้งค่าเองได้
- แสดงสถานะงานสาย (Late Submission Indicator)
- Dashboard ทั้งฝั่ง User และ Admin
- อัปโหลดไฟล์ผ่าน Cloudinary + แจ้งเตือนอีเมลผ่าน SendGrid

**ผลลัพธ์:** ลดงานจดคะแนนและติดตามงานด้วยมือ ระบบเก็บประวัติครบและแสดงอันดับแบบ Real-time

`Next.js` `TypeScript` `Prisma` `PostgreSQL` `Supabase` `Cloudinary` `SendGrid` `TanStack Query` `Zod`
</details>

<details>
<summary><b>2. ระบบจัดการคิวสัมภาษณ์ (Interview Queue)</b></summary>

วันสัมภาษณ์มีคนเยอะ จดคิวด้วยกระดาษแล้วช้าและพลาดบ่อย

- ดึงรายชื่อผู้สมัครจาก Google Sheets โดยไม่ลบประวัติคิวเก่า
- เช็คชื่อ ออกเลขคิว และส่งอีเมลบัตรคิวให้อัตโนมัติ
- เก็บประวัติคิวแยกตาม Event และมีสิทธิ์ Admin / Interviewer / Viewer

**ผลลัพธ์:** ทีมสรรหาไม่ต้องจดคิวและพิมพ์อีเมลทีละคน ระบบออกเลขคิวและส่งบัตรคิวให้เลย

`Next.js` `TypeScript` `Supabase` `Brevo`
</details>

<details>
<summary><b>3. เว็บค้นหาตำแหน่งงานว่าง (Job Vacancy)</b></summary>

คนสมัครหาตำแหน่งงานตามจังหวัดยาก ส่วนทีมสรรหาต้องส่งอีเมลยืนยันทีละคน

- ค้นหาตำแหน่งตามจังหวัด และกรองตามบริษัทในเครือ
- หน้าแอดมินเปลี่ยนแหล่งข้อมูลได้โดยไม่ต้องแก้โค้ด
- ส่งอีเมลเป็นชุด ดูตัวอย่างก่อนส่งจริง และอัปเดตสถานะกลับเข้าชีทให้อัตโนมัติ

**ผลลัพธ์:** ทีมสรรหาไม่ต้องส่งอีเมลยืนยันทีละคน เลือกเป็นชุดแล้วส่งได้เลย

`Google Apps Script` `JavaScript` `Google Sheets` `Brevo API`
</details>

<details>
<summary><b>4. ระบบเบิกสินค้าคงคลัง (Stock Req)</b></summary>

การเบิก คืน และเช็คสต็อกทำยาก ยอดคงเหลือคลาดเคลื่อน

- เบิกได้ 4 แบบ: ทั่วไป, พนักงานใหม่ (ตามชุด), กิจกรรม, และเช็คสต็อก
- คืนของบางส่วนได้ ระบบนับยอดไม่ให้เกินที่เบิก
- มี 3 ระดับสิทธิ์ + Audit Log
- แจ้งเตือนผ่าน LINE และอีเมล

**ผลลัพธ์:** ไม่ต้องจดการเบิกคืนด้วยมือ ยอดสต็อกอัปเดตเองทุกครั้ง

`Next.js` `TypeScript` `NextAuth` `Google Sheets API` `LINE API` `Cloudinary`
</details>

<details>
<summary><b>5. ระบบยืนยันตัวตน Onboarding (NextStep)</b></summary>

ระบบยืนยันตัวตนด้วย OTP ผ่านอีเมล + แยกสิทธิ์ตามบทบาท

- นักศึกษาต้องยืนยันด้วยชื่อ + เลขบัตรประชาชน + อีเมล
- มีหน้า Confirm ข้อมูล + PDPA และหน้ากฎระเบียบแยกตาม role
- Admin สามารถอนุมัติ / ปฏิเสธ และดูประวัติการแก้ไขได้

**ผลลัพธ์:** ลดงานตรวจสอบตัวตนด้วยมือ และควบคุมสิทธิ์การเข้าถึงข้อมูลได้ชัดเจน

`Next.js` `NextAuth` `Google Sheets` `Brevo` `Cloudflare Turnstile`
</details>

---

## Experience

**นักศึกษาฝึกงาน · COM7**  
มิถุนายน – ตุลาคม

ทำและดูแลระบบเว็บภายในให้ทีมสรรหาบุคลากรและทีมสต็อก  
มีระบบคิวสัมภาษณ์ หน้าค้นหาตำแหน่งงาน ระบบเบิกสินค้า และระบบยืนยันตัวตน Onboarding  
พัฒนาและดูแลระบบ Assignment Management อย่างต่อเนื่อง (รวม Mission Quest, Leaderboard, Level System)  
ใช้ Supabase จัดการข้อมูลและ Auth เชื่อมต่อ Google Sheets, LINE และอีเมล  
และเขียนคู่มือติดตั้งไว้ให้คนอื่นรับงานต่อได้

---

## Technical Skills

|                  |                                                                                          |
|------------------|------------------------------------------------------------------------------------------|
| **Languages**    | TypeScript, JavaScript, HTML, CSS                                                        |
| **Frontend**     | Next.js, React, Tailwind CSS, shadcn/ui, Framer Motion, Recharts                         |
| **Backend**      | Next.js API Routes, Node.js, JWT, NextAuth, bcrypt                                       |
| **Database**     | PostgreSQL, Supabase, Prisma ORM, Google Sheets API                                      |
| **Automation**   | Google Apps Script, Vercel Cron, clasp                                                   |
| **Integrations** | LINE Messaging API, LIFF, Brevo, Resend, SendGrid, Cloudinary, Cloudflare Turnstile     |
| **Tools**        | Git, GitHub, pnpm, npm, Vercel                                                           |

---

## Languages

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sumetha-rgb&layout=compact&theme=default&hide_border=true)

---

## Contact

สนใจร่วมงานหรืออยากคุยเพิ่มเติม ติดต่อได้ที่  
[sumetra2@gmail.com](mailto:sumetra2@gmail.com)
