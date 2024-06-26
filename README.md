# OPENSOURSE1    20243041 김준서
===========================================================================================================

#top
-----------------------------------------------------------------------------------------------------------
리눅스 명령어 top은 시스템의 실시간 성능을 모니터링하는 데 사용된다.
top 명령어를 실행하면 다양한 시스템 정보를 실시간으로 확인할 수 있으며, 
이는 시스템 성능 문제를 진단하고 관리하는 데 유용하다.

화면 구성 요소로는 
1. 상단 요약 정보
2. 프로세스 정보

상호작용 명령어로는 
q, h, k, r, u, m, p, T, 1, Space, f가 있다.

옵션으로는
-d SECONDS, -p PID, -n NUM, -b가 있다.


#ps
-----------------------------------------------------------------------------------------------------------
리눅스 명령어 ps는 현재 실행 중인 프로세스에 대한 정보를 표시하는 데 사용된다.
특정 프로세스를 모니터링하거나 관리 하는 데 유용하다.

터미널에서 ps 명령어를 입력하면, 현재 셸 세션에서 실행 중인 프로세스가 표시된다.

기본 출력
PID: 프로세스 ID
TTY: 터미널 타입
TIME: CPU 사용 시간
CMD: 실행된 명령어

옵션으로는
a, ,u, x, f가 있다.

-p PID, -u USER, -c COMMAND를 이용하여 특정 프로세스만 볼 수도 있다.


#jobs
-----------------------------------------------------------------------------------------------------------
리눅스 명령어 jobs는 현재 셸 세션에서 백그라운드로 실행 중인 작업을 표시하는 데 사용된다.
사용자가 관리할 수 있는 백그라운드 작업의 상태를 확인하는 데 유용하다.

터미널에서 jobs 명령어를 입력하면, 현재 셸에서 실행 중인 모든 작업의 목록이 표시된다.

작업 제어
jobs 명령어와 함께 사용되는 주요 명령어가 있다.
1. bg: 중지된 작업을 백그라운드에서 실행하도록 변경한다.
2. fg: 백그라운드 또는 중지된 작업을 포어그라운드로 가져온다.
3. kill: 특정 작업을 종료한다.



#kill
------------------------------------------------------------------------------------------------------------
리눅스 명령어 kill은 프로세스에 시그널을 보내 특정 동작을 하게 하는 명령어이다.
주로 프로세스를 종료시키는 데 사용되지만, 다양한 시그널을 사용하여 다른 작업도 수행할 수 있다.

시그널
주요 시그널은 다음과 같다.
1. SIGTERM: 종료 요청
2. SIGKILL: 강제 종료
3. SIGINT: 인터럽트
4. SIGHUP: 연결 종료
5. SIGSTOP: 프로세스 중지
6. SIGCONT: 중지된 프로세스 재개
