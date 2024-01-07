# 백준

## input 가져오는 법

### 1. readFileSync 사용하기
- input 의 모든 내용일 하나의 문자열에 넣고 문제에 맞게 split 해서 쓰기 ('\n' 이나 ' ' 으로 split 해야함)
```
var fs = require('fs'); 
var input = fs.readFileSync('/dev/stdin').toString();

var num = input.split(" ").map(function(e){
    return parseInt(e);
});

console.log(num[0]+num[1]);
```
