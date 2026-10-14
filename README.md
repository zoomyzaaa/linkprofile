# ต๊อด ♡ — Link Profile & Creator Hub

เว็บรวมลิงก์ส่วนตัวและคอมมูนิตี้ (Link in Bio / Creator Hub) สไตล์พาสเทลมินิมอล น่ารัก อบอุ่น พร้อมระบบเล่นเสียงเพลงคลอ และระบบจัดการข้อมูลหลังบ้าน (Admin Panel) เชื่อมต่อฐานข้อมูล Cloud Firestore แบบ Real-time

---

## ✨ จุดเด่น & ฟีเจอร์หลัก (Key Features)

### 🎀 หน้าบ้าน & ดีไซน์ (Frontend & Design)
- **Click to Enter Splash**: หน้าจอต้อนรับแบบเบลอนุ่มนวล ปล่อยให้เพลงเริ่มเล่นอัตโนมัติทันทีเมื่อคลิกเข้าเว็บ
- **Top Bar**:
  - **แถบคลื่นเสียง (Soundwave)**: แอนิเมชันคลื่นเสียงดุ๊กดิ๊ก กดเปิด-ปิดเพลงคลอพื้นหลังได้ตลอดเวลา
  - **ปุ่มหัวใจขวาบน**: ปุ่มเข้าสู่ระบบ Admin Panel แบบแนบเนียน
- **Profile Banner**:
  - พื้นหลังแบนเนอร์สีชมพูอ่อนละมุน (`#fdf9fc`)
  - รูปโปรไฟล์หลักขนาดใหญ่พร้อมจัดวางพอดีกรอบ
  - ชื่อเล่น (**ต๊อด**) และกล่องข้อความคำพูด (**Speech Bubble**)
  - แถวข้อความคำอธิบายตัวเอง (**♡ welcome kaaa ♡**)
  - **ปุ่มเสียงไมค์ 1 (click 🎤)**: กดแล้วมีเสียงพูด/เอฟเฟกต์เล่น 1 รอบ
- **Donate Section**:
  - หัวข้อ **donate here** สไตล์น่ารัก
  - ปุ่มโดเนททรงมน **"ระวังเสียตังงง"** พร้อมไอคอนหัวใจ SVG ลิงก์ตรงสู่ EasyDonate
  - **ปุ่มเสียงไมค์ 2**: ไอคอนไมค์ด้านซ้าย กดเล่นเสียงเอฟเฟกต์ 1 รอบ
- **Mustache Divider**: เส้นคั่นลายประตกแต่งด้วยไอคอนหนวดน่ารัก
- **Social Cards Grid (การ์ด 4 แพลตฟอร์ม)**:
  - การ์ดทรงสูง 4 ช่อง: **TikTok**, **Twitch**, **Instagram**, **SoundCloud**
  - ดีไซน์หัวใจลอยนูนด้านบน (Floating Heart Badge) พร้อมเอฟเฟกต์เงาสามมิติ
- **ปุ่มลอยกลับขึ้นด้านบน (Back to Top FAB)**: ปุ่มลูกศรลอยมุมขวาล่าง กดแล้วเลื่อนกลับขึ้นบนสุดอย่างนุ่มนวล
- **Custom Cursor**: เมาส์ลายน้องแกะ My Sweet Piano รองรับทั้งแบบปกติ (Base) และตอนชี้ปุ่ม (Hover) ขนาดมาตรฐาน 32x32 px
- **Typography**: ติดตั้งฟอนต์สวยงามเฉพาะตัว:
  - `Cloud Soft` (Light / Bold)
  - `Lulu Font TH`
  - `Helvetica Thai`
- **Social Link Preview (SEO / Open Graph)**: ส่งลิงก์บน LINE, Facebook, Messenger, Discord, X จะขึ้นรูปภาพปก (`images/preview.jpg`) และหัวข้อแบบการ์ดพรีวิวทันที

---

