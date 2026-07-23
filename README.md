# COS1103 Flowgorithm Practice

แบบฝึกหัดส่วนตัวสำหรับฝึกออกแบบอัลกอริทึมด้วย **Flowgorithm และ Pseudocode** ตั้งแต่การทำงานตามลำดับ การตรวจสอบข้อมูลด้วย `Do...While` ไปจนถึงโจทย์ที่มีข้อมูลหลายค่าซึ่งสัมพันธ์กัน

> A first-year computer science practice repository containing 24 Flowgorithm programs with readable pseudocode and flowchart previews.

## ดูงานบน GitHub อย่างไร

แต่ละโจทย์มีไฟล์ 3 แบบ:

| ไฟล์ | ใช้ทำอะไร |
|---|---|
| `.md` | อ่านโจทย์ ดูภาพผังงาน และอ่าน Pseudocode บน GitHub |
| `.png` | ภาพผังงานหรือภาพหน้าจอจริงจากโปรแกรม Flowgorithm |
| `.fprg` | ไฟล์ต้นฉบับสำหรับดาวน์โหลดไปเปิดด้วย Flowgorithm |

> **สำคัญ:** หากกดไฟล์ `.fprg` บน GitHub จะเห็นข้อมูล XML เพราะ GitHub แสดงโครงสร้างภายในของไฟล์ ไม่ได้หมายความว่าเป็น Python หรือไฟล์เสีย ให้กดลิงก์ **ดูผังงาน + Pseudocode** ในตารางด้านล่างแทน

## Practice If–Else 07/23/2026

แบบฝึก `If...Else` จำนวน 4 ข้อ โดยใช้ภาพหน้าจอผังงานจริงจาก Flowgorithm และจับคู่ภาพกับไฟล์ต้นฉบับตามชื่อเดียวกัน

| แบบฝึกหัด | เปิดดูผังงานและ Pseudocode |
|---|---|
| รับจำนวนเต็ม | [เปิดงาน](<04-if-else-practice/รับจำนวนเต็ม.md>) |
| รับยอดซื้อ ถ้ายอดซื้ออย่างน้อย 1,000 บาท ให้ส่วนลด 10% | [เปิดงาน](<04-if-else-practice/รับยอดซื้อ ถ้ายอดซื้ออย่างน้อย 1,000 บาท ให้ส่วนลด 10% - Final.md>) |
| รับอุณหภูมิ แล้วแสดงสถานะ | [เปิดงาน](<04-if-else-practice/รับอุณหภูมิ แล้วแสดงสถานะ.md>) |
| ตรวจคะแนน Invalid–Pass–Fail | [เปิดงาน](<04-if-else-practice/ตรวจคะแนนInvalid-Pass-Fail.md>) |

## จุดประสงค์

- ฝึกแยกปัญหาเป็น Input–Process–Output
- ฝึกตั้งชื่อตัวแปรและเลือกชนิดข้อมูล
- ป้องกันข้อมูลนอกช่วงด้วย `Do...While`
- ฝึกคำนวณจากข้อมูลหลายค่า
- อธิบายตรรกะของโปรแกรมด้วย Pseudocode
- เก็บหลักฐานพัฒนาการด้านการเขียนโปรแกรมตั้งแต่ปี 1

## ลำดับการเรียนรู้

| หมวด | จำนวน | เนื้อหา | ตัวอย่าง |
|---|---:|---|---|
| `01-basic-sequence` | 4 | รับข้อมูล คำนวณ และแสดงผล | พื้นที่สี่เหลี่ยม, VAT 7% |
| `02-input-validation` | 9 | ตรวจช่วงข้อมูลก่อนนำไปใช้ | อายุ, คะแนน, ราคา, ส่วนลด |
| `03-multiple-inputs` | 7 | ตรวจข้อมูลหลายค่าที่สัมพันธ์กัน | BMI, ยอดถอน, ช่วงเวลา, คะแนนรวม |
| `04-if-else-practice` | 4 | เลือกทำงานตามเงื่อนไข | จำนวนเต็ม, ส่วนลด, อุณหภูมิ, ผลสอบ |

## แบบฝึกหัดทั้งหมด

### 1. Basic sequence

