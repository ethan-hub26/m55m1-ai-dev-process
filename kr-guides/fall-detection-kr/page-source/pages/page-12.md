# Page 12

- PDF 페이지: `12`
- 제목 추정: (四) Vela編譯步驟:
- PDF 내 이미지 수: `2`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- (四) Vela編譯步驟:
- 。將輕量化完的模型放到vela\generated\
- 。並且修改vela目錄下的variables.bat
- 
- $ set MODEL_SRC_FILE=yolox_nano_nu_fall_full_integer_quant.tflite
- 
- $ set MODEL_OPTIMISE_FILE=yolox_nano_nu_fall_full_integer_quant_vela.tflite
- 。執行gen_model_cpp檔案
- 
- 執行結果會出現在
- vela\generated\yolox_nano_ti_lite_nu_fall_full_integer_quant_vela.tflite.cc
- 四、在PC上使用Anaconda環境進行模型訓練
