자바스크립트의 데이터 타입은 크게 2개로 나뉜다.
## Primitive Type - 값을 그대로 할당
- Number
- String
- Boolen
- null
- undefined

## Reference Type 값을 저장한 주소값을 할당 (참조)
- Object
- Array
- nction
- gExp


## Primitive Type이 메모리에 값을 담는 순서 (ex - var a = 1)

1. 메모리상에 변수명 a를 담을 공간을 확보한다.
2. 확보한 공간의 주소값을 변수명 a와 매칭한다.
3. 주소값에 값 1을 할당한다.

원시형 데이터들은 값 그 자체 이므로 서로 비교가 가능하다.

## Reference type이 메모리에 값을 담는 순서

1. 메모리에 공간을 확보한다
2. 확보한 공간에 주소값을 변수명과 매칭한다.
3. 각각의 프로퍼티의 값이 저장될 공간을 확보한다.
4. 확보한 공간에 프로퍼티의 값을 할당한다.
