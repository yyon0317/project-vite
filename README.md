
Node.js 최신 LTS 버전 설치 : nvm install --lts
Node.js 버전 확인인 : node -v
설치된 LTS 버전 활성화 : nvm use lts


vite 설치 : $ npm create vite@latest
    ✔ Project name: … project-vite
    ✔ Select a framework: > Vanilla
    ✔ Select a variant: > JavaScript

프로젝트 폴더 이동 : cd project-vite

npm install

package.json 파일에 정의된 "dev" 스크립트를 실행 : npm run dev


ss

## 프로젝트 실행
- vite를 설치합니다. npm create vite@latest
- gsap를 설치합니다. npm install gsap
- lenis를 설치합니다. npm install @studio-freight/lenis
- vite를 설치 후 환경 설정을 합니다. vite.config.js파일을 만들고 다음과 같이 작성합니다.
```javascript
export default {
    root: "src",
    build: {
    outDir: "../public",
    },
};























node_modules: 이 폴더에는 프로젝트가 사용하는 모든 외부 패키지와 라이브러리들이 저장됩니다. 프로젝트의 의존성을 관리하는데 사용됩니다. 이 폴더는 보통 개발자가 직접 수정하지 않으며, npm이나 yarn과 같은 패키지 매니저가 해당 패키지들을 자동으로 설치 및 관리합니다.
public: 이 폴더에는 웹 애플리케이션의 정적 파일들이 저장됩니다. 예를 들어, index.html 파일과 같은 웹 애플리케이션의 진입점 파일이나 이미지, 폰트 등의 정적 파일이 위치할 수 있습니다.
src: 이 폴더는 웹 애플리케이션의 소스 코드가 위치하는 주요 디렉토리입니다. 보통 JavaScript, CSS, 그리고 프론트엔드 프레임워크(Vue.js, React 등)의 컴포넌트들이 이곳에 들어갑니다.
src/assets: 이 폴더는 웹 애플리케이션에서 사용되는 정적 리소스들(이미지, 아이콘 등)이 저장되는 곳입니다.
index.html: 웹 애플리케이션의 진입점 파일로서, 웹 페이지의 구조를 정의하고 다른 스크립트 및 스타일시트 파일들을 로드하는 역할을 합니다.
.gitignore: Git 저장소에 포함시키지 않을 파일과 폴더를 정의하는 파일입니다. 보통 로컬 개발 환경에서 생성되는 캐시 파일이나 빌드된 파일들을 제외하고 Git으로 관리하는 파일들을 지정합니다.
package-lock.json: npm 패키지들의 의존성 트리를 고정시키기 위해 사용되는 파일입니다. 이 파일은 개발자가 프로젝트를 배포할 때, 일관된 의존성을 보장하고 다른 환경에서도 동일한 의존성을 설치할 수 있게 도와줍니다.
package.json: 프로젝트의 메타 정보와 의존성 패키지들을 정의하는 파일입니다. 프로젝트의 이름, 버전, 작성자 정보, 스크립트 등이 포함됩니다. 또한, 프로젝트가 의존하는 패키지들과 해당 패키지들의 버전 정보도 여기에 기록됩니다.
README.md: 프로젝트에 대한 설명이나 사용법, 기여 방법 등을 기록하는 파일로서, 보통 Markdown 형식으로 작성됩니다.
vite.config.js: 웹 애플리케이션 빌드 도구인 Vite의 설정 파일입니다.