| แบบฝึกหัด | อ่านบน GitHub | ไฟล์ Flowgorithm |
|---|---|---|
| คำนวณพื้นที่สี่เหลี่ยมผืนผ้า | [ดูผังงาน + Pseudocode](01-basic-sequence/rectangle-area.md) | [ดาวน์โหลด `.fprg`](01-basic-sequence/rectangle-area.fprg) |
| รวมคะแนนกลางภาคและปลายภาค | [ดูผังงาน + Pseudocode](01-basic-sequence/midterm-final-total.md) | [ดาวน์โหลด `.fprg`](01-basic-sequence/midterm-final-total.fprg) |
| หาคะแนนเฉลี่ย 3 วิชา | [ดูผังงาน + Pseudocode](01-basic-sequence/three-subject-average.md) | [ดาวน์โหลด `.fprg`](01-basic-sequence/three-subject-average.fprg) |
| คำนวณ VAT 7% และยอดสุทธิ | [ดูผังงาน + Pseudocode](01-basic-sequence/vat-calculator.md) | [ดาวน์โหลด `.fprg`](01-basic-sequence/vat-calculator.fprg) |

### 2. Input validation

| แบบฝึกหัด | อ่านบน GitHub | ไฟล์ Flowgorithm |
|---|---|---|
| ตรวจสอบอายุ 1–120 ปี | [ดูผังงาน + Pseudocode](02-input-validation/age-validation.md) | [ดาวน์โหลด `.fprg`](02-input-validation/age-validation.fprg) |
| ตรวจสอบราคาสินค้า 1–5,000 บาท | [ดูผังงาน + Pseudocode](02-input-validation/price-validation.md) | [ดาวน์โหลด `.fprg`](02-input-validation/price-validation.fprg) |
| ตรวจสอบจำนวนสินค้า 1–100 ชิ้น | [ดูผังงาน + Pseudocode](02-input-validation/quantity-validation.md) | [ดาวน์โหลด `.fprg`](02-input-validation/quantity-validation.fprg) |
| ตรวจสอบคะแนน 0–100 | [ดูผังงาน + Pseudocode](02-input-validation/score-validation.md) | [ดาวน์โหลด `.fprg`](02-input-validation/score-validation.fprg) |
| ตรวจสอบคะแนนกลางภาค 0–40 | [ดูผังงาน + Pseudocode](02-input-validation/midterm-score-validation.md) | [ดาวน์โหลด `.fprg`](02-input-validation/midterm-score-validation.fprg) |
| ตรวจสอบอุณหภูมิ -40 ถึง 60 °C | [ดูผังงาน + Pseudocode](02-input-validation/temperature-validation.md) | [ดาวน์โหลด `.fprg`](02-input-validation/temperature-validation.fprg) |
| ตรวจสอบแบตเตอรี่ 0–100% | [ดูผังงาน + Pseudocode](02-input-validation/battery-validation.md) | [ดาวน์โหลด `.fprg`](02-input-validation/battery-validation.fprg) |
| ตรวจชั่วโมงทำงานและคำนวณค่าจ้าง | [ดูผังงาน + Pseudocode](02-input-validation/work-hours-validation.md) | [ดาวน์โหลด `.fprg`](02-input-validation/work-hours-validation.fprg) |
| ตรวจราคาและคำนวณส่วนลด 10% | [ดูผังงาน + Pseudocode](02-input-validation/discount-calculator.md) | [ดาวน์โหลด `.fprg`](02-input-validation/discount-calculator.fprg) |

### 3. Multiple and related inputs

