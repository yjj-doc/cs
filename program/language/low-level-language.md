# Low level language
: 컴퓨터가 바로 처리 가능한 명령 집합  
: 고급 언어는 저급 언어로 변환되어 실행됨  

**종류**  
- Machine Language
- Assembly Language



## Machine Language
= Machine Code, Object Code  
: 0과 1로 구성된 이진 코드  
: 컴퓨터가 바로 처리해 실행 속도가 빠르지만 작성하기 어려움  


### Instruction Set  
: 프로세서가 실행하는 명령어 집합으로 프로세서 아키텍처에 따라 다름  

**ISA**  
Instruction Set Architectures  
: 명령어 집합 아키텍처  
: 하드웨어와 소프트웨어 사이의 인터페이스  

- 명령어
- 주소 지정 방식
- 데이터 타입
- 메모리 아키텍처
- 인터럽트
- 예외처리
- 외부 입출력
- ...



## Assembly Language
= Symbolic Machine Code  
: 머신 코드를 기호화한 명령어 집합 (니모닉 코드)  
: 어셈블리어는 어셈블러를 통해 기계어로 변환되어 실행됨  

> 레이블 | 옵코드 | 오퍼랜드 | 오퍼랜드 | 주석

코드 | 설명
---|---
LEA  | 메모리 주소 이동  
MOV  | 메모리에 있는 데이터 이동   
ADD  | 데이터 더하기
SUB  | 데이터 빼기
INC  | 데이터 값 1 증가
DEC  | 데이터 값 1 감소
PUSH | 스택에 데이터 추가
POP  | 스택에 있는 데이터 반환  
CALL | 프로시저 호출
...  | ...