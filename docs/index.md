# Welcome to Arduitronicshub  
## ศูนย์กลางคู่มือบอร์ด โดย Arduitronics.com

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




### บทเรียนที่ 2: ปุ่มเพื่อควบคุมหลอดแอลอีดี  

ก่อนอื่นต้องเข้าใจว่าสัญญาณขาเข้าจากปุ่มกดมีลักษณะเป็นสัสัญญาณดิจิทัล และมี 2 สถาวะ ได้แก่ 0 หรือ 1  ดังนั้นเราจึงต้องควบคุมการทำงานของเอาท์พุตต่างๆ จากปุ่มกดโดยเลือกจากสวาวะการทำงานเหล่านี้  









$$
\frac{n!}{k!(n-k)!} = \binom{n}{k}
$$


Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit[^2].

[^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
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
