# NetCapturer
A net packet capturer using Jpcap and Jfreechart

## 功能描述
代理抓包工具(NetCapturer)通过调用Jpcap，Jfreechart库实现了：
### 对传输在选定网卡数据包的抓取
### 分析数据包对应的发送与接收IP地址，发送与接收MAC地址，在传输层、网络层的协议，数据包长度（受限于Jpcap功能无法分析数据包在应用层的协议）
### 获取数据包传输数据并转化为16进制
### 实现数据包信息实时可视化
### 实现数据包信息各个协议占比可视化
### 实现程序启动后的数据包流量可视化
### 提供按编号查询数据包数据的功能
### 利用Java多线程实现抓包与显示并行执行
### 支持停止抓包后，点击确定按钮继续抓包
## 使用说明
### 使用步骤
#### 首先在下拉栏中根据显示的设备名、MAC地址选择网卡
#### 其次点击“确定”按钮开始抓取选定网卡上传输的数据包
#### 随后可点击“停止抓包”按钮暂停抓包操作
### 功能补充
#### 点击“清空”按钮清空用于显示数据包的表格
#### 点击“查询功能”按钮进入查询界面
#### 在查询界面，输入数据包编号可查看详细数据包的信息和数据

## Function description
* By calling Jpcap, the Jfreechart library implements:
### Capture of packets transmitted on the selected network card
### Analyze the IP address corresponding to the packet sending and receiving, the MAC address of the packet sending and receiving, the protocol at the transport layer and the network layer, and the packet length (due to the Jpcap function, the protocol of the packet at the application layer cannot be analyzed)
### Get the packet transfer data and convert it to hexadecimal
### Realize real-time visualization of data packet information
### Realize the visualization of each protocol proportion of packet information
### Realize the visualization of packet traffic after program startup
### Provides the function of querying packet data by number
### Using Java multithreading to realize the parallel execution of packet capture and display
### After stopping packet capture, click OK to continue packet capture
## Instructions for use
### Use steps
#### Select a NIC based on the device name and MAC address displayed in the drop-down list
#### Then click the "OK" button to start grabbing the data packets transmitted on the selected network card
#### Click the "Stop Packet Capture" button to stop packet capture
### Functional supplement
#### Click the "Clear" button to clear the table used to display the packets
#### Click the "Query Function" button to enter the query interface
#### On the query page, enter the packet number to view detailed packet information and data
