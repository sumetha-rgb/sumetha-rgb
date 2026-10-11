<h1 align="center">Sumetha</h1>

<p align="center"><b>Full-Stack Developer</b> · Intern at COM7</p>
<p align="center">Full-Stack Developer · Software Engineer · Data Analyst · DevOps Engineer</p>

<p align="center">
  <a href="mailto:sumetra2@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://linkedin.com/in/your-name"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,nodejs,tailwind,postgres,supabase,prisma,git,vercel&perline=10" alt="Skills" />
</p>

---

## About me

ผมเป็นนักพัฒนาเว็บ ตอนนี้ฝึกงานอยู่ที่ COM7 ทำระบบที่ใช้ภายในบริษัทให้ทีมสรรหาบุคลากรและทีมดูแลสต็อกสินค้า ผมทำเองตั้งแต่ออกแบบฐานข้อมูล เขียนหน้าเว็บ เขียนหลังบ้าน ต่อกับ LINE และอีเมล ไปจนถึงเอาขึ้นใช้งานจริง

**ตำแหน่งที่สนใจ:** Full-Stack Developer, Software Engineer, Data Analyst, DevOps Engineer

---

## Projects

| โปรเจกต์ | ช่วยอะไร | เทคโนโลยี |
|---|---|---|
| **Assignment Management** | สั่งงาน ตรวจงาน ให้คะแนน มี leaderboard | Next.js, Prisma, PostgreSQL |
| **Interview Queue** | เช็คชื่อ ออกเลขคิว ส่งบัตรคิวให้ผู้สมัคร | Next.js, Supabase, Brevo |
| **Job Vacancy** | ค้นหางานตามจังหวัด ส่งอีเมลยืนยันเป็นชุด | Apps Script, Brevo |
| **Document LINE Bot** | รับเอกสารผ่าน LINE และแจ้งสถานะอัตโนมัติ | Apps Script, LINE API, LIFF |
| **Stock Req** | เบิก คืน เช็คสต็อก แจ้งเตือนผ่าน LINE | Next.js, Google Sheets, NextAuth |

### รายละเอียดแต่ละโปรเจกต์ (กดเพื่อขยาย)

<details>
<summary><b>1. ระบบจัดการงานที่ได้รับมอบหมาย (Assignment Management)</b></summary>

เดิมการสั่งงานและตรวจงานพนักงานทำด้วยมือ และไม่มีเกณฑ์ให้คะแนนที่ตรงกัน

- สร้างงาน ส่งงาน ตรวจงาน ให้คะแนน และเขียนความเห็นได้
- ผู้ใช้มี 3 ระดับ คือ Staff, Admin และ Super Admin
- มีตารางอันดับคะแนน ดูแยกตามเดือนได้ และตั้งระดับกับเหรียญตามช่วงคะแนนเองได้

**ผลลัพธ์:** หัวหน้าไม่ต้องจดงานและคะแนนเอง ระบบเก็บสถานะงาน คะแนน และความเห็นไว้ที่เดียว พนักงานเปิดดูอันดับกับระดับของตัวเองได้ทันที

`Next.js` `TypeScript` `Prisma` `PostgreSQL`

</details>

<details>
<summary><b>2. ระบบจัดการคิวสัมภาษณ์ (Interview Queue)</b></summary>

วันสัมภาษณ์มีคนมาเยอะ จดคิวด้วยกระดาษแล้วช้าและพลาดบ่อย

- ดึงรายชื่อผู้สมัครจาก Google Sheets โดยไม่ลบประวัติคิวเก่า
- เช็คชื่อ ออกเลขคิว และส่งอีเมลบัตรคิวให้ผู้สมัคร
- เก็บประวัติคิวแยกตามงาน และมีสิทธิ์ Admin, Interviewer, Viewer

**ผลลัพธ์:** ทีมสรรหาไม่ต้องจดคิวและพิมพ์อีเมลทีละคน เช็คชื่อแล้วระบบออกเลขคิวและส่งบัตรคิวให้เลย ถ้าแก้รายชื่อในชีท ระบบดึงมาอัปเดตเอง และย้อนดูประวัติคิวของแต่ละงานได้

`Next.js` `TypeScript` `Supabase` `Brevo`

</details>

<details>
<summary><b>3. เว็บค้นหาตำแหน่งงานว่าง (Job Vacancy)</b></summary>

คนสมัครหาตำแหน่งงานตามจังหวัดยาก ส่วนทีมสรรหาต้องส่งอีเมลยืนยันทีละคน

- ค้นหาตำแหน่งตามจังหวัด และกรองตามบริษัทในเครือ
- หน้าแอดมินเปลี่ยนแหล่งข้อมูลได้ ไม่ต้องแก้โค้ด
- ส่งอีเมลทีละชุด ดูตัวอย่างก่อนส่งจริง และอัปเดตสถานะกลับเข้าชีทให้เอง

**ผลลัพธ์:** ทีมสรรหาไม่ต้องส่งอีเมลยืนยันทีละคน เลือกเป็นชุดแล้วส่งได้เลย และไม่ต้องกลับไปติ๊กในชีทว่าส่งแล้ว ถ้าอยากเปลี่ยนชีทตำแหน่งงาน ก็ทำที่หน้าแอดมินได้เอง ไม่ต้องรอคนแก้โค้ด

