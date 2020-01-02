# Starting Vue

## 00. 환경 구성

1. NodeJS 설치 (npm 구축)

2. `$ npm i -g @vue/cli`

3. `$ vue create <project-name> `

4. bootstrap 필요할 때: `$ npm i bootstrap-vue bootstrap` 

   - `main.js`에 다음 코드 추가

   - ```javascript
     import BootstrapVue from 'bootstrap-vue'
     import 'bootstrap/dist/css/bootstrap.min.css'
     import 'bootstrap-vue/dist/bootstrap-vue.css'
     
     Vue.use(BootstrapVue)
     ```



## 01. Vue 프로젝트 구성

**`App.vue`**: 메인페이지

`/views`: link 별 개별 페이지

`components`: 메인, 개별 페이지의 반응형 요소들