| แบบฝึกหัด | อ่านบน GitHub | ไฟล์ Flowgorithm |
|---|---|---|
| คำนวณราคารวมจากราคาและจำนวนสินค้า | [ดูผังงาน + Pseudocode](03-multiple-inputs/price-quantity-total.md) | [ดาวน์โหลด `.fprg`](03-multiple-inputs/price-quantity-total.fprg) |
| ตรวจยอดถอนและคำนวณยอดคงเหลือ | [ดูผังงาน + Pseudocode](03-multiple-inputs/deposit-withdrawal-balance.md) | [ดาวน์โหลด `.fprg`](03-multiple-inputs/deposit-withdrawal-balance.fprg) |
| ตรวจน้ำหนัก–ส่วนสูงและคำนวณ BMI | [ดูผังงาน + Pseudocode](03-multiple-inputs/bmi-calculator.md) | [ดาวน์โหลด `.fprg`](03-multiple-inputs/bmi-calculator.fprg) |
| ตรวจคะแนนต่ำสุดและสูงสุดที่สัมพันธ์กัน | [ดูผังงาน + Pseudocode](03-multiple-inputs/score-range-validation.md) | [ดาวน์โหลด `.fprg`](03-multiple-inputs/score-range-validation.fprg) |
| ตรวจเวลาเริ่ม–สิ้นสุดและคำนวณระยะเวลา | [ดูผังงาน + Pseudocode](03-multiple-inputs/time-duration.md) | [ดาวน์โหลด `.fprg`](03-multiple-inputs/time-duration.fprg) |
| ตรวจและรวมคะแนน 3 ส่วน | [ดูผังงาน + Pseudocode](03-multiple-inputs/three-part-score.md) | [ดาวน์โหลด `.fprg`](03-multiple-inputs/three-part-score.fprg) |
| ตรวจและรวมคะแนน 4 ส่วน | [ดูผังงาน + Pseudocode](03-multiple-inputs/four-part-score.md) | [ดาวน์โหลด `.fprg`](03-multiple-inputs/four-part-score.fprg) |

### 4. Practice If–Else 07/23/2026

| แบบฝึกหัด | อ่านบน GitHub | ไฟล์ Flowgorithm |
|---|---|---|
| รับจำนวนเต็ม | [ดูภาพจริง + Pseudocode](<04-if-else-practice/รับจำนวนเต็ม.md>) | [ดาวน์โหลด `.fprg`](<04-if-else-practice/รับจำนวนเต็ม.fprg>) |
| รับยอดซื้อ ถ้ายอดซื้ออย่างน้อย 1,000 บาท ให้ส่วนลด 10% | [ดูภาพจริง + Pseudocode](<04-if-else-practice/รับยอดซื้อ ถ้ายอดซื้ออย่างน้อย 1,000 บาท ให้ส่วนลด 10% - Final.md>) | [ดาวน์โหลด `.fprg`](<04-if-else-practice/รับยอดซื้อ ถ้ายอดซื้ออย่างน้อย 1,000 บาท ให้ส่วนลด 10% - Final.fprg>) |
| รับอุณหภูมิ แล้วแสดงสถานะ | [ดูภาพจริง + Pseudocode](<04-if-else-practice/รับอุณหภูมิ แล้วแสดงสถานะ.md>) | [ดาวน์โหลด `.fprg`](<04-if-else-practice/รับอุณหภูมิ แล้วแสดงสถานะ.fprg>) |
| ตรวจคะแนน Invalid–Pass–Fail | [ดูภาพจริง + Pseudocode](<04-if-else-practice/ตรวจคะแนนInvalid-Pass-Fail.md>) | [ดาวน์โหลด `.fprg`](<04-if-else-practice/ตรวจคะแนนInvalid-Pass-Fail.fprg>) |

## แนวคิดการตรวจสอบข้อมูล

```text
ทำซ้ำ
    แสดงข้อความขอข้อมูล
    รับค่า
ขณะที่ ข้อมูลอยู่นอกช่วงที่กำหนด
```

แนวคิดสำคัญคือ **เงื่อนไขของลูปบอกว่า “ค่าไม่ถูกต้อง”** ดังนั้นถ้าเงื่อนไขเป็นจริง โปรแกรมจะย้อนกลับไปรับค่าใหม่ และเมื่อเงื่อนไขเป็นเท็จจึงออกจากลูปไปคำนวณต่อ

## วิธีเปิดไฟล์ต้นฉบับ

1. ติดตั้ง [Flowgorithm](http://www.flowgorithm.org/)
2. ดาวน์โหลดหรือ Clone repository นี้
3. เปิดไฟล์นามสกุล `.fprg` ด้วย Flowgorithm
4. กด Run แล้วทดลองทั้งค่าที่ถูกต้อง ค่าต่ำกว่าช่วง และค่าสูงกว่าช่วง

## หมายเหตุ

Repository นี้เป็นแบบฝึกหัดส่วนตัวเพื่อแสดงพัฒนาการ ไม่ใช่เอกสารหรือเฉลยอย่างเป็นทางการของรายวิชา COS1103

Created by [Koko777-Python](https://github.com/Koko777-Python)
