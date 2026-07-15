# Analytics Engineering Labs

Repository นี้จัดเก็บโปรเจกต์และแบบฝึกหัดจากวิชา Analytics Engineering โดยแบ่งเนื้อหาออกเป็น Lab ต่างๆ ดังนี้:

## 📂 โครงสร้าง Repository

### 🔹 [Lab 1: Data Classification & Storage Design](Lab1/)
- **รายละเอียด:** การจำแนกประเภทข้อมูลและการออกแบบระบบจัดเก็บข้อมูลเบื้องต้น
- **ไฟล์สำคัญ:** เอกสารสรุปการออกแบบการจัดเก็บข้อมูล (.docx)

### 🔹 [Lab 2: IoT Data Cleaning Pipeline](Lab2/)
- **รายละเอียด:** การทำความสะอาดข้อมูลดิบ (Raw Data) จากเซนเซอร์ IoT โดยใช้ Python และ Pandas
- **สิ่งที่ทำ:**
    - จัดการข้อมูลซ้ำ (Duplicates)
    - ตรวจสอบและจัดการค่าผิดปกติ (Outliers) เช่น อุณหภูมิ (0-50°C) และแบตเตอรี่ (0-100%)
    - สร้างสถานะคุณภาพข้อมูล (Data Quality Status)
    - ส่งออกรายงานสรุปคุณภาพข้อมูล (Data Quality Report)
- **ไฟล์สำคัญ:** `cleaned_iot_data.csv`, `Data_Quality_Report.docx`, และ Notebook สำหรับประมวลผล

---
**จัดทำโดย:** Pannakorn Polasen 67160352
