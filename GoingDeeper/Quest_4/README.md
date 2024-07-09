🔑 **PRT(Peer Review Template)**
코더: 고대현
리뷰어: 최호재


- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)** (3/3)
    > 문제에서 요구하는 최종 결과물이 첨부되었는지 확인.
    > 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    > (퀘스트 문제 요구조건 등을 지칭)
    >    - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부
    -  [x] Text recognition을 위해 특화된 데이터셋 구성이 체계적으로 진행되었다.
        -  ctc loss 측정을 위한 라벨 인코딩: <img width="455" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/d6634e09-6447-4c54-a971-6c2f417044c9">
        -  텍스트 이미지 리사이징, 배치처리 등이 적절히 수행되었다. <img width="540" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/ae68f435-dd06-422d-a933-f64b8d2b0970">
    -  [x] CRNN 기반의 recognition 모델의 학습이 정상적으로 진행되었다.
        - 학습결과 loss가 안정적으로 감소: <img width="825" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/e2a3c963-f525-454d-a335-85718f5c2c09">
        - 대부분의 문자인식 추론 결과가 정확하다.: <img width="802" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/120aaa8a-74ac-4add-9419-e779ba715af0">

    -  [x] keras-ocr detector와 CRNN recognizer를 엮어 원본 이미지 입력으로부터 text가 추출되는 OCR이 End-to-End로 구성되었다.
        -  샘플 이미지들 원본으로 받아 OCR 수행 결과를 리턴하는 1개의 함수가 만들어졌다.: <img width="466" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/1ad0c20f-bc8c-401b-aeda-38582d7ce28e">


- [ ]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)** (1/3)
    - [x]  모델 선정 이유
        - validation loss 를 통해 가장 좋은 성능을 보이는 모델을 선정하였다. <img width="640" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/77887485-af63-4589-8082-ded929974861"> <img width="687" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/78bb9f1f-6661-4636-89fc-5b04f9e5532d">
    - [ ]  Metrics 선정 이유
        - accuracy 를 사용하였으나, 선정하신 이유는 적혀있지 않았습니다. <img width="536" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/3890e9e4-8565-4a8c-9994-7df1e0b50168">
    - [ ]  Loss 선정 이유
        - CTC loss 를 사용하였으나, 선정하신 이유는 적혀있지 않았습니다. <img width="764" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/30a1d18f-656a-4d5e-b862-4c8ad16844c8">
  

- [x]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)** (2/4)
    - [x]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
        - <img width="836" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/62a221f1-45c6-4f51-97fd-06a00f5230dd">
    - [ ]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
        - 이 부분은 아쉽게도 수행되지 않은것 같습니다.
    - [x]  각 실험을 시각화하여 비교하였나요?
        - index 기반 정확도 ( Right_Count)로 정성 평가를 수행함
        - <img width="383" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/6ead759c-6855-4e6c-9b86-3b469ba7ee23">
        - <img width="390" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/10cb428f-fa4c-497e-9209-c7354bfc7490">
    - [ ]  모든 실험 결과가 기록되었나요?


- [x]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)** (4/4)
    <img width="813" alt="image" src="https://github.com/hojae-m-choi/goaiffel-quest/assets/98305832/1a674e81-710e-4230-83e6-b421ca0d15fa">
    - [x]  배운 점
    - [x]  아쉬운 점
    - [x]  느낀 점
    - [x]  어려웠던 점

