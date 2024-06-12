🔑 **PRT(Peer Review Template)**

- [o]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
    - [o] 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
      사전학습된 모델 말고도 직접학습한 모델의 정확도를 85%기준을 넘겨서 실험을 진행했습니다
      <img width="790" alt="image" src="https://github.com/godaebbang/goaiffel-quest/assets/132184507/0028c0ee-8e63-40a4-acec-4ffe2ec2845e">
      임베딩한 결과또한 사전학습모델과 직접학습모델을 비교하여 진행했음이 보여집니다
      <img width="577" alt="image" src="https://github.com/godaebbang/goaiffel-quest/assets/132184507/e6bf2964-2f98-4243-a889-d9530d979ee0">
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 퀘스트 문제 요구조건 등을 지칭
    - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부
      <img width="789" alt="image" src="https://github.com/godaebbang/goaiffel-quest/assets/132184507/9e072525-0216-4b3e-b2b4-3f6eb49103bc">


- [o]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
    - [o]  모델 선정 이유
    - [o]  Metrics 선정 이유
    - [o]  Loss 선정 이유
    <img width="896" alt="image" src="https://github.com/godaebbang/goaiffel-quest/assets/132184507/5c70b49d-d3a1-4bb1-ba75-3bec2a92f9ed">
    <img width="951" alt="image" src="https://github.com/godaebbang/goaiffel-quest/assets/132184507/4f83d11d-5531-4efc-9fb9-30e384fb4672">
    각 모델별로 테스트를 진행했고 그에 따른 세부적인 회고와 문제점들을 작성해주셨습니다.
    <img width="951" alt="image" src="https://github.com/godaebbang/goaiffel-quest/assets/132184507/24310106-5749-4e01-a52d-e3d67e6ba600">
    또한 랜덤서치를 이용해 하이퍼파라미터 튜닝을 진행해 정확도를 높이는 학습을 진행하셨습니다.
  
- [o]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**
    - [o]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
    <img width="762" alt="image" src="https://github.com/godaebbang/goaiffel-quest/assets/132184507/d859a07c-e2e9-422b-9469-070fe0c2fb5b">
  데이터를 train 50%, validation, test은 25% 씩 분리해 사용햇습니다.
    - [o]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
      위에서 말했듯이 랜덤서치를 이용한 하이퍼파라미터 튜닝을 진행했습니다.
    - [o]  각 실험을 시각화하여 비교하였나요?
    <img width="562" alt="image" src="https://github.com/godaebbang/goaiffel-quest/assets/132184507/04ddcb29-5588-425c-a8b6-3ef44e7cced9">
    <img width="967" alt="image" src="https://github.com/godaebbang/goaiffel-quest/assets/132184507/0994bfa4-35ad-42e6-8988-97acdb7cfd9c">
    - [o]  모든 실험 결과가 기록되었나요?
    - 상세히 자세하게 마크다운형식으로 기록되어 실험을 확인하기에 용의합니다
    - <img width="910" alt="image" src="https://github.com/godaebbang/goaiffel-quest/assets/132184507/83ba3402-643e-44cd-b679-2700c672941f">


- [o]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
     <img width="927" alt="image" src="https://github.com/godaebbang/goaiffel-quest/assets/132184507/8b714a94-894a-4f59-9e27-8c8524eb16fc">
     회고가 상세히 기록되어있고 코드리뷰를 통해 RandomSearch를 이용하게된것을 이야기해주셨습니다. 또한 에폭을 진행할수록 과적합되는 문제를 발견해 말씀해주셨습니다.
    - [o]  배운 점
    - [o]  아쉬운 점
    - [o]  느낀 점
    - [o]  어려웠던 점
