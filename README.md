# rp2040_test

## 1. 블럭도
<img src="https://user-images.githubusercontent.com/65072588/174707180-eda5d597-3016-4781-89ad-246f235c04d7.JPG">

## 2. 작품 설명
아두이노 rp 2040을 PC와 연결후 기본 탑재된 LSM6DSOX센서와 온도센서를 이용하여 가속도, gyro를 그래프로 온도를 게이지로 나타냄

### Node-Red
<img src="https://user-images.githubusercontent.com/65072588/174705401-6d26e2ac-14cf-4757-9b75-2ba76c9fef97.png">

## 3. 결과
### DashBoard
<img src="https://user-images.githubusercontent.com/65072588/174705299-bdedfd46-1f56-41cd-9500-29063e0586a1.png">

### 영상
<img src="https://user-images.githubusercontent.com/65072588/174706173-a79a1582-6e22-4b83-9ede-6338810bb408.gif">

## 4. 피드백
현재 rp2040에서 PC를 거쳐 통신하는데 PC를빼고 rp2040에 탑재된 tiny mosquitto를 이용해 jetson nano와 바로 통신을 할 것
또한 현재 정제되지 않은 정보가 node-red로 통신하는데 누락된 정보가 있을 것 rp2040에서 정제된 정보를 
