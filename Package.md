![stack](https://user-images.githubusercontent.com/81912557/139839678-0ddcc135-7520-46d0-9bf4-fe7313586241.PNG)

# Library 
라이브러리와 패키지는 일종의 코드 모음이다.
- 모듈과 패키지의 집합을 Lib라고 한다.
- import A from B에서 A를 모듈 B를 패키지라고 한다. (import 패키지도 가능하다.)
 
       라이브러리 예시
       
       1. 표준 라이브러리
       - math, sys, time, random '''
       2. 외부 라이브러리 
       - requests, scrapy, Numpy, matplotlib, '''
       
# Package
프로그래밍 언어마다 의미가 조금씩 상의하지만, 파이썬에서는 패키지 관리자를 사용하여 설치하기 위한 준비된 라이브러리이다.
- 특정 기능과 관련된 여러 모듈을 하나의 상위폴더에 넣은 것
- Python 3.3이후 부터는 __init__.py가 없어도 패키지로 인식하지만, 버전 호환을 위해 파일을 만드는 것이 안전함.
- A.B에서 A는 패키지 B는 모듈(ex. seaborn.load_dataset()에서 seaborn은 패키지 load_dataset()은 모듈) 

# Module
모듈의 기능을 활용하여 코드를 분리하고 공유하는데, 이때 여러 기능들(함수,변수,클래스)을 따로 구현한 파일을 모듈이라고 한다.
- import로 불러오는 것이 모듈
- 여러기능들이 뭉쳐진 하나의 파이썬 파일이다.

# Function
- 기능성을 가진 코드의 집합

      함수
      1. 내장 함수
      - 별도의 import없이 사용 가능 (str, len ''')
      2. 외장 함수
      - import를 통해 불러드린 외부 모듈안에 있는 함수 (random, readline ''')
      
# Class
객체(인스턴스)를 만들기 위한 틀(클래스)



# 참조문헌
[My porfolio blog](https://thinkreen.github.io/python/py-FunctionModuleClass/)

