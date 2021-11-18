#로드셀저울 - HX711 신호증폭기 - 라즈베리파이가 연결된 경우에 작동하는 코드 입니다.


1. pip install -r requirements.txt 해당 명령어로 패키지 설치

2. 아래 링크에서 가중치를 저장한 뒤 data 폴더에 넣고 run하면 정상 작동합니다.(파이참 기준)
https://drive.google.com/file/d/1Fhug0s_wgZTGXXMvVso9K-vfmxMFo5Vr/view?usp=sharing

파일 명 : yolov3_11.09_final.weights

7개의 라벨 데이터 구별 가능
['닭강정', '짜장면', '짬뽕', '탕수육', '단무지', '만두', '라볶이']

opencv 파일 관련 오류가 날 경우 opencv3 버전으로 다운그레이드 또는 pip install opencv-python==4.1.2.30 입력시
특정 버젼으로 설치해 달라는 버젼으로 설치 하면 정상작동됩니다.