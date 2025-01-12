
# STM32F103 基础示例项目

本仓库包含了一系列基于 STM32F103 微控制器的基础示例，旨在为电子设计竞赛提供测试例程，帮助开发者快速上手 STM32F103 的开发。

## 项目列表

- **06_ws_00_HAL_32F1空工程**: 基于 STM32F1 的 HAL 库空项目模板，供新项目开发使用。
- **06_ws_01_模块_按键**: 按键输入模块，演示如何配置 GPIO 以读取按键状态。
- **06_ws_02_模块_串口接受**: 串口接收模块，展示如何通过 USART 接口接收数据。
- **06_ws_03_模块_串口发送**: 串口发送模块，展示如何通过 USART 接口发送数据。
- **06_ws_04_模块_u8g2**: 集成 u8g2 库的 OLED 显示模块，演示如何驱动 OLED 屏幕显示内容。
- **06_ws_05_模块_AT24**: AT24 系列 EEPROM 读写模块，展示如何通过 I2C 接口与 EEPROM 进行数据交互。
- **14_zy_06_模块_DMA调节PWM**: 使用 DMA 调节 PWM 信号，占空比控制示例。
- **14_zy_07_模块_读取磁编码器**: 读取磁编码器数据的模块，演示如何获取旋转位置信息。

## 快速开始

1. **环境准备**:
   - 安装 [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html) 以配置外设和生成初始化代码。
   - 安装 [Keil MDK](https://www.keil.com/download/product/) 或 [IAR Embedded Workbench](https://www.iar.com/iar-embedded-workbench/) 进行代码编写和调试。

2. **克隆仓库**:
   ```bash
   git clone https://github.com/D77go77/Stm32f103-base-demo.git
   ```

3. **打开项目**:
   - 使用 STM32CubeMX 打开相应的 `.ioc` 文件，查看或修改外设配置。
   - 在 Keil 或 IAR 中打开对应的项目文件，查看和编辑代码。

4. **编译和下载**:
   - 在开发环境中编译项目，确保无错误。
   - 使用 ST-LINK 或其他调试器将编译后的固件下载到 STM32F103 开发板。

5. **运行和验证**:
   - 运行下载的程序，根据项目功能验证其正确性，例如观察串口输出、OLED 显示或 PWM 信号等。

## 资源

- [STM32F103 官方文档](https://www.st.com/en/microcontrollers-microprocessors/stm32f103.html): 包含数据手册、参考手册等详细资料。
- [STM32CubeF1](https://www.st.com/en/embedded-software/stm32cubef1.html): STM32F1 系列的固件库和示例代码。
- [u8g2 库](https://github.com/olikraus/u8g2): 一款通用的图形显示库，支持多种显示屏。

## 许可证

本项目基于 GPL-3.0 许可证进行分发。有关详细信息，请参阅 [LICENSE](./LICENSE) 文件。

```
