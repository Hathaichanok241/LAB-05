#ใบงานที่ 5
##เรื่อง การใช้งานคำสั่ง Console.WriteLine()
##วัตถุประสงค์
1). เพื่อให้นักศึกษาบอกวิธีการใช้คำสั่งแสดงผลบน Text Mode ในภาษา C# ได้
2). เพื่อให้นักศึกษาสามารถปรับแต่งคำสั่งแสดงผลทางหน้าจอตามต้องการได้

##ขั้นเตรียมการทดลอง
1). สร้าง Project ตั้งชื่อเป็น Lab5 เพื่อทดลองการใช้งานคำสั่ง Console.WriteLine()
ลำดับขั้นการทดลอง
(หมายเหตุ ในรูปประกอบที่มี namespace เป็น Lab4 รบกวนแก้เป็น Lab5 ด้วยครับ)
2). ทดลองเรื่องจำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()

 2.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic1.png)

  2.2). รันโปรแกรม และบันทึกผลที่ได้

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/5.1.JPG?raw=true)


 2.3). แก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 2.4). รันโปรแกรม และบันทึกผลที่ได้
 
 
 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/5.2.JPG?raw=true)


###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร
 
ตอบ ใช้งานโดยใส่ตัวเลข
 
###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย
<hr>
<hr>
<hr>
<hr>
<hr>
 
 2.5). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)

 2.6). รันโปรแกรม และบันทึกผลที่ได้


![](https://github.com/Hathaichanok241/LAB-05/blob/master/5.3.JPG?raw=true)


3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้
 
 
 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/5.4.JPG?raw=true)


###คำถาม 5.3 การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีรูปแบบการใช้งานอย่างไร
<hr>
<hr>
<hr>
<hr>
<hr>


4). ทดลองเรื่องการกำหนดรูปแบบของอาร์กิวเมนต์
  4.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic5.png)

  4.2). รันโปรแกรม และบันทึกผลที่ได้
 
 
 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/5.5.JPG?raw=true)


5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้

![](https://github.com/Hathaichanok241/LAB-05/blob/master/5.6.JPG?raw=true)



6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้


![](https://github.com/Hathaichanok241/LAB-05/blob/master/5.7.JPG?raw=true)
 
 
## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

1.  string name = "Hello";

    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
    ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.1.JPG?raw=true)
    
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
  ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.2.JPG?raw=true)
    
3.    Console.WriteLine("Hello " + "World");

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.3.JPG?raw=true)
    
4.    Console.WriteLine("Here comes a slash \\");

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.4.JPG?raw=true)
    
5.    Console.WriteLine("|{0, 10}|", 999);

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.5.JPG?raw=true)
    
6.    Console.WriteLine("|{0,-10}|", 000);

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.6.JPG?raw=true)
    
7.    Console.WriteLine("The value: {0}.", 500);

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.7.JPG?raw=true)
    
8.    Console.WriteLine("The value: {0:C}.", 500);

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.8.JPG?raw=true)
    
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.9.JPG?raw=true)
    
10.   Console.WriteLine("{0,-10:C}", 12.3456789);

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.10.JPG?raw=true)
    
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.11.JPG?raw=true)
    
12.   Console.WriteLine("{0,-10:x}", 65535);

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.12.JPG?raw=true)
    
13.   Console.WriteLine("{0,-10:X}", 65535);

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.13.JPG?raw=true)
    
14.   int i; 


      Console.WriteLine("Value\tSquared\tCubed"); 
      
      
      for(i = 1; i < 10; i++) 
      
      
       Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
          
          
   ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.14.JPG?raw=true)
    
15.    Console.WriteLine("{0:#.###}.", 1234.56789);

 ![](https://github.com/Hathaichanok241/LAB-05/blob/master/img/5.8.15.JPG?raw=true)
    

