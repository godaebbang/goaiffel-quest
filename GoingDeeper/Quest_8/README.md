🔑 **PRT(Peer Review Template)**

코더: 고대현

리뷰어: 현동철

- [x] **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**

  - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
  - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개,
    퀘스트 문제 요구조건 등을 지칭 - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부
    - ![alt text](prt_review/image1.png)
    - ![alt text](prt_review/image2.png)
    - ![alt text](prt_review/image3.png)

- [x] **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**

  - [x] 모델 선정 이유
  - [x] Metrics 선정 이유
  - [x] Loss 선정 이유
  - 위 3개는 node의 내용대로 진행하였습니다.

- [x] **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**

  - [x] 데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
    - tf record를 활용하여 train, validation으로 나누어 진행하였습니다.
  - [x] 하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
    - node의 내용대로 진행하였습니다.
  - [x] 각 실험을 시각화하여 비교하였나요?
  - [x] 모든 실험 결과가 기록되었나요?
    - ![alt text](prt_review/image4.png)

- [x] **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**

  - [x] 배운 점
  - [x] 아쉬운 점
  - [x] 느낀 점
  - [x] 어려웠던 점
  - ![alt text](prt_review/image5.png)

- 추가 리뷰
  저는 simple baseline 모델을 학습시킬때 node에 있던 내용을 토대로 class Trainer의 def compute_loss 를 약간 수정하고, node의 train 함수를 활용하여 학습을 진행하였었는데 loss가 6이하로 감소하지 않았습니다. 아래 사진처럼 keras에서 제공해주는 loss, fit function을 사용하는것과, 직접 loss를 계산, fit 하는 과정의 어떤 차이가 있는지 공부를 해야겠다고 생각했습니다.
  ![alt text](prt_review/image6.png)
