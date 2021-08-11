# Information Security
1. Adversarial Robustness
  - Adversarial attack   
  :다양한 공격 기법을 이용하여 MNIST 데이터셋에 대하여 적대적 공격을 진행하였다.
    - PGD
    - FGSM
    - JSMA
    - CW_L2,Linf
    - Others
    
- Adversarial PGD defense  
  : PGD 방어기법을 통해 방어하고, 다른 공격 기법에 대하여 방어가 얼마나 잘 되는지 살펴보았다.  

- Adversarial attack + noise image  
  : 3가지 적대적 공격 기법에서, 원본 이미지가 아닌 랜덤 노이즈를 더 추가하여 공격하게 되면 얼마나 정확도가 떨어지는지 살펴본다.
  - PGD
  - FGSM
  - JSMA    
  - noise same time  
    +) 추가적으로, 각 공격 기법에 따라 학습 시키는 시간이 다르다. 시간을 동일하게 하기 위하여 이미지 갯수를 랜덤하게 늘린 후 같은 학습 시간 내의 정확도 차이를 살펴본다. (크게 차이가 나지 않는다.)
