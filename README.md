# SSAFY 12기 알고리즘 스터디
#### 삼성 역량테스트 B형 취득, 코테 대비를 목적으로 진행합니다.
#### [회의록📋](https://docs.google.com/document/d/1EjaM0CXsTt4PHvZbOxp-2EXrSIyDbMyl6VO1BHClmkc/edit?usp=sharing)

## Rules
- 매 주 정해진 알고리즘 주제 하에 문제를 추천합니다.
- 팀원 별 한 개의 문제를 추천하여 주 4개의 문제를 풉니다.
- 주 1회, 오프라인 모임을 통해 본인 코드를 설명하고 최적화를 위한 코드 리뷰를 합니다.

## Members

| 이름 (Github Link) | 소속 |
|------------------|------|
| [강진주](https://github.com/Pearl-K) | 전공 Java반 |
| [권민채](https://github.com/MinchaeKwon) | 전공 Java반 |
| [나영조](https://github.com/Taebee00) | 전공 임베디드반 |
| [이승록](https://github.com/SeokguKim) | 전공 임베디드반 |




## Week 1 : 재귀 ✅
[2705. 팰린드롬 파티션](https://www.acmicpc.net/problem/2705)
- N을 기준으로 홀/짝 경우를 나눠서 생각하기
- 문제를 부분 문제로 분할하다보면 이전의 값을 쓸 수 있다는 사실을 발견할 수 있다.
- 팀원들은 대체로 재귀를 사용한 top-down dp의 형식으로 접근했다. 


[16719. ZOAC](https://www.acmicpc.net/problem/16719)
- 문자열에서 가장 앞에 오는 문자의 위치를 발견
- 해당 위치~end 까지 먼저 재귀를 돌리고, 다음에 start ~현재 위치 재귀 함수를 돌린다 (정석 풀이)
- 문자열의 길이가 100으로 짧게 주어지기 때문에, 모든 문자를 탐색하여 정렬하는 풀이가 제한 시간 안에 돈다.


[20164. 홀수 홀릭 호석](https://www.acmicpc.net/problem/20164)
- 길이가 1, 2, 3 이상일 때 경우를 각각 나눠서 처리
- 3 이상일 때 이중 for문 사용하여 전체 문자열에서 가능한 모든 분기점을 잡고 3분할 하여 확인


[1278. 연극](https://www.acmicpc.net/problem/1278)
- 비트마스킹으로 next 상태를 표현할 수 있음


## Week 2 : 백트래킹 ✅
[1342. 행운의 문자열](https://www.acmicpc.net/problem/1342)


[10597. 순열장난](https://www.acmicpc.net/problem/10597)


[17255. N으로 만들기](https://www.acmicpc.net/problem/17255)


[1443. 망가진 계산기](https://www.acmicpc.net/problem/1443)
