## 小新Pad Pro 12.7（SM8250）TWRP Device Tree

### 已修复                              

- [x] 解密

- [x] 触控

- [x] 电量显示

- [x] USB

- [x] ADB

- [x] Bootloop

- [x] 花屏

- [x] FastbootD

### 未修复

- [ ] 屏幕只有一小条可以显示

其他功能都是默认好的

### 问题

现在的问题是联想小新这块平板的内核尚未开源，所以显示问题还未解决，目前定位到的问题是dsc

解决预想的方案是禁用dfps：

尝试修改dtbo中



这个TWRP的内核是基于440版本，如果你的版本和这个不一致，需要重新导入同版本的内核，否则会导致系统无法启动

