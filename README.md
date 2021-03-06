# Quiz Game.
**Quiz Game.** เป็นเกมปริศนาทายคำ ที่เต็มไปด้วยคำถามเบสิคเกี่ยวกับ **Java Programming Language.**

> **จุดประสงค์**

- เพื่อให้ผู้ใช้งานสนุกกับการเล่นเกทปริศนาทายคำ

- เพื่อให้ผู้ใช้งานได้ความรู้เกี่ยวกับ **Java Programming Language.** เพิ่มมากขึ้น

- เพื่อฝึกให้ผู้พัฒนาโปรแกรม ได้ฝึกฝนทักษะการเขียนโปรแกรมด้วย GUI.

![1](https://user-images.githubusercontent.com/45255939/49152606-f431d680-f345-11e8-911f-32f7587151db.PNG)

_รูปร่างหน้าต่างโปรแกรม **Quiz Game.**_

> **รายละเอียดเกี่ยวกับ Quiz Game**

###### 1.หน้าหลัก
![2](https://user-images.githubusercontent.com/45255939/49168718-b6937480-f36a-11e8-9699-4f9e3b860b98.PNG)

- หมายเลข [1] ปุ่มเริ่มเกม เมื่อผู้ใช้งานกดจะเด้งไปหน้าต่อไป
```
Code ที่สำคัญคือ 

new page2().setVisible(true);
  
this.setVisible(false);

Code นี้จะช่วยให้เมื่อกดStar แล้วจะเด้งไปหน้าต่างต่อไปที่มีชื่อว่า page2

```
- หมายเลข [2] ปุ่มเกี่ยวกับ จะแสดงถึงรายชื่อผู้พัฒนาโปรแกรมนี้

- หมายเลข [3] ปุ่มปิด จะทำการปิดโปรแกรมนี้ลง
```
Code ที่สำคัญคือ 

System.exit(0);

Code นี้จะทำการปิดโปรแกรม แล้วทำการเคลียร์ข้อมูล

```
###### 2.กรอกชื่อ
![3](https://user-images.githubusercontent.com/45255939/49170450-bb5a2780-f36e-11e8-8d72-0e0e98ac4416.PNG)

- หมายเลข [1] ปุ่มที่สามารถกรอกชื่อผู้ใช้งานลงไปได้

- หมายเลข [2] ปุ่มOK จะทำการเด้งไปหน้าต่อไป แล้วมี Pop up ข้อความขึ้นโชว์
```
Code ที่สำคัญคือ 

JOptionPane.showMessageDialog(this, "Welcome to Quiz game. : " + txtName.getText());
new page3().setVisible(true);
this.setVisible(false);

Code นี้จะทำการเด้งข้อความ Welcome to Quiz game. ตามด้วยชื่อที่คุณกรอกเข้าไปใน หมายเลข[1] และทำการเด้งไปสู่หน้าเกมทายคำถามข้อที่ 1
```

- หมายเลข [3] ปุ่มย้อนกลับ จะทำการย้อนกลับไปหน้าแรก
```
Code ที่สำคัญคือ 

new page1().setVisible(true);

this.setVisible(false);

Code นี้จะทำการย้อนกลับไปหน้าแรก
```

###### 3.เกมตอบคำถาม
![4](https://user-images.githubusercontent.com/45255939/49170451-bb5a2780-f36e-11e8-99bb-addce9fdd570.PNG)

- ส่วนที่ [1] จะเป็นเกี่ยวกับคำถามในแต่ละข้อ

- ส่วนที่ [2] จะเป็นเกี่ยวกับคำตอบ 4 ตัวเลือก เลือกข้อที่คิดว่าถูกที่สุด

###### ตัวโปรแกรม Quiz game.
> ต้องมีโปรแกรม Java(TM) Platform SE binary (ที่มากับติดตั้ง Netbane ) ในการรันโปรแกรม

Link Download : [Click!](https://drive.google.com/file/d/1cetUL3qFGOJkRzhiptEho7PEJZtyXzoI/view?usp=sharing/).


## ผู้พัฒนา
> 1.นายณัฐนนท์    หารภาพ   60022662 

> 2.นายภงส์ภิฉัตร   สุเมธะ      60022156	

