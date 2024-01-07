# 1주차 정리

## 스택

추가된 요소를 사용 가능한 메모리의 가장 앞 주소에 배치하는 <u>*선형 데이터</u> 구조

LIFO(last in, first out) 후입선출, 먼저 들어간 것이 나중에 나오는 자료 구조

**용어정리** 

- `push` : 스택에 요소를 추가하는 동작
- `pop` : 스택에 요소를 꺼내는 연산 (마지막으로 추가된 요소가 삭제됨)

### 스택 구현

- `top` : 가장 위의 있는 데이터의 인덱스 (스택에 아무것도 저장되어 있지 않다면 0)
- `push` : top을 1 증가시키고 Top이 가르키는 데이터에 위치 조정
- `pop` : top의 위치의 데이터를 반환하고 top을 1 감소

https://github.com/TheAlgorithms/JavaScript/blob/master/Data-Structures/Stack/Stack.js#L11-L57

---
<u>*선형 데이터</u> : 자료를 구성하는 원소들을 순차적으로 나열시킨 형태

## 큐

각 요소에 우선순위를 부여하는 데이터 구조의 한 종류

FIFO(first in first out) 선입선출, 큐에 가장 먼저 추가된 요소가 우선적으로 삭제되는 자료구조

**용어정리** 

- 인큐(enqueue) : 큐에 요소를 추가
- 디큐(dequeue) : 큐에서 요소를 삭제

### 큐 구현

https://github.com/TheAlgorithms/JavaScript/blob/master/Data-Structures/Queue/Queue.js#L9-L114