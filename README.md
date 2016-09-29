# ImagesResourse
>蓝牙开发是我之前在一个车联网的项目里用到的，捣鼓了半天整理了一些东西。使用环境是手机和单片机的通信，大体流程是手机通过发送故障码给单片机然后单片机广播回传数据，具体内容下面详细介绍~

iOS BLE开发调用的是CoreBluetooth系统原生库，基本用到的类有：
>CBCentralManager //系统蓝牙设备管理对象\n
>CBPeripheral //外围设备\n
>CBService //外围设备的服务或者服务中包含的服务\n
>CBCharacteristic //服务的特性\n
>CBDescriptor //特性的描述符\n

他们之间的关系如图:
![alt text](放这个位置 "Title")
