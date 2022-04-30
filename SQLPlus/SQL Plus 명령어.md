# SQL Plus 명령어
- `sqlplus` : 접속
- `exit` : 종료
<br/>

- `ed` : 편집
- `save` : 버퍼에 저장된 쿼리 저장 (ex. `save file.sql`)
- `get` : 파일로부터 쿼리 불러오기 (ex. `get file.sql`)
- `start`, `@` : 쿼리 불러온 후 실행 (ex. `@file.sql`)
- `host` : OS 명령 프롬프트로 나감
- `help` : 명령어의 사용법 출력
- `conn 아이디/비밀번호` : 사용자 변경

## spool
- `spool 파일명` : 화면에 출력되는 결과 저장 (ex. `spool file.sql`)
- `spool off` : 저장 종료

## show
- `show all` : SQL Plus의 설정값 확인
- `show user` : 현재 접속된 사용자 표시
- `show 옵션` : 해당 옵션의 현재 값

## set
- `set autocommit` : DML 수행 후 자동으로 commit함
- `set feedback` : 결과가 몇 건인지 보여줌
- `set heading on/off` : 결과 컬럼 이름을 보여줌/숨김
- `set linesize n` : 한 줄에 보여줄 수 있는 글자 수 설정
- `set pause on/off` : 결과를 화면 단위로 멈추는지 여부 설정 (기본값은 off)
- `set time on/off` : 프롬프트에 시간 출력 여부 (기본값은 off)
- `set timing on/off` : 실행시간 출력
