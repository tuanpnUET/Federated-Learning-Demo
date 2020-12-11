# Federated-Learning-Demo
Demo lại một phần của paper Communication-Efficient Learning of Deep Networks from Decentralized Data
**Mô hình MLP và CNN :**

python main\_nn.py

**Học liên kết với MLP và CNN:**

python main\_fed.py

**MNIST**

Kết quả được thể hiện trong Bảng 1 và Bảng 2, với các tham số C = 0,1, B = 10, E = 5.

Bảng 1. kết quả trainning 10 epochs với tỷ lệ học tập là 0,01

Model        | Acc. of IID| Acc.of Non-IID
FedAVG - MLP | 94.57%     | 70.44%
FedAVG - CNN | 96.59%     | 77.42%

Bảng 2. kết quả trainning 50 epochs với tỷ lệ học tập là 0,01

Model        | Acc. of IID| Acc.of Non-IID
FedAVG - MLP | 97.21%     | 93.03%
FedAVG - CNN | 98.60%     | 93.81%
