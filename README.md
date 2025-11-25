# 🧪 Java Concurrency Labs

> **"멀티스레드와 동시성(Concurrency)의 A to Z를 깊이 있게 탐구하는 학습 아카이브"** > CS 이론부터 Java의 저수준 동기화, 그리고 실무적인 Executor 프레임워크까지 체계적으로 학습하고 기록합니다.

## 🎯 Learning Objectives (학습 목표)

1. **Deep Dive**: 단순히 API 사용법을 넘어, OS 레벨의 원리와 메모리 모델을 이해합니다.
2. **Safety First**: 동시성 문제(Race Condition, Deadlock)를 예방하는 안전한 코드를 작성합니다.
3. **Clean Code**: 복잡한 비즈니스 로직 속에서도 가독성과 유지보수성을 잃지 않는 패턴을 연구합니다.
4. **Performance**: 효율적인 스레드 풀 관리와 비동기 처리를 통해 시스템 성능을 최적화합니다.

---

## 🗂️ Curriculum & Structure

학습 흐름에 따라 4단계로 구성되어 있습니다.

### 1️⃣ CS Fundamentals (기반 다지기)
> 스레드를 다루기에 앞서 필요한 운영체제 및 컴퓨터 구조 핵심 이론을 학습합니다.
- [ ] **Process & Thread**: 프로세스와 스레드의 차이, 메모리 구조(Code, Data, Heap, Stack)
- [ ] **Multi-Tasking**: Context Switching의 원리와 비용, 병렬성과 동시성의 차이
- [ ] **Scheduling**: OS 스케줄러의 작동 방식 (Round Robin, Priority 등)과 Spring `@Scheduled`

### 2️⃣ Thread Basics (스레드 기본기)
> Java 스레드의 생명주기를 이해하고, 기본적인 동기화 메커니즘을 익힙니다.
- [ ] **Thread Control**: `Thread` 클래스와 `Runnable` 인터페이스, `sleep`, `join`, `interrupt`
- [ ] **Lifecycle**: New, Runnable, Blocked, Waiting, Terminated 상태 전이도 분석
- [ ] **Memory Visibility**: CPU Cache와 Main Memory 불일치 문제, `volatile` 키워드의 역할
- [ ] **Synchronization**: `synchronized` 키워드(메서드/블록)와 Monitor 락의 원리
- [ ] **Advanced Locks**: `ReentrantLock`을 활용한 명시적 락 제어와 Condition

### 3️⃣ Advanced Techniques (고급 기술)
> 복잡한 동시성 문제를 해결하기 위한 패턴과 논블로킹(Non-blocking) 기술을 탐구합니다.
- [ ] **Producer-Consumer Pattern**: `wait()`와 `notify()`를 활용한 협력 패턴 구현
- [ ] **CAS (Compare And Swap)**: Lock-Free 알고리즘의 핵심 원리와 `Atomic` 변수
- [ ] **Concurrent Collections**: `ConcurrentHashMap`, `CopyOnWriteArrayList` 등의 내부 동작 원리

### 4️⃣ Practical Skills (실무 기술)
> 실제 백엔드 개발에서 사용되는 모던 자바 멀티스레딩 기술을 마스터합니다.
- [ ] **Future & Callable**: 비동기 작업의 결과값을 반환받는 메커니즘
- [ ] **Executor Framework**: 스레드 생성과 관리를 분리하는 우아한 방법
- [ ] **Thread Pool**: `ThreadPoolExecutor` 설정 전략과 실무 최적화 (Core/Max Pool Size)

