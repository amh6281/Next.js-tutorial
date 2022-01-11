<div align="center">
  <h1>📽︎Movie App📽︎</h1>
 <h4>영화 API를 활용한 Next.js 기반의 웹 사이트 입니다.</h4>
  </div>
<div align="center">
  <img src="https://user-images.githubusercontent.com/83646986/148895983-f78769c3-23b2-47e8-a080-3815199a63b1.gif" height="500"/>
</div>
<br>

## 💪 Skills
<img src="https://img.shields.io/badge/next%20js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
      
<br/>

## 📝 About The Project
> 이 프로젝트는 영화 API를 활용하여 React 기반의 웹 사이트를 만들면서, <br/> 더 나아가 Next.js를 연습하고 싶어 기획하게 되었습니다.

<br/>

## 👨‍💻 NextJS 특징
- SSR을 구현할 수 있다.
- 초기에 SSR로 렌더링한 HTML을 보내기에 SEO에 유리해지고, 페이지를 변경할 때마다 CSR방식으로 처리하기 때문에 <br /> SPA장점도 유지할 수 있다.
- 코드 분할을 통해 초기 구동 속도를 빠르게 할 수 있다.
- Page 디렉터리 안에 Page 폴더나 파일을 생성하면 자동으로 Path와 연결되기 때문에 Routing이 쉽다.
- Pre-rendering은 간단하게 각 페이지들을 위해 미리 HTML을 생성한다는 의미로 더 나은 성능과 SEO를 얻을 수 있다.
<br/>
     
## ✔︎ What to do?

- getServerSideProps를 통해 매 요청마다 페이지를 Pre-rendering 한다.

- rewrite를 사용하여 요청 경로를 다른 대상 경로로 매핑한다.

- [...params.js] 파일을 생성하여 동적인 경로를 만든다. (Dynamic Routing)

- next/router 모듈에서 useRouter를 사용하여 query에 담긴 데이터를 받아온다.
