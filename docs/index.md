# Welcome to Arduitronicshub  
## ศูนย์กลางคู่มือบอร์ด โดย Arduitronics.com

## ภาพรวมอุปกรณ์
![Screenshot](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/Parts.jpg)

<b>ขนาดของอุปกรณ์</b> - 17.69 * 11.64 * 1.88cm  
1. [<b>Grove - Led</b>](https://www.arduitronics.com/product3565): โมดูลแอลอีดีพร้อมใช้งานได้สะดวก
1. [<b>Grove - Buzzer</b>](https://www.arduitronics.com/product/3566): โมดูลบัซเซอร์ (buzzer) <br/>
1. <b>Grove - OLED ขนาด 0.96 นิ้ว</b>: โมดูล OLED ขนาด 0.96 นิ้ว <br/>
1. [<b>Grove - ปุ่มกด</b>](https://www.arduitronics.com/product/3578): โมดูลปุ่มกด (buzzer) <br/>
1. [<b>Grove - Rotary Potentiometer</b>](https://www.arduitronics.com/product/3562): โมดูลตัวต้านทานปรับค่าได้แบบหมุน <br/>
1. [<b>Grove - Sound sensor</b>](https://www.arduitronics.com/product/3563): โมดูลวัดเสียง <br/>
1. [<b>Grove - Light Sensor </b>](https://www.arduitronics.com/product/3564): โมดูลวัดค่าแสง <br/>
1. [<b>Grove - Temperature and Humidity sensor</b>](https://www.arduitronics.com/product/3571): โมดูลวัดอุณหภูมิและความชื้น<br/>
1. <b>Grove - Air Presure sensor</b>: โมดูลวัดความดันอากาศ <br/>
1. <b>Grove - 3-Axis Accelerator</b>: โมดูลวัดความเร่งของวัตถุ <br/>
1. <b>Seeeduino Lotus</b>: บอร์ด Arduino ของ Seeed studio ซึ่งมาพร้อมกับพอร์ดของ Grove <br/>  

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
ในกรณีที่ต้องการใช้โมดูลต่างๆที่อยู่บนบอร์ดกับวงจรอื่นๆ สามารถใช้คัตเตอร์หรือมีดเพื่อตัดแยกแต่ละโมดูลออกจากกัน  <br/>

**ขั้นตอนที่ 1**

ใช้คัดเตอร์หรือมีดกรีดที่รอยบากกของวงจรที่ทำไว้ให้

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

### เสียบสาย USB และดูการสาธิตการทำงาน
บอร์ดรุ่น Grove Kit (GK00001) มาพร้อมกับโปรแกรมที่ลงไว้จากโรงงาน โดยมีการสาธิตการทำงานของเซนเซอร์บนโมดูลต่างๆ  เพียงแค่แกะกล่องและเสียบสาย UBS ก็สามารถทดลองใช้งานเซนเซอร์ต่างๆได้  คุณสามารถเลือกการทำงานและปรับเปลี่ยนค่าเซนเซอร์ต่างๆบนบอร์ดได้โดยการใช้ปุ่มกด และโมดูลตัวต้านทานปรับค่าได้แบบหมุน <br/>

![](https://s3-us-west-2.amazonaws.com/files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/Firmware.jpg)

- **Scroll** -> Rotating Rotary Potentiometer
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
2. คลิ๊กเลือก `Tools` -> `Board` เพื่อเลือกชนิดของบอร์ด  และเลือก **Arduino/Genuino Uno** เป็นบอร์ดที่คุณใช้

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/board.png)

3. คลิ็ก `Tools` -> `Port` เพื่อเลือก Port ที่ถูกต้อง (เลือกให้ตรงกับ Port ที่แสดงไว้ในขั้นตอนก่อนหน้า).  ในตัวอย่างนี้เลือก `COM6`  
  **สำหรับผู้ใช้ Mac OS** จะเป็น `/dev/cu.SLAB_USBtoUART`.

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/port.png)

4. สร้างไฟล์ใหม่และใช้ชื่อ `Hello.ino` จากนั้น copy โปรกแกรมไปไว้ในไฟล์ที่สร้าง:

```Cpp
void setup() {
  Serial.begin(9600); // initializes the serial port with a baud rate of 9600
}
void loop() {
  Serial.println("hello, world"); // prints a string to a serial port
  delay(1000); //delay of 1 second
}
```

5. ที่มุมด้านซ้ายบนของ Arduino IDE จะมีปุ่ม 2 ปุ่มได้แก่ **Verify and Upload**  ปุ่มแรก (✓) กดเพื่อคอมไพล์ หลังจากที่คอมไพล์ผ่านแล้วให้กดปุ่มอัพโหลดโปรแกรม (→)

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/func.png)

6. ไปที่เมนู `Tools` -> `Serial Monitor` หรือกดปุ่ม **Serial Monitor** ที่มุมขวาบน (รูปแว่นขยาย) คุณสามารถดูหน้าจอแสดงผลการทำงานของโปรแกรม:

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/print.png)

**หมายเหตุ:** หากคุณติตตั้งโปรแกรมของเราจาก [USB drive ของ Seeeddtudio](https://www.seeedstudio.com/4GB-Plug-and-Go-USB-Flash-Driver-for-Grove-Beginner-Kit-All-Resources-Included-p-4547.html) , จะมี  **Files** -> **Sketch Book**, ไลบรารี่ทั้งหมดที่ต้องใช้

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/Sketchbook.png)

**หมายเหตุ:**  
        โมดูลทุกตัวบนบอร์ดได้ถูกเชื่อมต่อบน PCB เข้ากับ Seeeduino ไว้แล้ว ไม่จำเป็นต้องต่อสาย หรือ บัดกรีเพิ่มเติม   อย่างไรก็ตามหากคุณได้ตัดแยกชิ้นออกจากกัน และต้องการทดลองโดยต่อสายเคเบิ้ล  โปรดศึกษาคู่มือการใช้งานของแต่ละโมดูล

## เนื้อหาบทเรียน

### บทเรียนที่ 1: ไฟแอลอีดีกระพริบ

เราได้ทดลองโปรแกรม "Hello world" ไปแล้วก่อนหน้านี้  ตอนนี้เรามาทดลองการสั้งให้โมดูลแอลอีดีแสดงการกระพริบกัน   เราได้รู้จักองค์ประกอบพื้นฐานของการควบคุม ได้แก่ อินพุท การควบคุม และ เอาท์พุท  ในตัวอย่างแอลอีดีกระพริบนี้ จะเป็นการสั่งผ่านเอาท์พุทเท่านั้น ไม่มีการรับค่าอินพุท  โดยมี Seeeduino เป็นตัวควบคุมการทำงาน และแอลอีดีเป็นเอาท์พุท และสัญญาณที่ใช้เป็นสัญญาณดิจิทัล  การส่งสัญญาณในระดับ "สูง" จะทำให้แอลอีดีติดสว่าง

<font size=5;font color=#314B9F >ข้อมูลประกอบพื้นฐาน:</font>

- **สัญญาณดิจิทัลคืออะไร?**

**สัญญาณดิจิทัล:** เป็นสัญญาณที่มีระดับแอมพลิจูดเป็นระดับไม่ต่อเนื่อง (Discrete) ค่าแอมพลิจูดมีระดับที่ตายตัว เลือกไว้แล้ว   ในการใช้งานกับบอร์ดควบคุมของเรา สัญญาณดิจิทัลถูกกำหนดให้มีค่าเป็น 2 ระดับ คือ 0 โวลต์ (ระดับต่ำ หรือ 0) และ 5 โวลต์ (ระดับสูง หรือ 1)

![Alt text](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/digital.png)

- <font size=5;font color=#314B9F >อุปกรณ์ที่ต้องใช้</font>
    1. บอร์ด Seeeduino Lotus
    2. Grove LED
    3. Grove Cable (หากแยกโมดูลเซนเซอร์ออกจากตัวบอร์ด)

![](https://files.seeedstudio.com/wiki/Grove-Beginner-Kit-For-Arduino/img/LED.png)


- <font size=5;font color=#314B9F>การเชื่อมต่อฮาร์ดแวร์</font>
        - **เชื่อมต่อโมดูล** <br/>
            - ต่อไว้แล้วโดยการเชื่อมต่อบนบอร์ด (ไม่ต้องทำอะไรเพิ่ม) <br/>
            - เชื่อมต่อโดยใช้เคเบิ้ล <br/>
<br/>
- <font size=5;font color=#314B9F >ซอฟแวร์ที่ใช้</font>
        - เปิดโปรแกรม Arduino IDE <br/>
        - Copy โปรแกรมต่อไปนี้ เลือก Verify เพื่อตรวจสอบว่าทำงานได้หรือไม่ มีข้อผิดพลาดหรือไม่ จากนั้น Upload โปรแกรมลงที่บอร์ด



```cpp
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


- <font size=5;font color=#314B9F >Code Analysis</font>

```cpp
setup(){
}
```
ทุกครั้งที่เริ่มต้นการทำงาน sketch ฟังก์ชั่น `setup()` จะถูกเรียกเพื่อทำงานก่อนเป็นลำดับแรก  ซึ่งจะรวบรวมส่วนที่เป็นการกำหนดค่าตัวแปร และค่าเริ่มต้นต่างๆ  การกำหนดโหมดการทำงานของ pin ที่ใช้  การเรียกใช้ Library เป็นต้น  ฟังก์ชั่น `setup()` จะทำงานเมื่อเริ่มต้นเพียงครั้งเดียวหลังจากที่จ่ายไฟเลี้ยงให้วงจร หรือ กดปุ่ม reset บนตัวบอร์ด



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