`Java Virtual Machine(JVM)`은 Java 바이트 코드를 실행하기 위한 가상 머신
JVM은 플랫폼 독립적으로, JVM이 실행 가능한 환경이라면 어디든 Java 프로그램이 실행 가능
`Write once, Run anywhere`

---
### ✅ 1. JVM 구성 요소
#### (1) 클래스 로더(Class Loader)
- `.class` 파일을 로드하여 JVM 메모리로 올림
- **로딩 → 링크 → 초기화** 단계 수행
#### (2) 런타임 데이터 영역 (메모리 구조)
- 메소드 영역 (Method Area)
- 힙 (Heap)
- 스택 (Stack)
- PC 레지스터
- Native Method Stack
#### (3) 실행 엔진
- 바이트 코드를 실제로 해석하거나 컴파일하여 실행
- 인터프리터(Interpreter) + JIT 컴파일러(Just-In-Time)
#### 4) Java Native Interface (JNI)
- Java에서 Native Code(C/C++) 호출 가능하게 함

---
### 🔄 관련 주제 
- [[GC]]