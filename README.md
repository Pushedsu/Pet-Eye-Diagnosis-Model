# Pet-Eye-Diagnosis-Model


## 라벨 목록
- Conjunctivitis: 결막염
- Corneal Ulcerative Disease: 궤양성각막질환
- Cataract: 백내장
- None Corneal Ulcerative Disease: 비궤양성각막질환
- Pigmented Keratitis: 색소 침착성 각막염
- Entropion: 안검 내반증
- Blepharitis: 안검염
- Eyelid Tumor: 안검종양
- Nuclear Sclerosis: 핵경화
- Epiphora: 유루증
- NoneExistence: 무증상

개 안구 이미지만 학습한 모델입니다.

### 참고자료
https://zeuskwon-ds.tistory.com/49 를 클론하여 코드 작성하였습니다.

더 많은 데이터를 넣어 시도해본 전이학습 1epoch 시간과 accuarcy입니다.

아래 표의 데이터 셋의 비율은 간이안구진단모델_테스트.ipynb에서 확인할 수 있습니다.

v1과 테스트 파일의 데이터 셋의 차이가 있습니다. 그리고 v1에는 overfitting을 방지하는 callbacks 옵션을 추가하였습니다.

![1](https://user-images.githubusercontent.com/109027302/230709038-16776a4c-fa41-46ff-a25a-55e08a28b741.PNG)
