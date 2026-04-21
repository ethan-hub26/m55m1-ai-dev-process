# Page 39

- PDF 페이지: `39`
- 제목 추정: 5. 轉換至原始影像尺寸
- PDF 내 이미지 수: `4`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 5. 轉換至原始影像尺寸
- 。轉換邏輯：
- 
- 根據模型輸出的框座標與模型輸入影像的比例，計算對應原始影像的框位置與大小。
- 6. 最終結果生成
- 。生成結構化的偵測結果，包含：
- 
- 框的起點座標（m_x0、m_y0）和大小（m_w、m_h）。
- 
- 偵測置信度（m_normalisedVal）。
- 
- 物體分類（m_cls）。
- 39
- (四) 後處理程式解析(DetectorProcessing.cpp)
