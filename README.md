# MPU6500-HMC5983-AK8975-BMP280-MS5611-10DOF-IMU-PCB
以`MPU6500`-`HMC5983`-`AK8975`-`BMP280`-`MS5611`为传感元件的10轴IMU PCB，有三种不同尺寸的组合样式，Altium格式，可直接打样生产。
多年前的设计，丝印效果可能不是很好看，打样前建议根据个人习惯稍加修改。

个人博客，欢迎关注，更多嵌入式设计，请见CSDN：https://blog.csdn.net/Mark_md?spm=1011.2124.3001.5343

***
# V2

概述：V2版本是三个版本中的集大成者，共集成了全部5个元件的焊盘位。集成过流保护、反接保护、3.3V/5V电平转换。IIC/SPI总线，2.54插针/SH1.0接口引出方式。四周配有9mm减震球安装孔。
- 6DOF传感器：`MPU6500/6881` 兼容焊盘
- 地磁传感器：`HMC5983`-`AK8975` 共两个元件焊盘
- 气压计：`BMP280`-`MS5611` 共两个元件的焊盘（背面放置，避光、且方便垫海绵）
- 尺寸为44x44mm，实际有效面积很少，其中大部分都被四周的9mm减震球安装孔占用。
- 5V/3.3V供电，LDO使用ME6206。
- 集成过流保护、反接保护、3.3V/5V电平转换。
- 电路经多次打样实测，功能无异常，可放心使用。（建议使用V3版）

***
# V3

概述：V3继承于V2版本的设计，增加了四周的3mm固定孔，修改了AD的板框增加了3D显示的美观度。
- 电路经多次打样实测，功能无异常，可放心使用。（建议使用V3版）
- （对于对PCB体积要求不高的需求，建议使用此版本。集成的元件和功能较多，对调试比较友好。）
![image](https://github.com/ZhiliangMa/MPU6500-HMC5983-AK8975-BMP280-MS5611-10DOF-IMU-PCB/blob/main/img/IMU-V3-TOP.jpg)
![image](https://github.com/ZhiliangMa/MPU6500-HMC5983-AK8975-BMP280-MS5611-10DOF-IMU-PCB/blob/main/img/IMU-V3-BOTTOM.jpg)

***
# V5

概述：V5是Mini定制版本，尺寸仅有22x22mm。以 `MPU6500`-`HMC5983`-`MS5611` 为传感器，移除了3.3V/5V电平转换电路，使用FPC-10P排线作为通信接口。
- 6DOF传感器：`MPU6500/6881` 兼容焊盘
- 地磁传感器：`HMC5983` 单焊盘
- 气压计：`MS5611` 单焊盘（背面放置，避光、且方便垫海绵）
- V5是Mini定制版本，尺寸仅有22x22mm。
- 6FOF传感器采用四周切割悬浮的设计，减少板载元件发热对陀螺仪温漂的影响。
- 5V/3.3V供电，LDO使用ME6206。
- 集成过流保护、反接保护。
- 通信电平仅支持3.3V，无3.3V/5V电平转换。
- 电路经多次打样实测，功能无异常，可放心使用。
- （如对PCB面积不受限的场景应用，建议使用V3版，器件更丰富，功能更多。）
![image](https://github.com/ZhiliangMa/MPU6500-HMC5983-AK8975-BMP280-MS5611-10DOF-IMU-PCB/blob/main/img/IMU-V5-TOP.jpg)
![image](https://github.com/ZhiliangMa/MPU6500-HMC5983-AK8975-BMP280-MS5611-10DOF-IMU-PCB/blob/main/img/IMU-V5-BOTTOM.jpg)
![image](https://github.com/ZhiliangMa/MPU6500-HMC5983-AK8975-BMP280-MS5611-10DOF-IMU-PCB/blob/main/img/IMU-V5.jpg)
