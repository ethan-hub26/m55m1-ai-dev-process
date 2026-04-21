# Page 43

- PDF 페이지: `43`
- 제목 추정: 3. 輸入影像處理
- PDF 내 이미지 수: `4`
- 연결 자산:
- `image-scale` -> `image-scale.png` : 입력 이미지를 모델 크기에 맞게 스케일링하는 코드
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 3. 輸入影像處理
- 。使用imlib_nvt_scale() 將影像縮放到模型要求的尺寸。
- 。若模型需要有符號資料（IsDataSigned()），將影像資料轉換為int8 格式。
- 4. 推論觸發
- 。推論任務會根據當前影像進行物體檢測。
- 。使用FreeRTOS 隊列(Queue) 傳遞推論任務。
- 43
- (五) Main.cpp關鍵程式解析
