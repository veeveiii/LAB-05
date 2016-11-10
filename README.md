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
<hr>
##บันทึกผล2.1
![](https://scontent.fbkk2-3.fna.fbcdn.net/v/t34.0-12/15045651_1133025086817741_630315550_n.png?oh=9cee77d46394c128a2368c635d97df0d&oe=5826D49B)
<hr>

 #บันทึกผล : จากการทดลอง เป็นการเขียนโปรแกรมด้วยประโยค Console.Writeline(); หากกดรันด้วย Clt + F5 จะได้ผลที่แสดงขึ้นมาว่า ตามข้อความภายในวงเล็บและจะทำการเว้นบรรทัดทุกประโยคที่จบคำสั่งนั้นๆ 
 
 
 2.3). แก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 2.4). รันโปรแกรม และบันทึกผลที่ได้
<hr>
##บันทึกผล2.2
![](https://scontent.fbkk2-3.fna.fbcdn.net/v/t34.0-12/15058054_1133025090151074_993660204_n.png?oh=aaeb50a353e4b982c0ff8c785e85c058&oe=58265E42)

#บันทึกผล : 
<hr>
การเขียนโปรแกรมด้วยคำสั่ง Console.WriteLine(" {0} and {1}.",3,6); จะแสดงผลออกมาคือ 3 , 6 หมายความว่า กำหนดให้ตัวแรกคือ 3 และตัวที่ 2 คือ 6 ตามลำดับ
<hr>


###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร
<hr>
ตอบ การใช้เครื่องหมาย {} คือการบอกตำแหน่งของข้อความที่อยู่หลัง {} เช่น Console.WriteLine(" {0} and {1} and {2}.",5,9,8); ก็จะแสดงผลตามลำดับคือ 5 9 8 นั่นเอง.
<hr>
###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย
<hr> ตอบ ไม่สามารถใช้ได้ เพราะ การใช้เครื่องหมาย {} เป็นการลำดับตำแหน่ง ดังนั้นจึงต้องเรียงตามลำดับเสมอ 
ดังภาพ จะแสดงให้เห็นว่าผลของการเขียนแบบข้ามจะไม่ปรากฏผลตามที่ต้องการ
![](https://scontent.fbkk2-3.fna.fbcdn.net/v/t34.0-12/15033737_1133057996814450_1338463514_n.png?oh=6e14bbffae3d72894253478303c6f2ff&oe=5826AE98)
<hr>
 
 2.5). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)

 2.6). รันโปรแกรม และบันทึกผลที่ได้
<hr>
<hr>
<hr>
<hr>
<hr>

3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้
<hr>
<hr>
<hr>
<hr>
<hr>

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
<hr>
<hr>
<hr>
<hr>
<hr>

5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้

6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้

## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

```csharp
1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
3.    Console.WriteLine("Hello " + "World");
4.    Console.WriteLine("Here comes a slash \\");
5.    Console.WriteLine("|{0, 10}|", 999);
6.    Console.WriteLine("|{0,-10}|", 000);
7.    Console.WriteLine("The value: {0}.", 500);
8.    Console.WriteLine("The value: {0:C}.", 500);
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);
10.   Console.WriteLine("{0,-10:C}", 12.3456789);
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);
12.   Console.WriteLine("{0,-10:x}", 65535);
13.   Console.WriteLine("{0,-10:X}", 65535);
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
15.    Console.WriteLine("{0:#.###}.", 1234.56789);
```
