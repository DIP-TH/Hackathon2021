![DIP LOGO](https://www.ipthailand.go.th/images/001/DIP-Logo.png)
# My Better Country Hackathon ครั้งที่ 9
## Data Hack for IP..เปลี่ยนข้อมูลเป็นนวัตกรรมขับเคลื่อนทรัพย์สินทางปัญญา
[link present slide](https://docs.google.com/presentation/d/1cgiY1A42jkdYhpMrvsSKm9BOXET3sG6zMF62ppCPhAk/edit?usp=sharing)

## API 
สามารถขอใช้ได้ที่ https://api.ipthailand.go.th
ข้อมูลเครื่องหมายการค้าใช้ api รหัส A0015
[response example](https://github.com/DIP-TH/Hackathon2021/blob/main/tmdataStructure.jsonc)

## ข้อมูลคำสั่งการนายทะเบียน
[TMSimilarData/TMOrderMatra.json](https://github.com/DIP-TH/Hackathon2021/blob/main/TMSimilarData/TMOrderMatra.json)

| Field | Description |
| --- | --- |
| tr_no | เลขคำขอ |
| matra | มาตราที่สั่งการ |

## ข้อมูลรายละเอียดคำสั่งนายทะเบียน
[รายละเอียดคำสั่งนายทะเบียน](https://github.com/DIP-TH/Hackathon2021/blob/main/TMSimilarData/export.zip)

แตก zip จะได้ file tsv (tab seperate value)

| Field | Description |
| --- | --- |
| tr_no | เลขคำขอ |
| matra | มาตราที่สั่งการ |
|matra_desc| รายละเอียดคำสั่ง |

## ข้อมูลคำขอที่ติดเหมือนคล้าย
[TMSimilarData/TMSimilarData.json](https://github.com/DIP-TH/Hackathon2021/blob/main/TMSimilarData/TMSimilarData.json)

| Field | Description |
| --- | --- |
| tr_no | เลขคำขอ |
| d_tr_no_r | เลขคำขอที่เหมือนคล้าย |
|fl_flag| วิธีตรวจสอบ อักษรแรก/เสียงท้าย |
|word_flag| วิธีตรวจสอบ คำเหมือนคล้าย |
|fslast_flag| วิธีตรวจสอบ เสียงท้ายอีน |
|homonym_flag| วิธีตรวจสอบ เสียงพ้องพยางค์ |
|pic_flag| วิธีตรวจสอบ รูปภาพ |
|cond_pic| เงื่อนไข รูป |
|cond_class| เงื่อนไข จำพวก |
|cond_word| เงื่อนไข คำ |

## ข้อมูลคำขอที่ได้รับจดโดยไม่มีการสั่งแก้ไข
[TMSimilarData/TMReg.json](https://github.com/DIP-TH/Hackathon2021/blob/main/TMSimilarData/TMReg.json)

## รหัส Vienna Code
[/StandardCode/ViennaCodeTH.json](https://github.com/DIP-TH/Hackathon2021/blob/main/StandardCode/ViennaCodeTH.json)

| Field | Description |
| --- | --- |
| mark_code | รหัส |
| mark_desc | รายละเอียด |

## รหัสอักษรแรก
[/StandardCode/FirstLetterTH.json](https://github.com/DIP-TH/Hackathon2021/blob/main/StandardCode/FirstLetterTH.json)

| Field | Description |
| --- | --- |
| id | รหัส |
| first_c | รหัสอักษรโรมัน |
| group_c | อักษรไทย |

## รหัสเสียงท้าย
[/StandardCode/LastSoundTH.json](https://github.com/DIP-TH/Hackathon2021/blob/main/StandardCode/LastSoundTH.json)

| Field | Description |
| --- | --- |
| id | รหัส |
| read_s | คำอ่าน |
