<div align=center>
   <h1> FDS18-Tech-Interview </h1>
   <img width="300px" src="https://www.pinclipart.com/picdir/big/15-151793_download-rubber-duck-png-clipart-rubber-duck-clip.png"/>
   <p>패스트캠퍼스 프론트엔드 과정 18기 수강생을 위한 면접질문 모음 레포</p>
</div>

> 러버덕 진행 시 컨텐츠로 활용될 주제 모음입니다. 자신의 답변은 `Pull Request`로 공유주세요! 건의사항이나 질문은 `Issue`로 참여해주시면 됩니다.

<br/>

## 답변저장소

1. [Language](#Language)

   - [Javscript](https://github.com/FC-FrontEnd-School/FE18-Tech-Interview/tree/main/Language/javascript)

2. [CS](#CS)

   - [네트워크](https://github.com/FC-FrontEnd-School/FE18-Tech-Interview/tree/main/CS/network)
   - [자료구조](https://github.com/FC-FrontEnd-School/FE18-Tech-Interview/tree/main/CS/data-structure)
   - [운영체제](https://github.com/FC-FrontEnd-School/FE18-Tech-Interview/tree/main/CS/OS)
   - [데이터베이스](https://github.com/FC-FrontEnd-School/FE18-Tech-Interview/tree/main/CS/database)

3. [Frontend](#Frontend)

   - [Browser](https://github.com/FC-FrontEnd-School/FE18-Tech-Interview/tree/main/Frontend/Browser)
   - [Frontend](https://github.com/FC-FrontEnd-School/FE18-Tech-Interview/tree/main/Frontend/Frontend)

- [그 외 좋은 자료 추천](https://github.com/FC-FrontEnd-School/FE18-Tech-Interview/tree/main/etc)

<br/>

## 질문 목록

PR로 contribute해보세요!

---

# Language

## Javascript

- JS의 객체 생성 방식을 3가지 이상 설명하라
- 자바스크립트에서 private한 속성을 만드는 방법
- JS에서 재귀호출로 인한 stack overflow를 방지하는 방법
- 클로저는 무엇이며, 왜 사용하는가
- `==`과 `===`의 차이와 `===`을 사용하는 경우를 설명
- Class의 확장(extends)의 내부 동작을 설명
- JS의 `this`가 참조하는 값을 설명
- JS의 비동기 처리 방식을 설명
- 객체를 탐색하는 방법에 대해서 2가지를 작성해보세요.
- NodeList 타입에 대해 Array의 프로토타입 메서드를 사용하는 방법
- immutable과 mutable의 차이
  - JS의 immutable 객체의 종류
  - immutability의 장단점
  - 자신이 코드에서 불변성(immutability)를 달성하는 방법을 소개하라.
- undefined와 null의 차이점을 설명하라
- 다음과 같이 동작하는 `flatten`함수를 reduce로 구현하라
  ```js
  const arr = [
    [1, 2],
    [3, 4],
    [5, 6],
  ];
  const flattenedArray = flatten(arr);
  console.log(flattenedArray); //[1, 2, 3, 4, 5, 6];
  ```

<br/>

---

# CS

## 자료구조

- Heap과 Stack의 차이
- Binary Search Tree 에 대해 알고 있는가, 설명해달라

<br/>

---

# Frontend

## Browser

- 브라우저의 렌더링 동작과정을 짧게 설명
- SSR의 정의와 관련 경험
- 브라우저 저장소의 종류
- CORS란 무엇인가
  - CORS 해결 방식을 아는대로 열거하고, 자신이 자주 사용하는 방법 1가지와 실제 경험을 공유해주세요.
- Virtual DOM의 개념과 장단점
- REST API로 받은 데이터의 타입과 가공방법을 설명하라

## Frontend

- 프론트엔드 빌드 시스템을 설명
- 모듈 번들러의 역할과 종류
- JS 프레임워크 경험. 무엇을 왜 사용했나. 느낀 장단점.
- “기획 - 디자인 - API 개발 - 프런트엔드 개발”의 서비스 절차에서 프런트엔드 개발자의 역할은 무엇이라고 생각하는가
- 백엔드 개발 경험이 있는가
  - REST API 구축 경험과 구현 관점에서의 간단한 REST API 설계 방식 설명해 보세요. 브라우저의 URL 요청을 받아서 서버의 데이터를 화면에 다시 뿌려주기까지의 백엔드 쪽의 플로우를 알고 있는지 확인하는 차원.
- 프론트엔드의 성능 최적화란? 관련 경험이 있다면 소개해달라.
- 웹 서비스를 기획부터 배포까지 스스로 해본 경험이 있는가?

---

## Reference

- https://github.com/JaeYeopHan/Interview_Question_for_Beginner
- https://github.com/yangshun/front-end-interview-handbook/blob/master/contents/kr/javascript-questions.md
- https://joshua1988.github.io/web-development/interview/frontend-questions/#%EB%82%98%EC%98%AC-%EC%88%98-%EC%9E%88%EB%8A%94-%EC%A7%88%EB%AC%B8
