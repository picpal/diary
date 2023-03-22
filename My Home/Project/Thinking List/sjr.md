

# 파이썬 가상환경 설정

## 가상 환경 디렉터리 생성하기

가성환경을 만들 디렉터리로 이동
```bash
cd C:\Users\bwc\Desktop\picpal\pyprj
```

윈도우에서 명령 프롬프트를 실행하고 다음 명령어를 입력해 가상환경 용 디렉토리 생성
( 디렉토리의 명칭은 마음대로 해도 무관하지만, 가상환경을 나타낼 수 있는 명칭으로 사용하는게 좋다. )
```bash
mkdir venvs
```


## 가상 환경 만들기

생성된 가상환경 용 디렉토리로 이동
```bash
cd venvs
```

가상환경 생성 (1분 정도 소요)
- window
	```bash
	python -m venv myapi
	```
- max
	```bash
	python3 -m venv myapi
	```

위의 명령어에서 python3 -m venv는 파이썬 모듈에서 venv라는 모듈을 사용한다는 의미.
뒤에 나오는 myapi는 생성할 가상 환경의 이름 ( 자신의 환경에 맞는 이름으로 작성 )
잘 수행했다면  venv 디렉터리 아래에 myapi라는 디렉터리가 생성되어 있다.


## 가상 환경에 진입하기

### window

가상환경을 설치한 디렉토리로 이동
```bash
C:\Users\bwc\Desktop\picpal\pyprj\venvs>cd myapi
```

이동한 디렉토리의 Script 디렉토리로 이동
```bash
C:\Users\bwc\Desktop\picpal\pyprj\venvs\myapi>cd Scripts
```

해당 디렉토리에서 가상환경 실행하면 가상환경으로 진입됨. 
```bash
C:\Users\bwc\Desktop\picpal\pyprj\venvs\myapi\Scripts>activate
```


### mac

가상환경을 설치한 디렉토리의 bin으로 이동
```bash
pahkey@mymac venvs % cd myapi/bin 
```

해당 디렉토리에서 activate 실행하여 가상환경 진입
```bash
pahkey@mymac bin % source activate 
```


## 가상 환경에서 벗어나기

### window

가상환경에서 나오고 싶은경우 아래의 deactivate 명령어로 나오면 됨
```bash
(myapi) C:\Users\bwc\Desktop\picpal\pyprj\venvs\myapi\Scripts>deactivate
```


### mac
```bash
(myapi) pahkey@mymac bin % deactivate
```

## 가상 환경에 패키지 설치

fastapi를 예로 설치 ( 설치하면 해당 가상환경에만 설치되며 다른 가상환경에 영향이 없다. )
```bash
(myapi) C:\Users\bwc\Desktop\picpal\pyprj\venvs\myapi\Scripts>pip install fastapi
```

위의 명령어 실행 시 pip가 최신버전이 아닌 경우 오류가 날 수 있다. 아래의 명령어로 업데이트 후 다시 설치 실행.
```bash
python -m pip install --upgrade pip
```



## VS code 에서 가상환경 쉽게 진입하기
> 선행적으로 python 패키지가 설치되어 있어야 함.


ctrl + shft + p 를 누르면 해당 창이 열리는데 select interpreter 검색시 아래와 같은 항목이 나온다.
![[Pasted image 20230320160515.png]]





# 파이썬 함수

- .get_attribute("outerHTML")
	- webElement를 html 형태로 보여줌