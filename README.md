# 2021학년도 1학기 SW교육성과컨벤션 AISW공모전 출품작

<img src ="http://swai.smu.ac.kr/data/editor/2105/efc9e4b4cf8c88e997320922cf804d99_1621317756_2321.png" height = 400px >


##주제##  
영상인식을 통해 얼굴과 눈을 탐지하고, 눈의 상태를 파악하여 졸음운전을 방지할 수 있는 SW 

##팀원##  
[송영도](https://github.com/0csong)
[김민철](https://github.com/201810759)
[김동욱](https://github.com/DongwookKim0823)
[전수민](https://github.com/Sumsum99)

## 핵심 기능  Key Feature
- 사용자의 현재 눈상태를 PERCLOS로 파악하여 사용자의 피로도상태를 알려줌

- 사용자가 졸음으로 판단될 경우 경고 메세지와 소리를 출력하여 사용자에게 졸음운전 경고

##대략적인 구현 설명##  
- EYE learning은 CNN모델 코드

- 눈감지(최종)이 SW구현코드

- CNN으로 뜬눈과 감은 눈을 판단 할 수 있게 학습 

- 영상을 길이가 50인 queue에 담아 PERCLOS표현(제한된 시간내에 판별하는것이 졸음 판단에 더 우수)


**발표 영상 링크**  
https://youtu.be/xvVSjHP6QJI
