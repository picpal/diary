# prompt

1. 당신은 소프트웨어 엔지니어이며, javascript, nodejs에 대해 전문적으로 알고 있습니다. 당신은 사용자의 목표, 목적, 원하는 결과에 예제, 맥락에 맞는 기타 정보들을 수집해야합니다. 프롬프트에는 당신이 제공받은 모든 정보가 모두 포함되어야 합니다. 당신은 완벽한 프롬프트를 생성할 수 있다는 확신이 들 때까지 사용자에게 질문을 해야 합니다. 당신의 답변은 명확한 형식을 갖추고 chatGPT 상호작용에 최적화 되어야 합니다. 당신의 답변은 사용자에게 목표, 원하는 출력형식, 필요한 추가정보를 묻는것으로 시작합니다.

2. nodejs 환경에서 javascript를 활용하여 웹 크롤링 기능을 구현하려 합니다. 사용하는 라이브러리는 puppeteer, cheerio 이며, 토이 프로젝트 생성 방법부터 설명 해주길 바랍니다. 프로젝트에서 크롤링할 목표 사이트는 쿠팡, emart의 주문목록 페이지입니다.

3. 계속해서 설명해줘
4. 크롤링 페이지로 이동하기 위해서 로그인 후 특정 버튼을 클릭하는 기능을 추가해줘
5. page.click('#login-button') 에서 선택자를 xpath를 사용할 수 있니?



# NodeJs crawler

## 참고 사이트

	https://www.letmecompile.com/javascript-crawler-tutorial-part3/
	
	https://velog.io/@choi-ju12g/%EB%82%A8%EB%8F%84%ED%95%99%EC%88%99-%EC%8B%9D%EB%8B%A8-%EC%96%B4%ED%94%8C-2.-Node.js%EB%A5%BC-%EB%A1%9C%EA%B7%B8%EC%9D%B8%EC%9D%B4-%ED%95%84%EC%9A%94%ED%95%9C-%ED%8E%98%EC%9D%B4%EC%A7%80-%ED%81%AC%EB%A1%A4%EB%A7%81-%ED%95%98%EA%B8%B0
	
	https://velog.io/@jekyem/NodeJS%EB%A1%9C-%ED%81%AC%EB%A1%A4%EB%A7%81%EC%9D%84-%ED%95%B4%EB%B3%B4%EC%9E%90


## 필요 라이브러리
- 