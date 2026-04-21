# Page 21

- PDF 페이지: `21`
- 제목 추정: 透過ONNX轉成要使用的模型框架(TFlite)
- PDF 내 이미지 수: `2`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 透過ONNX轉成要使用的模型框架(TFlite)
- 。$onnx2tf -i <ONNX_MODEL_PATH> -oiqt -qcind images <CALI_DATA_NPY_FILE> "[[[[0,0,0]]]]"
- "[[[[1,1,1]]]]“
- 。$ onnx2tf -i YOLOX_outputs/yolox_nano_ti_lite_nu/yolox_nano_nu_medicine.onnx -oiqt -qcind
- images YOLOX_outputs\yolox_nano_ti_lite_nu\calib_data_320x320_n200.npy "[[[[0,0,0]]]]"
- "[[[[1,1,1]]]]“
- 
- ONNX_MODEL_PATH =>轉換完ONNX的檔案的路徑
- 
- CALI_DATA_NPY_FILE=>校準資料檔案的路徑，通常是.npy 格式的NumPy 檔案
- 21
- (九) ONNX to TFlite
