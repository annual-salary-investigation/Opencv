# Opencv
Opencv 학습
  - Opencv 설치경로 [https://velog.io/@kaiseong/%EB%9D%BC%EC%A6%88%EB%B2%A0%EB%A6%AC%ED%8C%8C%EC%9D%B4-OpenCV%EC%84%A4%EC%B9%98]
  - ! Opencv 설치경로 중간에 1시간정도 다운로드 하는 코드가 있는데 중간에 무선 랜 연결 끊어지지 않도록 마우스를 주기적으로 움직여 줘야한다...

![2023-05-15-112131_1920x1080_scrot](https://github.com/annual-salary-investigation/Opencv/assets/123913898/15a8f1e2-911b-49cb-b3ee-8fae1bd670d0)
설치중인 화면

라즈베리파이4 카메라 연결경로
  - sd카드를 리더기를 통해 window컴퓨터에 연결 -> "라즈베리파이 4 os 설치" 검색 후 window버젼으로 64bit로 설치 -> 설치 완료후 리더기에서 sd카드 제거해서 라즈베리파이4에 삽입 -> 기본설정 후 cmd 화면 켜서 $ libcamera-jpeg -o cam.jpg 입력 -> 끝
  - 위와 같은 경로로 카메라를 실행했을 때 안된다면 포맷 후 라즈베리파이 os를 다시 깔고 $ libcamera-jpeg -o cam.jpg 를 입력해야 할것이다.
  - 참고 [https://kdjun97.github.io/iot/raspberry-pi-install/]. 


  
