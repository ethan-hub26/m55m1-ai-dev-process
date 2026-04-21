# Page 06

- PDF 페이지: `6`
- 제목 추정: (一) 訓練環境安裝
- PDF 내 이미지 수: `2`
- 연결 자산:
- 없음
- HTML 반영 상태: `pending`
- 확인 메모: 

## Extracted Text
- NuDeveloper Ecosystem – Make engineers’ jobs easier.
- Copyright © 2025 Nuvoton Technology Corporation
- (一) 訓練環境安裝
- 。1. 建立python環境
- 
- $ conda create --name yolox_nano python=3.12
- 
- $ conda activate yolox_nano
- 
- 透過上述指令在anaconda上建立環境
- 。2. upgrade pip
- 
- $ python -m pip install --upgrade pip setuptools
- 。3. 至pytorch官網安裝pytorch
- 
- $ python -m pip install torch torchvision torchaudio --index-url
- https://download.pytorch.org/whl/cu118
- 四、在PC上使用Anaconda環境進行模型訓練
