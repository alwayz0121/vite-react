# Vite를 이용해 리액트 프로젝트 연습하기

매번 `Create React App`을 이용하다,<br>
라이브러리 번들을 더 빠르게 해주는 `vite`를 알게되어 짧게 사용해본다.
<br><br>

#### 참고 사이트

https://vitejs-kr.github.io/guide/#scaffolding-your-first-vite-project
<br><br>

## Create React App VS Vite 짧은 후기

#### <b>Create React App</b>

- 장점
  - 아직 공부하는 입장에서는, 리액트 외의 `webpack`, `babel` 등의 추가 설정을 몰라도 모든 필요한 부분이 설치되는 CRA가 접근하기 쉬웠다.<br>
- 아쉬운 점
  - (내 컴퓨터의 경우는) 설치, 개발 화면 띄우는 데에도 시간이 꽤 걸린다.

#### <b>Vite</b>

- 장점
  - Vite는 이름처럼 (프랑스어로 "빠르다"를 의미) 빠르다. <br>
    (설치, 개발 화면 띄우는 속도 등이 훨씬 빨라 만족도가 높았다.)
  - ES Module을 기반으로 Hot Module Replacement (HMR)이 빠르게 일어난다.
- 아쉬운 점
  - CRA와 달리 초기 설정을 해줘야 한다. 이 부분이 처음 진입장벽으로는 조금 있게 느껴졌다.

#### <b>그래서 나는?</b>

- 이번 기회에 Vite를 처음 알게 되었다. 초기 개발 환경 세팅 부분만 넘어가면 속도적인 면에서는 편리하다고 느꼈지만, 내가 모르는 차이점이 훨씬 많을 것이다.

- 아직은 CRA를 이용해 리액트 실력을 키우되, 굳이 하나의 생태계만 고집할 것이 아니라,<br>
  불편하다고 생각되는 부분을 따로 메모해서 개인 프로젝트에 천천히 적용해보며, 이후 회사에 들어가게 되면 관련 내용이 나올 때 의견을 드려볼 수도 있지 않을까 생각한다.
