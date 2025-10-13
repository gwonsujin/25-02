| 주제/단락               | 내용                                                                                                   |
| ------------------- | ---------------------------------------------------------------------------------------------------- |
| LED 정의              | LED는 Light Emitting Diode로 전류가 흐를 때 빛을 내는 반도체 소자이다.                                                  |
| LED 회로 구성 요소        | LED 동작에는 저항(Resistor)이 필요하며, GPIO 핀과 GND를 통해 연결한다.                                                   |
| LED 회로 연결           | GPIO 18번 핀을 +로, GND를 -로, 220Ω 저항(적·적·갈)과 함께 LED를 연결한다.                                               |
| 브레드보드               | 브레드보드는 전자부품 실습용 보드로 전원과 신호를 쉽게 배치할 수 있다.                                                             |
| GPIO 제어             | GPIO.output(18, HIGH) 명령으로 LED를 켜고, GPIO.output(18, LOW) 명령으로 LED를 끌 수 있다.                           |
| LED 점멸 제어 프로그램 설정   | GPIO.setmode(GPIO.BCM)으로 핀 번호 방식을 설정하고, GPIO.setup(LED, GPIO.OUT)으로 LED 채널을 출력용으로 설정한다.              |
| LED 점멸 제어 프로그램 실행   | 무한 루프에서 LED를 1초 간격으로 켰다 끄는 방식으로 LED 점멸을 구현한다.                                                        |
| 예외 처리               | KeyboardInterrupt 발생 시 LED를 끄고 GPIO.cleanup()으로 자원을 정리한다.                                            |
| PWM 정의              | PWM(Pulse Width Modulation)은 디지털 신호의 펄스 폭을 조절하여 아날로그 출력 효과를 내는 방식이다.                                 |
| PWM 사용 가능 핀         | PWM은 GPIO 12, 13, 18, 19번 핀에서만 사용할 수 있다.                                                             |
| PWM LED 밝기 제어 원리    | PWM 듀티사이클을 0~100%로 변화시켜 LED 밝기를 점차 밝게 하거나 어둡게 조절할 수 있다.                                              |
| PWM LED 밝기 제어 프로그램  | GPIO.PWM(LED, 100)으로 인스턴스를 생성하고 start(0)으로 시작, ChangeDutyCycle(i)로 듀티사이클을 조절한다.                      |
| Grove Pi+ 보드 소개     | Grove Pi+ 보드는 디지털 포트 7개, 아날로그 포트 3개, I2C 포트 3개, GrovePi 연결 시리얼 포트, 라즈베리파이 연결 시리얼 포트, Grove 헤더로 구성된다. |
| Grove Pi+ 연결 환경     | Grove Pi+ 보드는 라즈베리파이와 직렬 포트로 연결하여 다양한 센서와 액추에이터를 쉽게 사용할 수 있다.                                        |
| Grove Pi+ LED 실습    | LED를 D4 포트에 연결하고, digitalWrite 함수로 LED를 1초 간격으로 켜고 끈다.                                               |
| Grove Pi+ LED 실습 코드 | Python 코드에서 grovepi 라이브러리와 pinMode, digitalWrite를 사용해 LED를 제어한다.                                     |
| Grove Pi+ 예외 처리     | KeyboardInterrupt 발생 시 LED를 끄고 반복을 종료하며, IOError 발생 시 Error 메시지를 출력한다.                               |
