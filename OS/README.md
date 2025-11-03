# 🧠 Operating System (운영체제)

## 📚 주요 학습 주제

| 주제 | 설명 | 링크 |
|------|------|------|
| 프로세스 vs 스레드 | 프로그램 실행 단위의 차이와 동작 원리 | [process-vs-thread.md](./process-vs-thread.md) |
| CPU 스케줄링 | 프로세스 실행 순서를 결정하는 알고리즘 | [scheduling.md](./scheduling.md) |
| 메모리 관리 | 페이징, 세그멘테이션, 가상 메모리 등 | [memory-management.md](./memory-management.md) |
| 동기화(Synchronization) | 임계 구역과 세마포어, 모니터 등 | [synchronization.md](./synchronization.md) |
| 교착 상태(Deadlock) | 데드락의 발생 조건과 해결 방법 | [deadlock.md](./deadlock.md) |
| 파일 시스템 | 파일의 저장 구조 및 관리 방식 | [file-system.md](./file-system.md) |

---

## 🧩 면접 단골 질문 예시

- 프로세스와 스레드의 차이를 설명해보세요.  
- 컨텍스트 스위칭(Context Switching)이란 무엇인가요?  
- 가상 메모리가 필요한 이유는 무엇인가요?  
- 교착상태(Deadlock)가 발생하는 조건은 무엇이며, 해결 방법은?  
- 세마포어와 뮤텍스의 차이를 설명해보세요.  
- 페이징(Paging)과 세그멘테이션(Segmentation)의 차이는 무엇인가요?

---

## 🔍 참고하면 좋은 주제 흐름

1. **운영체제 개요**  
   - 운영체제의 역할  
   - 커널(Kernel) 구조  
   - 시스템 콜(System Call)

2. **프로세스 관리**  
   - 프로세스 상태 전이  
   - 스케줄링 알고리즘 (FCFS, SJF, RR 등)  
   - 컨텍스트 스위칭  

3. **메모리 관리**  
   - 연속/비연속 메모리 할당  
   - 가상 메모리  
   - 페이지 교체 알고리즘 (LRU, FIFO 등)

4. **동기화 & 데드락**  
   - 임계구역(Critical Section)  
   - 세마포어, 모니터  
   - 교착 상태 발생 조건 (상호배제, 점유대기 등)

5. **입출력 & 파일 시스템**  
   - 디스크 스케줄링  
   - 파일 구조  
   - 캐시 및 버퍼링  

---
