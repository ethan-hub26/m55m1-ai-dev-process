# Page 11

- PDF 페이지: `11`
- 제목 추정: STEP3:選取要儲存的labelimg格式，分別為PascalVOC、YOLO、
- PDF 내 이미지 수: `5`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- STEP3:選取要儲存的labelimg格式，分別為PascalVOC、YOLO、
- CreateML，依照要訓練的模型不同(yolo版本不相同)，來選擇要使用
- 的格式
- 。PascalVOC : XML 文件來保存標註信息，圖片的檔案名、尺寸（高度、寬度）、
- 以及每個標註框的類別和座標，用於TensorFlow、Keras。
- 。YOLO (You Only Look Once) : 純文字，每行表示一個標註框(本次使用)
- 
- <class_id> <x_center>
- <y_center>
- <width> <height>
- 
- 類別id 、
- 標註框中心座標
- 、標註框寬以及高
- 。CreateML : JSON 文件保存標註信息，JSON 文件描述一張圖片，包含標註框
- 的位置、類別以及相關元數據
- 11
- (二) LabelImg教學
