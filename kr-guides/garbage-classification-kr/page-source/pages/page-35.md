# Page 35

- PDF 페이지: `35`
- 제목 추정: 重點功能介紹
- PDF 내 이미지 수: `3`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 重點功能介紹
- 。初始化後處理參數：
- 
- 設定偵測門檻值、非極大值抑制（NMS）閾值、分類數量及Top-N 選項。
- 。處理模型輸出：
- 
- 解析YOLO 模型的輸出Tensor，計算偵測框的位置與大小，並篩選符合門檻值的物體。
- 。非極大值抑制（NMS）：
- 
- 移除重疊過高的偵測框，保留最相關的結果。
- 。轉換至原始影像尺寸：
- 
- 將模型輸出的座標框比例轉換至原始影像大小，得到真實的物體位置。
- 35
- (四) 後處理程式解析(DetectorProcessing.cpp)
- 目前階段
