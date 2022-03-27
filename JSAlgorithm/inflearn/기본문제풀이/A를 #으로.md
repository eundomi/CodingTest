## 📍 A를 #으로

### 문제 설명

대문자로 이루어진 영어단어가 입력되면 단어에 포함된 ‘A'를 모두 ’#‘으로 바꾸어 출력하는 문제입니다.<br>

### 코드 구현

```
function solution(s) {
  let answer = "";
  for (let x of s) {
    if (x == "A") answer += "#";
    else answer += x;
  }
  return answer;
}

let str = "BANANA";
console.log(solution(str));

```
