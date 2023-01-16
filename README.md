# Attention is all you need
Attention is all you need를 공부하고 Transformers구조를 구현하였습니다. 

# 환경
* google colab

# train data
* 챗봇 데이터 URL: https://raw.githubusercontent.com/songys/Chatbot_data/master/ChatbotData%20.csv

* 데이터 주소에서 데이터를 읽어들여 단어 사전과 사용 데이터 구성
* 11823개의 Question & Answer 데이터셋

![image](https://user-images.githubusercontent.com/93864811/212695528-0698dc20-da34-4568-8e74-b469357d1a81.png)

# train
* 150 epochs까지 헉습
* lr = 0.0001

| Epochs  | loss |
| ------------- | ------------- |
| 0  |2.700902548673991|
| 49  |0.01676506801174853|
| 99  |0.012194018709320714|
| 149  |0.006383201721866892|

# result
* 추가적인 학습으로 loss를 더 낮출 수 있었지만 colab gpu 리소스 부족으로 구현하는 것에 중점을 두었습니다.

* ![image](https://user-images.githubusercontent.com/93864811/212698572-545ba9ad-7e19-4964-bf81-97d0c6cda832.png)

# reference
https://arxiv.org/pdf/1706.03762.pdf


