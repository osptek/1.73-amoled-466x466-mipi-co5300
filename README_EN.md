# 1.73" 466×466 AMOLED MIPI module (CO5300) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 1.73-inch **AMOLED** panel, **466×466** resolution |
| Interface | **MIPI** |
| Driver IC | **CO5300** |
| Spec ID | **`1.73-amoled-466x466-mipi-co5300`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, interface and initialization documentation |
| `examples/` | **Sample projects** grouped by feature |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | **ESP-IDF5代码** (esp-lvgl-port + LVGL9) |
| `with-te/` | Tear-related samples (**屏幕防撕裂代码**, IDF5 & IDF6) |
| `eaf/` | EAF animation (**eaf动画代码**) |
| `freetype/` | FreeType fonts (**freetype字体代码**) |
| `lottie/` | Lottie animation (**lottie动画代码**) |
| `mjpeg/` | MJPEG video (**mjpeg视频代码**) |
| `image-decoder/` | Image decode (**图片解码代码**) |
| `display-touch-test/` | Display and touch tests (**显示和触摸单独测试程序**) |

### Sample project paths

#### Baseline (`examples/` root)

| Description | Path |
|:--|:--|
| esp-lvgl-port + LVGL9 | `examples/P4-IDF_CO5300-MIPI_ESP-LVGL-PORT_V9/` |

#### Tear-related (`with-te/`)

| Description | Path |
|:--|:--|
| LVGL common demo (ESP-IDF 5) | `examples/with-te/p4-idf_co5300-mipi_lvgl_common_demo/` |
| LVGL common demo (ESP-IDF 6) | `examples/with-te/p4-idf6_co5300-mipi_lvgl-common-demo/` |

#### EAF (`eaf/`)

| Description | Path |
|:--|:--|
| esp-lv-eaf-player | `examples/eaf/p4-idf_co5300-mipi_esp-lv-eaf-player/` |

#### FreeType (`freetype/`)

| Description | Path |
|:--|:--|
| FreeType font sample | `examples/freetype/p4-idf_co5300-mipi_lvgl-freetype-font/` |

#### Lottie (`lottie/`)

| Description | Path |
|:--|:--|
| Lottie playback | `examples/lottie/p4-idf_co5300-mipi_lvgl-lottie-player/` |
| Lottie batch loop | `examples/lottie/p4-idf_co5300-mipi_lvgl-lottie-player_batch-loop/` |
| Lottie touch switch | `examples/lottie/p4-idf_co5300-mipi_lvgl-lottie-player_touch-switch/` |

#### MJPEG (`mjpeg/`)

| Description | Path |
|:--|:--|
| MJPEG decode playback | `examples/mjpeg/p4-idf_co5300-mipi_mjpeg-decode_lvgl-v9/` |

#### Image decode (`image-decoder/`)

| Description | Path |
|:--|:--|
| Image decode sample | `examples/image-decoder/p4-idf_co5300-mipi_lvgl-decode-image/` |

#### Display and touch tests (`display-touch-test/`)

| Description | Path |
|:--|:--|
| CO5300 MIPI display test | `examples/display-touch-test/co5300_mipi_dsi/` |
| CST9217 touch I2C test | `examples/display-touch-test/P4-IDF_CST9217-I2C/` |
