# About The Project
가스 누출 사고는 다른 사고보다 많은 사망자를 내는 사고이며 끊임없이 사고가 있어왔다.
가스는 적외선 센서로 탐지 가능하기에 라즈베리파이의 적외선 센서로 가스탐지기를 만든다. 
라즈베리파이의 적외선 센서가 감지하면 LCD모듈을 이용해 시야 정보를 제공한다.

# Feature List
1. LCD 모듈로 시야 정보(문자) 제공
2. LED 센서로 시야 정보(빛) 제공
3. PIR 센서로 적외선 탐지

#  Feature List Details
1. 적외선 센서에 적외선이 탐지 된다.
2. 해당 적외선 센서 데이터를 LED 센서에 전달한다.
3. 적외선 센서 데이터를 LCD 모듈에 전달한다.
4. LED 센서는 녹색, 빨간색 빛을 노출하며 LCD모듈은 각 'GAS', 'NOT GAS' 텍스트 정보를 노출시킨다.
5. 이는 0.5초 주기로 센서 값을 요청, 전달한다.

# Hardware Configuration
![하드웨어 구성](https://user-images.githubusercontent.com/76561461/190068386-91173fa4-7f0b-4177-b5d3-8fe9dea49e89.PNG)
![하드웨어 구성2](https://user-images.githubusercontent.com/76561461/190068477-44df6122-0f8f-49ab-93d3-869ed6967b92.PNG)
<br/>

# Demo
https://youtu.be/3QMTGd7q3I4
