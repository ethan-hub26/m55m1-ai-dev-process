# Page 32

- PDF 페이지: `32`
- 제목 추정: 重點功能概述(inferenceTask.cpp)
- PDF 내 이미지 수: `3`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 重點功能概述(inferenceTask.cpp)
- 。推論執行（Inference Execution）：
- 
- 呼叫模型的推論函式，處理輸入資料並產生結果。
- 
- 使用後處理功能（DetectorPostprocessing）來解析模型輸出的Tensor 資料。
- 。任務處理（Task Handling）：
- 
- 提供FreeRTOS 任務的執行函式（inferenceProcessTask），負責處理推論任務佇列
- （Queue）。
- 
- 任務間使用訊號量（Semaphore）與互斥鎖（Mutex）進行同步。
- 32
- (三) 模型推理程式解析(inferenceTask.cpp)
- 目前階段
