# Math High School Lab

รวมแอปฝึกคณิตศาสตร์ระดับมัธยม เปิดเป็นเว็บด้วย GitHub Pages

## โครงสร้าง

```
index.html            หน้ารวมแอป (เลือกภาษาไทย/อังกฤษ และกรองตามระดับชั้น)
quadratic/
  index.html          Parabola Lab ฉบับภาษาไทย
  en.html             Parabola Lab English version
```

## เพิ่มแอปวิชาใหม่

1. สร้างโฟลเดอร์ใหม่ เช่น `linear/` แล้ววางไฟล์ `index.html` (ไทย) และ `en.html` (อังกฤษ ถ้ามี)
2. เปิด `index.html` ที่หน้าแรก แล้วเพิ่มรายการในอาร์เรย์ `APPS` เช่น

```js
{folder:'linear',grade:2,icon:'parabola',
 th:{title:'ชื่อแอปภาษาไทย',desc:'คำอธิบายสั้น ๆ',topic:'หัวข้อ'},
 en:{title:'English title',desc:'Short description',topic:'Topic'},
 pages:{th:'linear/',en:'linear/en.html'}}
```

`grade` คือระดับชั้น ม.1–ม.6 ใส่เป็นตัวเลข 1–6

3. อัปโหลดไฟล์ขึ้น GitHub แล้วรอ 1–2 นาที หน้าเว็บจะอัปเดตเอง
