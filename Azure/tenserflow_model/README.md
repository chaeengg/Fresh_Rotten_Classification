# <img src="https://github.com/weg-9000/image/blob/main/logo_mini.PNG" alt="Example Image" width="32" height="32" style="vertical-align: middle;"> 신선도 및 상태 분류 - TensorFlow 모델

이 저장소에는 Azure Custom Vision에서 내보낸 TensorFlow 모델이 포함되어 있습니다. 해당 모델은 과일/채소 분류, 신선도 판별, 품목 분류 작업을 지원합니다.

## 사용 방법

1. 모델 로드: `load_custom_vision_model()` 함수를 사용해 모델을 로드합니다.
2. 이미지 전처리: `preprocess_image()`로 이미지를 224x224 크기로 조정하고 정규화합니다.
3. 예측: `predict_with_custom_model()` 함수로 이미지를 분류합니다.
4. 결과 시각화: `analyze_image()` 함수로 이미지와 결과를 출력합니다.

## 주의사항
1. Python 3.10.11 사용

## 라이센스
MIT 라이센스.
    MIT License

    Copyright (c) Microsoft Corporation.

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE

### 2. **DenseNet/ResNet 모델 훈련 및 평가**
```
TensorFlow Model/
├── code/
| ├ TensorFlow.ipynb
| └── README.md
├── Model/
| ├ ZIP [1-1, 2-1, 2-2, 3-1, 3-2]
| └── README.md
└── README.md
```
---
