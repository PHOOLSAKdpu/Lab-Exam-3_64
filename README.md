1. clone project จาก repository DPU_CT519_Lab_Exam ลงมาที่เครื่อง

>> git clone https://github.com/PHOOLSAKdpu/Lab-Exam-3_64.git

2. เปิด terminal และ cd เข้าไปใน DPU_CT519_Lab_Exam/
3. ใช้คำสั่ง > docker-compose up -d

4. แก เข้าไปที่ App_2 > build dockerfile คำสั่ง >> "docker build -t my-golang-app ."

5. run container คำสั่ง >> "docker run -itd --rm --name my-running-app -p 5000:8090 my-golang-app"

6. เปิด browser 127.0.0.1:5000/index เพื่อ test ได้เลย
