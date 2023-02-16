## Resnet50 기반 버섯 및 야생초 이미지 분류 모델 개발


**📃 상세 내용**

![버섯 결과](https://user-images.githubusercontent.com/86357651/219311470-30e78a4d-8394-4214-9d4b-b9fb2793c85c.png)

<aside>
신종 코로나바이러스 감염증(코로나19) 발생 이후 실내 활동이 제한되면서 근교 산을 찾는 방문객이 전년보다 5%가량 증가했다. 이에 따라 등산객 사이에서 일어나는 사고도 증가하였다. 그중 일반인들은 산속에서 자라는 야생초와 버섯의 식용 가능을 구분하지 못하여 매년 자연독으로 인한 심각한 인명피해가 발생한다. 이러한 문제점을 해결하고자 야생초와 버섯의 종류를 구분해 주는 높은 정확도를 가진 이미지 분류 모델을 만들고자 한다.
</aside>
<br/>
<br/>

- Dataset: 버섯(20종 각각 450장) + 야생초(20종 각각 1000장)
- Train : Validation = 8 : 2
- Model : Resnet50 + Dropout(0.1)
- Optimizer : SGD(Stochastic Gradient Descent)
- Learning rate: 0.01
- Evaluate 결과: 정확도(95.21%), loss 값(0.2465)

<br/>
<br/>

**🛠 사용 기술**
- Python
- Tensorflow
