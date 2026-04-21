# Page 42

- PDF 페이지: `42`
- 제목 추정: 1. 影像緩衝區管理:
- PDF 내 이미지 수: `4`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- 1. 影像緩衝區管理:
- 。這些函式用於取得不同狀態的緩衝區，以便進行影像填充、推論或結果處理。
- 
- get_empty_framebuf()：尋找可用於新影像填充的緩衝區（狀態為eFRAMEBUF_EMPTY）。
- 
- get_full_framebuf()：尋找已填充影像且可用於推論的緩衝區（狀態為eFRAMEBUF_FULL）。
- 
- get_inf_framebuf()：尋找正在推論中的緩衝區（狀態為eFRAMEBUF_INF）。
- 2. 模型初始化：
- 。初始化YOLO 模型，分配Tensor 緩衝區。
- 。從模型指標與長度資訊中載入模型。
- 42
- (五) Main.cpp關鍵程式解析
