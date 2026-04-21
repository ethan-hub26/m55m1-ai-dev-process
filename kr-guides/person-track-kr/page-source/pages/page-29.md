# Page 29

- PDF ???: `29`
- ?? ??: NuDeveloper Ecosystem – Make engineers’ jobs easier.
- PDF ? ??? ?: `2`
- ?? ??:
- ??
- HTML ?? ??: `pending`
- ?? ??:

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 模型框架轉換
- 。Pytorch to ONNX
- 
- $python tools/export_onnx.py -f <MODEL_CONFIG_FILE> -c
- <TRAINED_PYTORCH_MODEL> --output-name <ONNX_MODEL_PATH>
- 輕量化
- 。Create calibration data
- 
- $python demo/TFLite/generate_calib_data.py --img-size <IMG_SIZE> --n-img
- <NUMBER_IMG_FOR_CALI> -o <CALI_DATA_NPY_FILE> --img-dir
- <PATH_OF_TRAIN_IMAGE_DIR>
- 。Convert ONNX to Tflite
- 
- $onnx2tf -i <ONNX_MODEL_PATH> -oiqt -qcind images <CALI_DATA_NPY_FILE>
- "[[[[0,0,0]]]]" "[[[[1,1,1]]]]"
- 29
- (五)ONNX
