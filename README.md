
นางสาวอภิญญา เมืองพงษา 57030242

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

  2.2). รันโปรแกรม และบันทึกผลที่ได้<br>
![](https://github.com/HoneyApinya/LAB-05/blob/master/5.1.png?raw=true)<br>
<hr>
เมื่อเพิ่ม . เข้าไปในโค้ดจะทำให้เว้นบรรทัดลงมา แสดงผลออกตามบรรทัดตามที่เขียน
<hr>

 2.3). แก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 2.4). รันโปรแกรม และบันทึกผลที่ได้<br>
 
 ![](https://github.com/HoneyApinya/LAB-05/blob/master/5.2.png?raw=true)<br>
 
 ผลที่ได้คือ จะนำ 3 และ 6 มาแสดงในตำแหน่งที่ 0 และ 1 ตามลำดับที่ได้เขียนไว้



###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร<br>

   { } เป็นเครื่องหมายที่ใช้ในการแสดงตำแหน่ง 
 

###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย<br>

   ก็จะนำตัวเลขตามตำแหน่งมาแสดง เช่น {0} ก็จะนำตำแหน่งที่ 0 มาแสดง {2} ก็จะนำตำแหน่งที่ 2 มาแสดง {3} ก็จะนำตำแหน่งที่ 3 ออกมาแสดง


 
 2.5). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)

 2.6). รันโปรแกรม และบันทึกผลที่ได้<br>
 ![](https://github.com/HoneyApinya/LAB-05/blob/master/5.3.png?raw=true)<br>

จะนำค่า 6 ที่อยู่ในตำแหน่งที่ 1 ออกมาแสดงผล ใน {1} ทั้ง2 วงเล็บ
และจำนำค่า 3 ที่อยู่ในตำแหน่งที่ 2 ออกมาแสดงผลใน {2}



3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้<br>
![](https://github.com/HoneyApinya/LAB-05/blob/master/5.4.png?raw=true)<br>

  จากรูป ค่าใน {0,5} เลข 5 ในตัวที่2หลังลูกน้ำ ในวงเล็บปีกกานั้น เป็นตัวบอกว่าในบรรทัดนี้ จะต้องเว้นวรรคไปกี่วรรค ซึ่งเลข 5 คือ5วรรค


###คำถาม 5.3 การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีรูปแบบการใช้งานอย่างไร<br>
 
 { , } หลักแรกน่าจะเป็นการเว้นบรรทัด ส่วนหลักที่ 2 เป็นการเว้นวรรคว่าจะห่างจากริมสุดเท่าไหร่ 
 หรือว่าจะใช้การกด spacebar แทนก็ได้ แต่ถ้าใช้วิธีนี้จะประหยัดพื้นที่การพิมมากว่า เพราะไม่ต้องมีช่องว่างแสดงความห่าง




4). ทดลองเรื่องการกำหนดรูปแบบของอาร์กิวเมนต์
  4.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic5.png)

  4.2). รันโปรแกรม และบันทึกผลที่ได้<br>
 ![](https://github.com/HoneyApinya/LAB-05/blob/master/5.5.png?raw=true)<br>



5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้
  
  ![](https://github.com/HoneyApinya/LAB-05/blob/master/5.6.png?raw=true)

6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้<br>
  ![](https://github.com/HoneyApinya/LAB-05/blob/master/5.7.png?raw=true)

## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

```csharp
1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
    
       ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.1.png?raw=true)
       
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.2.png?raw=true)
3.    Console.WriteLine("Hello " + "World");
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.3.png?raw=true)
4.    Console.WriteLine("Here comes a slash \\");<br>
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.4.png?raw=true)
5.    Console.WriteLine("|{0, 10}|", 999);<br>
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.5.png?raw=true)
6.    Console.WriteLine("|{0,-10}|", 000);<br>
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.6.png?raw=true)
7.    Console.WriteLine("The value: {0}.", 500);<br>
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.7.png?raw=true)
8.    Console.WriteLine("The value: {0:C}.", 500);<br>
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.8.png?raw=true)
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);<br>
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.9.png?raw=true)
10.   Console.WriteLine("{0,-10:C}", 12.3456789);<br>
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.10.png?raw=true)
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);<br>
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.92.png?raw=true)
12.   Console.WriteLine("{0,-10:x}", 65535);<br>
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.922.png?raw=true)
13.   Console.WriteLine("{0,-10:X}", 65535);<br>
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.93.png?raw=true)
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); <br>
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.94.png?raw=true)         
15.    Console.WriteLine("{0:#.###}.", 1234.56789);<br>
        ![](https://github.com/HoneyApinya/LAB-05/blob/master/55.95.png?raw=true)
```
