🔑 **PRT(Peer Review Template)**
- 코더 : 고대현
- 리뷰어 : 이정훈


- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부
![image](https://github.com/godaebbang/goaiffel-quest/assets/169136233/472c9085-7a88-46df-b8af-3461c36a3e41)
    - [ ]  ResNet50 + GAP + DenseLayer 결합된 CAM 모델의 학습과정이 안정적으로 수렴하였다.
    - [v]  CAM 방식과 Grad-CAM 방식의 class activation map이 정상적으로 얻어지며, 시각화하였을 때 해당 object의 주요 특징 위치를 잘 반영한다.![image](https://github.com/godaebbang/goaiffel-quest/assets/169136233/7e94a2cf-0cfd-4d9e-84b3-c18b355aefaa)

    - [v]  CAM과 Grad-CAM 각각에 대해 원본이미지합성, 바운딩박스, IoU 계산 과정을 통해 CAM과 Grad-CAM의 object localization 성능이 비교분석되었다.![image](https://github.com/godaebbang/goaiffel-quest/assets/169136233/1dd5f0b9-6e98-4624-b576-bb62c996d560)


- [v]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
    - [v]  모델 선정 이유 ![image](https://github.com/godaebbang/goaiffel-quest/assets/169136233/958d17e2-aaab-4609-9d15-5c0145413ac8)

    - [v]  Metrics 선정 이유
    - [v]  Loss 선정 이유

- [ ]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**
    - [v]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
    - [ ]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
    - [v]  각 실험을 시각화하여 비교하였나요?
    - [v]  모든 실험 결과가 기록되었나요?

- [v]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
    - [v]  배운 점
    - [v]  아쉬운 점
    - [v]  느낀 점
    - [v]  어려웠던 점
![image](https://github.com/godaebbang/goaiffel-quest/assets/169136233/0e011aa4-8abc-46e6-ac02-8878fd7b75e6)

