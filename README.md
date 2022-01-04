# keras-yolov4

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

## Introduction

This repository focusing on converting `*.weight` to `*.h5` (Keras) only. Any features in [qqwweee/keras-yolo3](https://github.com/qqwweee/keras-yolo3) doesn't change.

For `convert.py`, it is replaced by `convert.py` from [david8862/keras-YOLOv3-model-set](https://github.com/david8862/keras-YOLOv3-model-set/blob/master/tools/model_converter/convert.py) to prevent error message below:

> TypeError: buffer is too small for requested array ...
> 
> @
> ```
> conv_weights = np.ndarray(
>                shape=darknet_w_shape,
>               dtype='float32',
>               buffer=weights_file.read(weights_size * 4))
>           count += weights_size
> ```


---

## Quick Start

1. Change file path (for `.cfg`, `.weight`) in `convert.sh`
2. Run `sh convert.sh`
3. Check the `*.h5` in `./output/`

## References

 - https://github.com/qqwweee/keras-yolo3/issues/723 
 - https://qiita.com/TakaoNarikawa/items/e4521fd8c7a522e9d4fd