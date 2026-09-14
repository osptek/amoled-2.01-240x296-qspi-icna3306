<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 2.01″ AMOLED 240×296 (ICNA3306 · QSPI)</h1>

<p align="center"><b>AMOLED module · QSPI · ICNA3306 · capacitive touch</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Size: 2.01 inch" src="https://img.shields.io/badge/Size-2.01%22-3498DB?style=flat-square" />
  <img alt="Resolution: 240x296" src="https://img.shields.io/badge/Resolution-240%C3%97296-8E44AD?style=flat-square" />
  <img alt="Interface: QSPI" src="https://img.shields.io/badge/Interface-QSPI-27AE60?style=flat-square" />
  <img alt="Driver: ICNA3306" src="https://img.shields.io/badge/Driver-ICNA3306-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 2.01 inch 240×296 AMOLED QSPI module (ICNA3306) product image" src="./images/product.png" width="640" /></p>

## Contents

- [Overview](#overview)
- [Specifications](#specifications)
- [Sample projects](#sample-projects)
- [Repository layout](#repository-layout)
- [Resources](#resources)
- [Buy](#buy)
- [Support](#support)

---

## Overview

OSPTEK **2.01″ 240×296 AMOLED** is a **QSPI** color display module driven by **ICNA3306**, with capacitive touch (**CST816D**). Suited to handheld devices, wearables, and compact portrait HMI.

Spec ID (repository name): `amoled-2.01-240x296-qspi-icna3306`

Current module version: **AM201Q240296LK1**. Electrical and mechanical details follow [`docs/AM_201_Q240296_LK_1_a3e5aef203.pdf`](./docs/AM_201_Q240296_LK_1_a3e5aef203.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 2.01 inch |
| Type | AMOLED (color) |
| Resolution | 240×296 |
| Interface | QSPI |
| Driver IC | ICNA3306 |
| Touch driver | CST816D |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Sample projects

| Description | Path |
| ---- | ---- |
| ESP32-S3 · ICNA3306 QSPI + esp-lvgl-adapter / LVGL8 | [`examples/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl8/`](./examples/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl8/) |
| ESP32-S3 · ICNA3306 QSPI + esp-lvgl-adapter / LVGL9 | [`examples/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl9/`](./examples/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl9/) |
| ESP32-S3 · LVGL8 + TE | [`examples/with-te/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/`](./examples/with-te/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/) |
| ESP32-S3 · LVGL9 + TE | [`examples/with-te/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/`](./examples/with-te/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/) |
| ESP32-S3 · LVGL8 + TE + software rotate 90° | [`examples/with-te-sw-rotate-90/esp32s3-idf5_icna3306-qspi_lvgl8_amoled-with-te/`](./examples/with-te-sw-rotate-90/esp32s3-idf5_icna3306-qspi_lvgl8_amoled-with-te/) |

## Repository layout

```text
amoled-2.01-240x296-qspi-icna3306/                                # repo root (nav: ../../README_EN.md)
└── versions/
    └── AM201Q240296LK1/                                # full materials for this part number
        ├── README.md
        ├── README_EN.md
        ├── images/
        ├── docs/
        └── examples/
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (AM201Q240296LK1) | [`docs/AM_201_Q240296_LK_1_a3e5aef203.pdf`](./docs/AM_201_Q240296_LK_1_a3e5aef203.pdf) |
| Driver IC datasheet (ICNA3306) | [`docs/ICNA_3306_Datasheet_release_V0_03_20211008_2_966e953f85.pdf`](./docs/ICNA_3306_Datasheet_release_V0_03_20211008_2_966e953f85.pdf) |
| Touch IC datasheet (CST816D) | [`docs/CST_816_D_V1_0_2_1b06dfb078.pdf`](./docs/CST_816_D_V1_0_2_1b06dfb078.pdf) |
| Init sequence (text) | [`docs/ICNA3306_201_240X296_SPI_简码 20231208.txt`](./docs/ICNA3306_201_240X296_SPI_%E7%AE%80%E7%A0%81%2020231208.txt) |
| 2.01″ AMOLED adapter board (V1.0) | [`docs/2.01_AMOLED转接板V1.0_2025-05-22.pdf`](./docs/2.01_AMOLED%E8%BD%AC%E6%8E%A5%E6%9D%BFV1.0_2025-05-22.pdf) |
| Connector datasheet (OK-14F024-04) | [`docs/OK-14F024-04.pdf`](./docs/OK-14F024-04.pdf) |

### Samples

- [ESP32-S3 ICNA3306 QSPI + LVGL8](./examples/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl8/)
- [ESP32-S3 ICNA3306 QSPI + LVGL9](./examples/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl9/)
- [ESP32-S3 LVGL8 + TE](./examples/with-te/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/)
- [ESP32-S3 LVGL9 + TE](./examples/with-te/esp32s3-idf5_icna3306-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/)
- [ESP32-S3 LVGL8 + TE + software rotate 90°](./examples/with-te-sw-rotate-90/esp32s3-idf5_icna3306-qspi_lvgl8_amoled-with-te/)

## Buy

<p align="center">
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="AliExpress store" src="https://img.shields.io/badge/AliExpress-Official_Store-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://shop110742373.taobao.com/"><img alt="Taobao store" src="https://img.shields.io/badge/Taobao-Official_Store-FF6A00?style=for-the-badge" /></a>
</p>

**Overseas (AliExpress)**

- Store: [OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

**China (Taobao)**

- Store: [鱼鹰光电工厂店](https://shop110742373.taobao.com/)

## Support

- Technical support / product inquiry: <luyu@osptek.com>
- QQ group: **985881096**
- Website: <https://osptek.com/>
- Feel free to open an Issue in this repository with any questions

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
