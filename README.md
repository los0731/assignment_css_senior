##assignment_css_senior

#### **미션**
Turepic은 무료로 고해상도 사진을 다운로드 받을 수 있는 서비스 입니다.
제공된 목업 파일은 서비스의 메인 페이지입니다.

기획적으로 검색어를 입력하면 해당 검색 페이지로 이동하고, 
사용자가 목록의 끝까지 스크롤 다운하면 추천 이미지가 자동으로 로드 되도록 할 개발할 예정입니다.

주어진 `index.html`과 `style.scss`는 내부에서 개발 예정인 목(Mock) 입니다.
만약 기획적인 의도에 부합하면서 코드의 퀄리티를 향상할 수 있는 부분이 있다면 
개선점을 코멘트하고 발전 방향을 제시해주세요. 


#### **SCSS 활용**
생활코딩의 [SASS 설치 및 적용 가이드](https://opentutorials.org/module/237/2489https://opentutorials.org/module/237/2489)를 참고하였습니다. 

윈도우에서 설치
1. http://rubyinstaller.org/에 방문해서 ruby를 설치한다.
2. 윈도우키+R키를 누르고 `cmd`를 입력한다.
3. `gem install sass` 를 입력해서 sass 컴파일러를 설치한다.

맥/리눅스에서 설치
1. 맥과 리눅스에는 ruby가 설치 되어 있기 때문에
   `gem install sass`를 입력해서 sass 컴파일러를 설치한다.
   
SCSS 사용법
아래는 style.scss 파일이 변경될 때마다 자동으로 style.css파일로 변환해주는 명령
```
$ sass --watch style.scss:style.css
```

아래는 stylesheets/sass 디렉토리에 있는 모든 sass 파일을 CSS로 변환한 후에 stylesheets/compiled 디렉토리로 이동하는 명령

```
sass --watch stylesheets/sass:stylesheets/compiledsass --watch stylesheets/sass:stylesheets/compiled
```
