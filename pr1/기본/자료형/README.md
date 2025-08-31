# react 연습 1일 1커밋

# 8장 조건문

1. Number Type
   나머지를 구하는 연산은 모듈러 연산이라고 함
   console.log(num1 % num2);
   Infinity; --양의 무한대
   -Infinity; --음의 무한대
   NaN; // not a number 줄인거 -> 수치연산이 실패 했을때 결과값으로 사용
2. String Type
   let myName = "혜지니"; //여기에서 "" 나 '' 를 안쓰면 변수명으로 취급해서 저장시 오류 발생

   let introduceText = `${myName} 는 ${myLocation}에 삽니다. `;
   동적으로 만들어 줄 수 있음 (**"문자열을 조합할 때 변수를 값에 맞게 자동으로 삽입하는 것")
   -> 이걸 템플릿 리터럴 문법이라고 함 **중요

3. Boolean Type
   let isSwitchOn = true;
   let isEmpty = false;

4. Null Type(아무것도 없다)
   let empty = null;

5. undifined type
   let none;
   console.log(none); -- 변수는 선언하고 아무런 값도 할당되지 않을때 자동으로 들어가는값
