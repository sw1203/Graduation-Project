# 학과 졸업프로젝트로 진행한 영유아 돌연사 방지 침대

동기들과 라즈베리파이를 이용한 영유아 돌연사 방지 침대라는 주제로 졸업 프로젝트를 진행했습니다. 통계청 자료에 따르면 0세 이하 영유아의 사망원인 1위는 질식사고입니다. 이러한 사고를 방지하기 위해 시중에 많은 제품이 나와 있습니다. 이러한 제품들은 아기의 상태를 화면으로 모니터링하는 기능이 주를 이룹니다. 그렇기에 부모가 모니터를 계속 지켜봐야 한다는 불편함이 있습니다. 이러한 불편을 해결하고자 라즈베리파이 카메라와 파이썬 라이브러리를 활용하여 얼굴 인식을 하는 기능을 추가했습니다. 얼굴 인식을 통해 아이가 수면 중 뒤집히거나 이불 등에 얼굴이 가려져 질식의 위험이 발생 시 보호자의 휴대전화로 알림과 함께 실시간 영상을 제공하는 임베디드 시스템과 안드로이드 앱을 개발했습니다.

Code - Detectface.py : 얼굴 인식관련 코드
     - dht.py : 온습도 측정 코드
     - FindIP.py : 라즈베리파이의 IP 주소를 알아내기 위한 코드
     - Stream.py : 스트리밍 서비스를 제어하기 위한 코드
        - Stream.sh : 스트리밍 서비스 시작
        - StropStream.sh : 스트리밍 서비스 강제종료
     - test_all.py : 아기 울음소리 감지 코드

[졸업작품집]7_3.zip - 발표 PPT, 설계서, 시연영상

졸업프로젝트로 모두가 처음 개발하는 것들이 많아 코드가 지저분하고 많이 부족합니다. 