`Google Apps Script` `Google Sheets` `Brevo API`

</details>

<details>
<summary><b>4. ระบบรับเอกสารผู้สมัครผ่าน LINE (Document LINE Bot)</b></summary>

ตามเอกสารผู้สมัครผ่านแชทแล้วตกหล่น และดูสถานะไม่ชัด

- ผู้สมัครอัปโหลดเอกสารผ่านหน้าเว็บในแอป LINE (LIFF)
- ระบบส่งข้อความใน LINE บอกสถานะ ผ่าน ตีกลับ หรือเอกสารยังขาด
- แอดมินมีแดชบอร์ดกับไทม์ไลน์ของผู้สมัครแต่ละคนไว้ตรวจเอกสาร

**ผลลัพธ์:** ทีมไม่ต้องไล่ถามเอกสารผู้สมัครทีละคนในแชต ระบบแจ้งสถานะและเอกสารที่ยังขาดให้ผู้สมัครเอง และแอดมินเห็นจากหน้าเดียวว่าใครส่งครบแล้วหรือยัง

`Google Apps Script` `LINE Messaging API` `LIFF`

</details>

<details>
<summary><b>5. ระบบเบิกสินค้าคงคลัง (Stock Req)</b></summary>

การเบิก คืน และเช็คสต็อกในองค์กรทำยาก ยอดคงเหลือคลาดเคลื่อน และไม่รู้ว่าใครเบิกอะไรไป

- เบิกได้ 4 แบบ: ทั่วไป พนักงานใหม่ (ตามชุดที่ตั้งไว้) กิจกรรม และเช็คสต็อก
- คืนของบางส่วนได้ ระบบนับยอดที่คืนไม่ให้เกินที่เบิก
- ผู้ใช้มี 3 ระดับ และเก็บประวัติการแก้ไขระบบ (Audit Log)
- แจ้งเตือนผ่านการ์ด LINE และอีเมล และพิมพ์ในแชต LINE เพื่อเช็คสต็อกได้ทันที
- ใช้บนมือถือได้ ตารางจะเปลี่ยนเป็นการ์ดเมื่อจอแคบ

**จุดที่ต้องคิดเยอะ**

- กันสต็อกเพี้ยนตอนมีคนเบิกพร้อมกัน ด้วย Mutex ให้ตัดสต็อกทีละรายการ
- ลดจำนวนครั้งที่เรียก Google Sheets ด้วยแคช 15–30 วินาที และล้างแคชทันทีเมื่อมีการเขียนข้อมูล
- ถ้าเขียนข้อมูลแล้วโดน Google จำกัดอัตรา (429) ให้ลองใหม่ แต่ไม่ลองใหม่กรณีอื่น เพราะอาจได้แถวซ้ำ
- ส่ง LINE กับอีเมลหลังตอบผู้ใช้แล้ว ผู้ใช้จะได้ไม่ต้องรอ

**ผลลัพธ์:** ไม่ต้องจดการเบิกคืนด้วยมือ ยอดสต็อกอัปเดตเองทุกครั้งที่เบิกหรือคืน และย้อนดูได้ว่าใครเบิกอะไรไป เบิกให้พนักงานใหม่หลายคนตามชุดที่ตั้งไว้ได้ในครั้งเดียว และถามบอทใน LINE เพื่อเช็คสต็อกได้ทันที

`Next.js` `TypeScript` `NextAuth` `Google Sheets API` `LINE API` `Cloudinary`

</details>

---

## Experience

**นักศึกษาฝึกงาน · COM7**
มิถุนายน – ตุลาคม

ทำและดูแลระบบเว็บที่ใช้ภายในให้ทีมสรรหาบุคลากร มีระบบคิวสัมภาษณ์ หน้าค้นหาตำแหน่งงาน ระบบรับเอกสารผ่าน LINE และระบบเบิกสินค้า ใช้ Supabase เก็บข้อมูลและจัดการการล็อกอินของระบบคิวสัมภาษณ์ เชื่อมระบบกับ Google Sheets, LINE และอีเมล และเขียนคู่มือติดตั้งไว้ให้คนอื่นรับงานต่อได้

---

## Technical skills

| | |
|---|---|
| **Frontend** | Next.js, React, TypeScript, Tailwind CSS, shadcn/ui, Framer Motion |
| **Backend** | Next.js API Routes, Node.js, JWT, NextAuth |
| **Database** | PostgreSQL, Supabase, Prisma ORM, Google Sheets API |
| **Automation** | Google Apps Script, Google Sheets, Vercel Cron |
| **Integrations** | LINE Messaging API, LIFF, Brevo, Resend, SendGrid, Cloudinary |
| **Tools** | Git, GitHub, pnpm, npm, clasp |

---

## Contact

สนใจร่วมงานหรืออยากถามอะไรเพิ่ม ติดต่อได้ที่ [sumetra2@gmail.com](mailto:sumetra2@gmail.com)
