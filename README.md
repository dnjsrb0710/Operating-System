# Operating-System

## COMP312 / 운영체제 / 2020 / 1학기 / 강순주

>## 1번과제
> #### 배열과 Linked List 로 구현한 검색 기능 . 학생의 이름 검색 시 학번 출력, 학번 검색시 이름 출력.
>>코드 :  [HW1](https://github.com/dnjsrb0710/Operating-System/blob/main/HW01_2015110899_%EC%9D%B4%EC%9B%90%EA%B7%9C/main.c)

>## 2번과제
>#### 나만의 쉘을 만들어서 파일 내의 프로그램을 실행시켜라. fork()함수와 exec()함수들을 사용해 부모,자식 프로세스를 만들어 봄으로써 멀티프로세스의 개념을 이해한다.
>>코드 :  [myshell.c](https://github.com/dnjsrb0710/Operating-System/blob/main/HW02_2015110899_%EC%9D%B4%EC%9B%90%EA%B7%9C/myshell.c) , [div.c](https://github.com/dnjsrb0710/Operating-System/blob/main/HW02_2015110899_%EC%9D%B4%EC%9B%90%EA%B7%9C/div.c) , [sub.c](https://github.com/dnjsrb0710/Operating-System/blob/main/HW02_2015110899_%EC%9D%B4%EC%9B%90%EA%B7%9C/sub.c) , [fact.c](https://github.com/dnjsrb0710/Operating-System/blob/main/HW02_2015110899_%EC%9D%B4%EC%9B%90%EA%B7%9C/fact.c) , [sum.c](https://github.com/dnjsrb0710/Operating-System/blob/main/HW02_2015110899_%EC%9D%B4%EC%9B%90%EA%B7%9C/sum.c)

>## 3번과제
> #### 변수를 1씩 증가,감소시키며 동시에 돌아가는 멀티 쓰래드를 10000개 만들어 결과값을 확인한	다. 예상값과 결과값을 비교하고 race condition에 대하여 알아본다.
>>코드 :  [thread1000.c](https://github.com/dnjsrb0710/Operating-System/blob/main/HW03_2015110899_%EC%9D%B4%EC%9B%90%EA%B7%9C/thread1000.c)

>## 3-B번과제
> #### 전역변수 값이 더 잘 꺠지도록 하는 함수를 HW3의 코드에 추가하여 적은 thread의 개수에서도 race condition을 발생시키고 mutex함수들을 사용하여 이를 해결한다.
>>코드 :  [threadfail.c](https://github.com/dnjsrb0710/Operating-System/blob/main/HW03(B)_2015110899_%EC%9D%B4%EC%9B%90%EA%B7%9C/threadfail.c) , [threadsuccess.c](https://github.com/dnjsrb0710/Operating-System/blob/main/HW03(B)_2015110899_%EC%9D%B4%EC%9B%90%EA%B7%9C/threadsuccess.c)