# Page Source Index

- PDF: `垃圾分類.pdf`
- Page range: `1` - `46`

| Page | Title Guess | Images | Assets | File |
| --- | --- | ---: | --- | --- |
| 1 | | Photo by Jeffery Cheng | 3 | - | `pages/page-01.md` |
| 2 | 陸、智慧居家-垃圾分類 | 2 | - | `pages/page-02.md` |
| 3 | (一) 案例介紹– 垃圾分類 | 2 | - | `pages/page-03.md` |
| 4 | 簡介及應用– | 3 | - | `pages/page-04.md` |
| 5 | 對於四種垃圾辨識準確率達到90.1%，分別為紙類、塑膠頻、鋁罐、紙杯。 | 3 | result-photo | `pages/page-05.md` |
| 6 | • LabelImg | 2 | - | `pages/page-06.md` |
| 7 | (一) 資料集蒐集 | 2 | - | `pages/page-07.md` |
| 8 | 資料集透過自行蒐集的照片來進行訓練 | 2 | - | `pages/page-08.md` |
| 9 | STEP1 : 下載此連結，點擊連結內為labelImg.exe | 3 | labelimg-download | `pages/page-09.md` |
| 10 | STEP2 : 打開後要選取資料集位址，以及要儲存的位址 | 4 | labelimg-open | `pages/page-10.md` |
| 11 | STEP3:選取要儲存的labelimg格式，分別為PascalVOC、YOLO、 | 5 | - | `pages/page-11.md` |
| 12 | STEP4: 設定標註的種類並進行標註 | 6 | rectbox-button, label-dialog, label-list | `pages/page-12.md` |
| 13 | STEP5:使用yolo格式全部標註完以後，透過一段python程式將原本 | 4 | yolo2coco-class, yolo2coco-path | `pages/page-13.md` |
| 14 | GPU => Nvidia GTX 1080 ti(可以透過指令來得知自身顯卡規格) | 3 | - | `pages/page-14.md` |
| 15 | 安裝anaconda3 | 3 | - | `pages/page-15.md` |
| 16 | 安裝Pytorch, CUDA, MMCV version需要相互配合，如果無使用cpu來 | 2 | - | `pages/page-16.md` |
| 17 | 因為模型大小限制，在不外接Hyper RAM的情況下，只能使用2MB，因為 | 2 | - | `pages/page-17.md` |
| 18 | 資料結構按照下列分為 | 4 | dataset-structure | `pages/page-18.md` |
| 19 | 主要調整圖片大小、class數量、執行的epoch次數。 | 3 | - | `pages/page-19.md` |
| 20 | 轉換成ONNX後續再轉換成要使用的模型框架 | 2 | - | `pages/page-20.md` |
| 21 | 透過ONNX轉成要使用的模型框架(TFlite) | 2 | - | `pages/page-21.md` |
| 22 | 使用vela complier | 2 | - | `pages/page-22.md` |
| 23 | 看訓練出來每一個class的效果，包含各個class的準確率(AP，Average Precision)， | 3 | - | `pages/page-23.md` |
| 24 | 測試所有的照片集(單張亦可) | 2 | - | `pages/page-24.md` |
| 25 | (一) 軟體流程 | 2 | - | `pages/page-25.md` |
| 26 | 1. 系統初始化(System Initialization) | 2 | - | `pages/page-26.md` |
| 27 | 3. 模型推論(Model Inference) | 2 | - | `pages/page-27.md` |
| 28 | 重點功能概述(BoardInit.cpp & mpu_config_M55M1.h) : | 3 | - | `pages/page-28.md` |
| 29 | 1. 系統時鐘與模組時鐘初始化 | 3 | - | `pages/page-29.md` |
| 30 | 2. UART 初始化： | 4 | - | `pages/page-30.md` |
| 31 | 4. Arm Ethos-U NPU 初始化： | 4 | - | `pages/page-31.md` |
| 32 | 重點功能概述(inferenceTask.cpp) | 3 | - | `pages/page-32.md` |
| 33 | 1. 推論以及執行 | 4 | inference-run | `pages/page-33.md` |
| 34 | 2. FreeRTOS 的多任務架構 | 3 | freertos-queue | `pages/page-34.md` |
| 35 | 重點功能介紹 | 3 | - | `pages/page-35.md` |
| 36 | 1. 後處理初始化 | 3 | - | `pages/page-36.md` |
| 37 | 2. 執行後處理 | 4 | - | `pages/page-37.md` |
| 38 | 3. 偵測框解析與篩選 | 4 | - | `pages/page-38.md` |
| 39 | 5. 轉換至原始影像尺寸 | 4 | - | `pages/page-39.md` |
| 40 |  | 2 | - | `pages/page-40.md` |
| 41 |  | 3 | - | `pages/page-41.md` |
| 42 | 1. 影像緩衝區管理: | 4 | - | `pages/page-42.md` |
| 43 | 3. 輸入影像處理 | 4 | image-scale | `pages/page-43.md` |
| 44 | 5. 後處理與結果呈現 | 4 | draw-box | `pages/page-44.md` |
| 45 | Link | 3 | - | `pages/page-45.md` |
| 46 | - | 3 | - | `pages/page-46.md` |
