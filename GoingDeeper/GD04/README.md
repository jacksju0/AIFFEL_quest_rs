# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 신재욱.
- 리뷰어 : 박정훈.


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
<img width="354" height="226" alt="image" src="https://github.com/user-attachments/assets/3f043d6a-53ae-471e-8759-3c379bb16848" />

    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    <img width="551" height="403" alt="image" src="https://github.com/user-attachments/assets/a815db24-fd02-460b-b149-d998b276711a" />

    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**

<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/2d2a3283-44b9-4cc6-bdba-d82aa616d3f0" />

    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [ ]  **4. 회고를 잘 작성했나요?**
   <img width="807" height="396" alt="image" src="https://github.com/user-attachments/assets/d88a8d28-8503-48fc-b9cb-60add4eb9502" />

    
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    
   <img width="629" height="437" alt="image" src="https://github.com/user-attachments/assets/dfa33a21-513f-4dff-8876-4c4f75696b22" />

    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부


# 회고(참고 링크 및 코드 개선)
```<img width="819" height="512" alt="image" src="https://github.com/user-attachments/assets/81bfe41b-83bb-42c6-9901-75f677a07d7e" />

모델 훈련 시간이 5시간 이상 걸려서 테스트를 마무리 하였고,
   분석 결과 경향은 알게 되었으나, 훈련의 결과를 보려면 40 Epoch 정도를 통해
   좀더 자세한 결과를 보는 것이 좋았을 거라는 판단.

   loss와 metric 결과 Cutmix & Mixup의 성능과 결과가 비슷하게 유지 될것으로 봄.
   CutMix나 MixUp은 soft label을 사용하여 CrossEntropyLoss가 조금 더 크게 나오는 특성으로 인해 
   Validation loss가 낮은 것 만으로 판단하기는 무리가 있음.
   
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
