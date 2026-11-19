# 01_lcd_demo

[简体中文](README_ZH.md)

## 功能

该示例初始化 ST7789 LCD、LVGL、TF 卡、RGB LED、Wi-Fi 和蓝牙，并显示 LVGL 界面。

## 硬件需求

需要 ESP32-S3-LCD-1.47 开发板和一张 TF 卡。

## 怎么运行

使用 ESP-IDF 5.5.6 或 6.1.1，在本目录运行 `idf.py set-target esp32s3 build flash monitor`。

## 预期现象

LCD 显示 LVGL 界面，RGB LED 点亮，串口输出 Flash、TF 卡和无线初始化信息。

## 常见问题

暂无。
