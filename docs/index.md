# Welcome to Arduitronicshub  
## ศูนย์กลางคู่มือบอร์ด Grove Beginner Kit for Arduino ([GK00001](www.arduitronics.com/product/3553)) โดย [Arduitronics.com](www.arduitronics.com)

## ภาพรวมอุปกรณ์
![Screenshot](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/Parts.jpg)

<b>ขนาดของอุปกรณ์</b> - 17.69 * 11.64 * 1.88cm  
1. [<b>Grove - Led</b>](https://www.arduitronics.com/product3565): โมดูลแอลอีดีพร้อมใช้งานได้สะดวก  <br/>
2. [<b>Grove - Buzzer</b>](https://www.arduitronics.com/product/3566): โมดูลบัซเซอร์ (buzzer) <br/>
3. <b>Grove - OLED ขนาด 0.96 นิ้ว</b>: โมดูล OLED ขนาด 0.96 นิ้ว <br/>
4. [<b>Grove - ปุ่มกด</b>](https://www.arduitronics.com/product/3578): โมดูลปุ่มกด (buzzer) <br/>
5. [<b>Grove - Rotary Potentiometer</b>](https://www.arduitronics.com/product/3562): โมดูลตัวต้านทานปรับค่าได้แบบหมุน <br/>
6. [<b>Grove - Sound sensor</b>](https://www.arduitronics.com/product/3563): โมดูลวัดเสียง <br/>
7. [<b>Grove - Light Sensor </b>](https://www.arduitronics.com/product/3564): โมดูลวัดค่าแสง <br/>
8. [<b>Grove - Temperature and Humidity sensor</b>](https://www.arduitronics.com/product/3571): โมดูลวัดอุณหภูมิและความชื้น<br/>
9. <b>Grove - Air Presure sensor</b>: โมดูลวัดความดันอากาศ <br/>
10. <b>Grove - 3-Axis Accelerator</b>: โมดูลวัดความเร่งของวัตถุ <br/>
11. <b>Seeeduino Lotus</b>: บอร์ด Arduino ของ Seeed studio ซึ่งมาพร้อมกับพอร์ดของ Grove <br/>  

<b>หมายเหตุ</b>  อุปกรณ์ต่างๆ บนบอร์ดได้มีการต่อเชื่อมกับบอร์ด Seeeduino Lotus แล้วด้วยลายวงจรบนบอร์ด ดังนั้นไม่จำเป็นต้องเชื่อมต่อวงจรด้วยสายเคเบิ้ลของ Grove หากยังไม่ได้แยกอุปกรณ์ออกเป็นชื้นย่อยๆ  

ตำแหน่งการเชื่อมต่อบนลายวงจรมีดังต่อไปนี้  


| โมดูล   |     วิธีการต่อเชื่อม      |  ตำแหน่ง Pin /แอดเดรส |
|:----------:|:-------------:|:------:|
| LED                           | Digital | D4                                  |
| Buzzer                        | Digital | D5                                  |
| OLED Display 0.96"            | I2C     | I2C, 0x78(default)                  |
| Button                        | Digital | D6                                  |
| Rotary Potentiometer          | Analog  | A0                                  |
| Light                         | Analog  | A6                                  |
| Sound                         | Analog  | A2                                  |
| Temperature & Humidity Sensor | Digital | D3                                  |
| Air Pressure Sensor           | I2C     | I2C, 0x77(default) / 0x76(optional) |
| 3-Axis Accelerator            | I2C     | I2C, 0x19(default)                  |

<br/>
**ข้อแนะนำในการตัดแยกโมดูลเป็นชิ้นย่อยๆ**:*โปรดระมัดระวังในการใช้มีดตัด*
ในกรณีที่ต้องการใช้โมดูลต่างๆที่อยู่บนบอร์ดกับวงจรอื่นๆ สามารถใช้คัตเตอร์หรือมีดเพื่อตัดแยกแต่ละโมดูลออกจากกัน <br/>


**ขั้นตอนที่ 1**

ใช้คัดเตอร์หรือมีดกรีดที่รอยบากของวงจรที่ทำไว้ให้

**ขั้นตอนที่ 2**

ค่อยๆ โยกแผ่นวงจรย่อยของโมดูลเพื่อให้หลุดออกจากกัน

## รายการอุปกรณ์

| Modules                        | Quantity |
|--------------------------------|:----------:|
| Sensors                        |          |
| Temperature & Humidity Sensors | x1       |
| 3-Axis Accelerometers          | x1       |
| Air Pressure                   | x1       |
| Light Sensor                   | x1       |
| Sound Sensor                   | x1       |
| Input Modules                  |          |
| Rotary Potentiometer           | x1       |
| Button                         | x1       |
| Output Modules                 |          |
| LED                            | x1       |
| Buzzer                         | x1       |
| Display Module                 |          |
| OLED Display                   | x1       |
| Grove Cables                   | x6       |
| Micro USB Cable                | x1       |

## <br>เป้าหมายการเรียนรู้
* พื้นฐานการใช้งานอุปกรณ์และระบบที่ใช้ซอฟต์แวร์โอเพนซอร์ซ
* พื้นฐานการโปรแกรมบอร์ดตระกูล Arduino
* หลักการสื่อสารระหว่างบอร์ดกับเซนเซอร์
* การลงมือทดลองใช้งานอุปกรณ์และซอฟต์แวร์โอเพนซอร์ซ

## เสียบสาย USB และดูการสาธิตการทำงาน
บอร์ดรุ่น Grove Kit [(GK00001)](https://www.arduitronics.com/product/3553) มาพร้อมกับโปรแกรมที่ลงไว้จากโรงงาน โดยมีการสาธิตการทำงานของเซนเซอร์บนโมดูลต่างๆ  เพียงแค่แกะกล่องและเสียบสาย UBS ก็สามารถทดลองใช้งานเซนเซอร์ต่างๆได้  คุณสามารถเลือกการทำงานและปรับเปลี่ยนค่าเซนเซอร์ต่างๆบนบอร์ดได้โดยการใช้ปุ่มกด และโมดูลตัวต้านทานปรับค่าได้แบบหมุน <br/>

![](https://s3-us-west-2.amazonaws.com/files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/Firmware.jpg)

- **Scroll** -> ตัวต้านทานปรับค่าได้แบบหมุน (Rotating Rotary Potentiometer)
- **Select** -> กดปุ่มสั้นๆแล้วปล่อย
- **Exit Current Demo** -> กดปุ่มค้างแล้วปล่อย

บัซเซอร์และแอลอีดีใช้แสดงความพร้อมรอรับคำสั่ง

## เริ่มต้นการใช้งาน Arduino ได้อย่างไร

### การติดตั้ง Arduino IDE

- **Arduino IDE** คือ ซอฟแวร์ที่รวบรวมเครื่องมือต่างๆ (การติอต่อกับ ฮาร์ดแวร์  การ Compile โปรแกรม  Editor ที่ใช้ในการเขียน Skecth  การทดสอบการทำงานของโปรแกรมที่พัฒนาขึ้นบนบอร์ด) ซื่งจำเป็นที่ต้องใช้ในการพัฒนาระบบไมโครคอนโทรลเลอร์
- สามารถดาว์นโหลดโปรแกรม Arduino IDE [ได้ที่](https://www.arduino.cc/en/Main/Software) โดยตุณสามารถเลือกใช้ตาม OS ของคุณ

![](https://files.seeedstudio.com/wiki/Seeeduino_Stalker_V3_1/images/Download_IDE.png)


### การติดตั้งไดรเวอร์ของพอร์ต USB

- บอร์ด Arduino ติดต่อกับเครื่องพีซีผ่านเคเบิ่ลที่ใช้หัว USB รุ่นต่างๆ   ซึ่งไดรเวอร์ของหัว USB ที่ต้องติดตั้งนั้น ขึ้นกับชนิดของ Chip ที่ใช้บนบอร์ด Arduino ของคุณ  *หมายเหตุ: โดยปกติแล้วชนิดของชิบ USB จะถูกระบุไว้บนด้านหลังของตัวบอร์ด*
- ดาวน์โหลด [ไดรเวอร์ของ USB รุ่น CP2102](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers). **หมายเหตุ:** โปรดเลือกตาม OS ที่คุณใช้
- หลังจากติดตั้งไดรเวอร์สำเร็จแล้ว  ให้ต่อบอร์ด Arduino โดยใช้สายแลหัวต่อ USB เข้ากับเครื่องคอมพิวเตอร์
  - **สำหรับผู้ใช้ระบบปฏิบัติการ Windows** คุณสามารถดูพอร์ตที่ติดตั้งได้จาก 'My Computer' -> `Properties` -> `Hardware` -> `Device Management`  จะเห็น 'COM' และตัวเลขแสดงพอร์ต
  -  **สำหรับผู้ใช้ Mac OS**  คุณสามารถดูพอร์ตที่ติดตั้งได้จาก `` ที่มุมบนด้านซ้าย และเลือก `About this Mac` -> `System Report...` -> `USB`. จะเห็น CP2102 USB Driver
- กรณีที่ยังไม่ได้ติดตั้งไดรเวอร์  หรือ ติดตั้งไม่ถูกต้องกับ Chip ที่ใช้  จะเห็น "unknown device" ใน device manager  ให้ติดตั้งไดรเวอร์ใหม่

### เริ่มต้นใช้งาน Arduino IDE  

1. เปิดโปรแกรม **Arduino IDE** บนเครื่อง PC ของคุณ
2. คลิ๊กเลือก `Tools` -> `Board` เพื่อเลือกชนิดของบอร์ด  และเลือก **Arduino/Genuino Uno** เป็นบอร์ดที่คุณใช้<br/>
![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/board.png)<br/>
3. คลิ๊ก `Tools` -> `Port` เพื่อเลือก Port ที่ถูกต้อง (เลือกให้ตรงกับ Port ที่แสดงไว้ในขั้นตอนก่อนหน้า).  ในตัวอย่างนี้เลือก `COM6`  
  **สำหรับผู้ใช้ Mac OS** จะเป็น `/dev/cu.SLAB_USBtoUART`.
![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/port.png)<br/>
4. สร้างไฟล์ใหม่และใช้ชื่อ `Hello.ino` จากนั้น copy โปรแกรมไปไว้ในไฟล์ที่สร้าง:<br/>
``` cpp linenums="1"
void setup() {
  Serial.begin(9600); // initializes the serial port with a baud rate of 9600
}
void loop() {
  Serial.println("hello, world"); // prints a string to a serial port
  delay(1000); //delay of 1 second
}
```
5. ที่มุมด้านซ้ายบนของ Arduino IDE จะมีปุ่ม 2 ปุ่มได้แก่ **Verify and Upload**  ปุ่มแรก (✓) กดเพื่อคอมไพล์ หลังจากที่คอมไพล์ผ่านแล้วให้กดปุ่มอัพโหลดโปรแกรม (→)<br/>
![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/func.png)<br/>
6. ไปที่เมนู `Tools` -> `Serial Monitor` หรือกดปุ่ม **Serial Monitor** ที่มุมขวาบน (รูปแว่นขยาย) คุณสามารถดูหน้าจอแสดงผลการทำงานของโปรแกรม:<br/>
![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/print.png)<br/>
**หมายเหตุ:** หากคุณติตตั้งโปรแกรมของเราจาก [USB drive ของ Seeeddtudio](https://www.seeedstudio.com/4GB-Plug-and-Go-USB-Flash-Driver-for-Grove-Beginner-Kit-All-Resources-Included-p-4547.html) , จะมี  **Files** -> **Sketch Book**, ไลบรารี่ทั้งหมดที่ต้องใช้
![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/Sketchbook.png)  
<br/>
**หมายเหตุ:**  
        โมดูลทุกตัวบนบอร์ดได้ถูกเชื่อมต่อบน PCB เข้ากับ Seeeduino ไว้แล้ว ไม่จำเป็นต้องต่อสาย หรือ บัดกรีเพิ่มเติม   อย่างไรก็ตามหากคุณได้ตัดแยกชิ้นออกจากกัน และต้องการทดลองโดยต่อสายเคเบิ้ล  โปรดศึกษาคู่มือการใช้งานของแต่ละโมดูล
<br/>
## เนื้อหาบทเรียน
<br/>
### บทเรียนที่ 1: ไฟแอลอีดีกระพริบ
<br/>
เราได้ทดลองโปรแกรม "Hello world" ไปแล้วก่อนหน้านี้  ตอนนี้เรามาทดลองการสั้งให้โมดูลแอลอีดีแสดงการกระพริบกัน   เราได้รู้จักองค์ประกอบพื้นฐานของการควบคุม ได้แก่ อินพุท การควบคุม และ เอาท์พุท  ในตัวอย่างแอลอีดีกระพริบนี้ จะเป็นการสั่งผ่านเอาท์พุทเท่านั้น ไม่มีการรับค่าอินพุท  โดยมี Seeeduino เป็นตัวควบคุมการทำงาน และแอลอีดีเป็นเอาท์พุท และสัญญาณที่ใช้เป็นสัญญาณดิจิทัล  การส่งสัญญาณในระดับ "สูง" จะทำให้แอลอีดีติดสว่าง<br/>  
<font size=5;font color=#314B9F >ข้อมูลประกอบพื้นฐาน:</font>  

- **สัญญาณดิจิทัลคืออะไร?**

**สัญญาณดิจิทัล:** เป็นสัญญาณที่มีระดับแอมพลิจูดเป็นระดับไม่ต่อเนื่อง (Discrete) ค่าแอมพลิจูดมีระดับที่ตายตัว เลือกไว้แล้ว   ในการใช้งานกับบอร์ดควบคุมของเรา สัญญาณดิจิทัลถูกกำหนดให้มีค่าเป็น 2 ระดับ คือ 0 โวลต์ (ระดับต่ำ หรือ 0) และ 5 โวลต์ (ระดับสูง หรือ 1)  
![Alt text](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/digital.png)  
- <font size=5;font color=#314B9F >อุปกรณ์ที่ต้องใช้ (มีให้ในชุด [GK00001](https://www.arduitronics.com/product/3553))</font>  

1. บอร์ด Seeeduino Lotus  
2. Grove LED  
3. Grove Cable (หากแยกโมดูลเซนเซอร์ออกจากตัวบอร์ด)  

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/LED.png)

- <font size=5;font color=#314B9F>การเชื่อมต่อฮาร์ดแวร์</font>

    - **เชื่อมต่อโมดูล**  
        - ต่อไว้แล้วโดยการเชื่อมต่อบนบอร์ด (ไม่ต้องทำอะไรเพิ่ม) หรือ  
        - เชื่อมต่อโดยใช้เคเบิ้ล  

- <font size=5;font color=#314B9F >ซอฟแวร์ที่ใช้</font>  
        - เปิดโปรแกรม Arduino IDE <br/>
        - Copy โปรแกรมต่อไปนี้ เลือก Verify เพื่อตรวจสอบว่าทำงานได้หรือไม่ มีข้อผิดพลาดหรือไม่ จากนั้น Upload โปรแกรมลงที่บอร์ด



``` cpp linenums="1"
//LED Blink
//The LED will turn on for one second and then turn off for one second
int ledPin = 4;
void setup() {
  pinMode(ledPin, OUTPUT);
  }
void loop() {
  digitalWrite(ledPin, HIGH);
  delay(1000);
  digitalWrite(ledPin, LOW);
  delay(1000);
  }
```


- <font size=5;font color=#314B9F >อธิบายการทำงานของโค้ด</font>

``` cpp linenums="1"
setup(){  
}
```

ทุกครั้งที่เริ่มต้นการทำงาน sketch ฟังก์ชั่น `setup()` จะถูกเรียกเพื่อทำงานก่อนเป็นลำดับแรก  ซึ่งจะรวบรวมส่วนที่เป็นการกำหนดค่าตัวแปร และค่าเริ่มต้นต่างๆ  การกำหนดโหมดการทำงานของ pin ที่ใช้  การเรียกใช้ Library เป็นต้น  ฟังก์ชั่น `setup()` จะทำงานเมื่อเริ่มต้นเพียงครั้งเดียวหลังจากที่จ่ายไฟเลี้ยงให้วงจร หรือ กดปุ่ม reset บนตัวบอร์ด

```cpp linenums="1"
loop(){
}
```
หลังจากสร้างฟังก์ชั่น `setup()`ซึ่งจะตั้งและกำหนดค่าเริ่มต้น จากนั้นฟังก์ชั่น `loop()` จะทำงานวนลูปอย่างต่อเนื่อง ซึ่งจะทำงานตามโปรแกรมที่เขียนไว้เพื่อควบคุมการทำงานของบอร์ด

```cpp linenums="1"
int ledPin = 4;
```
<br/>
**ลักษณะการทำงาน:**  
&emsp;แปลงค่าให้เป็นตัวแปรชนิด int

**Syntax:**  
&emsp; int(**x**) or (int)**x** (C-style type conversion)

**พารามิเตอร์:**  
&emsp; **x**: ตัวแปรที่ต้องการแปลงค่า  สามารถเป็นตัวแปรชนิดใด้ก็ได้


กำหนดค่าตัวแปรชนิดจำนวนเต็ม (integer) ให้มีค่าเท่ากับ 4 ในชื่อตัวแปร ledPin

```cpp linenums="1"
pinMode(ledPin, OUTPUT);
```
<br/>
**ลักษณะการทำงาน:**

&emsp;กำหนดให้โหมดการทำงานของ pin มีลักษณะเป็นอินพุต หรือ เอาท์พุต  โปรดศึกษารายละเอียดการทำงานของ pin แบบดิจิทัลในรูปแบบต่รุ่นต่างๆ  

ตั้งแต่ Arduino 1.0.1 ตัวต้านทานภายในแบบพูลอัพ (pull-up resistor) สามารถเลือกได้โดยกำหนดเป็น `INPUT_PULLUP`  นอกจากนี้หากต้องการกำหนดให้ "ไม่ต้องใช้" "ตัวต้านทานภายนในแบบพูลอัพ สามารถทำได้โดยกำหนดเป็น `INPUT`

**Syntax:**

&emsp;pinMode(**pin, mode**)

**พารามิเตอร์:**

&emsp; **pin**: คือ หมายเลข pin ของบอร์ดที่ต้องการกำหนดโหมดการทำงาน

&emsp; **mode**: `INPUT`, `OUTPUT`, หรือ `INPUT_PULLUP`.

กำหนด ledPin เป็นโหมดการทำงานแบบ output

```cpp linenums="1"  
digitalWrite(ledPin, HIGH);
```
<br/>
**ลักษณะการทำงาน:**

กำหนดค่า `HIGH` หรือ `LOW` ให้ pin แบบดิจิทัล
เมื่อ pin ถูกกำหนดโหมดเป็น OUTPUT โดยใช้ pinMode()  แรงดันจะมีค่า 5 V เมื่อกำหนดแบบ `HIGH` (หรือ 3.3 V บนบอร์ดที่มีแรงดันทำงานที่ 3.3 V เช่น NodeMCU) หรือ 0 V (กราวด์) เมื่อกำหนดแบบ `LOW`  

หาก pin ถูกกำหนดให้ใช้โหมด INPUT สามารถใช้คำสั่ง digitalWrite() เพื่อกำหนดให้มีแรงดันแบบ HIGH หรือ LOW  &emsp; ทั้งนี้แนะนำให้ใช้ pinMode() โดยกำหนด  `INPUT_PULLUP` เพื่อกำหนดใช้ตัวต้านทานภายในแบบพูลอัพ

หากยังไม่ได้กำหนด pinMode() เป็น OUTPUT แต่ได้ต่อหลอดแอลอีดีไว้ที่ pin &thinsp; เมื่อเลือก digitalWrite(HIGH) หลอดแอลอีดีอาจจะสว่างไม่เต็มที่ และหากไม่ได้กำหนด pinMode() ไว้ digitalWrite() จะกำหนดให้ตัวต้ตัวต้านทานภายในแบบพูลอัพทำงาน ซึ่งจะทำหน้าที่เหมือนตัวต้านทานที่จำกัดการไหลของกระแสขนาดใหญ่ (current-limiting resistor)

<br/>
**ลักษณะการทำงาน:**  
&emsp;digitalWrite(**pin, value**)  


**พารามิเตอร์:**  
&emsp;**pin**: หมายเลข pin บนบอร์ด Arduino  
&emsp;**value**: `HIGH` or `LOW`.

เมื่อกำหนดให้ ledPin ทำงานเป็น output  การกำหนดให้มีค่า HIGH จะทำให้หลอดแอลอีดีสว่าง

```cpp linenums="1"
digitalWrite(ledPin, LOW);
```
เมื่อกำหนดให้ ledPin ทำงานเป็น output  การกำหนดให้มีค่า LOW จะทำให้หลอดแอลอีดีดับ

```cpp linenums="1"
delay(1000);
```
<br/>
**ลักษณะการทำงาน:**  
&emsp;หยุดการทำงานของโปรแกรมตามระยะเวลาที่กำหนดค่าพารามิเตอร์เป็นมิลลิวินาที (1000 มิลลิวินาทีเท่ากับ 1 วินาที)  

**Syntax:**  

&emsp;delay(**ms**)  

**พารามิเตอร์:**

&emsp;**ms**: ตัวเลขกำหนดเวลาหน่วยมิลลิวินาที (ms): ตัวแปรชนิด unsigned long

หน่วงเวลา 1000 ms หรือ 1 วินาที  

**ผลการทำงานและการแสดงผลคำสั่ง serialPrint:**

&emsp;โมดูลหลอดแอลอีดีจะติดสลับกับดับอย่างละ 1 วินาที  


<br/>
**การปรับค่าความสว่างของหลอดแอลอีดี:**


<div align=center><img src="https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/LED-res.jpeg"/></div>
</br>

บนตัวโมดูลหลอดแอลอีดีจะมี **ตัวต้านทานปรับค่าได้ซึ่งต้องปรับค่าโดยใช้ไขควงปากแฉก** การบิดปรับค่าจะทำให้หลอดแอลอีดีสว่างขึ้น!  

<br/>
- <font size=5;font color=#314B9F >เมื่อแยกโมดูลหลอดแอลอีดีออกจากตัวบอร์ดแล้ว</font>

ในกรณีที่ได้ตัดแยกโมดูลออกจากตัวบอร์ด Grove Beginner Kit แล้ว ให้ใช้สายเคเบิ้ลของ Grove เพื่อต่อเชื่อมระหว่าง **โมดูลหลอดแอลอีดี** กับบอร์ด Seeeduino Lotus ที่ตำแหน่ง pin **D4**

*******


### บทเรียนที่ 2: การใช้ปุ่มเพื่อควบคุมหลอดแอลอีดี  

ก่อนอื่นต้องเข้าใจว่าสัญญาณขาเข้าจากปุ่มกดมีลักษณะเป็นสัญญาณดิจิทัล และมี 2 สถาวะ ได้แก่ 0 หรือ 1  ดังนั้นเราจึงต้องควบคุมการทำงานของเอาท์พุตต่างๆ จากปุ่มกดโดยเลือกจากสภาวะการทำงานเหล่านี้ <br/>  


**การปฏิบัติในบทเรียนนี้:** ใช้ปุ่มกดเพื่อเปิด และปิด โมดูโมดูลหลอดแอลอีดี  <br/>  

<font size=5;font color=#314B9F >อุปกรณ์ที่ต้องใช้ (มีให้ในชุด [GK00001](https://www.arduitronics.com/product/3553))</font>  

1. Seeeduino Lotus
1. โมดูโมดูลหลอดแอลอีดี
1. โมดูลปุ่มกด
1. สายเคเบิ้ล (หากแยกโมดูลเซนเซอร์ออกจากตัวบอร์ด)

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/Button.png)

- <font size=5;font color=#314B9F >การต่อเชื่อมฮาร์ดแวร์</font>  
    - **การต่อกับโมดูล:**
        - โมดูลถูกต่อเชื่อมไว้ด้วยลายวงจรบนบอร์ดอยู่แล้ว  
        - บอร์ด Seeeduino เชื่อมต่อเข้ากับ PC โดยใช้สาย USB ที่ให้ในชุด  

    - **รายละเอียดการใช้ฮาร์ดแวร์**:
        - Input: ปุ่มกด
        - Control: บอร์ด Seeeduino
        - Output: โมดูลหลอดแอลอีดี

ทั้งเซนเซอร์และหลอดแอลอีดีใช้งานกับสัสัญญาณดิจิทัล ดังนั้นต่อเชื่อมต่อโดยใช้โหมดดิจิทัล

- **ซอฟแวร์ที่ใช้**:
      - เปิด Arduino IDE.
      - ก็อบปี้โปรแกรมด้านล่างนี้ จากนั้นคลิ๊กปุ่ม Verify &emsp; เมื่อ Arduino IDE แสดงว่าไม่มีข้อผิดพลาด  ให้ Upload โปรแกรมลงที่บอร์ด

``` cpp linenums="1"
//Button to turn ON/OFF LED
//Constants won't change. They're used here to set pin numbers:
const int buttonPin = 6;     // the number of the pushbutton pin
const int ledPin =  4;      // the number of the LED pin
// variables will change:
int buttonState = 0;         // variable for reading the pushbutton status

void setup() {
    // initialize the LED pin as an output:
    pinMode(ledPin, OUTPUT);
    // initialize the pushbutton pin as an input:
    pinMode(buttonPin, INPUT);
}

void loop() {
// read the state of the pushbutton value:
buttonState = digitalRead(buttonPin);

// check if the pushbutton is pressed. If it is, the buttonState is HIGH:
if (buttonState == HIGH) {
// turn LED on:
digitalWrite(ledPin, HIGH);
} else {
// turn LED off:
digitalWrite(ledPin, LOW);
      }
}
```



- <font size=5;font color=#314B9F >วิเคราะห์การทำงานของโปรแกรม</font>

```cpp
pinMode(ledPin, OUTPUT);
```

กำหนดให้หลอดแอลอีดีเป็นโหมด output

```cpp
pinMode(buttonPin, INPUT);
```

กำหนดให้ปุ่มกดเป็นโหมด Input


```cpp
buttonState = digitalRead(buttonPin);
```

<br/>
**ลักษณะการทำงาน:**

&emsp;อ่านค่าจากดิจิทัล pin ซึ่งจะมีค่าเป็น `HIGH` หรือ `LOW`.

**Syntax:**

&emsp;digitalRead(**pin**)

**Parameters:**

&emsp;**pin**: หมายเลข `pin` ที่ต้องการอ่านค่า

<br/>
ใช้ฟังก์ชั่นนี้เพื่ออ่านค่อ่านค่าจากดิจิทัล pin ซึ่งมีค่า HIGH หรือ LOW เมื่อมีการกดปุ่ม จะได้สถาวะ HIGH  ถ้าไม่กดจะเป็น LOW

```cpp
  if (buttonState == HIGH) {
    digitalWrite(ledPin, HIGH);
  } else {
    digitalWrite(ledPin, LOW);
  }
}
```

<br/>
**ลักษณะการทำงาน:**
&emsp;การใช้ if...else ทำให้การควบคุมการทำงานได้มากกว่าการใช้ If เพียงอย่างเดียว &emsp; นอกจากนี้ยังสามารถทดสอบเงื่อนไข (condition) การทำงานได้หลายเงื่อนไข โดยใช้ else if...  และหากไม่ตรงกับเงื่อนไขที่กำหนดไว้ใน if... และ else if...เลย จึงจะทำงานโดยโปรแกรมส่วนที่เขียนใน else ...

&emsp;การตรวจสอบเงื่อนไขแต่ละส่วนจะดำเนินไปตามลำดับ หากเงื่อนไขที่กำหนดไว้ไม่เป็นจริง (False) จะข้ามโปรแกรมในส่วนนั้นไป  และวนทำจนกว่าจะพบกับเงื่อนไขที่เป็นจริง (True) จากนั้นจะ run ตามเงื่อนไขในส่วนที่ต่อท้าย if() หรือ else if () นั้น หากไม่พบเงื่อนไขใดเลยที่เป็นจริง จะไป run ในส่วน else()

&emsp;ข้อสังเกตคือ การใช้งาน if()...else() นั้นสามารถเลือกลงท้ายด้วยการใช้ else() หรือ else if() เป็นท่อนสุดท้ายได้   และสามารถใช้ if... และตามด้วย else if() ได้โดยไม่จำกัดจำนวนครั้ง


**Syntax:**

```cpp
if (condition1) {
// do Thing A
}
else if (condition2) {
// do Thing B
}
else {
// do Thing C
}
```

&emsp;การใช้งานเงื่อนไขแบบ if ทำงานดังนี้:  หากเงื่อนไขที่กำหนดในวงเล็บหลัง **if(...)** "เป็นจริง" โปรแกรมในช่วงวงเล็บปีกกา {...} จะทำงาน   &emsp;หาก "เป็นเท็จ" โปรแกรมในช่วง **else(...)** จะทำงาน  &emsp;ดังนั้นจากเงื่อนไขในโปรแกรมที่เขียน ถ้าสภาวะของปุ่มกดเป็น HIGH จะทำให้ pin ที่ทำงานของหลอดแอลอีดีเป็น HIGH ด้วย หลอดจแอลอีดีจะสว่าง และในทางตรงข้าม หากสภาวะของปุ่มกดเป็น LOW หลอดแอลอีดีก็จะดับ


**ผลการทำงานของบอร์ด และการแสดงใน Serial Print**

&emsp;เมื่อกดปุ่ม หลอดแอลอีดีจะติดสว่าง

- <font size=5;font color=#314B9F >หากตัดแยกโมดูลออกจากบอร์ดแล้ว</font>

กรณีที่ได้ตัดแยกโมดูลออกจากตัวบอร์ด Grove Beginner Kit แล้ว ให้ใช้สายเคเบิ้ลของ Grove เพื่อต่อเชื่อมระหว่าง โมดูลหลอดแอลอีดี กับบอร์ด Seeeduino Lotus ที่ตำแหน่ง pin **D4**  และต่อเชื่อมกับปุ่มกดที่ตำแหน่ง pin **D6**







### บทเรียนที่ 3: การควบคุมความถี่ของการกระพริบ  

<br/>
ในบทเรียนที่แล้ว เราได้ศึกษาการทำงานของปุ่มกด ซึ่งมีสภาวะการทำงานเพียง 2 แบบ คือ เปิด/ปิด ซึ่งมีค่าแรงดันเป็น 5 V หรือ 0 V &emsp;อย่างไรก็ตามในทางปฏิบัติเรามักต้องการใช้งานสภาวะที่หลากหลายมากกว่าแค่ 0 หรือ 5 V  ดังนั้นจึงจำเป็นต้องมีการรับค่าจากสัญญาณแอนะลอก!!  และการใช้งานตัวต้านทานปรับค่าได้แบบหมุน (Rotary Potentiometer) จึงเป็นตัวอย่างที่นิยมนำมาศึกษาเพื่อเรียนรู้การทำงานของสัทั้งนี้เนื่องจากตัวต้านทานปรับค่าได้แบบหมุนสร้างสัญญาณแบบแอนะลอก  
<br/>

<font size=5;font color=#314B9F >ข้อมูลเบื้องต้น:</font>

- **สัญญาณแอนะลอกคืออะไร !!**

**สัญญาณแอนะลอกคือ:** สัญญาณที่มีค่าเปลี่ยนแปลงได้อย่าง "ต่อเนื่อง" ทั้งแอมพลิจูด ความถี่ และเฟส ตามเวลาที่เปลี่ยนผ่านไป  กล่าวอีกอย่างคือสัญญาณมีค่าเปลี่ยนไปได้แบบต่อเนื่องเมื่อเวลาเปลี่ยนไป &nbsp; ตัวอย่างของสัญญาณแอนะลอกคือ กระแสไฟฟ้า เสียง สัญญาณภาพ เป็นต้น  &nbsp; สัญญาณแบบไซนูซอยด์  สัญญาณรูปสามเหลี่ยม เป็นอีกตัวอย่างของสัญญาณแอนะลอก &nbsp; pin แบบแอนะลอกของบอร์ดไม่โครคอนโทรลเลอร์ของคุณมีค่าได้ระหว่าง 0 V ถึง 5 V โดยจะสั่งค่าได้ 1024 ขั้น ตั้งแต่ 0 ถึง 1023 &nbsp; โดย 0 หมายถึง 0 V  &nbsp;512 หมายถึง 2.5 V และ 1023 หมายถึง 5 V เป็นต้น

![Alt text](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/analog.png)




- <font size=5;font color=#314B9F >อุปกรณ์ที่ใช้</font>
    1. บอร์ด Seeeduino Lotus
    2. โมดูล Grove LED
    3. โมดูล Grove Rotary Switch
    4. ศายเคเบิ้ล (หากตัดแยกโมดูลออกจากบอร์ดแล้ว)

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/rotary.png)



- <font size=5;font color=#314B9F >การต่อเชื่อมฮาร์ดแวร์</font>  
    - **การต่อกับโมดูล:**
        - โมดูลถูกต่อเชื่อมไว้ด้วยลายวงจรบนบอร์ดอยู่แล้ว  
        - บอร์ด Seeeduino เชื่อมต่อเข้ากับ PC โดยใช้สาย USB ที่ให้ในชุด  

    - **รายละเอียดการใช้ฮาร์ดแวร์**:
        - Input: ตัวต้านทานปรับค่าได้แบบหมุน
        - Control: บอร์ด Seeeduino
        - Output: โมดูลหลอดแอลอีดี

อินพุตหรือสัญญาณขาเข้าของบอร์ดคือสัญญาณแอนะลอก  ดังนั้นจึงต้องต่อสัญญาณเข้าที่ Pin แบบแอนะลอก และโมดูลหลอดแอลอีดีต่อเชื่อมโดยใช้สัญญาณแบบดิจิทัล


- **ซอฟแวร์ที่ใช้**:
    - เปิด Arduino IDE.
    - ก็อบปี้โปรแกรมด้านล่างนี้ จากนั้นคลิ๊กปุ่ม Verify &emsp; เมื่อ Arduino IDE แสดงว่าไม่มีข้อผิดพลาด  ให้ Upload โปรแกรมลงที่บอร์ด

```Cpp linenums="1"
//Rotary controls LED
int rotaryPin = A0;    // select the input pin for the rotary
int ledPin = 4;      // select the pin for the LED
int rotaryValue = 0;  // variable to store the value coming from the rotary

void setup() {
// declare the ledPin as an OUTPUT:
pinMode(ledPin, OUTPUT);
pinMode(rotaryPin, INPUT);
}

void loop() {
// read the value from the sensor:
rotaryValue = analogRead(rotaryPin);
// turn the ledPin on
digitalWrite(ledPin, HIGH);
// stop the program for <sensorValue> milliseconds:
delay(rotaryValue);
// turn the ledPin off:
digitalWrite(ledPin, LOW);
// stop the program for for <sensorValue> milliseconds:
delay(rotaryValue);
}
```

- <font size=5;font color=#314B9F >อธิบายการทำงานของโค้ด</font>

```cpp
int rotaryPin = A0;    // select the input pin for the rotary
int ledPin = 4;      // select the pin for the LED
```
**ลักษณะการทำงาน:**  
&emsp;คุณอาจสังเกตว่าเราได้กำหนดค่าให้ rotatePin และ ledPin ด้วยวิธีที่ต่างกัน  ทั้งนี้เนื่องจากตัวต้านทานปรับค่าได้แบบหมุนสร้างสัญญาณแบบแอนะลอก (analog signal) ในขณะที่หลอดแอลอีดีควบคุมโดยใช้สัญญาณดิจิทัล  

&emsp;เพื่อ **กำหนดต่า Analog Pin**, ให้ใช้ A + หมายเลขของ Pin (เช่น `A0`).

&emsp;เพื่อ **กำหนดต่า Digital Pin**, ให้เขียนหมายเลข pin ได้เลย (เช่น `4`).

```cpp
rotaryValue = analogRead(rotaryPin);
```

**ลักษณะการทำงาน:**

&emsp;โปรแกรมด้านบนมีการอ่านค่าซึ่งกำหนดไว้จาก pin แบบแอนะลอก &ensp; โดยบอร์ดไมโครคอนโทรลเลอร์ที่คุณใช้อยู่นี้มีช่องสัญญาณ (pin) หลายช่อง  &nbsp;มีทั้ง pin ดิจิทัลและแอนะลอก  &nbsp;โดยช่องสัญญาณแบบแอนะลอกทำงานโดยแปลงค่าจากวงจรแปลง (Digital converter) แบบ 10 บิต &nbsp;นั่นหมายถึงค่าที่อ่าน หรือ ค่าที่กำหนดในโปรแกรมจะมีค่าเป็นจำนวนเต็มตั้งแต่ 0 ถึง 1023 โดยแรงดันอินพุตจะมีค่าระหว่าง 0 V และค่าแรงดันทำงานสูงสุด (Operating voltage) ของบอร์ด (5 V หรือ 3.3 V แล้วแต่ชนิดของบอร์ดที่คุณเลือกใช้) &ensp;ตัวอย่างเช่นหากคุณเลือกใช้งานบอร์ด Arduino Uno R3 แรงดันสูงสุดจะอยู่ที่ 5 V / ซึ่งแบ่งเป็น 1024 ขั้น หรือ 0.0049 โวลต์ (4.9 มิลลิโวลต์) ต่อขั้น

**Syntax:**

&emsp;analogRead(**pin**)

**พารามิเตอร์:**

&emsp;**pin**: ชื่อของ pin แบบแอนะลอก (A0 ถึง A5 บนบอร์ดส่วนใหญ่).

**ผลการทำงาน:**   
&emsp;อ่านค่าแอนะลอกจาก pin ที่กำหนด &emsp; ความละเอียดของค่าที่อ่านจะขึ้นกับตัวแปลงค่าแอนะลอกเป็นดิจิทัลซึ่งเป็นฮาร์ดแวร์ที่ฝังอยู่บนบอร์ดที่คุณใช้ โดยมีค่าได้ตั้งแค่ 0-1023 สำหรับบอร์ดที่ใช้วงจรแบบ 10 บิต หรือ 0-4095 สำหรับบอร์ดที่ใช้วงจรแบบ 12 บิต &nbsp;และใช้ชนิดของตัวแปรที่รับค่าจาก Pin เป็นแบบ int &ensp; ฟังก์ชั่นนี้ใช้อ่านค่าจาก pin แบบแอนะลอก (ในบทเรียนนี้อ่านค่าจากตัวต้านทานปรับค่าได้แบบหมุน) ซึ่งสำหรับอบอร์ดที่เราใช้นี้จะมีความละเอีดย 0~1023

```cpp
delay(rotaryValue);
```

**ฟังก์ชั่นหน่วงเวลา (Delay):** &ensp; ค่าที่กำหนดไว้ในวงเล็บคือระยะเวลาที่ต้องการหน่วงในหน่วยมิลลิวินาที &nbsp; เนื่องจากค่าที่กำหนดได้มาจากค่าที่อ่านได้จาก Pin แบบแอนะลอก ซึ่งสัมพันธ์กับการหมุนของตัวต้านทานปรับค่าได้ &nbsp; ดังนั้นช่วงเวลาที่หน่วงไว้จึงถูกควบคุมด้วยการหมุมหัวบิด (knob)


**ผลการทำงานของบอร์ด และการแสดงใน Serial Print:**

&emsp;การหมุนที่ตัวต้านทานปรับค่าได้จะเปลี่ยนแปลงความถี่ของการกระพริบของหลอดแอลอีดี

- <font size=5;font color=#314B9F >หากตัดแยกโมดูลออกจากบอร์ดแล้ว</font>

&emsp;กรณีที่ได้ตัดแยกโมดูลออกจากตัวบอร์ด Grove Beginner Kit แล้ว ให้ใช้สายเคเบิ้ลของ Grove เพื่อต่อเชื่อมระหว่าง โมดูลหลอดแอลอีดี กับบอร์ด Seeeduino Lotus ที่ตำแหน่ง pin D4 และใช้เคเบิ้ลต่อเชื่อมกับตัวต้านทานปรับค่าได้แบบหมุนเข้าที่ pin แบบแอนะลอก ช่อง **A0**  



### บทเรียนที่ 4: การทำให้บัซเซอร์ส่งเสียง

&ensp; เช่นเดียวกับการทำงานของหลอดแอลอีดี  &nbsp; โมดูลบัซเซอร์ทำงานในโหมดเอาท์พุต แต่แทนที่จะติดสว่าง ก็ส่งเสียงดัง "ตี๊ด" ซึ่งสามารถประยุกต์ใช้แจ้งเตือนได้ในหลายสถานการณ์ &nbsp; เราได้ศึกษาการใช้งานตัวต้านทานปรับค่าได้ในบทที่ผ่านมา ในบทนี้เราจะประยุกต์ใช้ตัวต้านทานปรับค่าได้ในการควบคุมระดับความดังของเสียงจากบัซเซอร์ การควบคุมนี้ต้องใช้สัญญาณ PWM (Pulse Width Modulation)!

<font size=5;font color=#314B9F >ข้อมูลเบื้องต้น:</font>

**PWM คืออะไร**  <br/>
&emsp; **Pulse Width Modulation, หรือ PWM** เป็นเทคนิคที่ใช้ในการสร้างสัญญาณแอนะลอกจากการสั่งงานแบบดิจิทัล  เนื่องจากสัญญาณจากการควบคุมแบบดิจิทัลจะมีรูปแบบเป็นคลื่นสี่เหลี่ยม (Square wave) ที่เกิดจากการเปิด/ปิด &nbsp;รูปแบบการเปิดปิดจะจำลองระดับแรงดันระหว่างระดับสูงสุด (5 V) และระดับปิด (0 V) โดยการปรับเปลี่ยนตามช่วงเวลาให้เป็นสัดส่วนระหว่างช่วงเวลาที่เปิดและปิด &nbsp; ช่วงเวลาที่สัญญาณอยู่ที่ระดับ "เปิด" คือช่วงกว้างของสัญญาณ &nbsp; และเพื่อให้เกิดระดับแรงดันที่เปลี่ยนแปลงได้แบบแอนะลอก เราจึงต้องควบคุมความกว้างของพัส (pulse width) &nbsp; ซึ่งหากมีการเปิดและปิดตามความกว้างของพัสที่กำหนดโดยมีการทำซ้ำที่รวดเร็วพอจะทำให้สัญญาณส่งผลให้อุปกรณ์ทำงานในลักษณะเดียวกับการควบคุมโดยช่องสัญญาณแบบแอนะลอก &nbsp;การใช้งาน PWM นี้เหมาะกับการใช้งานกับอุปกรณ์บางอย่าง เช่น บัซเซอร์ หลอดแอลอีดี มอเตอร์ เป็นต้น

สำหรับการทำงานของหลอดแอลอีดี เมื่อมีการปรับความกว้างของพัส จะทำให้หลอดแอลอีดีสว่างขึ้น &nbsp;สำหรับการทำงานของบัซเซอร์ เมื่อปรับความกว้างของพัสมากขึ้นจะทำให้บัซเซอร์ส่งเสียงดังขึ้น เป็นต้น

ดังที่แสดงในภาพด้านล่าง ใช้คำสั่ง `analogWrite()` เพื่อสร้างสัญญาณ PWM ยิ่งความกว้างของพัสมากขึ้น เสียงจากบัสเซอร์จะดังขึ้น


<div align=center><img src="https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/BuzzerPWM.jpg"/></div>

บนบอร์ด Seeeduino หรือบอร์ด Arduino UNO R3 จะมีช่องต่อ pin แบบดิจิทัล 6 ช่อง โดยมีสัญลักษณ ์“~” ซึ่งหมายถึงสามารถใช้งานเพื่อสร้างสัญญาณ PWM ได้ที่ช่อง: 3,5,6,9,10,11  จึงถูกเรียกว่า PWM pin


- <font size=5;font color=#314B9F >อุปกรณ์ที่ใช้</font>
    1. Seeeduino Lotus
    2. โมดูล Buzzer
    3. สายเคเบิ้ล (หากแยกโมดูลเซนเซอร์ออกจากตัวบอร์ด)

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/Buzzer.png)



- <font size=5;font color=#314B9F >การต่อเชื่อมฮาร์ดแวร์</font>  
    - **การต่อกับโมดูล:**
        - โมดูลถูกต่อเชื่อมไว้ด้วยลายวงจรบนบอร์ดอยู่แล้ว  
        - บอร์ด Seeeduino เชื่อมต่อเข้ากับ PC โดยใช้สาย USB ที่ให้ในชุด  


    - **ซอฟแวร์ที่ใช้**:
        - เปิด Arduino IDE.
        - ก็อบปี้โปรแกรมด้านล่างนี้ จากนั้นคลิ๊กปุ่ม Verify &ensp; เมื่อ Arduino IDE แสดงว่าไม่มีข้อผิดพลาด  ให้ Upload โปรแกรมลงที่บอร์ด


```Cpp linenums="1"
int BuzzerPin = 5;
int Potentiometer = A0;

void setup() {
  pinMode(BuzzerPin, OUTPUT);
  pinMode(Potentiometer, INPUT);
}

void loop() {
  int potentioValue, Value;
  potentioValue = analogRead(Potentiometer);
  Value = map(potentioValue, 0, 1023, 0, 255); //Mapping potentiometer value to PWM signal value
  analogWrite(BuzzerPin, Value);
}
```

- <font size=5;font color=#314B9F >อธิบายการทำงานของโค้ด</font>

```cpp
Value = map(potentioValue, 0, 1023, 0, 255);
```

**ลักษณะการทำงาน:**  

**Syntax:**

&emsp; map(**value, fromLow, fromHigh, toLow, toHigh**)


**Description:**

&emsp; เปลี่ยนช่วงของตัวเลขระดับหนึ่งไปเป็นอีกช่วงหนึ่ง &nbsp; จากช่วงระหว่าง **fromLow**  ถึง **fromHigh** เป็นช่วง **toLow** ถึง **toHgih**

&emsp; ทั้งนี้การทำงานของฟังก์ชั่น map() ไม่ได้มีข้อจำกัดเฉพาะช่วงที่อยู่ในค่าที่กำหนดในตัวแปรของฟังก์ชั่น เนื่องจากการทำงานนอกช่วงที่กำหนดบางครั้งอาจจะมีประโยชน์ในการสั่งการทำงานในโปรแกรมได้  &nbsp;แต่หากต้องการกำหนดให้ค่าตัวเลขอยู่ในช่วงที่กำหนด ให้ใช้พังก์ชั่น `constrain()` โดยฟังก์ชั่นนี้จะกำหนดให้ค่าที่ต่ำกว่าค่าขอบล่าง หรือ สูงกว่าค่าขอบบน อยู่ที่ขอบของช่วงที่กำหนด  

&nbsp; ข้อสังเกต:  ค่าขอบล่างของทั้งช่วง **fromLow** และ **toLow** อาจมีค่าต่ำกว่า หรือ สูงกว่าค่า **fromHigh** หรือ **toHigh** ได้ ทั้งนี้เพื่อใช้ในการกลับด้านช่วงของสัญญาณ เช่น

**y = map(x, 1, 50, 50, 1);**

หรือใช้ในฟังก์ชั่นที่ต้องการแปลงให้เป็นค่าติดลบ

**y = map(x, 1, 50, 50, -100);**

ทั้ง 2 ตัวอย่างนี้ใช้งานได้ ไม่ผิด syntax

อย่างไรก็ตามฟังก์ชั่น map() นี้จะงานกับตัวแปรแบบ int เท่านั้น ไม่สามารถใช้กับตัวเลขทศนิยมได้ เมื่อค่าที่ได้รับเป็นตัวแปรของฟังก์ชั่นมาในแบบทศนิยม  ฟังก์ชั่น map() จะปัดขึ้นให้เป็นจำนวนเต็ม


**พารามิเตอร์:**

**value**: ค่าที่ต้องการแปลงช่วง

**fromLow**: ขอบล่างของช่วงปัจจุบัน

**fromHigh**: ขอบบนของช่วงปัจจุบัน

**toLow**: ขอบล่างของช่วงใหม่ที่ต้องการปรับ

**toHigh**: ขอบบนของช่วงใหม่ที่ต้องการปรับ

ในโปรแกรมสำหรับการทดลองนี้ ใช้เพื่อปรับช่วงของตัวต้านทานปรับค่าได้ที่อ่านค่าจาก pin แบบแอนะลอก (0 ถึง 1023) ไปเป็นช่วงที่กำหนดความดังของบัซเซอร์ (0 ถึง 255)

```cpp
analogWrite(BuzzerPin, Value);
```


**ลักษณะการทำงาน:**

&emsp; การสั่งให้ค่าระดับสัญญาณแบบแอนลอกแสดงค่าที่ pin สามารถใช้ในการกำหนดความส่างของหลอดแอลอีดี หรือ การขับเคลื่อนมอเตอร์ด้วยระดับความเร็วต่างๆ &nbsp; หลังจากที่เรียกใช้ analogWrite() ช่อง pin ที่เลือกจะกำเนิดสัญญาณรูปคลื่นสี่เหลี่ยมที่มีค่าความกว้างของพัสเป็นสัดส่วนตามที่กำหนด (duty cycle) อย่างต่อเนื่อง จนกว่าจะมีการเปลี่ยนแปลง

**Syntax:**

analogWrite(**pin, value**)

**Parameters:**

**pin**:  `pin` ที่ต้องการใช้ โดยตัวแปรต้องเป็น: int.

**value**: สัดส่วนความกว้างของพัสต่อคาบ (duty cycle): มีค่าระหว่าง `0` (ระดับปิดสุด) และ `255` (ระดับเปิดสุด) โดยตัวแปรต้องเป็น: int.

กำหนดค่าตัวระดับสัญญาณแอนะลอก (PWM) ไปควบคุมบัซเซอร์


**ผลการทำงานของบอร์ด และการแสดงใน Serial Print:**

&emsp; ระดับความดังของเสียงจากบัซเซอร์จะเปลี่จนกว่าจะมีการเปลี่ยนแปลงสัมพันธ์กับการปรับค่าตัวต้านทานปรับค่าได้

&emsp;กรณีที่ได้ตัดแยกโมดูลออกจากตัวบอร์ด Grove Beginner Kit แล้ว ให้ใช้สายเคเบิ้ลของ Grove เพื่อต่อเชื่อมระหว่าง โมดูลบัซเซอร์ กับบอร์ด Seeeduino Lotus ที่ตำแหน่ง pin **D5**  

-----

- <font size=5;font color=#314B9F >การใช้งาน PWM</font>

ถึงตอนนี้เราได้เห็นการใช้งาน PWM แล้ว  ซึ่งจริงๆแล้วมันสามารถประยุกต์ใช้กับงานได้หลากหลาย อย่างไรก็ตามขอให้สังเกตว่าเราไม่สามารถใช้งานหลอดแอลอีดีบนบอร์ด Grove Beginner Kit [(GK00001)](www.arduitronics.com/product/3553) นี้ต่ออยู่ที่ pin 4 แล้วด้วยลายวงจรบนบอร์ด  ในขณะที่การใช้งาน PWM ทำได้ที่ pin 3, 5, 6, 9, 10, 11 เท่านั้น &nbsp; ดังนั้นหากคุณต้องการควบคุมโมดูลหลอดแอลอีดีด้วยสัญญาณ PWM  คุณต้องแยกโมดูลนี้ออกจากตัวบอร์ด และต่อเชื่อมฮารด์แวร์ด้วยสายเคเบิ้ล


ที่สำคัญท้ายสุด  เมื่อคุณต้องการใช้งานฟังก์ชั่น PWM คุณต้องแน่ใจว่าช่องสัญญาณ pin ที่คุณเลือกต้องมีเครื่องหมาย "~" กำกับด้วย

### บทเรียนที่ 5:  ให้ความสว่างภายนอกเป็นตัวควบคุมความสว่างของหลอดแอลอีดี

&emsp; โมดูลเซนเซอร์แสงที่ใช้ในบทเรียนนี้ ภายในประกอบด้วยตัวต้านทานปรับค่าได้ตามความเข้ม (Intensity) ของแสงภายนอก  &nbsp; ซึ่งอุปกรณ์นี้มีชื่อเรียกเป็นทางการว่า Light Dependent Resistor (LDR) หรือ ตัวต้านทานปรับค่าได้ตามความเข้มของแสง  &nbsp; ในบทเรียนนี้เราจะทดลองการเขียนโปรแกรมเพื่อควบคุมความสว่างของหลอดแอลอีดี โดยให้ความสว่างขึ้นกับระดับความสว่างของแสงภายนอก  โดยหลอดแอลอีดีจะติดสว่างเมื่ออยู่ในที่มืด และ หลอดแอลอีดีจะดับเมื่ออยู่ในที่สว่าง

ในบทเรียนต่อไปนี้เราจะใช้ Serial Monitor เพื่อสังเกตผลการทำงานของเซนเซอร์ ซึ่งจะมีการแนะนำการใช้งานเบื้องต้นดังนี้ !!!

<font size=5;font color=#314B9F >ข้อมูลเบื้องต้น:</font>

- **Serial Monitor คืออะไร**

Serial Monitor เป็นหน้าจอสำหรับแสดงผลการทำงานของบอร์ด Arduino  &nbsp;โดยเป็นการแสดงค่าที่ได้จากคำสั่งพิมพ์จากโปรแกรมเพื่อใช้รายงานผล หรือ ใช้ในการตรวจหาความผิดพลาด นอกจากนี้ยังสามารถใช้ในการส่งค่าอินพุทเพื่อให้โปรแกรมนำไปใช้งานต่อ  

ข้อสังเกต: คุณต้องเช็คให้แน่ใจว่าอัตราการส่งข้อมูล (baud rate) ตรงกับที่กำหนดไว้ในโปรแกรม

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/Serial.jpg)

คุณสามารถเปิดหน้าจอ Serial monitor ได้โดย **Tools** -> **Serial Monitor**

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/20200217144001.jpg)


- <font size=5;font color=#314B9F >อุปกรณ์ที่ใช้</font>
    1. บอร์ด Seeeduino Lotus
    2. โมดูล Grove LED
    3. โมดูลวัดค่าแสดง Grove Light Sensor
    4. เคเบิ้ล Grove Cable (ใช้กรณีที่แยกตัวโมดูลออกจากบอร์ดแล้ว)

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/Light.png)



- <font size=5;font color=#314B9F >การต่อเชื่อมฮาร์ดแวร์</font>  
    - **การต่อกับโมดูล:**
        - โมดูลถูกต่อเชื่อมไว้ด้วยลายวงจรบนบอร์ดอยู่แล้ว  
        - บอร์ด Seeeduino เชื่อมต่อเข้ากับ PC โดยใช้สาย USB ที่ให้ในชุด  

    - **โหมดการทำงานของฮาร์ดแวร์ที่ใช้ในการทดลอง:**
        - Input: โมดูลวัดค่าแสง
        - Control: บอร์ด Seeeduino Lotus
        - Output: โมดูลหลอดแอลอีดี  

    - **ซอฟแวร์ที่ใช้**:
        - เปิด Arduino IDE.
        - ก็อบปี้โปรแกรมด้านล่างนี้ จากนั้นคลิ๊กปุ่ม Verify &ensp; เมื่อ Arduino IDE แสดงว่าไม่มีข้อผิดพลาด  ให้ Upload โปรแกรมลงที่บอร์ด

```Cpp linenums="1"
// Light Switch
int sensorpin = A6; // Analog input pin that the sensor is attached to
int ledPin = 4;    // LED port
int sensorValue = 0;        // value read from the port
int outputValue = 0;        // value output to the PWM (analog out)

void setup() {
  pinMode(ledPin,OUTPUT);
  pinMode(sensorpin, INPUT);
  Serial.begin(9600);
}

void loop() {
  // read the analog in value:
  sensorValue = analogRead(sensorpin);

  Serial.println(sensorValue);

  if (sensorValue < 200) {
    digitalWrite(ledPin, LOW);
  }
  else {
    digitalWrite(ledPin, HIGH);
  }

  delay(200);
}
```

คุณสามารถอ่านค่าระดับความเข้มของแสงได้จาก **Serial Monitor** โดยไปที่ **Tools** -> **Serial Monitor**  

- <font size=5;font color=#314B9F> อธิบายการทำงานของโค้ด</font>

```cpp
Serial.begin(9600);
```


**ลักษณะการทำงาน:**

&emsp; กำหนดค่าอัตราการส่งข้อูลในหน่วยบิตต่อวินาที (baud) โดยส่งผ่านการสื่อสารแบบอนุกรม (Serial transmission) &nbsp เพื่อใช้ในการสื่อสารกับ Serial monitor ต้องแน่ใจว่าได้กำหนดค่าอัตราการส่งผ่านข้อมูล (baud rates) ไว้ตรงกับเมนูที่มุมขวาด้านล่างของหน้าจอ Serial Monitor &nbsp; คุณสามารถเลือกใช้ค่าอื่นที่เหมาะสมได้ เช่น การสื่อสารผ่าน pin 0 และ 1 เพื่อต่อเชื่อมกับอุปกรณ์ภายนอก ควรเลือกค่าอัตราการส่งข้อมูลให้เหมาะสมกับการทำงานของอุปกรณ์  

ตัวเลือกที่สามารถกำหนดได้อีกส่วนคือ parity และ Stop bit (มีไว้เพื่อตรวจสอบความถูกต้องในการส่งข้อมูลแบบอนุกรม เพื่อให้แน่ใจว่าด้านส่งและด้านรับได้ข้อมูลที่ตรงกัน --เพิ่มเติมจากผู้แปล)  โดยมีค่าตั้งต้นไว้ที่ 8 บิต ไม่มีการเช็ค parity และมีบิตที่แสดงเมื่อต้องการหยุดทำงาน (Stop bit) ยาว 1 บิต  

โปรแกรมที่ใช้ในการติดต่อกับฮาร์ดแวร์ใช้อัตราการส่งผ่านข้อมูลระหว่างกันที่ 9600


**Syntax:**

&emsp; Serial.begin(**speed**)

**พารามิเตอร์:**

&emsp; **speed**: อัตราการส่งข้อมูลมีค่าได้หลายแบบ เช่น `9600`, `115200` เป็นต้น

ในโปรแกรมนี้ต้ังค่าไว้ที่ 9600.

```cpp
Serial.println(sensorValue);
```


**ลักษณะการทำงาน:**

&emsp; แสดงค่าผ่านช่องสัญญาณแบบอนุกรม (Serial Port) ในลักษณะที่มนุษย์สามารถอ่านค่าได้เป็นตัวอักษร ASCII ตามด้วยค่าแสดงคำสั่งไปที่ต้นบรรทัด (ASCII 13 หรือ '\r') และค่าแสดงคำสั่งขึ้นบรรทัดใหม่ (ASCII 10 หรือ '\n')  ซึ่งทำงานเช่นเดียวกับคำสั่ง Serial.print()  


**Syntax:**

&emsp; Serial.println(**val**) หรือ Serial.println(**val**, **format**)

**พารามิเตอร์:**

&emsp; **val**: ค่าที่ต้องการแสดง  ชนิดข้อมูลที่ใช้: สามารถใช้ชนิดใดก็ได้

&emsp; **format**: กำหนดลักษณะตัวเลขที่ต้องการแสดง (จำนวนเต็ม) หรือ แสดงจำนวนตำแหน่งหลังทศนิยม (สำหรับเลขชนิด floating point).

ในการทดลองนี้เมื่อเปิดดู **Serial Monitor** จะแสดงค่าความสว่างที่อ่านค่าได้

**ผลการทำงานของบอร์ด และการแสดงใน Serial Print:**

&emsp; โมดูลหลอดแอลอีดีจะสว่างขึ้นถ้าอยู่ในที่มือ และจะดับเมื่อมีแสงภายนอก


- <font size=5;font color=#314B9F >Breakout Guide</font>

&emsp;กรณีที่ได้ตัดแยกโมดูลออกจากตัวบอร์ด Grove Beginner Kit แล้ว ให้ใช้สายเคเบิ้ลของ Grove เพื่อต่อเชื่อมระหว่าง โมดูลบัซเซอร์ กับบอร์ด Seeeduino Lotus ที่ตำแหน่ง pin **D4**  และต่อเชื่อมโมดูลอ่านค่าแสงไปที่ช่อง pin แบบแอนะลอก **A6**  



### Lesson 6: ความเข้มเสียงควบคุมความสว่างของหลอดแอลอีดี

&emsp; เซนเซอร์เสียงสามารถใช้ในการตรวจจับระดับความเข้มเสียงของสิ่งแวดล้อม  โดยแสดงผลเป็นความสว่างของแสงจากหลอดแอลอีดี  เราแน่ใจว่าคุณน่าจะเคยเห็นการใช้งานเสียงที่กำหนดควบคุมความสว่างของแสงมาบ้างแล้ว คราวนี้เราลองมาทำเองดูบ้าง และเช่นที่ผ่านมา การทำลองจะทำได้ไม่ยากเย็นนัก โดยใช้การพล็อตค่าใน Serial Plotter เพื่อสังเกตผลการวัดค่า  

<font size=5;font color=#314B9F >ข้อมูลเบื้องต้น:</font>

- **Serial Plotter คืออะไร**

Serial Plotter มีลักษณะการทำงานเดียวกับ Serial Monitor ที่ใช้งานในบทเรียนที่ผ่านมา  &nbsp; แต่คราวนี้แทนที่จะแสดงค่าเป็นตัวอักษร  Serial Plotter นำค่าที่ส่งมาจาก Serial Port มาพล็อตแสดงค่าเป็นกราฟตามช่วงเวลาจริงของสัญญาณที่ได้รับ  ซึ่งเป็นประโยชน์มากในการสังเกตดูการเปลี่ยนแปลงของสัญญาณ  

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/SerialPlotter.png)

คุณสามารถเปิด Serial Plotter ได้โดยคลิ็กที่ **Tools** -> **Serial Plotter**

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/serialplot.jpg)


- **การลงมือปฏิบัติ:** ความสว่างของหลอดแอลอีดีขึ้นกับความเข้มของเสียง  เมื่อไม่มีเสียง หลอดแอลอีดีจะดับ

- <font size=5;font color=#314B9F >อุปกรณ์ที่ใช้</font>
    1. บอร์ด Seeeduino Lotus
    2. โมดูล Grove LED
    3. โมดูลเซนเซอร์เสียง (Grove Sound Sensor)
    4. สายเคเบิ้ล Grove cable (ถ้าแยกตัวโมดูลออกจากบอร์ดแล้ว)

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/Sound.png)  

- <font size=5;font color=#314B9F >การต่อเชื่อมฮาร์ดแวร์</font>  
    - **การต่อกับโมดูล:**
        - โมดูลถูกต่อเชื่อมไว้ด้วยลายวงจรบนบอร์ดอยู่แล้ว  
        - บอร์ด Seeeduino เชื่อมต่อเข้ากับ PC โดยใช้สาย USB ที่ให้ในชุด  

    - **โหมดการทำงานของฮาร์ดแวร์ที่ใช้ในการทดลอง:**
        - Input: โมดูลวัดค่าแสง
        - Control: บอร์ด Seeeduino Lotus
        - Output: โมดูลหลอดแอลอีดี  

    - **ซอฟแวร์ที่ใช้**:
        - เปิด Arduino IDE.
        - ก็อบปี้โปรแกรมด้านล่างนี้ จากนั้นคลิ๊กปุ่ม Verify &ensp; เมื่อ Arduino IDE แสดงว่าไม่มีข้อผิดพลาด  ให้ Upload โปรแกรมลงที่บอร์ด  

```Cpp linenums="1"
//Sound Control Light
int soundPin = A2; // Analog sound sensor is to be attached to analog
int ledPin = 4; // Digital LED is to be attached to digital
void setup() {
  pinMode(ledPin, OUTPUT);
  pinMode(soundPin, INPUT);
  Serial.begin(9600);
}
void loop(){
  int soundState = analogRead(soundPin); // Read sound sensor’s value
  Serial.println(soundState);
  // if the sound sensor’s value is greater than 400, the light will be on.
  //Otherwise, the light will be turned off
  if (soundState > 400) {
    digitalWrite(ledPin, HIGH);
    delay(100);
  }else{
    digitalWrite(ledPin, LOW);
  }
}
```

คุณสามารถอ่านค่าความเข้มของแสงได้จาก **Serial Plotter** โดยไปที่ **Tools** -> **Serial Plotter**  

**ข้อสังเกต: คุณสามารถปรับค่าความสว่างได้ตามที่ต้องการ ขึ้นกับความสว่างของแสงในสิ่งแวดล้อม เพื่อการแสดงผลที่ชัดเจน**



- <font size=5;font color=#314B9F >อธิบายการทำงานของโค้ด</font>

```cpp
Serial.begin(9600);
```

ซอฟแวร์ทำงานบนเครื่องคอมพิวเตอร์ซึ่งสื่อสารกับบอร์ดที่ใช้ในการพัฒนาโปรแกรม  โดยมีอัตราการส่งข้อมูลที่ 9600  

```cpp
Serial.print(" ");
```
ฟังก์ชั่นนี้ใช้เพื่อกำหนดค่าให้แสดงที่ Serial Monitor  โดยค่าที่แสดงจะอยู่ระหว่างเครื่องหมาย " &emsp;   "  

```cpp
Serial.println( );
```

บรรทัดนี้แสดงค่าเหมือนด้านบน แต่ **serial.println** เป็นการสั่งให้ขึ้นบรรทัดใหม่  


```cpp
Serial.println(soundState);
```
Serial Monitor แสดงค่าที่อ่านได้จากเซนเซอร์เสียง  เมื่อคุณเปิดดู **serial monitor** คุณจะเห็นค่าที่แสดงเป็นตัวเลขที่สัมพันธ์กับค่าจากเซนเซอร์  


**ผลการทำงานของบอร์ด และการแสดงใน Serial Print:**

&emsp; โมดูลหลอดแอลอีดีจะสว่างขึ้นเมื่อมีเสียงดังจากสิ่งรอบข้าง


- <font size=5;font color=#314B9F >หากตัดแยกโมดูลออกจากบอร์ดแล้ว</font>

กรณีที่ได้ตัดแยกโมดูลออกจากตัวบอร์ด Grove Beginner Kit แล้ว ให้ใช้สายเคเบิ้ลของ Grove เพื่อต่อเชื่อมระหว่างโมดูลหลอดแอลอีดีกับบอร์ด Seeeduino Lotus ด้วย pin แบบดิจิทัล **D4** และโมดูลเซนเซอร์เสียง กับบอร์ด Seeeduino Lotus ที่ตำแหน่ง pin แบบแอนะลอก **A2**


### Lesson 7: แสดงบนจอโอแอลอีดี (OLED)






<br/>  
<br/>  
<br/>  
# ทดสอบ

$$
\frac{n!}{k!(n-k)!} = \binom{n}{k}
$$


Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit[^2].

[^1]: *Reference: [Arduino](https://www.arduino.cc/en/tutorial/PWM)*
[^2]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.


## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout แผนภาพโครงการ

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
