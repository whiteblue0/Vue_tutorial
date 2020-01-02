# Starting Vue

## 00. 환경 구성

1. NodeJS 설치 (npm 구축)
2. `$ npm i -g @vue/cli`
3. `$ vue init webpack hello-vue`
4. `$ npm start`

Linting Error 해결법:

1.

build /webpack.base.conf.js파일에서 모듈-> 규칙의 eslint에 대한 규칙을 주석 처리하거나 삭제.

`````` javascript
module: {
    rules: [
//    ...(config.dev.useEslint ? [createLintingRule()] : []),
``````

2.

프로젝트에 `config\index.js`파일에서 `useEslint: false`로 변경



## 01. 