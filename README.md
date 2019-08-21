# dell-latitude7370-Hackintosh-EFI-backup 
## 戴尔latitude7370 clover 配置
Dell latitude 7370 

Cpu:core m5 

Gpu : hd515 

**首先进入gurb执行以下代码修改dvmt大小** 

**（该操作存在风险，如对设备有任何损坏本人概不负责）**

`setup_var 0x432 0x3`

- 可正常使用
-- 显卡驱动正常
-- 声卡内建耳机孔扬声器正常
-- wifi 替换为dw1820a
-- 内置键盘正常
-- 变频正常 
-- 触摸屏正常
-- 亮度休眠正常  

- 存在的问题
-- 触摸板手势无法使用
-- 蓝牙可驱动但开机偶尔会出现五国 不驱动蓝牙不出现该问题
-- 雷电接口无法热插拔
