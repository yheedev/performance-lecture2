['프론트엔드 개발자를 위한, 실전 웹 성능 최적화(feat. React) - Part. 1'](https://www.inflearn.com/course/%EC%9B%B9-%EC%84%B1%EB%8A%A5-%EC%B5%9C%EC%A0%81%ED%99%94-%EB%A6%AC%EC%95%A1%ED%8A%B8-1/dashboard)의 2번째 강의를 수강한 내용을 기록했습니다.

### 실행

```
// git clone
https://github.com/performance-lecture/lecture2.git

cd performance-lecture2
code .

// 의존성 설치
npm i

// OpenSSL 호환성 이슈로 환경 변수 설정해서 legacy OpenSSL 알고리즘 허용 필요
$env:NODE_OPTIONS="--openssl-legacy-provider"

// 개발 서버 가동 (localhost:3000)
npm run start

// 평소에 이렇게 개발 서버 켭시다
$env:NODE_OPTIONS="--openssl-legacy-provider"; npm start

// JSON 서버 가동 (localhost:3001) npm run start 실행한 콘솔과 다른 콘솔에서 실행한 뒤에 종료하지 않을 것.
npm run server

// build & serve
npm run serve
```
