# Page 44

- PDF 페이지: `44`
- 제목 추정: 5. 後處理與結果呈現
- PDF 내 이미지 수: `4`
- 연결 자산:
- `draw-box` -> `draw-box.png` : 추론 결과를 화면에 그리는 함수 호출
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 5. 後處理與結果呈現
- 。DrawImageDetectionBoxes()：在影像上繪製檢測結果（矩形框和標籤）
- 。PresentInferenceResult()：顯示結果資訊（例如物件類別與座標）。
- 6. 主循環邏輯
- 。主循環中不斷檢查不同狀態的緩衝區並執行相應處理。
- 。每次循環間加入延遲(vTaskDelay(1)) 以避免佔用過多CPU 資源。
- 44
- (五) Main.cpp關鍵程式解析
