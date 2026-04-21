# Page 23

- PDF 페이지: `23`
- 제목 추정: 看訓練出來每一個class的效果，包含各個class的準確率(AP，Average Precision)，
- PDF 내 이미지 수: `3`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 看訓練出來每一個class的效果，包含各個class的準確率(AP，Average Precision)，
- 訓練的每個IOU的準確率
- 。IOU :衡量模型預測框與真實框（Ground Truth）重疊程度的指標。
- 。$ python demo\TFLite\tflite_inference.py -m <FULL_INTEGER_QUANT_TFLITE> -s <SCORE_THR> -
- i <PATH_OF_IMAGE> -a <PATH_OF_VAL_ANNOTATION_FILE>
- 。$ python demo\TFLite\tflite_inference.py -m
- YOLOX_outputs\yolox_nano_ti_lite_nu\yolox_nano_ti_lite_nu_hg_full_integer_quant.tflite -s 0.6
- -i datasets/hagrid_coco/val2017/0001.jpg -a hagrid_coco/annotations/hagrid_val.json
- 
- FULL_INTEGER_QUANT_TFLITE =>需要評估的全整數量化TFLite 模型（通常是.tflite 格式）。
- 
- SCORE_THR =>分數閾值，指定物體檢測的置信度閾值，只有高於此分數的檢測結果才會被保留。
- 
- PATH_OF_IMAGE =>影像路徑：指定要進行推論的圖片文件路徑
- 
- PATH_OF_VAL_ANNOTATION_FILE =>驗證標註檔案，指定包含圖片真實標註的檔案路徑（.json 文件）
- 23
- (十一) Evaluate TFlite int8/float Model
