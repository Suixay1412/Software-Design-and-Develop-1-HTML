# ใบงานการทดลอง HTML
 
## การทดลองที่ 3: การจัดการข้อความและการจัดรูปแบบ
### ขั้นตอนการทดลอง
1. ทดลองใช้ tag ต่างๆ:
```html
<h1>หัวข้อระดับ 1</h1>
<h2>หัวข้อระดับ 2</h2>
<p>ย่อหน้าปกติ</p>
<p>ข้อความ <strong>ตัวหนา</strong> และ <em>ตัวเอียง</em></p>
<p>ขึ้นบรรทัดใหม่<br>ด้วย br</p>
<hr>
<pre>
    ข้อความที่ต้องการ
    รักษารูปแบบ
    การเว้นวรรค
</pre>
```

### แบบฝึกหัด
1. สร้างหน้าเว็บแนะนำตัวเองที่ประกอบด้วย:
   - ชื่อ-นามสกุล
   - ประวัติการศึกษา
   - งานอดิเรก
   - เป้าหมายในอนาคต
 ข้อกำหนดที่ต้องมี:
   - หัวข้อหลักและหัวข้อย่อย
   - ย่อหน้าที่มีการจัดรูปแบบ
   - การขึ้นบรรทัดใหม่
   - เส้นคั่นระหว่างเนื้อหา
### บันทึกผลการทดลอง
- รหัสเอกสาร HTML ที่เขียน:
```html
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>แนะนำตัวเอง</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2 {
            color: #333;
        }
        .section-divider {
            border-bottom: 2px solid #ccc;
            margin: 20px 0;
        }
        .content-section {
            margin: 20px 0;
        }
    </style>
</head>
<body>

    <h1>ชื่อ-นามสกุล</h1>
    <p>นายปวริศวร์ วงศ์แสนสุข</p>
    <div class="section-divider"></div>

    <h2>ประวัติการศึกษา</h2>
    <div class="content-section">
        <p>สถาบันเทคโนโลยีพระจอมเกล้าเจ้าคุณทหารลาดกระบัง</p>
    </div>
    <div class="section-divider"></div>

    <h2>งานอดิเรก</h2>
    <div class="content-section">
        <p>อ่านหนังสือ</p>
    </div>
    <div class="section-divider"></div>

    <h2>เป้าหมายในอนาคต</h2>
    <div class="content-section">
        <p>ยังไม่แน่ชัด</p>
    </div>
    <div class="section-divider"></div>

</body>
</html>
```
- ภาพผลลัพธ์:
[วางภาพ screenshot ที่นี่]
![image](https://github.com/user-attachments/assets/cfdc03ae-2c49-4f10-9ea2-3a7e1e6c95a6)


