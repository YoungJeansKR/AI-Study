# AI-Study
AI 머신러닝 및 딥러닝 학습 자료입니다.
<br><br>
기초 머신러닝 Linear_Regression부터 Fine-Tuning, 딥러닝 심화학습(GAN, 강화학습)까지 업로드 하겠습니다.
<br><br><br><br>

Linear Regression을 이용한 당뇨병 예측
-------------
<br>
<p align="left">
  <img src="./images/HW1-1.png" width="40%" height="40%"/>
  <img src="./images/HW1-2.png" width="40%" height="40%"/>
</p>
<br><br><br>

KNN을 이용한 손글씨 인식 with PCA
-------------
<br>
<p>
  - Training Data: 50000 Test Data: 10000
  - K = 5
 </p>
<br><br><br><br><br>

<p align="left">
  <img src="./images/HW2-1.png" width="40%" height="40%"/>　　　
  <img src="./images/HW3-1.png" width="40%" height="40%"/>
</p>
<p align="left">
　<img src="./images/HW2-2.png" width="37%" height="45"/>　　　　　　
  <img src="./images/HW3-2.png" width="37%" height="45"/>
</p>
- KNN VS PCA 차원축소
  - run time, Accuracy 차이 비교 -> 유의미한 결과 도출
<br><br><br>

K-Means를 이용한 뇌 MRI Image Segmentation
-------------
<br>
- K = 4(Cluster 개수 = 4)
<br>

<p align="left">
  <img src="./images/HW4-1.png" width="30%" height="30%"/>
  <img src="./images/HW4-2.png" width="30%" height="30%"/>
</p>
<p align="left">
  <img src="./images/HW4-3.png" width="30%" height="30%"/>
  <img src="./images/HW4-5.png" width="30%" height="30%"/>
</p>
<p align="left">
  <img src="./images/HW4-4.png" width="30%" height="30%"/>
  <img src="./images/HW4-6.png" width="30%" height="30%"/>
</p>
<br><br><br>

CNN MNIST Data Label Shuffle
-------------
<br>
- Training Data: 60000 Test Data: 10000
<br>
<img src="./images/HW6-1.png" width="40%" height="40%"/>
<img src="./images/HW6-2.png" width="40%" height="40%"/>
결론 : Data를 잘못 설정해도 Loss는 조금씩 떨어지고 정확도는 조금씩 올라간다
-> 만약 Loss 자체가 떨어지지 않는다면 Optimizer 문제(Learning Rate)
<br><br><br>

CNN Transfer Learning(Fine-Tune)
-------------
<br>
DATA LOAD (STL10 Dataset) 96X96X3 클래스10개 클래스당 500개 => 총5000개 데이터 => 충분히 훈련안됨 test데이터는 8000개
<img src="./images/HW7-1.png" width="40%" height="40%"/>
<img src="./images/HW7-2.png" width="40%" height="40%"/>
<img src="./images/HW7-3.png" width="40%" height="40%"/>
<img src="./images/HW7-4.png" width="40%" height="40%"/>
<img src="./images/HW7-5.png" width="40%" height="40%"/>
Training Data: 50000 Test Data 10000
Replace the last few layers 분류기가 달라서 이전 마지막 8번 FC 출력기만 제거하고 갈아끼웠음
Accuracy 향상 -> 유의미한 결과 도출
<br><br><br>

GAN을 이용한 손글씨 Image 생성
-------------

<br>
- Training Data: 60000 Test Data: 10000
<br>

<img src="./images/HW8-1.png" width="40%" height="40%"/>
<img src="./images/HW8-2.png" width="40%" height="40%"/>
<img src="./images/HW8-3.png" width="40%" height="40%"/>
<br><br><br><br>
  
