## code
 * git branch -a  

 * git checkout -b dev ทำการสร้างบันชื่อdev
 
* echo "Commads" > README.md เขียนข้อความลงให้ไฟล์

* git add . เพื่อติดตามตามความเปลี่ยนแปลงของไฟล์ทั้งหมด

 * git commit -m "commit"ใช้เพื่อบันทึกความเปลี่ยนแปลงที่เกิดขึ้นสู่ local repo
 
* git push -u origin feature คำสั่งเพื่อส่งการเปลี่ยนแปลงของ master ที่ต้องการไปยัง remote repository

 * git merge --no-ff feature ทำได้เมื่ออยู่ที่master เป็นการทำให้เชื่อต่อบนเส้นเดียวกัน
