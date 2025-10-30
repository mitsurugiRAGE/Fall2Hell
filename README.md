# Fall2Hell
## 개요
- 구상 프로젝트: 간단한 SSH 로그 분석기
- 프로젝트명: Fall2Hell
- 프로젝트 주제: Defensive Security, Data Parsing, Pattern Analysis, CSV Report
- 프로젝트 목적:
    1. 모조 SSH 접속 로그를 파싱 및 분석하여 '비정상적인 침입 시도'를 감지할 수 있다
    2. 감지된 침입을 시도한 컴퓨터의 IP와 침입 시도 횟수, 첫 시도, 마지막 시도, 접속을 시도한 포트 번호 등을 CSV 리포트로 출력할 수 있다
- 프로젝트 선택 동기:
>개인적으로 사용하는 개발용 서버에서 비정상적인 침입(혹은 자동화된 포트 스캔)의 조짐으로
>보이는 로그를 발견하게 되었음.
>이에 흥미를 가지고 SSH 로그 형식(`/var/log/auth.log`)의 더미 데이터를 다루고
>분석하여 CSV 리포트로 만드는 실습을 진행해 보려 함.

## 주요 기능
- SSH 로그 분석기
    - Linked List (수상한 접근 시도를 리스트로 관리)
    - 해시 테이블에서 필요한 데이터 추출
    - "비정상적인 침입 시도" 구분 정책 구현
    - CSV 파일로 리포트 출력
## GitHub Repository
https://github.com/mitsurugiRAGE/Fall2Hell
