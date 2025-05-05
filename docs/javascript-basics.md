# JavaScript 기초 가이드

## JavaScript란?
JavaScript는 웹 개발에서 가장 중요한 언어 중 하나야! 웹사이트를 동적으로 만들고 사용자와 상호작용하게 해주지.

## JavaScript 시작하기
JavaScript는 별도 설치가 필요 없어. 그냥 웹 브라우저만 있으면 돼! 
- 크롬이나 파이어폭스 같은 브라우저에서 F12 키를 눌러 개발자 도구를 열고 콘솔 탭으로 가면 바로 코드를 작성할 수 있어.
- 또는 HTML 파일 안에 `<script>` 태그를 사용해서 JavaScript 코드를 추가할 수도 있지.

## 첫 번째 프로그램
다음과 같이 간단한 "Hello World" 프로그램을 만들어 볼 수 있어:

```javascript
console.log("Hello, World!");
// 또는 알림창으로 표시하기
alert("Hello, World!");
```

## 기본 문법
### 변수
```javascript
// 요즘 방식
let name = "코딩초보";
const age = 16;
let isStudent = true;

// 옛날 방식 (var는 가능하면 쓰지 마!)
var oldSchool = "이건 옛날 방식";
```

### 조건문
```javascript
if (age >= 18) {
    console.log("성인입니다.");
} else {
    console.log("미성년자입니다.");
}
```

### 반복문
```javascript
for (let i = 0; i < 5; i++) {
    console.log(`${i}번째 반복`);
}
```

### 함수
```javascript
function greet(name) {
    return `안녕, ${name}!`;
}

// 화살표 함수 (최신 문법)
const greetArrow = (name) => `안녕, ${name}!`;

console.log(greet("친구"));
```

## 다음 단계
기본적인 JavaScript를 배웠다면, 간단한 프로젝트를 시작해보는 게 좋아! 예를 들어:
- 투두리스트 만들기
- 간단한 계산기 웹앱
- 랜덤 인용구 생성기

코딩 재밌게 배워봐! 🚀