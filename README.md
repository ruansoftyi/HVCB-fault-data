# HVCB-fault-data
The sampling frequency is set to 50kHz, and to obtain the effective part of the voiceprint signal, a waveform of 0.6 seconds before and after the fault (a total of 30,000 points) is intercepted as the effective data sample.
The voiceprint sensor uses the MAX9814 microphone amplifier as the acquisition module, with a frequency range of 50Hz–20kHz, a sensitivity of -48dB–66dB, and an omnidirectional polar pattern. A DAQ122 multi-channel data acquisition system manufactured by Lingzhi Electronics is used. 
以高压真空断路器未接负载情况下合闸线圈声纹为触发信号，分别采集了正常状态、操动机构储能单弹簧卡涩状态、操动机构储能双弹簧卡涩状态、传动机构连杆运动受阻状态和紧固件松动状态五种声纹信号作为基本故障，每种故障各采集了10组。将单弹簧卡涩和紧固件松动组合；单弹簧卡涩和连杆受阻组合；紧固件松动和连杆受阻组合；紧固件、单弹簧和连杆组合又衍生出4种故障，每种故障采集10组。一共有9种故障信号，每种故障各采集了10组。

类别0：正常信号    0_0无噪声  0_1白噪声  0_2环境噪声  0_3设备噪声 0_4三种噪声
类别1：传动机构连杆受阻信号 1_0无噪声  1_1白噪声  1_2环境噪声  1_3设备噪声 1_4三种噪声
类别2：单弹簧机构动作卡涩信号 2_0无噪声  2_1白噪声  2_2环境噪声  2_3设备噪声 2_4三种噪声
类别3：紧固件松动信号 3_0无噪声  3_1白噪声  3_2环境噪声  3_3设备噪声 3_4三种噪声
类别4：双弹簧机构动作卡涩信号 4_0无噪声  4_1白噪声  4_2环境噪声  4_3设备噪声 4_4三种噪声
类别5：连杆+单弹簧信号 5_0无噪声  5_1白噪声  5_2环境噪声  5_3设备噪声 5_4三种噪声
类别6：连杆+紧固件信号 6_0无噪声  6_1白噪声  6_2环境噪声  6_3设备噪声 6_4三种噪声
类别7：紧固件+单弹簧信号 7_0无噪声  7_1白噪声  7_2环境噪声  7_3设备噪声 7_4三种噪声
类别8：紧固件+单弹簧+连杆信号 8_0无噪声  8_1白噪声  8_2环境噪声  8_3设备噪声 8_4三种噪声

