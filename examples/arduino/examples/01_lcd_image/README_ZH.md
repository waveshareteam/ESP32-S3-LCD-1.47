# 01_lcd_image

[English](README.md)

## 功能

该示例从 TF 卡读取 PNG 图片，并通过 SPI 在 ST7789 LCD 上显示。

## 硬件需求

需要 ESP32-S3-LCD-1.47 开发板、一张 TF 卡和示例目录中的图片文件。

## 怎么运行

在 Arduino IDE 中选择 ESP32S3 Dev Module，使用 Arduino-ESP32 4.0.0 编译 `01_lcd_image.ino`，并把 `SD Card File` 中的图片复制到 TF 卡根目录。

## 预期现象

LCD 依次显示 TF 卡中的 PNG 图片，串口输出读取和显示状态。

## 常见问题

TF 卡必须使用示例代码支持的文件系统和图片文件名。
