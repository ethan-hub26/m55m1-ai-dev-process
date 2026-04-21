# Page 38

- PDF 페이지: `38`
- 제목 추정: 3. 偵測框解析與篩選
- PDF 내 이미지 수: `4`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 3. 偵測框解析與篩選
- 。邏輯：
- 
- 從模型輸出中解析每個偵測框的座標、大小和置信度。
- 
- 篩選置信度高於threshold 的框，並將座標從模型輸入比例轉換至原始影像比例。
- 4. 非極大值抑制（NMS）
- 。目的：
- 
- 移除重疊率（IoU）高於nms 門檻值的重複框，只保留最高置信度的框。
- 
- 確保每個物體僅對應一個框。
- 38
- (四) 後處理程式解析(DetectorProcessing.cpp)
