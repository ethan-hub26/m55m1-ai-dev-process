# Page 34

- PDF 페이지: `34`
- 제목 추정: 2. FreeRTOS 的多任務架構
- PDF 내 이미지 수: `3`
- 연결 자산:
- `freertos-queue` -> `freertos-queue.png` : FreeRTOS 큐 기반 추론 태스크 구조
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 2. FreeRTOS 的多任務架構
- 。功能用法：
- 
- 從任務佇列中接收推論請求（xQueueReceive）。
- 
- 執行推論與後處理。將推論結果傳回給發送者（xQueueSend）。
- 34
- (三) 模型推理程式解析(inferenceTask.cpp)
