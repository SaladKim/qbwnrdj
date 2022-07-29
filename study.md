기본 설정
npm install -g @vue/cli - vue-cli 설치시 vue 버전을 볼 수 있음
프로젝트 생성 시 터미널에서 바로 vue create가 실행되는데 그 때 생성 옵션을 정해야함

vue 프로젝트 구조  
- node_modules - npm으로 설치된 패키지 파일들이 모여 있는 디렉토리  
- public - 웹팩(webpack)을 통해 관리되지 않는 정적 리소스가 모여 있는 디렉토리  
- src/assets - 이미지, css, 폰트 등을 관리하는 디렉토리  
- src/components - vue 컴포넌트 파일이 모여 있는 디렉토리  
- App.vue - 최상위(Root) 컴포넌트  
- main.js 가장 먼저 실행되는 자바스크립트 파일로써, Vue 인스턴스를 생성하는 역할을 담당  
- .gitignore - 깃허브에 업로드할때 제외할 파일 설정  
- babel.config.js - 바벨(babel) 설정 파일  
- package-lock.json - 설치된 package의 디펜던시 정보를 관리하는 파일   
- package.json - 프로젝트에 필요한 package를 정의하고 관리하는 파일  
- README.md - 프로젝트 정보를 기록하는 파일