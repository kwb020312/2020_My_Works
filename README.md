# 나의포트폴리오

---

# 트위터

<a href="https://github.com/kwb020312/Nwitter">트위터</a>

React 와 Firebase 를 사용하여 트위터를 만들었으며
Github 에서 제공하는 무료호스팅을 이용하여 호스팅함

# 머신러닝

<a href="https://github.com/kwb020312/Machine_Learning_Light">머신러닝</a>

머신러닝을 이해하기 위해 Google Machine Learning 을 이용했으며,
웹캠을 손가락으로 가린경우 밤으로 인식하기 때문에 폰트가 하얀색,  백그라운드가 검정색이 된다
웹캠을 손가락으로 가리지 않은경우 낮으로 인식하기 때문에 폰트가 검정색,  백그라운드가 흰색이 된다.

# 유튜브

<a href="https://github.com/kwb020312/ChoTube">유튜브</a>

React 와 MongoDB 를 이용하여 유튜브 클론을 만들었으며,
Axios 를 통해 서버와 클라이언트가 자유롭게 데이터를 주고받을 수 있다.

# 인스타그램

<a href="https://github.com/kwb020312/InstarClone">인스타그램</a>

Expo 를 통하여 웹앱을 만들었으며 , 인스타그램을 클론코딩함

# GraphQL

<a href="https://github.com/kwb020312/GraphQL_Client_AND_Server">GraphQL</a>

GraphQL 을 이용하여 데이터를 통신하여 보았음

# NestJs

<a href="https://github.com/kwb020312/hi-nest">NestJS</a>

NestJs 를 활용하여 테스팅을 해보았음

# 삼일상고 급식

<a href="https://github.com/kwb020312/Expo_SamilHighSchool_Meal">삼일상고 급식</a>

AWS 를 이용하여 서버를 띄우고 Expo 를 사용하여 웹에서 데이터를 스크롤링 하였음

# 페이스북

<a href="https://github.com/kwb020312/faceclone">페이스북</a>

NodeJS 서버의 다양한 모듈들을 활용하여 페이스북 클론코딩을 해보았음

---

# JavaScript 배움터

## 전역변수

```javascript
// 해당 스크립트 처럼 가장 바깥에 선언한 변수는 전역변수가 된다.
const scope = 'global'
function scope() {
  alert(scope)
}
scope()
```

## 현제시간

```javascript
// Date 생성자를 사용하여 현재시간을 구할 수 있다.
var today = new Date()
console.log(today)
```

## 화살표 함수

```javascript
// 화살표 함수는 아래와 같이 작성한다
function test() {

}
// 위의 함수를
const test = () => {

}
```

## Spread 연산자

```javascript
const a = [1,2,3]
const b = [...a]
console.log(b)
// [1,2,3]
```

## == 과 ===

```javascript
const a = 1
const b = "1"
a == b
// true
a === b
// false
// == 는 값만 === 는 타입까지 비교
```

## 정규식 적용법

```javascript
const test = '1a2b3c'
test.match(/[1-9]/g)
// ["1","2","3"]
```

## 백틱

```javascrpit
const test1 = 'hello'
// test1 = 'hello'
const test2 = `h
e
l
l
o
`
// test2 = 'hello'
```

## const , let

```javascript
const a = '1'
a = 1
// Constant error
let b = '1'
b = 1
// success
```

# 프로그래밍 상식

## HTTP HTTPS

<img src="https://upload.wikimedia.org/wikipedia/commons/d/da/Internet2.jpg"/>

HTTPS HTTP 와 달리 보안을 중요시하며 관련 인증서가 있어야 등록할 수 있다.

## Chrome Console

<img src="https://developers.google.com/web/tools/chrome-devtools/console/images/console-save-as.png?hl=ko"/>

크롬에서 F12 키를 누른다면 JavaScript 를 사용할 수 있는 콘솔창이 열린다.

## Sync Async

<img src="https://media.vlpt.us/images/sdc337dc/post/d88f437d-f95d-4a27-baaa-39749f1c17c0/image.png" />

동기 작업은 일처리를 끝낸 이후 다음 일처리로 가지만 비동기는 같이 시작한다.

##  Scope

<img src="https://media.vlpt.us/post-images/bathingape/4f517250-1384-11ea-af6d-0d4ea8242636/image.png"/>

스코프란,

```javascript
var a = '123'
function sayA() {
  var a = '456'
  return a
}
// return '456'
```

## 헝가리안

<img src="https://img1.daumcdn.net/thumb/R800x0/?scode=mtistory2&fname=https%3A%2F%2Ft1.daumcdn.net%2Fcfile%2Ftistory%2F2244753C586BD9C40C"/>

헝가리안 표기법이란

변수 이름에 데이터 타입을 접두어로 붙이는 표기법이다. 숫자라면 nVar, 배열이라면 aVar 이런 식으로 붙인다.

## FOUC

<img src="https://petrey.co/static/3dcb535cd891f09edd3c1bc710f3a77d/2d0dc/Screen-Shot-2017-05-02-at-10.29.35-AM-copy.jpg"/>

FOUC 란 외부의 CSS 코드를 불러오기 전 스타일이 적용되지 않은 페이지가 잠시 나타나는 현상이다. 

## Same Origin Policy

<img src="https://t1.daumcdn.net/thumb/R720x0/?fname=http://t1.daumcdn.net/brunch/service/user/1pJY/image/OhRUYAA_taKZtLVo5BMCpomOqUo.png"/>

동일 출처정책은 다른 도메인과의 상호작용을 제한하는 정책이다.

## DOCTYPE

<img src="https://www.minddevelopmentanddesign.com/wp-content/uploads/2009/12/shutterstock_117763438.jpg"/>

DOCTYPE은 문서형을 말하며, 해당 문서가 어떤 버전의 어떤 마크업 언어로 구성되어있는지를 의미한다.
