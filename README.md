# vue
1) vue-loader@next
2) vue-style-loader
3) @vue/compiler-sfc
<br/><br/>

# eslint
1) eslint
2) eslint-plugin-vue
3) babel-eslint

# npm
1) npm init -y 
<br/><br/>

# webpack
## Dev 설치 package
1) webpack
2) webpack-cli
3) webpack-dev-server@next
4) html-webpack-plugin
<br/><br/>

# webpack.config.js
1) entry: 파일을 읽어들이기 시작하는 진입점 설정
(webpack은 자바스크립트를 진입적으로 사용함.)
- 여러개의 진입점도 설정 가능


2) output: 결과물(번들)을 반환하는 설정
. path (생략 가능)
__dirname : 현재 파일이 있는 경로
결과물을 dist라는 폴더로 만들 것이다.

.filename

. clean : 빌드시 이전 폴더 삭제 후 dist 생성

. plugins : 다양한 플러그인들을 설정

. devServer : dev 실행시 url localhost로 보이도록 설정

3) module
rules - use : 맨 아래부터 적용됨
<br/><br/>

# package.json 설정
script: dev, build 설정
browerslist : 지원 iexplore 설정
<br/><br/>

# postcssrc.js



# index.html - script
1) reset-css 설정
<br/><br/>

# javascript
1) js - main.js
<br/><br/>

# scss
1) css-loader
2) style-loader
3) sass
4) sass-loader
5) postcss (공급업체 접두사)
6) autoprefixer
7) postcss-loader

# babel / .babelrc.js
1) @babel/core
2) @babel/preset-env
3) @babel/plugin-transform-runtime
4) babel-loader

# 기타
1) file-loader