### ⚙️ ระบบหลังบ้าน (Admin Panel)
เข้าใช้งานได้โดยกดปุ่ม **รูปหัวใจ (ขวาบน)**:
- **ระบบความปลอดภัย**: ล็อกอินด้วยรหัสผ่าน Admin
- **แก้ไขข้อมูลได้แบบ Real-time**:
  - ชื่อที่แสดง และชื่อบนกล่องคำพูด
  - ข้อความ Speech Bubble
  - คำอธิบายตัวเองแถวล่าง (Bio)
  - รูปโปรไฟล์: รองรับการเลือกรูปจากเครื่อง พร้อม Crop/บีบอัดภาพให้อัตโนมัติ หรือใส่ลิงก์รูปภาพ
  - เสียงไมค์ 1 และ ไมค์ 2: เลือกไฟล์เสียงจากเครื่อง หรือใส่ลิงก์ URL พร้อมปุ่มทดลองฟัง
  - ลิงก์โดเนท (Donate URL)
  - ลิงก์โซเชียลมีเดียทั้ง 4 ช่องทาง (TikTok, Twitch, Instagram, SoundCloud)
  - ลิงก์เพลงพื้นหลัง (Background Music URL)
  - แถบเลื่อนปรับระดับความดังเพลง (Music Volume Slider)
  - แถบเลื่อนปรับความโปร่งแสงภาพพื้นหลัง GIF (Background Opacity Slider)
- **ระบบแคช LocalStorage**: โหลดข้อมูลเวอร์ชันล่าสุดทันทีใน 0 วินาที ไม่ต้องรอเน็ต
- **Cloud Firestore Real-time Sync**: บันทึกข้อมูลและซิงค์แสดงผลสดบนทุกอุปกรณ์ทันที

---

## 📁 โครงสร้างโปรเจกต์ (Project Structure)

```text
linkprofile/
├── index.html                      # หน้าเว็บหลัก, CSS สไตล์ทั้งหมด, JS และ Admin Panel
├── README.md                       # เอกสารคู่มือโปรเจกต์
├── images/                         # โฟลเดอร์รูปภาพและไอคอน
│   ├── preview.jpg                 # รูปภาพปกสำหรับแชร์ลิงก์ (Social Share Preview)
│   ├── mainprofile.png             # รูปโปรไฟล์หลัก
│   ├── หนวด.png                    # ไอคอนหนวดคั่นกลางหน้าเว็บ (HD)
│   ├── bg.gif                      # ภาพพื้นหลังเคลื่อนไหวด้านหลัง
│   ├── tiktok-icon.jpg             # ไอคอน TikTok
│   ├── insta-icon.jpg              # ไอคอน Instagram
│   ├── soundcloud-logo.jpg         # ไอคอน SoundCloud
│   ├── favicon.png                 # ไอคอนบนแท็บเบราว์เซอร์ (32x32)
│   └── apple-touch-icon.png        # ไอคอนบุ๊กมาร์กสำหรับ iOS (180x180)
├── cursor/                         # โฟลเดอร์เคอร์เซอร์เมาส์พิเศษ
│   ├── base.png                    # เมาส์สถานะปกติ (32x32)
│   ├── hover.png                   # เมาส์สถานะชี้ปุ่ม/ลิงก์ (32x32)
│   ├── base-orig.png               # ไฟล์ต้นฉบับความละเอียดสูง
│   └── hover-orig.png              # ไฟล์ต้นฉบับความละเอียดสูง
└── fonts/                          # โฟลเดอร์ฟอนต์ท้องถิ่น
    ├── CloudSoft-Light.otf
    ├── CloudSoft-Bold.otf
    ├── Lulu.ttf
    └── ...
```

---

## 🚀 การติดตั้งและเปิดใช้งาน (Deployment)

โปรเจกต์นี้เขียนด้วย Vanilla HTML, CSS และ JavaScript ล้วน ไม่ต้องติดตั้ง Node.js หรือสั่ง build ใด ๆ สามารถเปิดใช้งานได้ผ่าน:

1. **GitHub Pages**:
   - ไปที่แท็บ **Settings** ของ Repository บน GitHub
   - เข้าไปที่หัวข้อ **Pages**
   - ในส่วน **Build and deployment** ให้เลือก Source เป็น `Deploy from a branch`
   - เลือก Branch `main` โฟลเดอร์ `/ (root)` แล้วกด **Save**
   - เว็บจะออนไลน์ที่ URL: `https://<username>.github.io/<repo-name>/`

2. **เปิดทดสอบบนเครื่อง Local**:
   - ดับเบิลคลิกไฟล์ `index.html` หรือเปิดผ่าน VS Code Extension เช่น Live Server
