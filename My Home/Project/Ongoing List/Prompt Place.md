# Project Structure

- front end : javascript, typescript, react, nextJs, tailwindCSS
- back end : nextJs, mysql

# Domain 
- AWS ( www.promptseed.io )
- promptseed - "prompt"와 "seed"를 통합한 이름으로, 새로운 아이디어에 영감(씨앗)을 주고 육성하는 창의적인 프롬프트를 공유

# Hosting & SSL
-  AWS

# #1 Create NextJs framework
## why?
1. 라우팅 구현이 간단함
2. SSG, SSR, CSR 을 지원
3. SEO 최적화를 하기에 편리함
4. 백엔드를 따로 구축하지 않고 NextJS 에서 한번에 구축가능
	- 혼자서 모든 기능을 개발해야하는 상황에서 여러 프레임워크 및 언어를 사용하는 한계
5. React 위에 만들어진 프레임워크라서 React를 다루던 상황에서 익숙한 방법 그대로 사용가능
6. 기회가 된다면 NestJs를 이용해서 백엔드 영역을 만들어 보자


## How?
1. create NextJs app (자동 생성 사용)
	```bash
	npx create-next-app@latest --typescript
	```

2. 설치된 경로로 이동하여 정상 설치 확인 (http://localhost:3000)

	```bash
	npm run dev 
	or 
	yarn dev
	```

3.  