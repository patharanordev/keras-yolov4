# keras-yolov4

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

## Introduction

Modified from [qqwweee/keras-yolo3](https://github.com/qqwweee/keras-yolo3)

> A Keras implementation of YOLOv3 (Tensorflow backend) inspired by [allanzelener/YAD2K](https://github.com/allanzelener/YAD2K).

This repository focusing on converting `*.weight` to `*.h5` (Keras) only. Any features in [qqwweee/keras-yolo3](https://github.com/qqwweee/keras-yolo3) doesn't change.

---

## Quick Start

1. Change file path (for `.cfg`, `.weight`) in `convert.sh`
2. Run `sh convert.sh`
3. Check the `*.h5` in `./output/`

## References

 - https://github.com/qqwweee/keras-yolo3/issues/723 
 - https://qiita.com/TakaoNarikawa/items/e4521fd8c7a522e9d4fd