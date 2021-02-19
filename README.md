# VirtualSensor
VirtualSensor เป็นโมดูลที่สร้างขึ้นจาก Xposed ซึ่งสร้างเซ็นเซอร์หลายตัวบนอุปกรณ์ที่ไม่มี ทำเซ็นเซอร์ฟิวชั่นโดยใช้ค่าจากมาตรความเร่งและเข็มทิศซึ่งเป็นข้อกำหนดหลักสองประการสำหรับโมดูลนี้

ขณะนี้มีพระปรมาภิไธยย่อเล็กย่อ 5 ตัว:
* TYPE_ROTATION_VECTOR
* TYPE_GYROSCOPE
* TYPE_GEOMAGNETIC_ROTATION_VECTOR
* TYPE_GRAVITY
* TYPE_LINEAR_ACCELERATION

Being the most useful sensor for many applications, the gyroscope is the main sensor this project is about.

## How to use
The Xposed Framework is a required dependency. Android versions from JellyBean (SDK16) up to Marshmallow (SDK23) are supported. I myself have not tested the module on versions older than Marshmallow.
Some OEMs might have made heavy enough modifications to the AOSP code to break this module, please keep that in mind.

## Bug report
Reporting bugs is very important in order for this module to work on more devices. As I do not have the ability to test it on a lot of devices, I can only rely on the community to test it and report bugs.
When submitting a bug report, please make sure to include as much information as possible. A logcat dump is often mandatory.

## License
This project is under the LGPL v.3.0 license. The license itself can be found in the LICENSE file within the project files.
