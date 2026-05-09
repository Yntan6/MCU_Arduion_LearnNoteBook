# MCU_Arduion_LearnNoteBook

# 基础定义与解释
## 关于IDE里默认的两个函数
- setup函数是初始化，只运行一次
- loop函数是主函数代码，反复运行
### 一、Setup里：
1. 串口初始化
2.引脚初始化
3.变量初始化
### 二、Loop里：
- 主函数

# 引脚信号操作
`pinMode(PIN,MODE);`

一、数字输入输出

- `PIN`引脚号
- `MODE`工作模式：
	- `OUTPUT` 输出模式
	- `INPUT` 输入模式
	- `INPUT_PULLUP` 上拉输入模式，不用外接电阻；注意不能接负电平，不能接大于5V的电平
- digitalRead(PIN);
- digitalWrite(PIN,VALUE);
	- VALUE: `HIGH` 高电平 or `LOW` 低电平

二、模拟输入输出
- analogRead(PIN);
- analogWrite(PIN,VALUE);
	- VALUE:0-255 

### 
