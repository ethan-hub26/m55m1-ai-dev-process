# Page 27

- PDF 페이지: `27`
- 제목 추정: 3. 模型推論(Model Inference)
- PDF 내 이미지 수: `2`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 3. 模型推論(Model Inference)
- 。位置: InferenceTask.cpp使用模型執行推論(m_model->RunInference())，並獲取模型輸出張量
- (GetOutputTensor)。
- 。推論階段處理了模型運算核心的執行過程，計算出每個分類的機率和預測框(InferenceTask)。
- 4. 結果輸出及後處理(Post-processing)
- 。位置: DetectorPostProcessing.cpp執行非極大值抑制（NMS）過濾低相關預測。
- 。調整預測框尺寸，將模型輸出的結果轉換為原始圖像空間的座標。
- 。使用分類閾值篩選最終的檢測結果(DetectorPostProcessing)。
- 5. Main loop
- 。主函數可能包含循環控制，保持系統處於運行狀態，直到觸發退出條件（如接收到退出信
- 號）。
- 。確保所有資源在退出時正確釋放。
- 27
- (一) 軟體流程
