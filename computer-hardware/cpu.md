# CPU
Central Processing Unit  
≒ Processor, Microprocessor, Micro Processor Unit

: 중앙 처리 장치  
: 컴퓨터 시스템 전체를 작동/통제하고 연산을 수행하는 물리적 장치  
: 초기에는 진공관으로 구성되었으며 현재는 수십억 개의 트랜지스터로 구성된 칩  

**구성 요소**   
- [제어 장치](#제어-장치)
- [연산 장치](#연산-장치)
- [레지스터](#레지스터)

```
           중앙 처리 장치    
        제어장치 <=> 연산장치
                 ↑↓
데이터 입력 => 기억장치 => 데이터 출력

제어 장치로부터 발생되는 제어 신호로 주기억장치와 데이터를 주고 받으며 연산을 수행 
```



## 제어 장치
Control Unit  
= 명령어 장치  
: 데이터 처리를 위해 명령 지시  

1. 주기억 장치에서 명령어를 인출
2. 인출된 명령어 해석
3. 해당 데이터와 해석된 명령어를 연산 장치로 보냄 (연산 장치에서 처리)
4. 연산된 결과를 받아와 이를 주기억 장치나 레지스터에 저장



## 연산 장치
Arithmetic Logic Unit  
= 실행 장치  
: 산술 연산과 논리 연산을 수행하는 장치  
: 산술 연산은 사칙 연산을 수행하며 논리 연산은 AND, OR, NOT 등 참/거짓을 판별하는 연산 수행  



## 레지스터
: CPU에 존재하는 메모리로 빠른 처리를 위해 데이터와 명령어를 일시적으로 저장  
: 제어 장치에 의해 데이터를 보관하고 전송함

- 범용 레지스터
- 세그먼트 레지스터
- 제어 레지스터
- 플래그 레지스터
- 명령어 레지스터  
- 인덱스 레지스터



### 범용 레지스터
: 다목적으로 사용하는 레지스터로 주로 데이터 처리를 위해 사용

레지스터 | 설명
---|---
EAX(RAX) | 산술 및 논리 연산을 위한 레지스터로 연산 결과도 저장
EBX(RBX) | 메모리 주소 저장   
ECX(RCX) | 반복 명령어 실행을 위한 카운터 레지스터
EDX(RDX) | 부호 확장이나 큰 수의 연산을 위한 레지스터



### 세그먼트 레지스터

레지스터 | 설명
---|---
CS  | 코드가 저장된 세그먼트
DS  | 데이터가 저장된 세그먼트
SS  | 스택이 저장된 세그먼트
ES  | 보조 세그먼트