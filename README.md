# Sentiment Analysis Model Deployment
# DataSci-MiniProject

## File
- **DataSet**: sentiment140-subset.csv
- **Colab Notebook**: 6410210311_miniproject.ipynb

## คำอธิบายโปรเจค
โปรเจคนี้เป็นการพัฒนาและประเมินโมเดลการวิเคราะห์อารมณ์ (Sentiment Analysis) โดยใช้ข้อมูลจากชุดข้อมูล Sentiment140 ซึ่งประกอบไปด้วยข้อความที่ผู้ใช้โพสต์บน Twitter พร้อมกับความรู้สึก (positive/negative) ที่เกี่ยวข้องกับข้อความนั้น โดยมีขั้นตอนการทำงานหลัก ๆ คือการเตรียมข้อมูล (Preparing Data) การเลือกโมเดล (Model Selection) การประเมินโมเดล (Model Evaluation) และการนำโมเดลไปใช้งาน (Deploy Model) โดยผ่านขั้นตอนการสร้างและประเมินโมเดลด้วย SVM, ANN, Naive Bayes, Logistic Regression, และ K-Nearest Neighbors (KNN) รวมถึงการบันทึกและใช้โมเดลที่ดีที่สุดสำหรับการทำนายความรู้สึกของข้อความใหม่ๆ

## วิธีการใช้งาน

1. **ดาวน์โหลดข้อมูล**: โปรดดาวน์โหลดชุดข้อมูล Sentiment140 และบันทึกไว้ใน Google Drive ตามที่ระบุในโค้ด
2. **รันโค้ด**: รันโค้ดที่ให้ไว้ใน Google Colab เพื่อทำการเตรียมข้อมูล, เลือกและประเมินโมเดล, และบันทึกโมเดลที่ดีที่สุด
3. **ทดสอบโมเดล**: โหลดโมเดลที่ดีที่สุดแล้วใช้ในการทำนายผลลัพธ์ของข้อความใหม่ๆ

## ความต้องการ

- Python 3.x
- Google Colab
- Google Drive
- scikit-learn
- pandas
- NLTK

## ข้อจำกัด

- ข้อมูลที่ใช้ในการฝึกและทดสอบโมเดลมาจากชุดข้อมูล Sentiment140 เท่านั้น
- การวิเคราะห์อารมณ์ในข้อความอาจมีความถี่ของคำศัพท์หรือลักษณะของข้อความที่ไม่สอดคล้องกับโมเดลที่พัฒนาขึ้น
- โมเดลที่ได้สร้างขึ้นอาจมีปัญหาในการจำแนกและทำนายข้อความที่มีความยาวหรือความซับซ้อนมากขึ้น

## การติดต่อ

<a href="https://fb.com/tortyzz" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="tortyzz" height="50" width="50" /></a>

