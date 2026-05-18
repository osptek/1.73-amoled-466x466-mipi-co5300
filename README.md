# 1.73 寸 466×466 AMOLED MIPI 模组（CO5300）资料与示例

**English：** [`README_EN.md`](README_EN.md)

---

> 本仓库提供该模组的 **示例工程**，以及数据手册、规格与接口说明等资料，便于选型参考与集成开发。

## 产品概要

| 项目 | 说明 |
|:--|:--|
| 模组规格 | 1.73 英寸 **AMOLED**，分辨率 **466×466** |
| 接口 | **MIPI** |
| 驱动芯片 | **CO5300** |
| 规格标识 | 产品资料中常用 **`1.73-amoled-466x466-mipi-co5300`** 表示本规格 |

---

## 仓库结构

### 顶层目录

| 路径 | 说明 |
|:--|:--|
| `docs/` | 数据手册、规格说明、接口与初始化相关文档 |
| `examples/` | 按功能分类的 **示例工程** |

### `examples/` 分类

| 分类 | 说明（对应内部资料目录） |
|:--|:--|
| `examples/` 根目录 | **ESP-IDF5代码**（esp-lvgl-port + LVGL9） |
| `with-te/` | **屏幕防撕裂代码**（含 ESP-IDF5 / ESP-IDF6） |
| `eaf/` | **eaf动画代码** |
| `freetype/` | **freetype字体代码** |
| `lottie/` | **lottie动画代码** |
| `mjpeg/` | **mjpeg视频代码** |
| `image-decoder/` | **图片解码代码** |
| `display-touch-test/` | **显示和触摸单独测试程序** |

### 示例工程路径

#### 基础（`examples/` 根目录）

| 说明 | 路径 |
|:--|:--|
| esp-lvgl-port + LVGL9 | `examples/P4-IDF_CO5300-MIPI_ESP-LVGL-PORT_V9/` |

#### 屏幕防撕裂代码（`with-te/`）

| 说明 | 路径 |
|:--|:--|
| LVGL 通用演示（ESP-IDF 5） | `examples/with-te/p4-idf_co5300-mipi_lvgl_common_demo/` |
| LVGL 通用演示（ESP-IDF 6） | `examples/with-te/p4-idf6_co5300-mipi_lvgl-common-demo/` |

#### eaf动画代码（`eaf/`）

| 说明 | 路径 |
|:--|:--|
| esp-lv-eaf-player | `examples/eaf/p4-idf_co5300-mipi_esp-lv-eaf-player/` |

#### freetype字体代码（`freetype/`）

| 说明 | 路径 |
|:--|:--|
| FreeType 字体示例 | `examples/freetype/p4-idf_co5300-mipi_lvgl-freetype-font/` |

#### lottie动画代码（`lottie/`）

| 说明 | 路径 |
|:--|:--|
| Lottie 播放 | `examples/lottie/p4-idf_co5300-mipi_lvgl-lottie-player/` |
| Lottie 批量循环 | `examples/lottie/p4-idf_co5300-mipi_lvgl-lottie-player_batch-loop/` |
| Lottie 触摸切换 | `examples/lottie/p4-idf_co5300-mipi_lvgl-lottie-player_touch-switch/` |

#### mjpeg视频代码（`mjpeg/`）

| 说明 | 路径 |
|:--|:--|
| MJPEG 解码播放 | `examples/mjpeg/p4-idf_co5300-mipi_mjpeg-decode_lvgl-v9/` |

#### 图片解码代码（`image-decoder/`）

| 说明 | 路径 |
|:--|:--|
| 图片解码示例 | `examples/image-decoder/p4-idf_co5300-mipi_lvgl-decode-image/` |

#### 显示和触摸单独测试程序（`display-touch-test/`）

| 说明 | 路径 |
|:--|:--|
| CO5300 MIPI 显示测试 | `examples/display-touch-test/co5300_mipi_dsi/` |
| CST9217 触摸 I2C 测试 | `examples/display-touch-test/P4-IDF_CST9217-I2C/` |
