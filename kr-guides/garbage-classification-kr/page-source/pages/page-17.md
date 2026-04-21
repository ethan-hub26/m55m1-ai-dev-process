# Page 17

- PDF 페이지: `17`
- 제목 추정: 因為模型大小限制，在不外接Hyper RAM的情況下，只能使用2MB，因為
- PDF 내 이미지 수: `2`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 因為模型大小限制，在不外接Hyper RAM的情況下，只能使用2MB，因為
- YOLOX_Nano_ti_lite_nu僅僅0.91MB，為最適合使用在M55M1的Model。
- 訓練–
- 。$ python tools/train.py -f exps/default/yolox_nano_ti_lite_nu.py -d 1 -b 64 --fp16 -o -c
- pretrain/tflite_yolox_nano_ti/320_DW/yolox_nano_320_DW_ti_lite.pth
- 。對應的功能為
- $ python tools/train.py -f <MODEL_CONFIG_FILE> -d 1 -b <BATCH_SIZE> --fp16 -o -c <PRETRAIN
- MODEL PATH>
- 。對上面放置檔案進行解釋
- 
- MODEL_CONFIG_FILE => 將下載的yolox_nano中的yolox-nano-ti-nu model，連同位址一起放入
- 
- BATCH_SIZE => 設定一次訓練所要的batch大小，一般設定64，若電腦設備無法承受，可自行往下調(-> 32 -> 16)
- 
- PRETRAIN MODEL PATH => 放置預先訓練好的權重，亦在下載的yolox_nano中
- 17
- (六) YOLOX_Nano模型訓練
