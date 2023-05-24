# AI-Study
AI 머신러닝 및 딥러닝 학습 자료입니다.
<br><br>
기초 머신러닝 Linear_Regression부터 Fine-Tuning, 딥러닝 심화학습(GAN, 강화학습)까지 업로드 하겠습니다.
<br><br>

Linear Regression을 이용한 당뇨병 예측
-------------
<br>
<p align="left">
  <img src="./images/HW1-1.png" width="40%" height="40%"/>
  <img src="./images/HW1-2.png" width="40%" height="40%"/>
</p>
<br><br>

KNN을 이용한 손글씨 인식 with PCA
-------------
- Training Data : 50000 <br>
- Test Data : 10000 <br>
- K = 5
<br><br>
<p align="left">
  <img src="./images/HW2-1.png" width="40%" height="40%"/>　　　
  <img src="./images/HW3-1.png" width="40%" height="40%"/>
</p>
<p align="left">
　<img src="./images/HW2-2.png" width="37%" height="45"/>　　　　　　
  <img src="./images/HW3-2.png" width="37%" height="45"/>
</p>

- KNN VS PCA 차원축소<br>
  - Run Time, Accuracy 차이 비교 -> 유의미한 결과 도출
<br><br><br>

K-Means를 이용한 뇌 MRI Image Segmentation
-------------
- K = 4 (Cluster 0-3)
<br><br>

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
<br><br>

CNN Fashion MNIST Data Label Shuffle
-------------
- Training Data : 60000
- Test Data : 10000
<br><br><br>

<img src="./images/HW6-1.png" width="60%" height="30%"/>

- 정상실행
- Accuracy : 90.51%
<br><br><br>

<img src="./images/HW6-2.png" width="60%" height="30%"/>

- Label Shuffle (무작위)
- Accuracy : 10.93%
<br><br><br>

- 결론 : Data를 잘못 설정해도 Loss는 조금씩 떨어지고 정확도는 조금씩 올라간다 <br>
  - 만약 Loss 자체가 떨어지지 않는다면 Optimizer 문제 (Learning Rate)
<br><br><br>

CNN Transfer Learning(Fine-Tune)
-------------
<p align="left">
  <img src="./images/HW7-1.png" width="30%" height="40%"/>
  <img src="./images/HW7-2.png" width="30%" height="40%"/>
  <img src="./images/HW7-3.png" width="30%" height="40%"/>
</p>

- 부족한 Data Training
  - Training Data : 5000 (Class당 500개 Data)
  - Test Data : 8000
  - Accuracy : 26.675%

<br><br>

<img src="./images/HW7-4.png" width="50%" height="40%"/>

- 충분한 Data Training
  - Training Data : 50000
  - Test Data : 10000
  - Accuracy : 63.050%

<br><br>

<img src="./images/HW7-5.png" width="50%" height="150"/>

- Transer Learning
  - 마지막 8번 FC Layer 교체
  - Training Data : 5000
  - Test Data : 8000
  - Accuracy : 60.193%

<br><br>

- 결과 : Accuracy 향상 -> 유의미한 결과 도출
<br><br><br>

GAN을 이용한 손글씨 Image 생성
-------------
- Training Data : 60000 <br>
- Test Data : 10000
<br><br>

 <img src="./images/HW8-1.png" width="70%" height="100"/>
 <img src="./images/HW8-2.png" width="70%" height="100"/>
 
- D(g(z)) 변화 관찰
  - D(g(z) 수치가 향상될수록 good
<br><br><br><br>

<img src="./images/HW8-3.png" width="60%" height="60%"/>

- Generator에 의해 생성된 손글씨 Image
<br><br><br><br>
  
