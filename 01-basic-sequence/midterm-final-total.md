# รวมคะแนนกลางภาคและปลายภาค

[← กลับหน้าหลัก](../README.md) · [ดาวน์โหลดไฟล์ Flowgorithm](./midterm-final-total.fprg)

## โจทย์

รับคะแนนกลางภาคและปลายภาค แล้วหาคะแนนรวม

**แนวคิดที่ฝึก:** ลำดับคำสั่ง (Sequence), การรับค่า, การคำนวณ และการแสดงผล

## ผังงานจาก Flowgorithm

![ผังงาน รวมคะแนนกลางภาคและปลายภาค](./images/midterm-final-total.png)

> ภาพหน้าจอนี้มาจากโปรแกรม Flowgorithm และจับคู่กับไฟล์ต้นฉบับของโจทย์นี้โดยตรง

## Pseudocode

```text
เริ่มต้น
    ประกาศ Integer midscore, finalscore, totalscore
    แสดงผล "Enter midterm score: "
    รับค่า midscore
    แสดงผล "Enter final score: "
    รับค่า finalscore
    totalscore ← midscore + finalscore
    แสดงผล "Total score = " & totalscore
จบการทำงาน
```

## ทดลองให้ครบ

- ทดสอบค่าปกติที่ควรผ่าน
- หากมีการตรวจช่วง ให้ทดสอบค่าต่ำกว่าขอบเขตและสูงกว่าขอบเขต
- เปรียบเทียบผลลัพธ์กับการคำนวณด้วยตนเอง
