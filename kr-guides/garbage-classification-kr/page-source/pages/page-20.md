# Page 20

- PDF 페이지: `20`
- 제목 추정: 轉換成ONNX後續再轉換成要使用的模型框架
- PDF 내 이미지 수: `2`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 轉換成ONNX後續再轉換成要使用的模型框架
- 。$ python tools/export_onnx.py -f <MODEL_CONFIG_FILE> -c <TRAINED_PYTORCH_MODEL> --
- output-name <ONNX_MODEL_PATH>
- 。$ python tools/export_onnx.py -f exps/default/yolox_nano_ti_lite_nu.py -c
- YOLOX_outputs/yolox_nano_ti_lite_nu/latest_ckpt.pth --output-name
- YOLOX_outputs/yolox_nano_ti_lite_nu/yolox_nano_nu_medicine.onnx
- 
- MODEL_CONFIG_FILE =>用於描述模型結構與參數，也是從下載的yolox_nano當中給予位址
- 
- TRAINED_PYTORCH_MODEL => 指定已訓練完成的PyTorch 模型（通常是.pth 文件），作為轉換的來源
- 
- ONNX_MODEL_PATH =>轉換後的ONNX 模型儲存路徑與名稱
- 20
- (九) Pytorch to ONNX
