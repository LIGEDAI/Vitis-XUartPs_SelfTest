# Vitis-XUartPs_SelfTest函数用法简介
## 1.定义
其原函数定义为`s32 XUartPs_SelfTest(XUartPs *InstancePtr){......}`
**`XUartPs_SelfTest`**：这是 Xilinx 提供的一个函数，用于检查和验证 UART 设备是否正常工作。这个函数执行一些基本的硬件自检，确保 UART 设备能够正常进行数据的发送和接收。**`uart_ps`**：这是 UART 的驱动实例，它是 `XUartPs` 结构体的一个变量，包含了与 UART 设备相关的配置和状态信息。
