# ตรวจคะแนน Invalid–Pass–Fail

[← กลับหน้าหลัก](../README.md) · [ดาวน์โหลดไฟล์ Flowgorithm](<./ตรวจคะแนนInvalid-Pass-Fail.fprg>)

## โจทย์

รับคะแนน ตรวจสอบช่วงที่ถูกต้องตั้งแต่ 0–100 คะแนน แล้วแสดงผล `Pass`, `Fail` หรือ `Invalid Score`

**แนวคิดที่ฝึก:** ตรวจสอบความถูกต้องของข้อมูลก่อนใช้เงื่อนไขตัดสินผล

## ผังงานจาก Flowgorithm

![ผังงาน ตรวจคะแนน Invalid Pass Fail](<./images/ตรวจคะแนนInvalid-Pass-Fail.png>)

> ภาพหน้าจอนี้จับคู่กับไฟล์ `ตรวจคะแนนInvalid-Pass-Fail.fprg` ตามชื่อเดียวกัน

## Pseudocode

```text
เริ่มต้น
    ประกาศ Integer score
    แสดงผล "Enter Score"
    รับค่า score

    ถ้า score >= 0 และ score <= 100 แล้ว
        แสดงผล "Score = " & score & " Points"

        ถ้า score >= 50 แล้ว
            แสดงผล "Pass"
        มิฉะนั้น
            แสดงผล "Fail"
        จบเงื่อนไข
    มิฉะนั้น
        แสดงผล "Invalid Score"
    จบเงื่อนไข
จบการทำงาน
```

## ตัวอย่างทดสอบ

| `score` | ผลลัพธ์ |
|---:|---|
| `-1` | `Invalid Score` |
| `49` | `Fail` |
| `50` | `Pass` |
| `100` | `Pass` |
| `101` | `Invalid Score` |
