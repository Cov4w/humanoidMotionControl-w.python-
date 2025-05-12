# humanoidMotionControl(w.python)
## 1. UART(Universal Asynchronous Receiver/Transmitter) 통신
### 로봇을 움직이기 위한 유선 통신
#### 로봇을 움직이기 위한 유/무선 통제 방법 중 유선 방법(UART)에 대해 알아보았습니다.
#### UART는 비동기 직렬 통신 프로토콜 중 하나로 두 장치간 데이터를 한비트씩 순차적으로 주고받는 방식입니다.
## 2. Protocol
### 모든 기기간에는 Protocol(통신규약)이 있다.
#### 휴머노이드의 모션을 제어하기 위한 프로토콜은 15byte로 되어있다.
## 3. pySerial
### 파이썬에서 외부기기(humanoid)를 제어하기 위한 방법 
