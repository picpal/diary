

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

가상환경 생성
- window
	```bash
	python -m venv myapi
	```
- max
	```bash
	python3 -m venv myapi
	```