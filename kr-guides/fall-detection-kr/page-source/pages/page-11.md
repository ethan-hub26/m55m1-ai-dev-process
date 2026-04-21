# Page 11

- PDF 페이지: `11`
- 제목 추정: (三) 模型框架轉換
- PDF 내 이미지 수: `2`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- (三) 模型框架轉換
- 。將訓練完成的checkpoint檔(.ckpt)轉成onnx檔(.onnx)
- 
- $ python tools/export_onnx.py -f exps/default/yolox_nano_ti_lite_nu.py -c
- YOLOX_outputs/yolox_nano_ti_lite_nu/latest_ckpt.pth --output-name
- YOLOX_outputs/yolox_nano_ti_lite_nu/yolox_nano_nu_fall.onnx
- 。將onnx檔轉成tensorflow框架並輕量化轉成tflite檔(.tflite)
- 
- $ python demo/TFLite/generate_calib_data.py --img-size 320 320 --n-img 200 -o
- YOLOX_outputs\yolox_nano_ti_lite_nu\calib_data_320x320_n200.npy --img-dir
- datasets\COCO\train2017
- 
- $ onnx2tf -i YOLOX_outputs/yolox_nano_ti_lite_nu/yolox_nano_nu_fall2.onnx -oiqt -qcind
- images YOLOX_outputs\yolox_nano_ti_lite_nu\calib_data_320x320_n200.npy "[[[[0,0,0]]]]"
- "[[[[1,1,1]]]]"
- 四、在PC上使用Anaconda環境進行模型訓練
