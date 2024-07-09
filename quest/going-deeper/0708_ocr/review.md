🔑 **PRT(Peer Review Template)**

reviewer: 이현동  
coder: 권영찬

- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
    > - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    > - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 퀘스트 문제 요구조건 등을 지칭
    >    - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부
        
    - [x] Text recognition을 위해 특화된 데이터셋 구성이 체계적으로 진행되었다.
        - text image resizing, label encoding, batch, etc...  
            ![image](https://github.com/DevHDL/aiffel-research-yck/assets/163500244/7a44635c-295c-4f71-88fe-55c5a5caae0d)
            ![image](https://github.com/DevHDL/aiffel-research-yck/assets/163500244/74bb7fdd-9a38-433e-acab-e71b6f3c024a)

    - [x] CRNN 기반의 recognition 모델의 학습이 정상적으로 진행되었다.  
         ![image](https://github.com/DevHDL/aiffel-research-yck/assets/163500244/f0f3082a-525d-4214-bff3-dc703d3fdbfb)

    - [x] keras-ocr detector와 CRNN recognizer를 엮어 원본 이미지 입력으로부터 text가 출력되는 OCR이 End-to-End로 구성되었다.  
        ![image](https://github.com/DevHDL/aiffel-research-yck/assets/163500244/a97625e1-b9fe-42f5-b3bc-12d21d1d6932)

    
- [x]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
    > - [ ]  모델 선정 이유
    > - [ ]  Metrics 선정 이유
    > - [ ]  Loss 선정 이유
    
    - 각 단계별로 markdown을 잘 활용함
      ![image](https://github.com/DevHDL/aiffel-research-yck/assets/163500244/9e2527e9-c179-4092-9607-d6f7efb6dea1)
    - 단, 복잡한 코드에서의 주석도 함께 있으면 좋을 것 같습니다.

- [x]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**
    > - [ ]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
    > - [ ]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
    > - [ ]  각 실험을 시각화하여 비교하였나요?
    > - [ ]  모든 실험 결과가 기록되었나요?
    
    - 루브릭에 해당하는 부분은 모두 존재함
    - 실험결과도 잘 나와있습니다.  
      ![image](https://github.com/DevHDL/aiffel-research-yck/assets/163500244/ec609fd6-fb6c-4a7d-ade8-49bdb4cb1005)


- [x]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
    ![image](https://github.com/DevHDL/aiffel-research-yck/assets/163500244/dc25ddaa-53f8-48ea-8024-c177764c6087)

    - [x]  배운 점
    - [x]  아쉬운 점
    - [x]  느낀 점
    - [x]  어려웠던 점
