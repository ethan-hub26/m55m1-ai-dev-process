# Page 09

- PDF 페이지: `9`
- 제목 추정: (二) 模型訓練設定
- PDF 내 이미지 수: `4`
- 연결 자산:
- `train-config` -> `train-config.png` : 학습 설정 파일 조정 예시
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- (二) 模型訓練設定
- 。在訓練檔yolox_nano_ti_lite_nu.py中指定訓練和驗證資料集位置和訓練設定
- 
- 設定適量迭代次數(500次需3小時)
- 。類別檔coco_classes.py中定義資料集種類數
- 
- (none, fall-detected, sitting, standing)
- 。輸入訓練指令
- 
- $ python tools/train.py -f exps/default/yolox_nano_ti_lite_nu.py -d 1 -b 64 --fp16 -o -c
- pretrain/tflite_yolox_nano_ti/320_DW/yolox_nano_320_DW_ti_lite.pth
- 四、在PC上使用Anaconda環境進行模型訓練
