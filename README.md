# aws-iot-device-sdk-js-v2
# 宠物喂食器开发计划书

This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.
For more information, please check Tuya Developer Website.


## 一、方案标题

宠物喂食器

## 二、方案应用场景

 ### 1） 产品地点：家中、宠物店或流浪动物救助站
 ### 2） 产品背景：去年疫情突发，封城、封小区以及人员隔离，让原本享受千般宠爱的宠物们变成了靠吃猫砂、塑料袋度日的小可怜，甚至有些生生饿死。
## 三、产品功能：可以为宠物量身定做喂养方案，个性化的定期为宠物投放粮食，避免了上述情况的发生，设计了一款宠物喂食器。
* 用户可以选择不同宠物预设的喂养模式
* 也可以自定义喂养时间和喂养量
* 在储存仓内的粮食减少时可以在绑定的手机app上提醒主人及时补充宠物食物
* 同时自带摄像头可以在手机上实时监控并记录爱宠的动态
* 自带音响，可以设定吸引宠物进食的声音，培养宠物习惯使用宠物喂食器
* 自带小夜灯功能、在夜晚为宠物提供照明
* 同时也可以定期为宠物添加饮用水（可选）


## 四、开发计划

### 4月10日前完成
1）3月15日前：物料准备 <br>
涂鸦三明治开发套件、WiFi通信板（VWXR2）、减速电机、外壳、电子秤模块、<br>
openmv或者其他摄像头模块、小喇叭、LED灯等、总成供电由直流供电电源板执行，<br>
12V DC输入或5V USB输入<br>
2）3月16—25日：嵌入式开发、云开发 <br>
利用keil MDK平台编程 <br>
3）3月31前整体调试 <br>
4）4月1—10日：实际测试运行 <br>
放置在宠物店或者家中测试是否能够满足预期 <br>

