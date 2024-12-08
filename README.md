# 20242R0136COSE37302

---

### README: 드론 기반 객체 탐지 성능 개선 프로젝트

---

#### **프로젝트 제목**  
**드론 이미지에서의 객체 탐지 향상: CBAM 및 FEM 모듈을 활용한 YOLO 모델 개선**

---

#### **소개**

본 프로젝트는 VisDrone 데이터셋을 활용해 드론 영상에서의 객체 탐지 성능을 개선하는 데 중점을 둡니다.  
YOLO(You Only Look Once) 모델은 실시간 탐지 능력으로 잘 알려져 있지만, 밀집된 작은 객체가 포함된 드론 영상에서는 성능이 저하될 수 있습니다. 이를 개선하기 위해 CBAM(Convolutional Block Attention Module)과 FEM(Feature Enhancement Module)을 통합한 YOLO 모델을 설계하였습니다.

프로젝트는 Jupyter Notebook 하나로 구성되어 있으며, 데이터 전처리, 모델 학습, 결과 분석까지 모든 과정이 포함되어 있습니다.

---

#### **주요 특징**

1. **개선된 YOLO 아키텍처**  
   - CBAM: 채널 및 공간 주의 메커니즘 추가.
   - FEM: 다양한 스케일의 특징 학습을 위한 모듈 설계.

2. **VisDrone 데이터셋 전처리**  
   - YOLO 포맷으로 어노테이션 변환.
   - 데이터셋을 훈련(train)/검증(validation)으로 분리 및 정리.

3. **Jupyter Notebook 기반 통합 워크플로우**  
   - 데이터 전처리, 모델 학습, 성능 평가 과정을 한 파일에서 실행 가능.

4. **향상된 성능**  
   - mAP@50: 30.13% → 42.04%  
   - mAP@50-95: 17.43% → 25.65%

---

#### **사용 방법**

1. **필요한 환경 설정**
   - Python 3.8 이상
   - Jupyter Notebook
   - PyTorch, Ultralytics YOLO, OpenCV, tqdm 등 필수 라이브러리 설치:
  
2. **노트북 실행**
   - Jupyter Notebook에서 프로젝트 파일 열기:

3. **각 셀 실행**
   - **데이터 전처리**: 데이터셋 구조 생성 및 어노테이션 변환.
   - **모델 학습**: 개선된 YOLO 모델을 사용해 학습 시작.
   - **결과 분석**: 학습 결과 시각화 및 성능 평가.
---

#### **결과 및 분석**

- **튜닝 전 모델 성능**  
  - mAP@50: 30.13%  
  - mAP@50-95: 17.43%  

- **튜닝 후 모델 성능**  
  - mAP@50: 42.04%  
  - mAP@50-95: 25.65%  

CBAM 및 FEM 모듈을 통합함으로써 작은 객체와 밀집된 환경에서 YOLO 모델의 성능이 크게 향상되었습니다.

---

#### **데이터셋 정보**

- 데이터셋: [VisDrone 2019](https://github.com/VisDrone/VisDrone-Dataset)
- 어노테이션 포맷: YOLO 형식 (`x_center y_center width height`)

---

#### **추가 정보**

- **모델**: [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)  
- **라이센스**: MIT License  

---

#### **문의 및 기여**
이 프로젝트에 기여하거나 문의 사항이 있다면 [이메일 주소]로 연락해 주세요. Issue나 Pull Request도 환영합니다!

---

Jupyter Notebook 기반으로 추가적인 사용자 가이드나 예제 코드가 필요하다면 말씀해 주세요!

