# dell-latitude7370-Hackintosh-EFI-backup 
## 戴尔latitude7370 clover 配置
Dell latitude 7370 

Cpu:core m5 

Gpu : hd515 

**首先进入gurb执行以下代码修改dvmt大小** 

**（该操作存在风险，如对设备有任何损坏本人概不负责）**

`setup_var 0x432 0x3`
- 可正常使用
  
    1. 显卡驱动正常  

    2. 声卡内建耳机孔扬声器正常
  3. wifi替换为dw1820a
  4. 内置键盘正常
  5. 变频正常 
  6. 触摸屏正常
  7. 亮度休眠正常  

- 存在的问题
  1. 触摸板手势无法使用
  2. 雷电接口无法热插拔 
   
