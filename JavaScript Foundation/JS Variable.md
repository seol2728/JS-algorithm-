
# 자바스크립트 변수

## 자바스크립트에서 변수 사용법

```
/*
var 변수는 중복으로 사용해도 오류X
*/

var number;
var name;
var seol;
var falg = false;
var Hello = "Hello, World!";

/*
const let은 변수 재선언 X
단 const는 변수 재선언, 재 할당등 불가능
*/
const seol;

seol = 'handsom'
console.log(seol) //오류다 이 시꺄!

let seol;

seol = 'Ugly'
constole.log (seol) //Ugly
```

**자바스크립트** 에서 변수는 var, let, const 가 존재한다

<details><summary>
var은 간단한 테스트에서 편리하게 사용 가능하지만 코드가 많아지면 어디에서 어떻게 사용되는지 파악이 힘들고 값이 바뀔수도 있음
</summary>
</details>


<details><summary>
const는 값이 재 할당이 안되기 때문에 맨 처음에 선언해두고 사용하면 같은 변수를 사용했을때 오류를 내보냄
</summary>
</details>


<details><summary>
let은 값이 재 할당이 되기때문에 변수 안에 내용을 넣어야 할때 사용하면 좋음
</summary>
</details>




